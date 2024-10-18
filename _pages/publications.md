---
#layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on my [Google Scholar profile]({{site.author.googlescholar}})
{% endif %}

2024
------
**Nhan D. T. Nguyen**, H. Phan, S. Geirnaert, K. Mikkelsen and P. Kidmose, ___AADNet: An End-to-End Deep Learning Model for Auditory Attention Decoding, submitted to *IEEE Transactions on Neural Systems and Rehabilitation Engineering*, Sep. 2024 (in review) [[preprint]](https://arxiv.org/abs/2410.13059)

**Nhan D. T. Nguyen**, H. Phan, K. Mikkelsen and P. Kidmose, ___Single-word Auditory Attention Decoding Using Deep Learning Model, [[preprint]]()

2023
------
**Nhan D. T. Nguyen**, K. Mikkelsen and P. Kidmose, ___Cognitive Component of Auditory Attention to Natural Speech Events, submitted to *Frontiers Human Neuroscience*, July. 2024 (in review) [[preprint]](https://arxiv.org/abs/2312.10543)

2012
------

**Nhan D. T. Nguyen**, SeungYoung Lee and DongHan Kim. ___Two-stage Hidden MarkovModel in Gesture Recognition for Human Robot Interaction___. *International Journal of Advanced Robotic Systems: Human Robot Interaction (IJARS)* (SCIE), vol. 9, 39:2012 [[PDF]](https://journals.sagepub.com/doi/pdf/10.5772/50204)

**Nhan D. T. Nguyen**, SangYep Lee, LanAnh Trinh, SangYep Nam and DongHan Kim. ___A Method of Human Posture Recognition Based on Skeletal Feature Analysis___. *Proceeding of International Conference on Electronics, Information and Communication (ICEIC)*, Seoul, Korea, 2012 [[PDF]](/files/ICEIC_2012_A_Method_of_Human_Posture_Recognition_Based_on_Skeletal_Feature_Analysis.pdf)

2011
-----

**Nhan D. T. Nguyen**, D. Stonier, SungYoung Lee and DongHan Kim. ___A New Approach for Human-Robot Interaction Using Human Body Language___. *International Conference on Convergence and Hybrid Information Technology (LNCS 6935)*, Daejeon, Korea, 2011 [[PDF]](https://www.researchgate.net/profile/Nhan-Nguyen-Duc-Thanh/publication/221416253_A_New_Approach_for_Human-Robot_Interaction_Using_Human_Body_Language/links/5c172ec0299bf139c75e2c30/A-New-Approach-for-Human-Robot-Interaction-Using-Human-Body-Language.pdf)


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
