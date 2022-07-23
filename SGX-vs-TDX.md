## Are TDX going to replace SGX?

***Fact: Intel has deprecated SGX in its 11th, 12th generations of Core processors [1] [2].***

#### Q1: Was SGX completely deprecated by Intel?

A1: Not really; only PC processors.

#### Q2: Can Intel TDX possibly replace Intel SGX?

From my perspective, Intel TDX is indeed a good alternative to Intel SGX. TDX outperforms SGX for the following aspects:

1. **Compatibility**: TDX provides VM abstraction, a natural fit for the cloud service provider. VM abstraction can support unmodified applications by a POSIX-compatible guest kernel or today's Unikernels [4]. Existing SGX LibOSes (Gamine [5] or Occlum [6]) are still working in progress to support various applications.

2. **Performance**: TDX supports para-virtualization and SR-IOV for high-performance I/O. On the contrary, SGX must involve expensive context switches for I/O intensive workloads. Although asynchrony can assist, asynchrony brings more CPUs into busy looping.

3. **Security**: TDX utilizes multi-key memory encryption (MKTME) and introduces a secure yet thin hypervisor (i.e., SEAM module) that minimizes the controlled-channel attacks compared with SGX.

4. **Utilization**: SGX statically partitions the physical memory into two halves; secure memory (i.e., enclave page cache or EPC) cannot be shared with the OS, whereas TD (namely, encrypted VM) pages can be flexibly configured to be private, shared or public (unencrypted).

Given the above comparison, I can hardly vote for SGX. TDX supports remote attestation and memory encryption just like SGX does.

Worse still, recent scalable SGX on Xeon3 gives up memory integrity, making TDX and SGX almost the same security level. When TDX is released, SGX will probably be doomed in the long run.

#### Q3: Will Intel SGX be finally replaced by Intel TDX?

A3: Probably not. Two reasons:

- As long as Intel still reuses SGX to assist the remote attestation of TDX [3].
- SGX is useful for micro-services such as key management services (KMS) with small TCB.

[1] https://cdrdv2.intel.com/v1/dl/getContent/634648

[2] https://cdrdv2.intel.com/v1/dl/getContent/655258

[3] https://www.intel.com/content/www/us/en/developer/articles/technical/intel-trust-domain-extensions.html

[4] http://unikernel.org/

[5] https://github.com/gramineproject/gramine

[6] https://github.com/occlum/occlum