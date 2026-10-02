---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a <span class="hl">Postdoctoral Fellow at the [ETH AI Center](https://ai.ethz.ch/)</span>, working on AI safety and the trustworthy application of AI in industrial domains. I earned my Ph.D. in Applied Mathematics from [Harvard University's John A. Paulson School of Engineering and Applied Sciences](https://seas.harvard.edu/), and my alma mater is [NYU Courant](https://cims.nyu.edu/dynamic/).

<div class="research-box">
  <p>My research focuses on <span class="hl">trustworthy AI for decision-making</span> and <span class="hl">AI safety</span>. I develop frameworks and methods that enable machine learning and foundation models to operate responsibly in the real world, with the goal of making AI <span class="hl">reliable, accountable, and safe</span> when deployed in high-stakes domains.</p>
  <p>My recent work addresses the following questions:</p>
  <ol>
    <li>
      <span class="rq">How can we make autonomous AI systems capable, reliable, and safe in complex multi-agent environments?</span>
      <span class="rq-work">Focusing on supply chains, I built the <a href="https://infotheorylab.github.io/beer-game/">first live LLM-powered simulation of the Beer Game</a>, a multi-echelon testbed, and showed that autonomous GenAI agents can <a href="https://arxiv.org/pdf/2605.17036">cut costs by up to 80%</a> compared to human teams. I then identified a key risk, <em>agent bullwhip</em>: agents make inconsistent decisions in identical situations, and this instability compounds across the supply chain into occasional outsized errors. I developed guardrails and reinforcement learning post-training methods that <a href="https://arxiv.org/pdf/2605.17036">mitigate this unreliability</a>.</span>
    </li>
    <li>
      <span class="rq">Who is accountable for what AI generates, and how can we enforce that accountability?</span>
      <span class="rq-work">I co-developed <a href="https://arxiv.org/pdf/2602.07235">ArcMark</a>, a distortion-free multi-bit watermark that embeds multiple bytes of information, such as user or model IDs, into just a few hundred tokens, so that generated text can be traced back to its source. I also developed zero-bit watermarks that detect AI-generated text with high accuracy and minimal distortion, including the <a href="https://openreview.net/pdf?id=Lnij8CaFFO">Correlated-Channel watermark</a> and <a href="https://arxiv.org/pdf/2506.06409">HeavyWater and SimplexWater</a>, revealing new connections between LLM watermarking and coding theory.</span>
    </li>
    <li>
      <span class="rq">How can we make AI-assisted decisions trustworthy and unbiased for every individual?</span>
      <span class="rq-work">I showed that equally accurate models can make <a href="https://openreview.net/pdf?id=nzkWhoXUpv">conflicting, arbitrary predictions for the same individual</a>, and that common bias-mitigation interventions can amplify this arbitrariness. I also characterized the <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=DGQASc8AAAAJ&citation_for_view=DGQASc8AAAAJ:d1gkVwhDpl0C">limits of verifying personalized models</a>, and developed <a href="https://drops.dagstuhl.de/storage/00lipics/lipics-vol329-forc2025/LIPIcs.FORC.2025.7/LIPIcs.FORC.2025.7.pdf">Kernel Multiaccuracy</a>, a one-step method to correct biased predictions across many subgroups at once.</span>
    </li>
  </ol>
</div>

<div class="keywords">
  <span class="keywords-label">Keywords:</span>
  <span class="keyword">AI Safety</span>
  <span class="keyword">Agentic AI</span>
  <span class="keyword">Multi-Agent Systems</span>
  <span class="keyword">LLM Watermarking</span>
  <span class="keyword">AI for Supply Chain Management</span>
  <span class="keyword">AI for Manufacturing</span>
  <span class="keyword">Model Multiplicity</span>
  <span class="keyword">Algorithmic Fairness</span>
</div>

I have published in leading venues across machine learning, information theory, and management, including **NeurIPS**, **IEEE ISIT**, and **Harvard Business Review**.

# News

<ul class="news-list">
  <li><span class="news-date">Sep 2026</span><span>Received the <span class="hl">NUS Global Postdoctoral Award</span> with the Department of Industrial Systems Engineering and Management (ISEM), College of Design and Engineering, National University of Singapore.</span></li>
  <li><span class="news-date">Sep 2026</span><span><a href="https://arxiv.org/pdf/2602.07235">ArcMark: Distortion-Free Multi-Byte LLM Watermark via Optimal Transport</a> was accepted at <span class="hl">NeurIPS 2026</span>. ArcMark reliably embeds <span class="hl">multiple bytes of information</span>, such as a <span class="hl">user ID or model version</span>, into just a few hundred tokens without distorting the LLM's output.</span></li>
  <li><span class="news-date">May 2026</span><span>New paper: <a href="https://arxiv.org/pdf/2605.17036">Reliability and Effectiveness of Autonomous AI Agents in Supply Chain Management</a>. We identify <span class="hl"><em>agent bullwhip</em></span>, where decision instability compounds across autonomous agents into outsized errors, and show that <span class="hl">guardrails and reinforcement learning post-training</span> mitigate it.</span></li>
  <li><span class="news-date">Mar 2026</span><span><a href="https://www.linkedin.com/feed/update/urn:li:activity:7445995138574835712/">Defended</a> my <span class="hl">Ph.D. thesis</span>, <a href="https://www.proquest.com/docview/3350090589?pq-origsite=gscholar&amp;fromopenview=true&amp;sourcetype=Dissertations%20&amp;%20Theses">Trustworthy AI: Ensuring Reliability and Accountability from Models to Agents</a>.</span></li>
  <li><span class="news-date">Feb 2026</span><span>Presented <a href="https://infotheorylab.github.io/beer-game/">Can GenAI Agents Manage a Supply Chain?</a> at the <a href="https://mitsloan.mit.edu/faculty/academic-groups/system-dynamics/about-us">MIT Sloan System Dynamics Seminar</a> and the USI SD Research Lab.</span></li>
  <li><span class="news-date">Dec 2025</span><span>Published <a href="https://hbr.org/2025/12/when-supply-chains-become-autonomous">When Supply Chains Become Autonomous</a> in <span class="hl">Harvard Business Review</span> (<a href="https://infotheorylab.github.io/beer-game/assets/GenAI_Final_Version_w_Plots.pdf">full paper with plots</a>). We introduce a testbed based on the MIT Beer Game, in which GenAI agents <span class="hl">autonomously manage a multi-echelon supply chain</span>, and evaluate their performance.</span></li>
  <li><span class="news-date">Sep 2025</span><span>Launched the <a href="https://infotheorylab.github.io/beer-game/">first live simulation of the Beer Game powered by LLMs</a>, a joint project of Harvard, MIT, and Georgia Tech (Harvard Information Theory Lab, MIT Data Science Lab, and Georgia Tech Scheller College of Business).</span></li>
  <li><span class="news-date">Jul 2025</span><span>Presented <a href="https://openreview.net/pdf?id=Lnij8CaFFO">Optimized Couplings for Watermarking Large Language Models</a> (<a href="https://drive.google.com/file/d/1saeZGgbkPrfPqT27g1ZuH94EyA5nYcwK/view?usp=sharing">slides</a>) at <span class="hl">ISIT 2025</span>, University of Michigan.</span></li>
  <li><span class="news-date">Jun 2025</span><span>Presented <a href="https://drops.dagstuhl.de/storage/00lipics/lipics-vol329-forc2025/LIPIcs.FORC.2025.7/LIPIcs.FORC.2025.7.pdf">Kernel Multiaccuracy</a> (<a href="https://drive.google.com/file/d/10pvZUYim2P6dt-fN83yG5ugle4DBKDMT/view?usp=sharing">slides</a>) at <span class="hl">FORC 2025</span>, Stanford University.</span></li>
</ul>

# Publications 
- [ArcMark: Distortion-Free Multi-Byte LLM Watermark via Optimal Transport](https://arxiv.org/pdf/2602.07235)\
Atefeh Gilani, Sajani Vithana, **Carol Xuan Long**, Oliver Kosut, Lalitha Sankar, Flavio P Calmon\
Advances in Neural Information Processing Systems (**NeurIPS**), 2026.
  <details><summary><strong>TL/DR</strong></summary>
  <p>We formulate distortion-free watermarking as a channel coding problem and derive its information-theoretic capacity. Guided by this limit, we propose **ArcMark**, which embeds multiple bytes of information into a few hundred tokens without distorting the next-token distribution, and outperforms competing multi-bit watermarks in reconstruction accuracy, including under attacks.</p>
  </details>

- [Reliability and Effectiveness of Autonomous AI Agents in Supply Chain Management](https://arxiv.org/pdf/2605.17036)\
**Carol Xuan Long**, David Simchi-Levi, Feng Zhu, Huangyuan Su, Andre P Calmon, Flavio P Calmon\
Preprint, 2026.
  <details><summary><strong>TL/DR</strong></summary>
  <p>In the MIT Beer Game, GenAI agents reduce total supply chain costs by up to 80% relative to human teams, but can exhibit large run-to-run instability. We characterize this as **agent bullwhip** and show that reinforcement learning post-training and operational guardrails both reduce tail events and mitigate it.</p>
  </details>

- [When Supply Chains Become Autonomous](https://hbr.org/2025/12/when-supply-chains-become-autonomous)\
**Carol Xuan Long**, David Simchi-Levi, Andre P Calmon, Flavio P Calmon\
Harvard Business Review, 2025.

- [HeavyWater and SimplexWater: Watermarking Low-Entropy Text Distributions](https://arxiv.org/pdf/2506.06409?)\
Dor Tsur\*, **Carol Xuan Long**\*, Claudio M. Verdun, Hsiang Hsu, Chen-Fu Chen, Haim Permuter, Sajani Vithana, Flavio P Calmon\
Advances in Neural Information Processing Systems (**NeurIPS**), 2025.
  <details><summary><strong>TL/DR</strong></summary>
  <p>Our goal is to design watermarks that optimally use side information to maximize detection accuracy and minimize distortion of generated text. We propose two watermarks **HeavyWater** and **SimplexWater** that achieve SOTA performance. Our theoretical analysis also reveals surprising new connections between LLM watermarking and **coding theory**.</p>
  </details>

- [Optimized Couplings for Watermarking Large Language Models](https://openreview.net/pdf?id=Lnij8CaFFO), [(slides)](https://drive.google.com/file/d/1saeZGgbkPrfPqT27g1ZuH94EyA5nYcwK/view?usp=sharing)\
**Carol Xuan Long**\*, Dor Tsur\*, Claudio M. Verdun, Hsiang Hsu, Haim Permuter, Flavio P Calmon\
IEEE International Symposium on Information Theory (**ISIT**), 2025.
  <details><summary><strong>TL/DR</strong></summary>
  <p>We argue that a key component in watermark design is generating a coupling between the side information shared with the watermark detector and a random partition of the LLM vocabulary. Our analysis identifies the optimal coupling and randomization strategy under the worst-case LLM next-token distribution that satisfies a min-entropy constraint. We propose the **Correlated-Channel watermarking scheme** --- a closed-form scheme that achieves high detection at zero distortion.</p>
  </details>

- [Kernel Multiaccuracy](https://drops.dagstuhl.de/storage/00lipics/lipics-vol329-forc2025/LIPIcs.FORC.2025.7/LIPIcs.FORC.2025.7.pdf), [(slides)](https://drive.google.com/file/d/10pvZUYim2P6dt-fN83yG5ugle4DBKDMT/view?usp=sharing)\
**Carol Xuan Long**, Wael Alghamdi, Alexander Glynn, Yixuan Wu, Flavio P Calmon\
Foundations of Responsible Computing (**FORC**), 2025.
  <details><summary><strong>TL/DR</strong></summary>
  <p>We connect multi-group notions with *Integral Probability Metrics*, and propose **KMAcc** --- a non-iterative, one-step optimization to correct multiaccuracy errors in the kernel space.</p>
  </details>

- [Predictive Churn with the Set of Good Models](https://arxiv.org/pdf/2402.07745)\
Jamelle Watson-Daniels, Flavio P Calmon, Alexander D’Amour, **Carol Xuan Long**, David C. Parkes, Berk Ustun\
Under Review, 2024.
  <details><summary><strong>TL/DR</strong></summary>
  <p>We study the effect of predictive churn — flips in predictions across ML model updates — through the lens of predictive multiplicity – i.e., the prevalence of conflicting predictions over the set of near-optimal models (the ε-Rashomon set). </p>
  </details>

- [Multi-Group Proportional Representation in Retrieval](https://openreview.net/pdf?id=BRZYhVHvSg)\
Alex Osterling, Claudio M Verdun, **Carol Xuan Long**, Alexander Glynn, Lucas Monteiro Paes, Sajani Vithana, Martina Cardone, Flavio P Calmon\
Advances in Neural Information Processing Systems (**NeurIPS**), 2024.
  <details><summary><strong>TL/DR</strong></summary>
  <p>We introduce Multi-Group Proportional Representation (MPR), a novel metric that measures representation across intersectional groups. We propose practical methods and algorithms for estimating and ensuring MPR in image retrieval, with minimal compromise in retrieval accuracy. </p>
  </details>

- [Individual Arbitrariness and Group Fairness](https://openreview.net/pdf?id=nzkWhoXUpv)\
**Carol Xuan Long**, Hsiang Hsu, Wael Alghamdi, Flavio P Calmon\
Advances in Neural Information Processing Systems (**NeurIPS**), 2023, **Spotlight Paper**.
  <details><summary><strong>TL/DR</strong></summary>
  <p>Fairness interventions in machine learning optimized solely for group fairness and accuracy can exacerbate predictive multiplicity. A third axis of “arbitrariness” should be considered when deploying models to aid decision-making in applications of individual-level impact. </p>
  </details>

<!-- <pre><code>
@inproceedings{long2023individual,
  title={Individual Arbitrariness and Group Fairness},
  author={Long, Carol Xuan and Hsu, Hsiang and Alghamdi, Wael and Calmon, Flavio},
  booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
  year={2023}
}</code></pre> -->

- [On the epistemic limits of personalized prediction](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=DGQASc8AAAAJ&citation_for_view=DGQASc8AAAAJ:d1gkVwhDpl0C)\
Lucas Monteiro Paes\*, **Carol Long**\*, Berk Ustun, Flavio Calmon (* Equal Contribution)\
Advances in Neural Information Processing Systems (**NeurIPS**), 2022.
  <details><summary><strong>TL/DR</strong></summary>
  <p>It is impossible to reliably verify that a personalized classifier with $k \geq 19$ binary group attributes will benefit every group that provides personal data using a dataset of $n = 8 × 10^9$ samples – one for each person in the world. </p>
  </details>


<!-- <pre><code>
@article{monteiro2022epistemic,
  title={On the epistemic limits of personalized prediction},
  author={Monteiro Paes, Lucas and Long, Carol and Ustun, Berk and Calmon, Flavio},
  journal={Advances in Neural Information Processing Systems},
  volume={35},
  pages={1979--1991},
  year={2022}
}</code></pre> -->

# Beyond Research
Outside of work, I am a globetrotter, dancer, and music-lover. Growing up as a swimmer, I enjoy sports. From completing a half-marathon and recovering from an ACL injury, I’ve collected many stories to tell (for better or worse!). Whenever I can, I head outdoors --- my top three U.S. national parks are Yellowstone, the Grand Canyon, and Mount Rainier. 

<!-- Outside of work, I am a globaltrotter, dancer, and music-lover. Growing up as a swimmer, I enjoy sports. From completing a half-marathon and recovering from an ACL injury, for better or worse, I do have many stories to tell. Of course, I also love cooking Canton/Singaporean food and reading away in the comfort of home!  -->