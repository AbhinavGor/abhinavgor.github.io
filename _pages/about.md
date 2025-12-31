---
permalink: /
title: "Abhinav Gorantla"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Abhinav Gorantla is a Ph.D student in Computer Science at [Arizona State University](https://scai.engineering.asu.edu), working with [Prof. K. Selçuk Candan](https://kscandan.site) in the [EMIT Lab](https://emitlab.github.io). He recently completed his M.S. in Computer Science at ASU. His research focuses on algorithms and systems for causal and generative machine learning, with an emphasis on causal benchmarking frameworks, multi-objective optimization (Skyline/Pareto-style selection).

He also has experience as a full-stack web developer and applied ML engineer. He is a co-author of [CausalBench](https://causalbench.org), a flexible benchmarking platform for causal machine learning that received the Best Demo Award at [ACM CIKM 2024](https://dl.acm.org/doi/proceedings/10.1145/3627673).

## Research 

My research lies at the intersection of causal machine learning, multi-objective optimization, and generative models. I am especially interested in:

- **Causal benchmarking and systems.** Designing and maintaining [CausalBench](https://causalbench.org), a benchmarking framework and service for causal learning algorithms (causal discovery, causal inference, and interpretability).
- **Multi-objective optimization & skyline queries.** Studying efficient Skyline/Pareto-style retrieval in relational data, including how causal structure can impact efficiency of Pareto-style retrieval algorithms.

## Education 

* **Doctor of Philosophy** in Computer Science, Arizona State University, **starting Jan 2026** (incoming)  
  * Advisor: Prof. K. Selçuk Candan  
* **Master of Science** in Computer Science, Arizona State University, Dec 2025  
  * GPA: 4.00/4.00
  * Advisor: Prof. K. Selçuk Candan  
* **Bachelor of Technology** in Computer Science and Engineering, Vellore Institute of Technology, May 2023  
  * GPA: 8.98/10.00

## Experience
* **August 2024 - Now**: Graduate Research Assistant at [Emitlab](https://emitlab.github.io), [School of Computing and Augmented Intelligence, ASU](https://scai.engineering.asu.edu/)
  * Developing an optimized algorithm for efficient Skyline retrieval in relational database systems.
  * Collaborating with researchers at CASCADE Lab to maintain and improve [causalbench.org](https://causalbench.org), a platform dedicated to causal discovery benchmarks.
  * Built a causal-analysis recommendation system; led end-to-end integration and serverless deployment on AWS Lambda; published at [**CIKM 2025**](https://cikm2025.org/).

* **August 2024 - May 2025**: Graduate Teaching Assistant at [School of Computing and Augmented Intelligence, ASU](https://scai.engineering.asu.edu/)
  * Assisted in CSE515 and CSE510 graduate-level computer science courses.


* March 2024 – August 2024: Graduate Services Assistant at [Emitlab](https://emitlab.github.io), [School of Computing and Augmented Intelligence, ASU](https://scai.engineering.asu.edu/)
  * Helped develop the `causalbench` Python package and causalbench.org website as an end-to-end benchmarking solution for the causal machine learning community.  
  * Served as a full-stack developer on CausalBench, integrating datasets, models, and metrics into a unified evaluation workflow.  
  * Redesigned the backend architecture for the Skysong project, enabling responsive causal analyses in production (≈80% faster response times, ≈30% lower deployment cost via AWS SageMaker).

* April 2022 – June 2023: SDE Intern at Webknot Technologies Pvt. Ltd.
  * Revamped API endpoints within the Palette project, achieving a notable 30% reduction in response times.
  * Fine-tuned data flow for the DeckGL plugin within Sisense by elevating the efficiency of JAQL queries, ensuring a smoother and more responsive user experience.
  * Engineered a custom plugin for Sisense BI software, enabling the seamless display of geojson data on a GeoJSON layer atop maps rendered via DeckGL.


## Publications

1. A. Kapkıç, P. Mandal, **A. Gorantla**, S. Wan, E. Çoban, P. Sheth, H. Liu, and K. S. Candan.  
   “CausalBench-ER: Causally-Informed Explanations and Recommendations for Reproducible Benchmarking.”  
   *Proceedings of the 34th ACM International Conference on Information and Knowledge Management (CIKM ’25)*,  
   Seoul, Republic of Korea, Nov 10–14, 2025, pp. 6426–6431.  
   [[paper]](https://doi.org/10.1145/3746252.3761606)
2. A. Kapkıç, P. Mandal, **A. Gorantla**, S. Wan, E. Çoban, P. Sheth, H. Liu, and K. S. Candan.  
   “CausalBench: Causal Learning Research Streamlined.”  
   *Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ’25), Vol. 2*,  
   Toronto, Canada, Aug 3–7, 2025, pp. 6239–6240.  
   [[paper]](https://doi.org/10.1145/3711896.3737598) [[tutorial site]](https://tutorial.causalbench.org/) [[slides]](https://tutorial.causalbench.org/resources/KDD25_Tutorial_Deck.pdf) [[video]](https://www.youtube.com/watch?v=oGA2kf4Trg4)
3. A. Kapkıç, P. Mandal, S. Wan, P. Sheth, **A. Gorantla**, Y. Choi, H. Liu, and K. S. Candan.  
   “Introducing CausalBench: A Flexible Benchmark Framework for Causal Analysis and Machine Learning.”  
   *Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM 2024)*, pp. 5220–5224, 2024. (🏆 Best Demo Paper Award)  
   [[paper]](https://doi.org/10.1145/3627673.3679218) [[website]](https://docs.causalbench.org)

## Tutorials

* **CausalBench: Causal Learning Research Streamlined** – Tutorial at KDD 2025, Toronto, Canada.  
  Overview of causal machine learning, challenges in benchmarking, and hands-on use of the CausalBench platform.  
  [[tutorial site]](https://tutorial.causalbench.org/) [[slides]](https://tutorial.causalbench.org/resources/KDD25_Tutorial_Deck.pdf) [[video]](https://www.youtube.com/watch?v=oGA2kf4Trg4)


## Community Service & Outreach
* **Student Volunteer**, ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2025)

## Projects

1. **Research Publications Analysis tool**
   - Proposed an architecture and built a research publications analysis tool for ASU. This tool was built as a web application which could fetch research paper information affiliated with ASU using SCOPUS APIs and perform a text analysis on their abstracts.
   - Reduced the server response time by 80% and improved the user experience by integrating RabbitMQ message queues in the system.
   - **Tech stack used:** ReactJS, NodeJS, Python-FastAPI, RabbitMQ, MongoDB, AWS S3, AWS Sagemaker, OpenAI APIs.
2. **Multimodal Image Retrieval System using Advanced Feature Analysis and Search Techniques**
   - Developed a Python-based image retrieval engine encompassing feature extraction from Caltech101 dataset images, latent semantics computation, clustering, and classification.
   - Employed Locality Sensitive Hashing to index image features, optimizing nearest neighbor searches and ensuring scalability for expansive image datasets.
3. **Enhancing Diversity in the LLM Modulo Framework through Multi-Response Generation**
   - Developed the Diversified LLM Modulo framework to address looping and redundancy in the LLM Modulo framework.
   - Improved the performance of the LLM Modulo Framework on Planning tasks. Tested my framework on the [Google Deepmind Natural Plan benchmark](https://github.com/google-deepmind/natural-plan) and achieved a performance improvement of 300% by increasing the diversity of LLM (Large Language Model) Responses.

<!-- [![Visit tracker](https://mapmyvisitors.com/map.png?cl=ffffff&w=a&t=t&d=WZOKWdh_jqsLTegV7MhXolepLGxHeA92Gxx2VcwD_hQ&co=2d78ad&ct=ffffff)](https://mapmyvisitors.com/web/1bwk8 "Visit tracker") -->