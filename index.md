I am a third‑year PhD student co‑advised by Todd Millstein and George Varghese with research interests in 
computer networks and systems, formal verification, and building LLM-based pipelines.   More specifically, 
I work on synthesizing verifiably correct implementations using new modularity techniques, and testing network 
implementations using generative AI and symbolic execution. 

##Publications

1. Eywa: Automating Model Based Testing using LLMs [Submitted to SIGCOMM'25] \href{https://drive.google.com/file/d/1Qme1n7HAnF8ndsiEBORygyUZbRgRp-iD/view?usp=sharing}{[\textcolor{blue}{Link}]}} \newline
{Mentors: Ryan Beckett, Siva Kakarla, Todd Millstein, George Varghese}
Created a LLM-based tool to automatically generate models for network protocols like DNS and BGP; surprisingly, LLM errors enrich the test suite rather than affect coverage. We found 15 new bugs in 10 DNS implementations and 4 new bugs in 3 BGP implementations. 
}

\cvitem{June'24-Sept'24}{\textbf{Microsoft Research Internship: Generating Models from Specifications using LLMs} \newline
[\textit{Mentor: Akash Lal}] \newline 
Developed a tool (MockGen) using an LLM to generate models (called mock implementations) as well as high-coverage test cases from OpenAPI specifications for Azure services such as DNS and BlockBlob. Unlike AutoMessi which uses symbolic execution, I used the LLM to {\em directly} generate tests and {\em fed back} the test results to the LLM to improve the mock. This achieved a mock accuracy of 95\% relative to manually written mocks.
}

\cvitem{Sept'23-May'24}{\textbf{If Layering is useful, why not sublayering? [HotNets 2024, Presented Paper] \href{https://conferences.sigcomm.org/hotnets/2024/papers/hotnets24-309.pdf}{[\textcolor{blue}{Link}]}} \newline
[\textit{Mentors: Todd Millstein, Scott Shenker, George Varghese}] \newline 
Proposed recursively breaking up monolithic layers into simpler sublayers for ease of verification, debugging and principled hardware offload.  Proposed a new sublayering for TCP and showed sublayering could simplify verification for HDLC bit-stuffing using CoQ.
}

\cvitem{June'23-Sept'23}{\textbf{Microsoft Research Internship: Securing Azure RBAC with Static Analysis [Applied for Patent]}\newline
[\textit{Mentors: Behnaz Arzani, Ryan Beckett, Nikolaj Bjorner, Siva Kakarla}] \newline
Developed a static analysis tool for Azure RBAC to verify policies, detect duplicates, and generate exhaustive tests for Azure Implementations. We reduced the verification time for large policies from 30 minutes to 0.16s using various optimization algorithms. We also found 5 discrepancies across C\# and C++ implementations of Azure RBAC.
}

\cvitem{April'22-June'23}{\textbf{MESSI: Behavioral Testing of BGP Implementations [NSDI 2024, Presented paper] \href{https://www.usenix.org/system/files/nsdi24-singha.pdf}{[\textcolor{blue}{Link}]}}\newline
[\textit{Mentors: Ryan Beckett, Siva Kakarla, Todd Millstein, George Varghese}] \newline 
Automated testing of BGP Implementations such as Quagga, FRR, GoBGP, Batfish, by generating high coverage tests using symbolic execution and enumerative testing. Solved BGP-specific challenges due to statefulness, regular expressions, and incremental updates. Our tool found 22 bugs across 5 BGP implementations.
}

\cvitem{April'21-Sep'21}{\textbf{TransLIST : A Transformer-Based Linguistically Informed Sanskrit Tokenizer \newline [Published at EMNLP 2022] \href{https://arxiv.org/pdf/2210.11753.pdf}{[\textcolor{blue}{Link}]}}\newline
[\textit{Mentors: Laxmidhar Behera, Pawan Goyal, IIT Kanpur}] \newline 
Developed a novel Sanskrit word segmentation model combining character-level input with latent word information and an ensemble-based constrained inference algorithm, achieving 1.8-point F-score and 7.2-point PM gains over SOTA.
}





