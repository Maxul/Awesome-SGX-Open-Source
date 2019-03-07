# Awesome-SGX-open-source

Hope you'd be glad to add a star if you think this list is helpful!

## Runtime Framework

### Industrial Leading Projects

Microsoft OpenEnclave: [https://github.com/Microsoft/openenclave](https://github.com/Microsoft/openenclave) **to support OP-TEE and Windows**

Microsoft EVM:[https://github.com/Microsoft/eEVM](https://github.com/Microsoft/eEVM)

Google Asylo: [https://github.com/google/asylo](https://github.com/google/asylo)

### Library OS for quickly deploying (almost) unmodified applications

Panoply: Low-TCB Linux Applications with SGX Enclaves: [https://github.com/shwetasshinde24/Panoply](https://github.com/shwetasshinde24/Panoply)

Graphene / Graphene-SGX Library OS:a library OS for Linux multi-process applications, with Intel SGX support: [https://github.com/oscarlab/graphene](https://github.com/oscarlab/graphene)

SGX-LKL Library OS for running Linux applications inside of Intel SGX enclaves: [https://github.com/lsds/sgx-lkl](https://github.com/lsds/sgx-lkl)

Docker: [https://github.com/tozd/docker-sgx](https://github.com/tozd/docker-sgx)

## Remote Attestation and Secure Channel

### Remote Attestation (RA)

Intel End2End RA: [https://github.com/intel/sgx-ra-sample](https://github.com/intel/sgx-ra-sample)

IBM simplified RA without accessing IAS too frequently: [https://github.com/IBM/sgx-trust-management](https://github.com/IBM/sgx-trust-management)

RA-based TLS: [https://github.com/cloud-security-research/sgx-ra-tls](https://github.com/cloud-security-research/sgx-ra-tls)

Data Center Attestation Primitives (DCAP) since Intel SGX SDK 2.3.1: [https://github.com/intel/SGXDataCenterAttestationPrimitives](https://github.com/intel/SGXDataCenterAttestationPrimitives)

[https://github.com/Microsoft/Azure-DCAP-Client](https://github.com/Microsoft/Azure-DCAP-Client)

### SSL/TLS

Enclave-ised SSL: [https://github.com/lsds/TaLoS](https://github.com/lsds/TaLoS)

In-enclave App+SSL:

[https://github.com/bl4ck5un/mbedtls-SGX](https://github.com/bl4ck5un/mbedtls-SGX)

[https://github.com/wolfSSL/wolfssl-examples](https://github.com/wolfSSL/wolfssl-examples)

[https://github.com/intel/intel-sgx-ssl](https://github.com/intel/intel-sgx-ssl)

## Language Framework

Rust:

[https://github.com/fortanix/rust-sgx](https://github.com/fortanix/rust-sgx)

[https://github.com/baidu/rust-sgx-sdk](https://github.com/baidu/rust-sgx-sdk)

Python: [https://github.com/mesalock-linux/mesapy](https://github.com/mesalock-linux/mesapy)

Python binder for SGX SDK :[https://github.com/adombeck/python-sgx](https://github.com/adombeck/python-sgx)

Golang binder: [https://github.com/rupc/go-with-intel-sgx](https://github.com/rupc/go-with-intel-sgx) 

C#: [https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX](https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX)

Lua: [https://github.com/vschiavoni/SecureStreams-DEBS17](https://github.com/vschiavoni/SecureStreams-DEBS17)

A code confidentiality framework for Intel SGX: [https://github.com/utds3lab/sgxelide](https://github.com/utds3lab/sgxelide)

## Blockchain

Hyperledger:

[https://github.com/hyperledger-labs/private-data-objects](https://github.com/hyperledger-labs/private-data-objects)

[https://github.com/hyperledger-labs/fabric-secure-chaincode](https://github.com/hyperledger-labs/fabric-secure-chaincode)

EVM:

[https://github.com/Microsoft/eEVM](https://github.com/Microsoft/eEVM)

Proof of Luck + IPFS:

[https://github.com/luckychain/lucky](https://github.com/luckychain/lucky)

[https://github.com/luckychain/node-secureworker](https://github.com/luckychain/node-secureworker)

[https://github.com/bl4ck5un/Town-Crier](https://github.com/bl4ck5un/Town-Crier)

[https://github.com/LedgerHQ/bolos-enclave](https://github.com/LedgerHQ/bolos-enclave)

## Specific Applications

SGX + Tor:

[https://github.com/kaist-ina/SGX-Tor](https://github.com/kaist-ina/SGX-Tor)

SGX + BitCoin:

[https://github.com/BitObscuro/Obscuro](https://github.com/BitObscuro/Obscuro)

Channel ID Private Key Protection:

[https://github.com/google/channel-id-enclave](https://github.com/google/channel-id-enclave)

## Private Key/Passphrase Management

SGX Enabled OpenStack Barbican Key Management System:

[https://github.com/cloud-security-research/sgx-kms](https://github.com/cloud-security-research/sgx-kms)

A server with SGX enclave that stores private keys and performs crypto operations upon requests:

[https://github.com/cloud-key-store/keystore](https://github.com/cloud-key-store/keystore)

Protecting Web Passwords using Trusted Execution Environments:

[https://github.com/SafeKeeper](https://github.com/SafeKeeper)

## Database

Opaque: a package for Apache Spark SQL that enables strong security for DataFrames using Intel SGX trusted hardware:

Future work: Remote attestation, data key delivery, key storage service

[https://github.com/ucbrise/opaque](https://github.com/ucbrise/opaque)

Database intended for Blockchain

[https://github.com/kaimast/credb](https://github.com/kaimast/credb)

Protect in-memory sqlite, not .db file encryption:

[https://github.com/yerzhan7/SGX_SQLite](https://github.com/yerzhan7/SGX_SQLite)

Protect Audit-Log via Sqlite:

[https://github.com/lsds/LibSEAL](https://github.com/lsds/LibSEAL)

From scratch:

[https://github.com/mars-research/sgx-db](https://github.com/mars-research/sgx-db)

## DRM

Protect Enclave Code:

[https://github.com/intel/linux-sgx-pcl](https://github.com/intel/linux-sgx-pcl)

A code confidentiality framework for Intel SGX:

[https://github.com/utds3lab/sgxelide](https://github.com/utds3lab/sgxelide)

## Profiling

Report statistics of E/Ocalls, EPC Paging:

[https://github.com/ibr-ds/sgx-perf](https://github.com/ibr-ds/sgx-perf)

Actor model for better Enclave IPC:

[https://github.com/ibr-ds/EActors](https://github.com/ibr-ds/EActors)

Stress benchmark:

[https://github.com/sebva/stress-sgx](https://github.com/sebva/stress-sgx)

User-level paging:

[https://github.com/acsl-technion/eleos](https://github.com/acsl-technion/eleos)

SwitchLess:

[https://github.com/oweisse/hot-calls](https://github.com/oweisse/hot-calls)

## Harden Memory

ASLR:[https://github.com/jaebaek/SGX-Shield](https://github.com/jaebaek/SGX-Shield)

TSX:[https://github.com/sslab-gatech/t-sgx](https://github.com/sslab-gatech/t-sgx)

MPX:[https://github.com/tudinfse/sgxbounds](https://github.com/tudinfse/sgxbounds)

## Distributed System

ZooKeeper: [https://github.com/sereca/SecureKeeper](https://github.com/sereca/SecureKeeper)

SGX-aware container orchestrator: [https://github.com/sebva/sgx-orchestrator](https://github.com/sebva/sgx-orchestrator)

VM-Migration: [https://github.com/SSGAalto/sgx-migration](https://github.com/SSGAalto/sgx-migration)

P2P: [https://bitbucket.org/P2PUsingSGX/p2pusingsgx](https://bitbucket.org/P2PUsingSGX/p2pusingsgx)

## I/O

Building Distributed Enclave Applications with Sancus and SGX:

[https://github.com/sancus-pma/tutorial-dsn18](https://github.com/sancus-pma/tutorial-dsn18)

Fidelius: Protecting User Secrets from Compromised Browsers:

[https://github.com/SabaEskandarian/Fidelius](https://github.com/SabaEskandarian/Fidelius)

## Attacks

[https://github.com/lsds/spectre-attack-sgx](https://github.com/lsds/spectre-attack-sgx)

[https://github.com/jovanbulck/sgx-tutorial-space18](https://github.com/jovanbulck/sgx-tutorial-space18)

[https://github.com/jovanbulck/sgx-step](https://github.com/jovanbulck/sgx-step)

[https://github.com/jovanbulck/sgx-pte](https://github.com/jovanbulck/sgx-pte)

[https://github.com/m1ghtym0/sgx-timing](https://github.com/m1ghtym0/sgx-timing)

[https://github.com/sslab-gatech/sgx-bomb](https://github.com/sslab-gatech/sgx-bomb)

[https://github.com/sgxrop/sgxrop](https://github.com/sgxrop/sgxrop)
