<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

<script>
  MathJax = {
    tex: {
      inlineMath: [['$', '$']]
    }
  };
</script>
# The ideal materialist

$$\left(\frac{1}{10^{5}}\sum_{n=-\infty}^{+\infty}e^{-n^{2}/10^{10}}\right)^{2}\simeq\pi$$

The above [formula](https://www.researchgate.net/publication/242433843_GET_BILLIONS_AND_BILLIONS_OF_CORRECT_DIGITS_OF_PI_FROM_A_WRONG_FORMULA) gives accurately *42 billion* digits of $\pi$ and fails around 43 billions.

Approximation theory is the key to understand most of today's technological world, including ML. A wonderful inway into that *mycelium concept* is [Chebfun](https://my.siam.org/Store/Product/viewproduct/?ProductId=31254869), a paradigm I have been working within for quite some time now.

## Links to some interesting links related to me and my work

1. The [Tricomi Chebfun Tomography algorithmic pipeline](https://superfri.org/index.php/superfri/article/view/111).
2. The [Ars Technica series of articles](https://arstechnica.com/science/2011/07/running-high-performance-neural-networks-on-a-gamer-gpu/) on my work (with students) at the cutting edge of ML in 2011, with Gamer GPUs - thanks Adam for your excellent journalism!
3. [LinkedIn profile](https://www.linkedin.com/in/yann-le-du-3308609a/).
4. [Twitter HQ](https://twitter.com/Yann_Le_Du) where I often post about the AI/LLM revolution, and about Shakti/k.
5. [Medium posts](https://medium.com/@yann.ledu.fr).
6. [Collected non private publications](https://scholar.google.com/citations?user=b4JXA28AAAAJ&hl=en) in Google Scholar.
7. My very successful recent foray into the industry took place at [MWM, a wonderful French software company](https://mwm.io/) where I worked on big data statistical modeling and ML. 
8. My [last century's software startup](https://www.infogreffe.fr/entreprise-societe/413813874-synsoft-750197B130190000.html) which I dreamed would be a new Netscape, and where we developed software for Tactile Screen Cashiers which I thought would take over the market.
9. [Github profile](https://github.com/ianxek), with an eclectic asortment of old and newer code, most of the code is not shown because it belongs to the CNRS or, more recently, to MWM. Btw, *ianxek* is my name in [Lojban](https://mw.lojban.org/index.php?title=Lojban&setlang=en-US)!
10. My [literate programming mode in Vim](https://gitlab.com/hpu/codoc) called *Kosmogram*
11. My [CodeAbbey profile](https://www.codeabbey.com/index/user_profile/ianxek). Love that site, will do all the problems.

## Thoughtshots

1. [Why Vim is my best editor.](why_vim.md)
2. [The birth of SaCzilla](saczilla001_modified_fibo.md) : post 01 in the study of the [SaC programming
   language](https://www.sac-home.org/doku.php)

## Philosophy

> _The more the universe seems comprehensible, the more it seems pointless._
>
> Steven weinberg, _Dreams of a final Theory_

> _We counter existential dread with optimistic nihilism._
>
> Kurzgesagt, [_Optimistic Nihilism_](https://youtu.be/MBRqu0YOH14)

Because both [Bernardo
Kastrup](https://www.bernardokastrup.com/2013/04/why-materialism-is-baloney-overview.html) and [Richard Dawkins](https://www.amazon.com/Magic-Reality-Know-Whats-Really/dp/1451675046) are right.

Read [Eisenstein](https://ascentofhumanity.com/) : probably the best summary of our global
condition.

The way our ancestors viewed and felt the world is forever gone. Non-civilized humans are fast
disappearing, their habitat being slowly but certainly destroyed. The civilized human condition is
not to be dreamed, but to be lived and hopefully driven.

## Why write ?

Because I want to share my thoughts, and sharing is the force that pulls thoughts out of the void.

_Sharing is to thought what the event horizon is to a singularity : this is where thought radiates._

## Me

Yes, I'm a physicist, of the ideal materialist kind which means I love computing and everything ML.

With over 20 years of experience in both academia and industry, I am confident in my ability to make a positive contribution to both academia and industry, as long as it has meaning in the grand scheme of things. My long-standing familiarity with Machine Learning dates back to 2000 when I began a postdoc in Oxford's Theoretical Physics Department. There, I pioneered a data processing pipeline in observational cosmology with artificial neural networks to detect rare events in massive datasets. I was aware that ANNs could outperform my previous work, but only if properly trained on my modeling results, and began using SNNS together with ANNs crafted in C. My supervisor in Oxford was amazed at the power of the approach, but the Universal Approximation capacity of ANNs was not widely recognized, to say the least. I persevered, and this insight was validated by subsequent publications, and the later GPU revolution of 2012, which significantly reduced processing time, confirmed that I was on the right track, even though my approach was ahead of its time.

ML has always been in my toolbox since then, as I will detail below, and I have more recently turned my attention more specifically both to fast.ai (Jeremy Howard's “Practical Deep Learning”) and, in my current job, porting Pytorch code to JAX. I think I possess a unique combination of skills, that of theoretical physics with computing and ML in all its declinations, from hand coded ANNs to high level ML libraries. Indeed, I have a Master's degree in Theoretical Physics and a PhD in Observational Cosmology: the latter's “observational” component highlights that I have always balanced my theoretical investigations with code implementation and data acquisition, because I believe this is the ideal combination of thought and reality check. Donald Knuth says it best: “Science is what we understand well enough to explain to a computer; art is everything else.”

As a Research Engineer at CNRS in France, I was also a lead engineer for the Electron Paramagnetic Resonance (EPR) platform. I introduced the Chebfun “processing functions instead of data” approach, originally developed by the Numerical Analysis group at Oxford, allowing for interpolation with arbitrary data sampling and achieving 10x data compression with 15-digit accuracy. This allowed me to make significant contributions to the field, including the development of Chebfun-based EPR computed tomography which resulted in a 10x speed increase and 3x better resolution, which also means I have extensive knowledge of image processing. I also collected and mined EPR data using KDB, Python, and SQL, increasing spectrum storage and retrieval by 100x. Additionally, I designed and implemented a hardware/software module for faster data acquisition using the Chebfun paradigm. Taken together, those achievements demonstrate my expertise in mathematical modeling, statistics, and data analytics.

Always on the lookout for opportunities to apply ML, I used Python, Julia, and CUDA to optimize and mine EPR data, leading to the creation of a project that leverages ANNs to curate expert knowledge into automatic spectrum analysis with 100x productivity and 75% accuracy. That required I design and assemble (with a team of CS masters students interns I selected and led) a large hybrid CPU/GPU cluster able to handle the highly demanding computing tasks (right around the 2012 GPU revolution and the emergence of CUDA). This also allowed me to further develop novel algorithms for EPR statistical computed tomography to improve medical diagnostics by allowing selection of image features to get a probability of existence, always keeping hold both of the theoretical and practical sides.

Thanks to being responsible for the EPR platform for material science R&D, I have extensive experience in working with a diverse range of clients and companies. Indeed, I managed the instrument's budget, maintenance, and upgrades, and ensured the instrument was in good working order to meet the needs of external clients. I understand the constraints and reporting requirements in industry, and was able to balance these with the need for timely completion of work and careful budget planning.

Later and more recently, in my role in the industry as a Senior Research Engineer for transverse R&D at the MWM software company, I leverage my experience in academia and problem-solving skills to contribute to the development of various domains, especially ML and Data Science. I actually designed, developed, and put into production a statistical prediction framework in Python/Pandas/BigQuery for user LTV in Business Intelligence, reducing the time for exhaustive statistical information from 10s of hours to just 7 minutes. I also used my physics background in optimization to produce a reliable quasi James-Stein estimator of combined sources mean, and performed a fully documented automated analysis of large BigQuery tables for business applications using Python within the fast.ai Nbdev framework, together with OpenCV. This last project also showcases my ability to communicate effectively and translate technical findings to non-technical stakeholders, as well as my commitment to writing clean, well-documented code. Indeed, I value working in teams of people with a range of skills, from technical to non-technical. I have excellent interpersonal and communication skills, and I am confident in my ability to collaborate effectively with colleagues and stakeholders.

Throughout my career, I have thus developed a range of technical skills and abilities in mathematical modeling, statistics, data analytics, and machine learning, including more recently deep learning with a feasibility study of porting Pytorch code (for source separation in music applications) to JAX. I have proven experience in solving real-world problems both in academia and industry with data using for example Python, C, and BigQuery, and am thus fully proficient in Python and Pandas. I believe the best approach combines mathematical insight with AI (an intersection where LLMs now play a crucial role in my own workflow), which in practice means, for example, applying deep learning to tasks that previously required a model-oriented approach; this has been the direction of my work also in the industry where the deadlines are much tighter than in academia and require a subtle equilibrium between exploration and producing results.

## Programming

As for programming languages I use anything physicists use plus :

* [Cone](https://cone.jondgoodwin.com/),
* [ATS](http://www.ats-lang.org/),
* [SaC](https://www.sac-home.org/doku.php).

## Contact

_Find me_ : I hang around on the [Cone](https://discord.gg/4RdwshKW) &
[ATS](https://discord.gg/3CBHQzTk) channels on Discord, and the [SaC channel on
Slack](https://sac-ylc6885.slack.com/).

_Contact me_ : ianxek@{name of positively charged nucleon}mail.com

