---
layout: home
order: 1
permalink: /
title: Workshop 2023
# redirect_from: /index.html
desc_title: Backdoors in Deep Learning @ NeurIPS 2023
description: <strong>The Good, the Bad and the Ugly</strong> - Modern AI development requires using and sharing of models and data safely. Uncovering backdoor, a foe and a friend at the front door.
social: true
---

<!-- **UPDATE**: fill out this form if you are interested in a post-workshop social: [https://forms.gle/XjeSVmyHnsp7EmLB6](https://forms.gle/XjeSVmyHnsp7EmLB6). -->

<!-- ### Schedule (Meeting Room 317A, 9 AM - 5 PM, July 29, 2023) -->
### Schedule (Coming Soon)

<!-- ⭐ **Link to ICML page: [https://icml.cc/virtual/2023/workshop/21499](https://icml.cc/virtual/2023/workshop/21499)** ⭐ -->


<!-- |---------------------|----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| Start Time (GMT-10, Hawaii)          | Session                                                                                | Speaker(s)                                                                            |
|---------------------|----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| 9:00 am | Opening Remarks                                                                        | Organizers                                                                            |
|---------------------|----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| 9:05 am | Invited talk 1                                                                         | Johannes Ballé |
| 9:35 am | Invited talk 2                                                                        | Tsachy Weissman  |
| 10:05 am | Coffee break                                                                           |  |
| 10:20 am | Invited talk 3                                                                                |José Miguel Hernández-Lobato |
| 10:50 am | Oral 1                                                                                |Neural Distributed Compressor Does Binning |
| 11:10 am  | Panel discussion                                                                     | Ashish Khisti, Ties van Rozendaal, George Toderici, Rashmi Vinayak |  |
| 11:55 am | Lunch break
|---------------------|----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| 12:55 pm | Invited talk 4                                                                         | Hyeji Kim |
| 1:25 pm | Oral 2                                                                                | Entropy Coding of Unordered Data Structures |
| 1:45 pm | Invited talk 4                                                                         | Yan Lu |
| 2:15 pm | Poster session                                                                          | |
|---------------------|----------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| 3:45 pm | Invited talk 5                                                                     | Aaron Wagner |
| 4:15 pm | Oral 3                                                                                | Neural Image Compression: Generalization, Robustness, and Spectral Bias |
| 4:35 pm | Oral 4                                                                     | Slicing Mutual Information Generalization Bounds for Neural Networks |
| 4:55 pm   | Closing Remarks                                                                        | Organizers    | -->

### Call for Papers


We cordially invite submissions and participation in our “Backdoors in Deep Learning: The Good, the Bad, and the Ugly” workshop (neurips2023-bugs.github.io) that will be held on December 15 or 16, 2023 at NeurIPS 2023, New Orleans, USA. 

The submission deadline is **September 29, 2023, 23:59 AoE** and the submission link <a href="https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/BUGS">https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/BUGS</a>.

#### Motivation and Topics

Deep neural networks (DNNs) are revolutionizing almost all AI domains and have become the core of many modern AI systems. Despite their superior performance compared to classical methods, DNNs also face new security problems, such as adversarial and backdoor attacks, that are hard to discover and resolve due to their black-box-like property. Backdoor attacks are possible because of insecure model pretraining and outsourcing practices. Due to the complexity and the tremendous cost of collecting data and training models, many individuals/companies employ models or training data from third parties. Malicious third parties can add backdoors into their models or poison their released data before delivering it to the victims to gain illegal benefits. This threat seriously damages the safety and trustworthiness of AI development.

While most works consider backdoors “evil”, some studies leverage them for good purposes. A popular approach is to use the backdoor as a watermark to detect illegal uses of commercialized data/models. Watermarks can also be used to mark generated data, which becomes crucial with the introduction of big generative models (LLMs, text-to-image generators). For instance, the paper “A Watermark for Large Language Models” has received an outstanding paper award at ICML 2023, showing the community’s great interest in this critical topic. Besides, a few works employ the backdoor as a trapdoor for adversarial defense. Learning the underlying working mechanisms of backdoors also elevates our understanding of how deep learning models work.
This workshop is designed to provide a comprehensive understanding of the current state of backdoor research. Our goal is to foster discussion and perspective exchange, as well as to engage the community in identifying social good applications of backdoors. As such, we welcome submissions related to any aspect of backdoor research, including but not limited to:


* Backdoor attacks
  * Poisoning attacks
  * Dirty-label backdoor attacks
  * Clean-label backdoor attacks
  * Backdoors in various learning paradigms (supervised, semi-supervised, self-supervised)
  * Backdoors in various computer vision tasks (object detection, segmentation)
  * Backdoors in multimodal models (vision+language)
  * Backdoors in federated learning
  * Backdoors in NLP and less-studied domains (speech, graphs)
  * Backdoors in generative models (e.g., Diffusion models)
  * Backdoors in Large Language Models
* Backdoor defenses
  * Backdoor detection (poisoned inputs, poisoned models) - Backdoor mitigation (data sanitization, model repair)
  * Understanding backdoor behaviors
* Backdoor for social good
  * Watermarking (for IP Protection, Ownership Verification, Generative Data Marking, etc...)
  * Trapdoor/Honeypot defenses
  * Model unlearning
  * Deep model behavior understanding

The workshop will employ a double-blind review process. Each submission will be evaluated based on the following criteria:

* Soundness of the methodology
* Relevance to the workshop
* Societal impacts

We only consider submissions that haven’t been published in any peer-reviewed venue, including NeurIPS 2023 conference. **We allow dual submissions with other workshops or conferences. The workshop is non-archival and will not have any official proceedings**. All accepted papers will be allocated either a poster presentation or a talk slot.
 
<!-- ### Call for Reviewers
Please fill out this [Google form](https://docs.google.com/forms/d/e/1FAIpQLSd3L9_o7vAZUSWjWMxi18jZHuIrBaafUBm6v1fTZQorK2o9Qw/viewform) if you are interested in reviewing for the workshop.

🏆 **2 free ICML 2023 workshop registrations will be given as "Best Reviewer Awards"** 🏆 -->

### Important Dates

* **Submission deadline**: September 29, 2023, 11:59 PM Anywhere on Earth (AoE)
* **Author notification**: October 27, 2023
* **Camera-ready deadline**: December 1, 2023, 11:59 PM Anywhere on Earth (AoE)
* **Workshop date**: TBD

### Submission Instructions

Papers should be submitted to OpenReview: <a href="https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/BUGS">https://openreview.net/group?id=NeurIPS.cc/2023/Workshop/BUGS</a>

Submitted papers should have up to 6 pages (excluding references, acknowledgments, or appendices). Please use the NeurIPS submission template provided at <a href="https://neurips.cc/Conferences/2023/PaperInformation/StyleFiles">https://neurips.cc/Conferences/2023/PaperInformation/StyleFiles</a>.
Submissions must be anonymous following NeurIPS double-blind reviewing guidelines, NeurIPS Code of Conduct, and Code of Ethics. Accepted papers will be hosted on the workshop website but are considered non-archival and can be submitted to other workshops, conferences, or journals if their submission policy allows.


<!-- **Submission website: [OpenReview](https://openreview.net/group?id=ICML.cc/2023/Workshop/NCW)**

We solicit short workshop paper submissions of up to 4 pages + unlimited references/appendices. Please format submissions in ICML style. Submissions will be double blind: reviewers cannot see author names when conducting reviews, and authors cannot see reviewer names.

Some accepted papers will be accepted as contributed talks. All accepted posters are expected to be presented in-person at the poster session, and all papers published via Openreview after the workshop.

This workshop will not have formal proceedings, so we welcome the submission of work currently under review at other archival ML venues. We also welcome the submission of work recently published in information theory venues (e.g. Transactions on Information Theory, ISIT, ITW) that may be of interest to an ML audience. However, we will not consider work recently published in or accepted to other archival ML venues (e.g. ICML main conference). -->

### Speakers (Coming Soon)

<!-- <table style="width:75%">
  <tr>
    <td style="text-align:center"><img src="assets/img/johannes_balle.png" height="175"></td>
    <td style="text-align:center"><img src="assets/img/jose_hernandez-lobato.jpg" height="175"></td>
    <td style="text-align:center"><img src="assets/img/hyeji_kim.png" height="175"></td>
    <td style="text-align:center"><img src="assets/img/yan_lu.jpg" height="175"></td>
  </tr>
  <tr>
    <td style="text-align:center"><a href="https://balle.io">Johannes Ballé</a> <br> Research Scientist, Google</td>
    <td style="text-align:center"><a href="https://jmhl.org">José Miguel Hernández-Lobato</a> <br> Professor, Cambridge</td>
    <td style="text-align:center"><a href="https://sites.utexas.edu/hkim/">Hyeji Kim</a> <br> Assistant Professor, UT Austin</td>
    <td style="text-align:center"><a href="https://www.microsoft.com/en-us/research/people/yanlu/">Yan Lu</a> <br> Partner Research Manager, Microsoft Research Asia</td>
  </tr>
  <tr>
    <td style="text-align:center"><img src="assets/img/aaron_wagner.jpg" height="175"></td>
    <td style="text-align:center"><img src="assets/img/tsachy_weissman.png" height="175"></td>
  </tr>
  <tr>
    <td style="text-align:center"><a href="https://www.ece.cornell.edu/faculty-directory/aaron-b-wagner">Aaron Wagner</a> <br> Professor, Cornell</td>
    <td style="text-align:center"><a href="https://web.stanford.edu/~tsachy/">Tsachy Weissman</a> <br> Professor, Stanford</td>
  </tr>
</table> -->

### Panelists (Coming Soon)

<!-- <table style="width:75%">
  <tr>
    <td style="text-align:center"><img src="assets/img/ashish_khisti.jpg" height="175"></td>
    <td style="text-align:center"><img src="assets/img/ties_van_rozendaal.jpg" height="175"></td>
    <td style="text-align:center"><img src="assets/img/george_toderici.jpg" height="175"></td>
    <td style="text-align:center"><img src="assets/img/rashmi_vinayak.jpg" height="175"></td>
  </tr>
  <tr>
    <td style="text-align:center"><a href="https://www.ece.utoronto.ca/people/khisti-a/">Ashish Khisti</a> <br> Professor, University of Toronto</td>
    <td style="text-align:center"><a href="http://www.tivaro.nl/">Ties van Rozendaal</a> <br> Senior Deep Learning Researcher, Qualcomm</td>
    <td style="text-align:center"><a href="https://research.google/people/author38233/"> George Toderici </a> <br> Senior Staff Research Scientist, Google</td>
    <td style="text-align:center"><a href="http://www.cs.cmu.edu/~rvinayak/">Rashmi Vinayak</a> <br>Assistant Professor, CMU</td>
  </tr>
</table> -->

### Organizers 


<table style="width:100%">
  <tr>
    <td style="text-align:center"><img src="assets/img/org-khoa-doan-square.jpg" height="150" width="150"></td>
    <td style="text-align:center"><img src="assets/img/org-anidruddha-saha-square.jpeg" height="150"  width="150"></td>
    <td style="text-align:center"><img src="assets/img/org-anh-tran-square.jpg" height="150" width="150"></td>
    <td style="text-align:center"><img src="assets/img/org-yingjie-lao-square.jpg" height="150" width="150"></td>
    <td style="text-align:center"><img src="assets/img/org-kok-seng-wong-square.png" height="150" width="150"></td>
  </tr>
  <tr>
    <td style="text-align:center"><a href="https://khoadoan.me">Khoa D Doan</a> <br>VinUniversity, Vietnam</td>
    <td style="text-align:center"><a href="https://ani0075saha.github.io">Aniruddha Saha</a> <br>University of Maryland, College Park, USA</td>
    <td style="text-align:center"><a href="https://scholar.google.com/citations?user=FYZ5ODQAAAAJ&hl=en">Anh Tuan Tran</a> <br>VinAI Research, Vietnam</td>
    <td style="text-align:center"><a href="https://ylao.people.clemson.edu">Yingjie Lao</a> <br>Clemson University, USA</td>
    <td style="text-align:center"><a href="https://vinuni.edu.vn/people/kok-seng-wong">Kok-seng Wong</a> <br>VinUniversity, Vietnam</td>
  </tr>
  <tr>
    <td style="text-align:center"><img src="assets/img/org-ang-li-square.jpeg" height="150" width="150"></td>
    <td style="text-align:center"><img src="assets/img/org-haripriya-harikumar-square.jpg" height="150"  width="150"></td>
    <td style="text-align:center"><img src="assets/img/org-eugene-bagdasaryan-square.jpeg" height="150" width="150"></td>
    <td style="text-align:center"><img src="assets/img/org-micah-goldblum-square.jpg" height="150" width="150"></td>
    <td style="text-align:center"><img src="assets/img/org-tom-goldstein-square.jpg" height="150" width="150"></td>
  </tr>
  <tr>
    <td style="text-align:center"><a href="https://angli.ai">Ang Li</a> <br>Simular Research, USA</td>
    <td style="text-align:center"><a href="https://haripriyaaharikumar.github.io">Haripriya Harikumar</a> <br>Deakin University, Australia</td>
    <td style="text-align:center"><a href="https://ebagdasa.github.io/">Eugene Bagdasaryan</a> <br>Cornell Tech, USA</td>
    <td style="text-align:center"><a href="https://goldblum.github.io/">Micah Goldblum</a> <br>New York University, USA</td>
    <td style="text-align:center"><a href="https://www.cs.umd.edu/~tomg/">Tom Goldstein</a> <br>University of Maryland, College Park, USA</td>
  </tr>
</table>


### Organizers affiliations
<td style="text-align:center"><a href="https://vinuni.edu.vn/college-of-engineering-computer-science/"><img src="assets/img/inst-vinuni-cecs.png" height="75"></a></td>
<br>

<td style="text-align:center"><a href="https://www.cs.umd.edu/"><img src="assets/img/inst-umd-cs.png" height="75"></a></td>
<br>

<td style="text-align:center"><a href="https://www.vinai.io/"><img src="assets/img/inst-vinai.png" height="75"></a></td>
<br>


<td style="text-align:center"><a href="https://www.clemson.edu/index.html"><img src="assets/img/inst-clemson.png" height="75"></a></td>
<br>

<td style="text-align:center"><a href="https://www.deakin.edu.au/"><img src="assets/img/inst-deakin.png" height="75"></a></td>
<br>

<td style="text-align:center"><a href="https://tech.cornell.edu/"><img src="assets/img/inst-cornell-tech.png" height="75"></a></td>
<br>

<td style="text-align:center"><a href="https://www.nyu.edu/"><img src="assets/img/New_York_University-Logo.png" height="75"></a></td>
