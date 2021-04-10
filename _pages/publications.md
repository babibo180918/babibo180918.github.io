---
#layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on my [Google Scholar profile]({{site.author.googlescholar}})
{% endif %}

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
