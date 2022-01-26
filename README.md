# Awesome SGX Open Source Projects

*Hope you'd be glad to add a star if you think this list is helpful!*

Academic Conference Collections:
[Link](https://github.com/Maxul/Awesome-SGX-Open-Source/blob/master/Academy.md)

## Runtime Framework

### Industrial Leading Projects

Microsoft OpenEnclave: [https://github.com/Microsoft/openenclave](https://github.com/Microsoft/openenclave)

Microsoft Confidential Consortium Framework: [https://github.com/microsoft/CCF](https://github.com/microsoft/CCF)

Apache Teaclave: [https://github.com/apache/incubator-teaclave](https://github.com/apache/incubator-teaclave)

Ant Financial Occlum: [https://github.com/occlum/occlum](https://github.com/occlum/occlum)

Next-Generation Occlum, optimized for Intel SGX 2.0: [https://github.com/occlum/ngo](https://github.com/occlum/ngo)

KubeTEE TFF: [https://github.com/SOFAEnclave/trusted-function-framework](https://github.com/SOFAEnclave/trusted-function-framework)

Google Asylo: [https://github.com/google/asylo](https://github.com/google/asylo)

Fortanix Enclave Development Platform: [https://github.com/fortanix/rust-sgx](https://github.com/fortanix/rust-sgx)

Scontain: [https://github.com/scontain](https://github.com/scontain)

MarbleRun: [https://github.com/edgelesssys/marblerun](https://github.com/edgelesssys/marblerun)

### Library OS for quickly deploying (almost) unmodified applications

Porpoise: A tool to port commodity application to Intel SGX:
[https://github.com/iisc-cssl/porpoise](https://github.com/iisc-cssl/porpoise)

Mystikos: Tools and runtime for launching unmodified container images in Trusted Execution Environments:
[https://github.com/deislabs/mystikos](https://github.com/deislabs/mystikos)

Gramine Library OS with Intel SGX Support (formerly called Graphene):
[https://github.com/gramineproject/gramine](https://github.com/gramineproject/gramine)

SGX-LKL: Library OS for running Linux applications inside SGX enclaves:
[https://github.com/lsds/sgx-lkl](https://github.com/lsds/sgx-lkl)

Ratel: Dynamic Binary Translation with SGX Enclaves:
[https://github.com/ratel-enclave/ratel](https://github.com/ratel-enclave/ratel)

Panoply: Low-TCB Linux Applications with SGX Enclaves:
[https://github.com/shwetasshinde24/Panoply](https://github.com/shwetasshinde24/Panoply)

Container: Protected Container Runtime for Confidential Computing: 
[https://github.com/alibaba/inclavare-containers](https://github.com/alibaba/inclavare-containers)

Edgeless RT: SDK for TEEs/SGX based on Open Enclave with Go support:
[https://github.com/edgelesssys/edgelessrt](https://github.com/edgelesssys/edgelessrt)

## Remote Attestation and Secure Channel

### Remote Attestation (RA)

Microsoft Azure Attestation service (MAA) for Attesting Trusted Execution Environments (TEEs):
[https://github.com/Azure-Samples/microsoft-azure-attestation](https://github.com/Azure-Samples/microsoft-azure-attestation)

Linux SGX remote attestation example including the communication with IAS:
[https://github.com/svartkanin/linux-sgx-remoteattestation](https://github.com/svartkanin/linux-sgx-remoteattestation)

OpenID Connect Via Enclave:
[https://github.com/DanielShteinbok/spring-oidc-conclave-authentication](https://github.com/DanielShteinbok/spring-oidc-conclave-authentication)

Intel Security Libraries for Data Center (Intel SecL-DC):
[https://github.com/intel-secl/intel-secl](https://github.com/intel-secl/intel-secl)
[SGX Caching Service](https://github.com/intel-secl/sgx-caching-service)
[SGX Quote Verification Service](https://github.com/intel-secl/sgx-verification-service)
[SGX Host Verification Service](https://github.com/intel-secl/sgx-hvs)
[SGX Hub](https://github.com/intel-secl/sgx-ah)
[SGX Agent](https://github.com/intel-secl/sgx_agent)

SGX Quote Verification Service, cloud-nativized:
[https://github.com/pw4ever/isecl-sqvs](https://github.com/pw4ever/isecl-sqvs)

OPERA: Open Remote Attestation for Intel's Secure Enclaves:
[https://github.com/Calctopia-OpenSource/opera](https://github.com/Calctopia-OpenSource/opera)

Intel end-to-end RA: [https://github.com/intel/sgx-ra-sample](https://github.com/intel/sgx-ra-sample)

Data Center Attestation Primitives (DCAP): [https://github.com/intel/SGXDataCenterAttestationPrimitives](https://github.com/intel/SGXDataCenterAttestationPrimitives)

RA-based TLS: [https://github.com/cloud-security-research/sgx-ra-tls](https://github.com/cloud-security-research/sgx-ra-tls)

IBM simplified RA without accessing IAS too frequently: [https://github.com/IBM/sgx-trust-management](https://github.com/IBM/sgx-trust-management)

Azure Attestation SGX Certification Cache: [https://github.com/Microsoft/Azure-DCAP-Client](https://github.com/Microsoft/Azure-DCAP-Client)

Enclave Mutual Attestation Library:
[https://github.com/AntonioDan/SGX_Enclave_Mutual_Attestation_Library](https://github.com/AntonioDan/SGX_Enclave_Mutual_Attestation_Library)


### SSL/TLS

Enclavised LibreSSL: [https://github.com/lsds/TaLoS](https://github.com/lsds/TaLoS)

Enclavised mbedTLS: [https://github.com/bl4ck5un/mbedtls-SGX](https://github.com/bl4ck5un/mbedtls-SGX)

Enclavised WolfSSL: [https://github.com/wolfSSL/wolfssl-examples](https://github.com/wolfSSL/wolfssl-examples)

Enclavised OpenSSL (Intel Official): [https://github.com/intel/intel-sgx-ssl](https://github.com/intel/intel-sgx-ssl)

SGX-OpenSSL (SGX-Tor Project): [https://github.com/sparkly9399/SGX-OpenSSL](https://github.com/sparkly9399/SGX-OpenSSL)

## Language Framework

Rust:

- [https://github.com/baidu/rust-sgx-sdk](https://github.com/baidu/rust-sgx-sdk)

- [https://github.com/fortanix/rust-sgx](https://github.com/fortanix/rust-sgx)

WebAssembly:

- Wasm interpreter in Rust: [https://github.com/mesalock-linux/wasmi-sgx](https://github.com/mesalock-linux/wasmi-sgx)

- Twine: An Embedded Trusted Runtime for WebAssembly: [https://github.com/jamesmenetrey/unine-twine](https://github.com/jamesmenetrey/unine-twine)

- WebAssembly Micro Runtime (WAMR): [https://github.com/bytecodealliance/wasm-micro-runtime](https://github.com/bytecodealliance/wasm-micro-runtime)

Python: 

- MesaPy: A Memory-Safe Python Implementation based on PyPy: [https://github.com/mesalock-linux/mesapy](https://github.com/mesalock-linux/mesapy)

- Python binder for SGX SDK: [https://github.com/adombeck/python-sgx](https://github.com/adombeck/python-sgx)

Golang:

- EGo: a framework for building confidential apps in Go:
[https://github.com/edgelesssys/ego](https://github.com/edgelesssys/ego)

- Golang: [https://github.com/intel/GrapheneSGX-Golang-Support-and-Enhancement](https://github.com/intel/GrapheneSGX-Golang-Support-and-Enhancement)

- Golang binder: [https://github.com/rupc/go-with-intel-sgx](https://github.com/rupc/go-with-intel-sgx) 

- GOTEE: Secured Routines using SGX: [https://github.com/epfl-dcsl/gotee](https://github.com/epfl-dcsl/gotee)

JavaScript: [https://github.com/evervault/node-secureworker](https://github.com/evervault/node-secureworker)

C#: [https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX](https://github.com/Liaojinghui/A_C-Sharp_Project_With_SGX)

Lua: [https://github.com/vschiavoni/SecureStreams-DEBS17](https://github.com/vschiavoni/SecureStreams-DEBS17)

Erlang: [https://github.com/Erlang-Enclave-Thesis/sgx-erlang-extension](https://github.com/Erlang-Enclave-Thesis/sgx-erlang-extension)

C++: [https://github.com/intel/linux-sgx](https://github.com/intel/linux-sgx)

PSec: Programming Language for Creating Secure Distributed Systems leveraging Intel SGX: [https://github.com/ShivKushwah/PSec](https://github.com/ShivKushwah/PSec)

## Blockchain

Automata Network: Web 3.0 Realized with Tracless Privacy and Seamless Compatibility:
[https://github.com/automata-network/automata](https://github.com/automata-network/automata)

Phala Blockchain: a blockchain-based confidential computing cloud:
[https://github.com/Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain)

lockbox: Key Share Management in SGX Secure Enclaves:
[https://github.com/commerceblock/lockbox](https://github.com/commerceblock/lockbox)

sWorker: Crust MPoW-based Offchain Storage inside TEE Enclaves:
[https://github.com/crustio/crust-sworker](https://github.com/crustio/crust-sworker)

Teechain: A Secure Payment Network with Asynchronous Blockchain Access:
[https://github.com/lsds/Teechain](https://github.com/lsds/Teechain)

Anonify: A blockchain-Agnostic Execution Environment with Privacy and Auditability:
[https://github.com/LayerXcom/anonify](https://github.com/LayerXcom/anonify)

Hyperledger: Confidentiality-Preserving, Off-Chain Smart Contracts:

[https://github.com/hyperledger-labs/private-data-objects](https://github.com/hyperledger-labs/private-data-objects)

[https://github.com/hyperledger/fabric-private-chaincode](https://github.com/hyperledger/fabric-private-chaincode)

substraTEE: Trusted Off-Chain Compute Framework for Substrate Blockchains:
[https://github.com/scs/substraTEE](https://github.com/scs/substraTEE)

eEVM: Enclave EVM as Ethereum Virtual Machine:
[https://github.com/Microsoft/eEVM](https://github.com/Microsoft/eEVM)

BitCoin Mixer:
[https://github.com/BitObscuro/Obscuro](https://github.com/BitObscuro/Obscuro)

Proof of Luck for IPFS:
[https://github.com/luckychain/lucky](https://github.com/luckychain/lucky)

Town Crier: An Authenticated Data Feed For Smart Contracts:
[https://github.com/bl4ck5un/Town-Crier](https://github.com/bl4ck5un/Town-Crier)

Ledger BOLOS Enclave:
[https://github.com/LedgerHQ/bolos-enclave](https://github.com/LedgerHQ/bolos-enclave)

## Machine Learning

Confidential Computing Zoo provides confidential computing solutions based on Intel SGX, TDX, HEXL, etc. technologies:
[https://github.com/intel/confidential-computing-zoo](https://github.com/intel/confidential-computing-zoo)

Enclave Hardening for Private ML (GBDT Learning + Differential Privacy):
[https://github.com/loretanr/dp-gbdt](https://github.com/loretanr/dp-gbdt)

Tensorflow Lite For Intel SGX:
[https://github.com/Jumpst3r/tensorflow-lite-sgx](https://github.com/Jumpst3r/tensorflow-lite-sgx)

An trusted and lite version of OpenCV based on Intel SGX:
[https://github.com/xymeng16/opencv_lite_sgx](https://github.com/xymeng16/opencv_lite_sgx)

Confidential ONNX Inference Server:
[https://github.com/microsoft/onnx-server-openenclave](https://github.com/microsoft/onnx-server-openenclave)

Secure Aggregation for Federated Learning:
[https://github.com/mc2-project/secure-aggregation](https://github.com/mc2-project/secure-aggregation)

Secure Collaborative Training and Inference for XGBoost:
[https://github.com/mc2-project/secure-xgboost](https://github.com/mc2-project/secure-xgboost)

Confidential Computing of Machine Learning using Intel SGX:
[https://github.com/prasadkjose/confidential-ml-sgx](https://github.com/prasadkjose/confidential-ml-sgx)

MesaTEE GBDT-RS: A Fast and Secure GBDT library:
[https://github.com/mesalock-linux/gbdt-rs](https://github.com/mesalock-linux/gbdt-rs)

TF-Trusted: Run TensorFlow Models in Secure Enclaves:
[https://github.com/capeprivacy/tf-trusted](https://github.com/capeprivacy/tf-trusted)

Bioinformatic Interpreter with Intel SGX: [https://github.com/hello31337/BI-SGX](https://github.com/hello31337/BI-SGX)

Accountable Deep Learning: [https://github.com/arefasvadi/SGX-ADL](https://github.com/arefasvadi/SGX-ADL)

Open Deep Learning Compiler Stack: [TVM in Intel SGX Example](https://github.com/dmlc/tvm/tree/master/apps/sgx)

Slalom: Fast, Verifiable and Private Execution of Neural Networks in Trusted Hardware (ICLR 2019)
[https://github.com/ftramer/slalom](https://github.com/ftramer/slalom)

EnclaveML: a framework for tokenized federated learning:
[https://github.com/jamslevy/enclaveML](https://github.com/jamslevy/enclaveML)

Plinius: Secure ML model training with Intel SGX and PM for fault tolerance:
[https://github.com/anonymous-xh/plinius](https://github.com/anonymous-xh/plinius)

SGX-Darknet: SGX compatible ML library:
[https://github.com/anonymous-xh/sgx-dnet](https://github.com/anonymous-xh/sgx-dnet)

## Common Libraries

A trusted libjpeg on Intel SGX:
[https://github.com/xymeng16/libtjpeg](https://github.com/xymeng16/libtjpeg)

ZLIB Data Compression Library inside SGX Enclaves:
[https://github.com/ffosilva/zlib-sgx](https://github.com/ffosilva/zlib-sgx)

Enclaved-FE: enable applications using Fentec Functional Encryption libraries ([CiFEr](https://github.com/fentec-project/CiFEr), [GoFE](https://github.com/fentec-project/gofe)) in Intel SGX:
[https://github.com/cryptohackathon/enclaved-FE](https://github.com/cryptohackathon/enclaved-FE)

Libsodium AES-NI based AES-256-GCM:
[https://github.com/Maxul/SGX-AES-256](https://github.com/Maxul/SGX-AES-256)

## Applications

SRX – SGX Recovery Extension:
[https://github.com/andrade/srx](https://github.com/andrade/srx)

Hidden anonymization with SGX-based mixes:
[https://github.com/oEscal/sgx-based-mix-networks](https://github.com/oEscal/sgx-based-mix-networks)

Black-Scholes-Merton computation in Intel SGX:
[https://github.com/sbellem/sgx-bsm](https://github.com/sbellem/sgx-bsm)

Avocado: a secure distributed in-memory key-value store:
[https://github.com/mbailleu/avocado](https://github.com/mbailleu/avocado)

Accelerating Encrypted Deduplication via SGX:
[https://github.com/jingwei87/sgxdedup](https://github.com/jingwei87/sgxdedup)

SGX-based Genome Variants Search:
[https://github.com/ndokmai/sgx-genome-variants-search](https://github.com/ndokmai/sgx-genome-variants-search)

SMac: Secure Genotype Imputation in Intel SGX:
[https://github.com/ndokmai/sgx-genotype-imputation](https://github.com/ndokmai/sgx-genotype-imputation)

SGXKaller: Private Contact Discovery Service:
[https://github.com/Arslan8/SGXKaller](https://github.com/Arslan8/SGXKaller)

Achieving Reconciliation between Privacy Preservation and Auditability For File Hosting (Intel SGX + IPFS + Hyperledger Fabric):
[https://github.com/wuliangshun/SGX-base-File-Hosting](https://github.com/wuliangshun/SGX-base-File-Hosting)

bwa-sgx-scone: a parallel privacy preserved [BWA](https://github.com/lh3/bwa)(DNA sequence alignment) solution using Intel SGX and SCONE:
[https://github.com/dsc-sgx/bwa-sgx-scone](https://github.com/dsc-sgx/bwa-sgx-scone)

Veracruz: privacy-preserving collaborative compute:
[https://github.com/veracruz-project/veracruz](https://github.com/veracruz-project/veracruz)

C3PO: providing security functions for Open Mobile Evolved Core (OMEC):
[https://github.com/omec-project/c3po](https://github.com/omec-project/c3po)

SafeTrace: Privacy Preserving Voluntary COVID-19 Self-Reporting Platform for Contact Tracing:
[https://github.com/enigmampc/SafeTrace](https://github.com/enigmampc/SafeTrace)

Hardware Secure Crypto Wallet for Ethereum and SKALE:
[https://github.com/skalenetwork/sgxwallet](https://github.com/skalenetwork/sgxwallet)

Private Contact Discovery Service for Signal:
[https://github.com/signalapp/ContactDiscoveryService](https://github.com/signalapp/ContactDiscoveryService)

Channel ID Private Key Protection:
[https://github.com/google/channel-id-enclave](https://github.com/google/channel-id-enclave)

Trustworthy and Accountable Function-as-a-Service:
[https://github.com/SSGAalto/sfaas](https://github.com/SSGAalto/sfaas)

Securing Storage Encryption:
[https://github.com/ayeks/TresorSGX](https://github.com/ayeks/TresorSGX)

## Network

Hidden anonymization with SGX-based mix-networks:
[https://github.com/oEscal/sgx-based-mix-networks](https://github.com/oEscal/sgx-based-mix-networks)

ZeroCache: a Cloud-Oriented Middlebox for Network Confidential Computing:
[https://github.com/Maxul/zerocache](https://github.com/Maxul/zerocache)

SnowHaze VPN Zero-Knowledge Verification:
[https://github.com/snowhaze/zka-sgx](https://github.com/snowhaze/zka-sgx)

MACSec: Secure Network Interface with SGX:
[https://github.com/fkirc/secure-network-interface-with-sgx](https://github.com/fkirc/secure-network-interface-with-sgx)

SENG: SGX-Enforced Network Gateway (USENIX Security 2020):
[https://github.com/sengsgx/sengsgx](https://github.com/sengsgx/sengsgx)

SGX + CDN (USENIX Security 2020):
[https://github.com/smherwig/phoenix](https://github.com/smherwig/phoenix)

ConsenSGX: Scaling Anonymous Communications Networks with Trusted Execution Environments (PETS 2019):
[https://github.com/sshsshy/ConsenSGX](https://github.com/sshsshy/ConsenSGX)

SGX + Snort Intrusion Detection System:
[https://github.com/cloud-security-research/sgx-ids](https://github.com/cloud-security-research/sgx-ids)

SafeBricks: Shielding Network Functions in the Cloud (NSDI 2018):
[https://github.com/YangZhou1997/SafeBricks](https://github.com/YangZhou1997/SafeBricks)

SGX + Tor (NSDI 2017):
[https://github.com/kaist-ina/SGX-Tor](https://github.com/kaist-ina/SGX-Tor)

SGX + Web Crawler:
[https://github.com/ShengHow95/simple-selenium-sgx-crawler](https://github.com/ShengHow95/simple-selenium-sgx-crawler)

## Data Analytics

Ryoan: A distributed sandbox for untrusted computation on secret data:
[https://github.com/ut-osa/ryoan](https://github.com/ut-osa/ryoan)

MC2: A Platform for Secure Analytics and Machine Learning:
[https://github.com/mc2-project/mc2](https://github.com/mc2-project/mc2)

Opaque: An encrypted data analytics platform:
[https://github.com/mc2-project/opaque-sql](https://github.com/mc2-project/opaque-sql)

Confidential Analytics on Azure SGX VM's with Apache Spark and SCONE:
[https://github.com/mdrakiburrahman/sgx-pyspark-sql-demo](https://github.com/mdrakiburrahman/sgx-pyspark-sql-demo)

BiORAM-SGX: A Practical Privacy-Preserving Data Analysis for Personal Genome by Intel SGX:
[https://github.com/cBioLab/BiORAM-SGX](https://github.com/cBioLab/BiORAM-SGX)

## Private Search

Snoopy: Surpassing the Scalability Bottleneck of Oblivious Storage:
[https://github.com/ucbrise/snoopy](https://github.com/ucbrise/snoopy)

mc-oblivious: Oblivious RAM inside of Intel SGX enclaves:
[https://github.com/mobilecoinofficial/mc-oblivious](https://github.com/mobilecoinofficial/mc-oblivious)

ZeroTrace: Oblivious Memory Primitives from Intel SGX:
[https://github.com/sshsshy/ZeroTrace](https://github.com/sshsshy/ZeroTrace)

X-Search: Revisiting Private Web Search using Intel SGX:
[https://github.com/Sand-jrd/SGX-Search](https://github.com/Sand-jrd/SGX-Search)

Private Information Retrieval:
[https://github.com/patrickwang96/BO-PIR-SGX](https://github.com/patrickwang96/BO-PIR-SGX)

Private SSE Schemes:
[https://github.com/MonashCybersecurityLab/SGXSSE](https://github.com/MonashCybersecurityLab/SGXSSE)

POSUP: Oblivious Search and Update Platform with SGX:
[https://github.com/thanghoang/POSUP](https://github.com/thanghoang/POSUP)

A Secure, Efficient and Scalable Query Framework for Outsourcing Data:
[https://github.com/fishermano/QShield](https://github.com/fishermano/QShield)

BISEN: Boolean Isolated Searchable Encryption:
[https://github.com/bernymac/BISEN](https://github.com/bernymac/BISEN)

## Private Key/Password Management

Key-Manager for Faasm (a high-performance stateful serverless runtime):
[https://github.com/faasm/keymanager](https://github.com/faasm/keymanager)

SGX Enabled OpenStack Barbican Key Management System:
[https://github.com/cloud-security-research/sgx-kms](https://github.com/cloud-security-research/sgx-kms)

A server with SGX enclave that stores private keys and performs crypto operations upon requests:
[https://github.com/cloud-key-store/keystore](https://github.com/cloud-key-store/keystore)

Protecting Web Passwords using Trusted Execution Environments:
[https://github.com/SafeKeeper](https://github.com/SafeKeeper)

## Encrypted Database

StealthDB: an encrypted database from intel sgx with small trusted computing base: [https://github.com/cryptograph/stealthdb](https://github.com/cryptograph/stealthdb)

Database intended for Blockchain: [https://github.com/kaimast/credb](https://github.com/kaimast/credb)

Protect in-memory sqlite, not .db file encryption: [https://github.com/yerzhan7/SGX_SQLite](https://github.com/yerzhan7/SGX_SQLite)

STANlite: an in-memory database engine for SGX-enabled secure data processing:
[https://github.com/ibr-ds/STANlite](https://github.com/ibr-ds/STANlite)

Protect Audit-Log via Sqlite: [https://github.com/lsds/LibSEAL](https://github.com/lsds/LibSEAL)

Trusted in-memory key-value stores: [https://github.com/cocoppang/ShieldStore](https://github.com/cocoppang/ShieldStore)

## Distributed Systems

SecDATAVIEW: A Secure Big Data Workflow Management System for Heterogeneous Computing Environments:
[https://github.com/shiyonglu/SecDATAVIEW](https://github.com/shiyonglu/SecDATAVIEW)

Oak: Meaningful Control of Data in Distributed Systems:
[https://github.com/project-oak/oak](https://github.com/project-oak/oak)

Memory Sharing Library for Intel SGX Card:
[https://github.com/cloud-security-research/memsharing-sgxcard](https://github.com/cloud-security-research/memsharing-sgxcard)

Kubernetes Device Plugin for Intel SGX:
[https://github.com/AliyunContainerService/sgx-device-plugin](https://github.com/AliyunContainerService/sgx-device-plugin)

SGX-Aware Container Orchestrator: [https://github.com/sebva/sgx-orchestrator](https://github.com/sebva/sgx-orchestrator)

ZooKeeper: [https://github.com/sereca/SecureKeeper](https://github.com/sereca/SecureKeeper)

VM-Migration: [https://github.com/SSGAalto/sgx-migration](https://github.com/SSGAalto/sgx-migration)

P2P: [https://bitbucket.org/P2PUsingSGX/p2pusingsgx](https://bitbucket.org/P2PUsingSGX/p2pusingsgx)

Raft: [https://github.com/LuminousXLB/EnclaveRaft](https://github.com/LuminousXLB/EnclaveRaft)

## Profiling

TEEMon: A continuous performance monitoring framework for TEEs: [https://github.com/rcrane/TEEMon](https://github.com/rcrane/TEEMon)

Utilities for monitoring SGX driver statistics: [https://github.com/fortanix/sgxtop](https://github.com/fortanix/sgxtop)

Report statistics of E/Ocalls, EPC Paging: [https://github.com/ibr-ds/sgx-perf](https://github.com/ibr-ds/sgx-perf)

Stress benchmark: [https://github.com/sebva/stress-sgx](https://github.com/sebva/stress-sgx)

nbench benchmark: [https://github.com/utds3lab/sgx-nbench](https://github.com/utds3lab/sgx-nbench)

LMbench benchmark: [https://github.com/vsecurity-research/sgx-bench](https://github.com/vsecurity-research/sgx-bench)

Linux SGX benchmarks (on encrypted buffer transfer): [https://github.com/eliadt/sgx_benchmarks](https://github.com/eliadt/sgx_benchmarks)

## Performance

rkt-io Library OS for running Linux applications inside of Intel SGX enclaves:
[https://github.com/Mic92/rkt-io](https://github.com/Mic92/rkt-io)

Flume: a blazingly fast multi-producer, multi-consumer channel: [https://github.com/occlum/flume](https://github.com/occlum/flume)

User-level paging: [https://github.com/acsl-technion/eleos](https://github.com/acsl-technion/eleos)

SwitchLess: [https://github.com/oweisse/hot-calls](https://github.com/oweisse/hot-calls)

SGXTuner: a distributed tuning system for enclaves: [https://github.com/dzobbe/sgxtuner](https://github.com/dzobbe/sgxtuner)

Actor model for better Enclave IPC: [https://github.com/ibr-ds/EActors](https://github.com/ibr-ds/EActors)

## Defenses

Repurposing Segmentation as a Practical LVI-NULL Mitigation in SGX (USENIX Security 2022):
[https://github.com/IAIK/LVI-NULLify](https://github.com/IAIK/LVI-NULLify)

SGXRay: Automated Vulnerability Finding in SGX Enclave Applications:
[https://github.com/baidu/sgxray](https://github.com/baidu/sgxray)

Collection of tools to perform memory analysis of machine SGX-enabled:
[https://github.com/tregua87/sgx-forensic](https://github.com/tregua87/sgx-forensic)

Open Enclave specific security automation projects (CodeQL static analysis, Fuzzing and binary analysis):
[https://github.com/openenclave/openenclave-security](https://github.com/openenclave/openenclave-security)

Auditee: a Tool to verify the reproducibility of SGX enclave builds:
[https://github.com/sbellem/auditee](https://github.com/sbellem/auditee)

Tamarin Models (Formal Verification) for State Continuity of Enclave Programs:
[https://github.com/OSUSecLab/SGX-Enclave-Formal-Verification](https://github.com/OSUSecLab/SGX-Enclave-Formal-Verification)

A Java flow analysis tool for SGX data sensitivity:
[https://github.com/SOF3/enclavlow](https://github.com/SOF3/enclavlow)

SGXL: Using 2MB large pages to mitigate page-based side-channels:
[https://github.com/csl-iisc/SGXL](https://github.com/csl-iisc/SGXL)

Obfuscuro: A Commodity Obfuscation Engine for Intel SGX (NDSS 2019):
[https://github.com/adilahmad17/Obfuscuro](https://github.com/adilahmad17/Obfuscuro)

CoSMIX: A Compiler-based System for Secure Memory Instrumentation and Execution in Enclaves (ATC 2019):
[https://github.com/acsl-technion/cosmix](https://github.com/acsl-technion/cosmix)

Citadel: Trusted Reference Monitors for Linux using Intel SGX Enclaves:
[https://github.com/HarriBellThomas/citadel](https://github.com/HarriBellThomas/citadel)

SGX Branch Shadowing Mitigation:
[https://github.com/SSGAalto/sgx-branch-shadowing-mitigation](https://github.com/SSGAalto/sgx-branch-shadowing-mitigation)

Enclave Protected Code Loader:
[https://github.com/intel/linux-sgx-pcl](https://github.com/intel/linux-sgx-pcl)

A code confidentiality framework for Intel SGX:
[https://github.com/utds3lab/sgxelide](https://github.com/utds3lab/sgxelide)

Deflection (CAT-SGX): Practical and Efficient in-Enclave Verification of Privacy Compliance:
[https://github.com/StanPlatinum/cat-sgx](https://github.com/StanPlatinum/cat-sgx)

Behavior-based Program Partitioning for Security Enclaves:
[https://github.com/anahitH/program-partitioning-for-security-enclaves](https://github.com/anahitH/program-partitioning-for-security-enclaves)

### Hardened Memory

Address space layout randomization (ASLR): [https://github.com/jaebaek/SGX-Shield](https://github.com/jaebaek/SGX-Shield)

Hardware transactional memory (TSX): [https://github.com/sslab-gatech/t-sgx](https://github.com/sslab-gatech/t-sgx)

Compiler-based boundary check: [https://github.com/tudinfse/sgxbounds](https://github.com/tudinfse/sgxbounds)

Linear/SQRT/Path ORAM: [https://github.com/maanrachid/SGXORAM](https://github.com/maanrachid/SGXORAM)

### I/O Protection

Building Distributed Enclave Applications with Sancus and SGX:
[https://github.com/sancus-pma/tutorial-dsn18](https://github.com/sancus-pma/tutorial-dsn18)

Fidelius: Protecting User Secrets from Compromised Browsers:
[https://github.com/SabaEskandarian/Fidelius](https://github.com/SabaEskandarian/Fidelius)

## Attacks

SmashEx: Smashing SGX Enclaves Using Exceptions (CCS 2021)

[https://github.com/cimcs/poc-exploits-of-smashex](https://github.com/cimcs/poc-exploits-of-smashex)

Interface-Based Side Channel Attack Against Intel SGX (INFOCOM 2022)

[https://github.com/sgx-interface-side-channel/sgx-interface-side-channel](https://github.com/sgx-interface-side-channel/sgx-interface-side-channel)

Frontal Attack: Leaking Control-Flow in SGX via the CPU Frontend (USENIX Security 2021)

[https://github.com/dn0sar/frontal_poc](https://github.com/dn0sar/frontal_poc)

VoltPillager: Hardware-based fault injection attacks against IntelSGX Enclaves using the SVID voltage scaling interface (USENIX Security 2021)

[https://github.com/zt-chen/voltpillager](https://github.com/zt-chen/voltpillager)

Faulty Point Unit: ABI Poisoning Attacks on Intel SGX (ACSAC 2020)

[https://github.com/fritzalder/faulty-point-unit](https://github.com/fritzalder/faulty-point-unit)

COIN Attacks: on Insecurity of Enclave Untrusted Interfaces in SGX (ASPLOS 2020)

[https://github.com/mustakcsecuet/COIN-Attacks](https://github.com/mustakcsecuet/COIN-Attacks)

Plundervolt: Software-based Fault Injection Attacks against Intel SGX (Oakland 2020)

[https://github.com/KitMurdock/plundervolt](https://github.com/KitMurdock/plundervolt)

SgxPectre Attacks: Stealing Intel Secrets from SGX Enclaves via Speculative Execution (EuroS&P 2019)

[https://github.com/OSUSecLab/SgxPectre](https://github.com/OSUSecLab/SgxPectre)

Spectre Attacks: Exploiting Speculative Execution (Oakland 2019)

[https://github.com/lsds/spectre-attack-sgx](https://github.com/lsds/spectre-attack-sgx)

RIDL: Rogue In-Flight Data Load (Oakland 2019)

[https://github.com/vusec/ridl](https://github.com/vusec/ridl)

ZombieLoad: Cross-Privilege-Boundary Data Sampling (CCS 2019)

[https://github.com/IAIK/ZombieLoad](https://github.com/IAIK/ZombieLoad)

SGX-ROP: Practical Enclave Malware with Intel SGX (DIMVA 2019)

[https://github.com/sgxrop/sgxrop](https://github.com/sgxrop/sgxrop)

MicroScope: enabling microarchitectural replay attacks (ISCA 2019)

[https://github.com/dskarlatos/MicroScope](https://github.com/dskarlatos/MicroScope)

Nemesis: Studying Microarchitectural Timing Leaks in Rudimentary CPU Interrupt Logic (CCS 2018)

[https://github.com/jovanbulck/nemesis](https://github.com/jovanbulck/nemesis)

Tutorial: Uncovering and mitigating side-channel leakage in Intel SGX enclaves (SPACE 2018)

[https://github.com/jovanbulck/sgx-tutorial-space18](https://github.com/jovanbulck/sgx-tutorial-space18)

SGX-Step: A practical attack framework for precise enclave execution control (SysTEX 2017)

[https://github.com/jovanbulck/sgx-step](https://github.com/jovanbulck/sgx-step)

Telling Your Secrets Without Page Faults: Stealthy Page Table-Based Attacks on Enclaved Execution (USENIX Security 2017)

[https://github.com/jovanbulck/sgx-pte](https://github.com/jovanbulck/sgx-pte)

SGX-Bomb: Locking Down the Processor via Rowhammer Attack (SysTEX 2017)

[https://github.com/sslab-gatech/sgx-bomb](https://github.com/sslab-gatech/sgx-bomb)

SGX-Timing: Cache Attacks on Intel SGX (EuroSec 2017)

[https://github.com/m1ghtym0/sgx-timing](https://github.com/m1ghtym0/sgx-timing)

## Beyond SGX Enclave Projects

Penglai-Enclave: Open-sourced secure and scalable TEE system for RISC-V:
[https://github.com/Penglai-Enclave/Penglai-Enclave](https://github.com/Penglai-Enclave/Penglai-Enclave)

Keystone: An Open-Source Secure Enclave Framework for RISC-V Processors:
[https://github.com/keystone-enclave/keystone](https://github.com/keystone-enclave/keystone)

MultiZone Security TEE for RISC-V processors:
[https://github.com/hex-five/multizone-sdk](https://github.com/hex-five/multizone-sdk)

AWS Nitro Enclaves: CPU and memory isolation for Amazon EC2 instances using Nitro Hypervisor:
[https://github.com/aws/aws-nitro-enclaves-cli](https://github.com/aws/aws-nitro-enclaves-cli)
