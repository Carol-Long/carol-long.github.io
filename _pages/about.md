---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hello! I am a final-year Ph.D. candidate at Harvard University, advised by [Flavio du Pin Calmon](http://people.seas.harvard.edu/~flavio/). I develop robust and reliable solutions that enable trustworthy adoption of AI across critical domains. I am currently on the job market for positions starting in September 2026, with a preference for opportunities in Europe.

My research focuses on **reliable, responsible and trustworthy Machine Learning**, and my work spans GenAI Agents, supply chain management, LLM watermarking, algorithmic fairness, multiplicity, and more. I use tools and frameworks from Optimization, Information Theory, Probability, and Statistics. 
I am open for collaborations and can be reached via email!


I received my undergraduate degree in Math and Computer Science at [NYU Courant](https://cims.nyu.edu/dynamic/) and my industry experience includes [Citadel LLC](https://www.citadel.com) and [Meta](https://about.meta.com).

# News 

### September 2025
- 🚀 Can GenAI agents🤖 manage a supply chain? Lessons from the classical beer game.
- 🎯 A joint team from Harvard Information Theory Lab, MIT Data Science Lab, and GeorgiaTech Scheller College of Business has built 𝘁𝗵𝗲 𝗳𝗶𝗿𝘀𝘁 𝗹𝗶𝘃𝗲 𝘀𝗶𝗺𝘂𝗹𝗮𝘁𝗶𝗼𝗻 𝗼𝗳 𝘁𝗵𝗲 𝗕𝗲𝗲𝗿 𝗚𝗮𝗺𝗲 𝗽𝗼𝘄𝗲𝗿𝗲𝗱 𝗯𝘆 𝗟𝗟𝗠𝘀. 
- 👉 Try the interactive simulation [here](https://infotheorylab.github.io/beer-game/).

### July 2025 
- 🎤 Presented [Optimized Couplings for Watermarking Large Language Models](https://openreview.net/pdf?id=Lnij8CaFFO) [(slides)](https://drive.google.com/file/d/1saeZGgbkPrfPqT27g1ZuH94EyA5nYcwK/view?usp=sharing) at IEEE International Symposium on Information Theory @ University of Michigan.

### Jun 2025
- 🎤 Presented [Kernel Multiaccuracy](https://drops.dagstuhl.de/storage/00lipics/lipics-vol329-forc2025/LIPIcs.FORC.2025.7/LIPIcs.FORC.2025.7.pdf) [(slides)](https://drive.google.com/file/d/10pvZUYim2P6dt-fN83yG5ugle4DBKDMT/view?usp=sharing) at Foundations of Responsible Computing @ Stanford University.


# Publications 
- [HeavyWater and SimplexWater: Watermarking Low-Entropy Text Distributions](https://arxiv.org/pdf/2506.06409?)\
Dor Tsur\*, **Carol Xuan Long**\*, Claudio M. Verdun, Hsiang Hsu, Chen-Fu Chen, Haim Permuter, Sajani Vithana, Flavio P Calmon\
Under Review, 2025.
  <details><summary><strong>TL/DR</strong></summary>
  <p>Our goal is to design watermarks that optimally use side information to maximize detection accuracy and minmize distortion of generated text. We propose two watermarks **HeavyWater** and **SimplexWater** that achieve SOTA performance. Our theoretical analysis also reveals surprising new connections between LLM watermarking and **coding theory**.</p>
  </details>

- [Optimized Couplings for Watermarking Large Language Models](https://openreview.net/pdf?id=Lnij8CaFFO), [(slides)](https://drive.google.com/file/d/1saeZGgbkPrfPqT27g1ZuH94EyA5nYcwK/view?usp=sharing)\
**Carol Xuan Long**\*, Dor Tsur\*, Claudio M. Verdun, Hsiang Hsu, Haim Permuter, Flavio P Calmon\
IEEE International Symposium on Information Theory (**ISIT**), 2025.
  <details><summary><strong>TL/DR</strong></summary>
  <p>We argue that a key component in watermark design is generating a coupling between the side information shared with the watermark detector and a random partition of the LLM vocabulary. Our analysis identifies the optimal coupling and randomization strategy under the worst-case LLM next-token distribution that satisfies a min-entropy constraint. We propose the **Correlated-Channel watermarking scheme** --- a closed-form scheme that achieve high detection at zero distortion.</p>
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
  <p>We study the effect of predictive churn - flip in predictions over ML model updates - through the lens of predictive multiplicity – i.e., the prevalence of conflicting predictions over the set of near-optimal models (the ε-Rashomon set). </p>
  </details>

- [Multi-Group Proportional Representation in Retrieval](https://openreview.net/pdf?id=BRZYhVHvSg)\
Alex Osterling, Claudio M Verdun, **Carol Xuan Long**, Alexander Glynn, Lucas Monteiro Paes, Sajani Vithana, Martina Cardone, Flavio P Calmon\
Advances in Neural Information Processing Systems (**NeurIPS**), 2024.
  <details><summary><strong>TL/DR</strong></summary>
  <p>We introduce Multi-Group Proportional Representation (MPR), a novel metric that measures representation across intersectional groups. We propose practical methods and algorithms for estimating and ensuring MPR in image retrieval, with minimal compromise in retrieval accuracy. </p>
  </details>

- [Individual Arbitrariness and Group Fairness](https://openreview.net/pdf?id=nzkWhoXUpv)\
**Carol Xuan Long**, Hsiang Hsu, Wael Alghamdi, Flavio P Calmon\
Advances in Neural Information Processing Systems (**NeurIPS**), 2023, <span style="color:red">**Spotlight Paper**</span>.
  <details><summary><strong>TL/DR</strong></summary>
  <p>Fairness interventions in machine learning optimized solely for group fairness and accuracy can exacerbate predictive multiplicity. A third axis of ``arbitrariness'' should be considered when deploying models to aid decision-making in applications of individual-level impact. </p>
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

# Misc
Outside of work, I am a globetrotter, dancer, and music-lover. Growing up as a swimmer, I enjoy sports. From completing a half-marathon and recovering from an ACL injury, I’ve collected many stories to tell (for better or worse!). Whenever I can, I head outdoors --- my top three U.S. national parks are Yellowstone, the Grand Canyon, and Mount Rainier. 

<!-- Outside of work, I am a globaltrotter, dancer, and music-lover. Growing up as a swimmer, I enjoy sports. From completing a half-marathon and recovering from an ACL injury, for better or worse, I do have many stories to tell. Of course, I also love cooking Canton/Singaporean food and reading away in the comfort of home!  -->