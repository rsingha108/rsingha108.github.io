
## About

I am a third‑year PhD student co‑advised by Todd Millstein and George Varghese with research interests in 
computer networks and systems, verification and testing of network protocol implementations, and building LLM-based pipelines.   More specifically, 
I work on synthesizing verifiably correct implementations using new modularity techniques, and testing network 
implementations using generative AI and symbolic execution. 

## Publications

* [CornerCase: Extremal Testing of Network Protocols using LLMs [Submitted to NSDI 2027]]
(Mentors: Ryan Beckett, Siva Kakarla, Todd Millstein, George Varghese)
Built an LLM-driven extremal testing framework that extracts validity constraints from RFCs and systematically generates boundary-case inputs for protocols such as HTTP, DNS, BGP, SMTP, and QUIC. Using differential testing across implementations, CornerCase uncovered 42 anomalies, including critical bugs such as redirect loops triggered by encoded null bytes in the h2o HTTP server; 26 issues have already been acknowledged and 18 fixed.

* [Eywa: Automating Model Based Testing using LLMs [Published at NSDI 2026]][paper](https://www.usenix.org/conference/nsdi26/presentation/mondal) [code](https://github.com/microsoft/Model_Based_Testing_Using_LLMs)  
(Mentors: Ryan Beckett, Siva Kakarla, Todd Millstein, George Varghese)  
Created a LLM-based tool to automatically generate models for network protocols like DNS and BGP; surprisingly, LLM errors enrich the test suite rather than affect coverage. Eywa found 33 unique bugs across widely used DNS, BGP, and SMTP implementations, 16 of which were previously undiscovered despite extensive prior testing with manually crafted models.

* [If Layering is useful, why not sublayering? [Published at HotNets 2024]](https://conferences.sigcomm.org/hotnets/2024/papers/hotnets24-309.pdf)  
(Mentors: Todd Millstein, Scott Shenker, George Varghese)  
Proposed recursively breaking up monolithic layers into simpler sublayers for ease of verification, debugging and principled hardware offload.  Proposed a new sublayering for TCP and showed sublayering could simplify verification for HDLC bit-stuffing using CoQ.

* [MESSI: Behavioral Testing of BGP Implementations [Published at NSDI 2024]][paper](https://www.usenix.org/system/files/nsdi24-singha.pdf) [code](https://github.com/rsingha108/MESSI)  
(Mentors: Ryan Beckett, Siva Kakarla, Todd Millstein, George Varghese)  
Automated testing of BGP Implementations such as Quagga, FRR, GoBGP, Batfish, by generating high coverage tests using symbolic execution and enumerative testing. Solved BGP-specific challenges due to statefulness, regular expressions, and incremental updates. Our tool found 22 bugs across 5 BGP implementations.

* [TransLIST : A Transformer-Based Linguistically Informed Sanskrit Tokenizer [Published at EMNLP 2022]](https://arxiv.org/pdf/2210.11753.pdf)  
(Mentors: Laxmidhar Behera, Pawan Goyal, IIT Kanpur)  
Developed a novel Sanskrit word segmentation model combining character-level input with latent word information and an ensemble-based constrained inference algorithm, achieving 1.8-point F-score and 7.2-point PM gains over SOTA.


## Internships

* **Microsoft Research Internship 2026:  Automated Network Protocol testing with Multi-Agent LLMs**  
(Mentor: Soheil Abbasloo)
Developed a dialectical multi-agent LLM framework for generating and refining test suites for Internet protocols such as BGP and DNS. Designed feedback-driven agents for test generation, evaluation, and refinement, achieving 95–100% test-suite quality within 2–3 cycles, while single-agent baselines mostly plateau below 80% even after 20 cycles.

* **Microsoft Research Internship 2024: Generating Models from Specifications using LLMs**  
(Mentor: Akash Lal)  
Developed a tool (MockGen) using an LLM to generate models (called mock implementations) as well as high-coverage test cases from OpenAPI specifications for Azure services such as DNS and BlockBlob. Unlike AutoMessi which uses symbolic execution, I used the LLM to directly generate tests and fed back the test results to the LLM to improve the mock. This achieved a mock accuracy of 95% relative to manually written mocks.

* **Microsoft Research Internship 2023: Securing Azure RBAC with Static Analysis** [Applied for Patent]  
(Mentors: Behnaz Arzani, Ryan Beckett, Nikolaj Bjorner, Siva Kakarla)  
Developed a static analysis tool for Azure RBAC to verify policies, detect duplicates, and generate exhaustive tests for Azure Implementations. We reduced the verification time for large policies from 30 minutes to 0.16s using various optimization algorithms. We also found 5 discrepancies across C\# and C++ implementations of Azure RBAC.

* **Intel Corporation 2022 : Auto Thresholding of Transport Traffic in MsQuic Library**  
(Mentor: Rong Pan, now VP at AMD)  
Implemented a novel algorithm in MsQuic to dynamically expedite mission-critical flows based on congestion, achieving 3x and 10x latency improvements for two Google Data Center workloads.


* **DAAD-WISE 2020 : Semantic Frame Identification**  
(Mentor: Chris Biemann, University of Hamburg)   
Enhanced semantic frame disambiguation using a fine-tuned BERT model, achieving a 1.2-point F-score improvement over SOTA on FrameNet data.










