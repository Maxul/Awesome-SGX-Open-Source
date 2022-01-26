## Will Intel TDX replace Intel SGX?

***Fact: In 2022, Intel has deprecated SGX in the 12th generation of Core processors [1].***

#### Q1: Was SGX completely deprecated by Intel?

A1: No. Only PC processors.

#### Q2: Why will Intel TDX replace Intel SGX?

Personally, I believe that Intel TDX is a good alternative to Intel SGX. TDX outperforms SGX for the following reasons:

1. **Compatibility**: TDX provides VM abstraction, a natural fit for the cloud service provider.
The VM abstraction can easily support any unmodified applications by a POSIX-compatible guest kernel or today's Unikernels [3]. Existing SGX LibOSes (Gamine [4] or Occlum [5]) are still working in progress to support various applications.

2. **Performance**: TDX supports para-virtualization or even SR-IOV for high-performance I/O. On the contrary, SGX must involve expensive context switches for I/O intensive workloads. Although asynchrony was proven to assist, asynchrony has to bring more CPUs into busy looping.

3. **Security**: TDX utilizes multi-key memory encryption (MKTME) and introduces a secure hypervisor (i.e., SEAM module) that minimizes the controlled-channel attacks than SGX.

4. **Utilization**: SGX must statically partition the physical memory into two halves; the secure memory (i.e., enclave page cache or EPC) cannot be shared with the OS. TD (namely, encrypted VM) pages can be flexibly configured to be private, shared or public (unencrypted).

Given the above comparison, I do not see any wins for SGX. TDX supports remote attestation and memory encryption just like SGX does. Worse, recent scalable SGX on Xeon3 abandons memory integrity, making TDX and SGX almost the same security level. When TDX is released, SGX will probably be doomed in the long run.

#### Q3: Will Intel SGX be finally replaced by Intel TDX?

A3: Probably not. For two reasons.

- As long as Intel still reuses SGX to assist the remote attestation of TDX [2].
- SGX is pretty useful for micro-services such as key management services (KMS).

[1] https://edc.intel.com/content/www/us/en/design/ipla/software-development-platforms/client/platforms/alder-lake-desktop/12th-generation-intel-core-processors-datasheet-volume-1-of-2/001/operating-systems-support/

[2] https://www.intel.com/content/www/us/en/developer/articles/technical/intel-trust-domain-extensions.html

[3] http://unikernel.org/

[4] https://github.com/gramineproject/gramine

[5] https://github.com/occlum/occlum