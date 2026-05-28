---
layout: default
has_previous: true
special_theme: 'Special Theme: Evaluation of Multimodal Generation and Retrieval Systems'
---


## **The Second Workshop on Evaluation for Multimodal Generation**

<p style="text-align: justify;">
    Multimodal generation and retrieval systems are increasingly central to modern information retrieval, powering retrieval-augmented generation (RAG), multimodal search, recommendation, and knowledge-intensive applications. Despite rapid progress in multimodal large language models (MLLMs), robust and principled evaluation of multimodal generation and retrieval remains a major open challenge for the IR community. This workshop aims to foster discussions and research efforts by bringing together researchers and practitioners in information retrieval, natural language processing, computer vision, and multimodal AI. Our goal is to establish evaluation methods for multimodal research and advance research efforts in this direction.
</p>


## **Call for Papers**
<a id="call-for-papers"></a>

Both long paper and short papers (up to 9 pages and 4 pages respectively with unlimited references and appendices) are welcomed for submission. 

A list of topics relevant to this workshop (but not limited to):

- Multimodal retrieval for RAG, Agentic AI, recommendation systems

- Evaluation of retrieved cross-modal samples, without relying on augmented generation

- Multi-aspect evaluation methods capturing inter- and intra-modal coherence, relevance, grounding, and contextual consistency

- Benchmark retrieval datasets, evaluation protocols and annotations for text–image–audio–video–3D generation

- Automatic and human-centric metrics for informativeness, factuality, fluency, faithfulness, calibration, and usability for multimodal generation

- Methodology for detecting, analysing, and mitigating multimodal bias, stereotypes, toxicity, and hallucinations

- Evaluation in multimodal low-resource and multilingual settings, including culturally aware and cross-lingual metrics

- Agent-based evaluation of multimodal generation in multi-turn, tool-use, or iterative editing scenarios

- Game-theoretic or optimization-based formulations of evaluation objectives and protocols 

- Evaluation of the generation quality of synthetic multimodal data, provenance/attribution, and downstream impact on training and deployment

- Ethical considerations in the evaluation of multimodal text generation, including bias detection and mitigation strategies

- Evaluation of Security and Privacy Dimensions in Multimodal Applications

## **Invited Speakers**
<a id="invited-speakers"></a>


<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; width: 30%; text-align: center;">
      <h3><a href="https://marksanderson.org/">Mark Sanderson</a></h3>
      <img src="/assets/img/MarkSanderson_00139_head.jpg" alt="Mark Johnson" style="border-radius: 50%; max-width: 100%; height: auto;"><br>
    </td>
    <td style="border: none; width: 70%; text-align: left;">
      <p style="text-align: justify;">
          <h3> Talk Title: Evaluating information access? Don't forget the questions</h3> <br>
          Mark Sanderson is Professor of Information Retrieval at RMIT University and Dean of Research for the STEM College, with a Ph.D. in Computer Science from the University of Glasgow. His influential work spans search snippets, imageCLEF, information retrieval, data analysis, and recommender systems, earning over 15,000 Google Scholar citations and induction into the ACM SIGIR Academy in 2024. <br><br>
The evaluation of information access systems will often require the creation of benchmark datasets, made up of components such as sets of documents, sets of questions, and sets of labels that indicate notion such as relevance, accuracy, readability, etc. Much focus is on ways of creating the labels efficiently. This is not just a recent area of interest, it has often been the focus a great deal of research effort. But what of the other components of a benchmark? One component that receives less attention than perhaps it should are questions. Traditionally, the formation of these questions was not given a great deal of thought this despite significant evidence indicating that question design is of critical importance to the creation of benchmarks that are valid. In this talk, I will briefly outline the history of benchmark creation discussing why questions have not received a great deal of attention. I will then highlight a series of research projects but have been undertaken over the last few years at RMIT examining the importance of questions and their integration into benchmark design.
      </p>
    </td>
  </tr>
</table>


<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; width: 30%; text-align: center;">
        <h3><a href="http://www.mysmu.edu/faculty/jingjiang/">Jing Jiang</a></h3>
        <img src="/assets/img/JJ_Photo.jpg" alt="Jing Jiang" style="border-radius: 50%; max-width: 100%; height: auto;"><br>
    </td>
    <td style="border: none; width: 70%; text-align: left;">
        <p style="text-align: justify;">
          <h3> Talk Title: Evaluation of Pre-trained Vision-Language Models</h3> <br>
      Jing Jiang is a Professor in the School of Computing at the Australian National University, previously serving as Professor of Computer Science at Singapore Management University. Her research focuses on applied natural language processing, and she has held major editorial and conference leadership roles, including EMNLP 2019 program co-chair and Editor-in-Chief of ACL Rolling Review. <br><br>
            Recent years have witnessed remarkable progress in natural language processing and computer vision, powered by pre-trained foundation models that have demonstrated strong generalization capabilities for downstream tasks. In this talk I will discuss our work on evaluating pre-trained vision-language models from a few unique angles including their potential social biases and their cultural understanding.
      </p>
    </td>
  </tr>
</table>

<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; width: 30%; text-align: center;">
        <h3><a href="https://www.microsoft.com/en-us/research/people/pathom/">Paul Thomas</a></h3>
        <img src="/assets/img/paul_thomas.jpg" alt="Paul Thomas" style="border-radius: 50%; max-width: 100%; height: auto;"><br>
    </td>
    <td style="border: none; width: 70%; text-align: left;">
        <p style="text-align: justify;">
          <h3> Talk Title: Evaluating Multimodal Conversation at Scale</h3> <br>
            Paul Thomas is a senior applied scientist at Microsoft, where he works on measurement for Bing and other products. His research focuses on information retrieval, especially how people use and evaluate web search systems. <br> <br>
      Microsoft 365 Copilot helps millions of people around the world find, summarise, create, and edit digital artefacts of many types. Measuring and improving Copilot’s quality relies on constant and in-depth evaluations, but these evaluations are made difficult by precisely the same features that make the product interesting: it is multimodal, multilingual, multiturn, serving a huge number and diversity of people, and with strong guarantees on data protection and privacy. In this talk I’ll outline some of the challenges of evaluating such a system at scale, and some of the techniques we have developed to help understand and improve the product.
      </p>
    </td>
  </tr>
</table>

<table style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td style="border: none; width: 30%; text-align: center;">
        <h3><a href="https://cs.adelaide.edu.au/~javen/">Javen Shi</a></h3>
        <img src="/assets/img/javen_shi_cropped.jpg" alt="Javen Shi" style="border-radius: 50%; max-width: 100%; height: auto;"><br>
    </td>
    <td style="border: none; width: 70%; text-align: left;">
        <p style="text-align: justify;">
          <h3> Talk Title: The Hidden Intervention: How Cross-Modal Pairing Encodes the Causal Structure of Reality</h3> <br>
Professor Javen Qinfeng Shi is Founding Director of the Causal AI Group and a director at the Australian Institute for Machine Learning, with research spanning causation, AI, mind, and metaphysics. He is highly ranked in probabilistic graphical models and causation, and his award-winning work has been applied across industries including materials, agriculture, mining, health, education, and bushfire response. <br> <br>
        Every image paired with a caption, every video paired with a narration, every sound paired with its source: these are not accidents of annotation. They are windows into the causal structure of the world, natural experiments in which one facet of reality is perturbed while the underlying generative essence is held in place. In this talk, I advance the argument that cross-modal pairing is, at its core, a form of intervention, and that multimodal representation learning is, implicitly, both causal discovery and causal representation learning. By making this implicit causality explicit, we gain the ability to identify and disentangle latent variables that govern perception across modalities, and to build representations that are robust, interpretable, and grounded in the deep structure of how the world generates its appearances. This causal grounding also illuminates the mechanisms behind domain adaptation and distribution shift, revealing which features remain invariant across environments and how representations and mappings evolve when they do not. Ultimately, a system that has learned the true causal structure of its training signal is not merely memorising associations, but constructing a faithful world model, one capable of simulating the consequences of unseen interventions and generalising with the fluency and flexibility that natural intelligence embodies.
      </p>
    </td>
  </tr>
</table>

## **Submission Instructions**
<a id="submission"></a>

<p style="text-align: justify;">
We welcome both ARR paper commitment and direct paper submission.
More details on ARR paper commitment will be coming soon.
For direct paper submission, you are invited to submit your papers in our <a href="https://openreview.net/group?id=ACM.org/SIGIR/2026/Workshop/EvalMG">OpenReview portal</a>. 
For ARR paper commitment, you can submit your papers in the dedicated <a href="https://openreview.net/group?id=ACM.org/SIGIR/2026/Workshop/EvalMG_ARR_Commitment">paper commitment page on OpenReview</a>.
Papers are required to strictly follow the <a href="https://sigir2026.org/en-AU/pages/submissions/full-papers-track">SIGIR submission guidelines</a>.
We invite both <a href="https://sigir2026.org/en-AU/pages/submissions/full-papers-track">long papers</a> (9 pages) and <a href="https://sigir2026.org/en-AU/pages/submissions/short-papers-track">short papers</a> (4 pages) submissions. 
All the submitted papers have to be anonymous for double-blind review.  
</p>

**Direct Submission:** https://openreview.net/group?id=ACM.org/SIGIR/2026/Workshop/EvalMG

**ARR Commitment:** https://openreview.net/group?id=ACM.org/SIGIR/2026/Workshop/EvalMG_ARR_Commitment

### ![NEW](https://img.shields.io/badge/NEW-orange?style=flat) ***SIGIR'26 Fast Track Option***
We welcome SIGIR'26 submissions that were not accepted to submit both the paper and review comments (as attachments) to our direct submission portal. Please note that submissions without the review will lead to a desk reject. 

### ***Non-archival Option***
<p style="text-align: justify;">
To promote discussions within the community, our workshop includes a non-archival track. 
Authors have the flexibility to submit their papers accepted to other conferences (e.g., ACL, EMNLP, WWW, KDD, SIGIR) to our workshop. 
Accepted non-archival submissions will be offered the opportunity to give oral or poster presentation, and will not be included in the workshop proceedings. 
</p>

## **Important Dates**
<a id="important-dates"></a>

- Mar 25, 2026: Submission Open

- May 2, 2026: Workshop Paper Direct Submission Deadline

- May 27, 2026: ARR Commitment & SIGIR Fast-track Submission Deadline

- June 2, 2026: Workshop Paper Notification

- July 24, 2026: Workshop Day

Note: All deadlines are 11:59PM UTC-12:00 (“Anywhere on Earth”)

## **Organisers**
<a id="organizers"></a>

- <a href="https://weiezhang.github.io/">Wei Emma Zhang</a>, Adelaide University
- <a href="https://iang.io/">Xiang Dai</a>, CSIRO
- <a href="https://people.csiro.au/K/S/Sarvnaz-Karimi">Sarvnaz Karimi</a>, Monash & CSIRO
- <a href="https://elliottd.github.io/">Desmond Elliot</a>, University of Copenhagen
- <a href="https://biaoyanf.github.io/">Byron Fang</a>, Oracle
- <a href="https://www.linkedin.com/in/mongyuansim/">Mong Yuan Sim</a>, Adelaide University & CSIRO

## **Sponsor**
<a id="sponsor"></a>

<p style="text-align: center;">
    <img src="/assets/img/RAIR-Lockup_CMYK_2-lines.png" alt="RAIR Logo" style="max-width: 90%; height: auto;">
</p>


## **Previous Edition**
- <a href="/2025/">EvalMG25 @ COLING 2025</a>
