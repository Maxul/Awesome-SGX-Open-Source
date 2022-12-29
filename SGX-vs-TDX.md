## Will Intel TDX replace Intel SGX?

***Fact: Intel has deprecated SGX in the 11th and 12th generations of Core processors [1] [2].***

#### Q1: Was SGX completely deprecated by Intel?

A1: Not really. Only personal computer processors.

#### Q2: Will Intel TDX possibly replace Intel SGX?

From my perspective, Intel TDX is indeed a good alternative to Intel SGX. TDX outperforms SGX in the following aspects:

1. **Compatible**: TDX provides the abstraction of a virtual machine (VM), a natural fit for supporting unmodified applications by a POSIX-compatible guest kernel or today's Unikernels [3]. Existing SGX LibOSes (Gamine [4] or Occlum [5]) are working in progress to support various applications.

2. **Performant**: TDX supports para-virtualization and SR-IOV for high-performance I/O. On the contrary, SGX must involve expensive context switches for I/O intensive workloads. Although asynchrony (e.g., FlexSC [6]/io_uring) does assist, asynchrony brings more CPUs into busy looping.

3. **Secure**: TDX employs a multi-key memory encryption engine (MKTME) and introduces a secure yet thin hypervisor (i.e., SEAM module) that minimizes the controlled-channel attacks as existed in SGX [7]. Nevertheless, TCB in SGX is supposed to be smaller than in TDX.

4. **Highly utilized**: SGX statically partitions the physical memory into two halves; secure memory (i.e., enclave page cache or EPC) cannot be shared with the OS, whereas TD (namely, encrypted VM) pages can be flexibly configured to be private, shared or public (unencrypted).

Given the above comparison, I can hardly vote for SGX. TDX supports remote attestation and memory encryption just like SGX does.

Worse still, the recent scalable SGX on Xeon3 gives up memory integrity, making TDX and SGX almost the same security level. When TDX is released, SGX will probably be doomed in the long run.

#### Q3: Will Intel SGX be finally replaced by Intel TDX?

A3: Probably not, for two reasons:

- As long as Intel still reuses SGX to assist the remote attestation of TDX [8].
- SGX is useful for micro-services such as key management services (KMS) with small TCB.

[1] https://cdrdv2.intel.com/v1/dl/getContent/634648

[2] https://cdrdv2.intel.com/v1/dl/getContent/655258

[3] http://unikernel.org/

[4] https://github.com/gramineproject/gramine

[5] https://github.com/occlum/occlum

[6] FlexSC: Flexible System Call Scheduling with Exception-Less System Calls. OSDI 2010.

[7] Controlled-Channel Attacks: Deterministic Side Channels for Untrusted Operating Systems. IEEE S&P 2015.

[8] https://www.intel.com/content/www/us/en/developer/articles/technical/intel-trust-domain-extensions.html

**Ack**: I would like to thank Mona Vij for the discussion on this page.