---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{[author.googlescholar](https://scholar.google.com/citations?user=xEmA2LIAAAAJ&hl=vi&oi=sra)}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

***Journal Articles***
1. Le, T., Dang, N. A., Nguyen, K. and **Le, B. N.** (2023) “AiMA - An AI-Based Mobile System to Assist College Students with Math-Related Issues”, VNUHCM Journal of Science and Technology Development, 26(3), pp. 2863-2875. doi: https://doi.org/10.32508/stdj.v26i3.4104.

***International Conferences***
1. Nguyen Thanh Binh, Duc Dang Khoi Nguyen, **Binh Nguyen Le Nguyen**, Le Duy Tan: A Machine Learning-Based Anomaly Packets Detection for Smart Homes, The 12th International Symposium on Information and Communication Technology (SOICT 2023). Accepted (September 2023).
2. Le, T.D., **Le, N.B.N.**, Truong, N.M.Q., Nguyen, H.P.T., Huynh, KT. (2023). Real-Time Air Quality Monitoring System Using Fog Computing Technology. In: Dao, NN., Thinh, T.N., Nguyen, N.T. (eds) Intelligence of Things: Technologies and Applications. ICIT 2023. Lecture Notes on Data Engineering and Communications Technologies, vol 188. Springer, Cham. https://doi.org/10.1007/978-3-031-46749-3_15

***Dosmetic Conferences***
1. Nguyen Phuc Khang, **Binh Nguyen Le Nguyen**, Nam Anh Dang Nguyen, Le Duy Tan: Zalo Mini App International University Union - Effective information connection solution for union members and young people", School Level Scientific Conference - "Promoting the Role of Youth Union of Universities and Colleges in Improvement of Digital Competence and Innovation for Students in Ho Chi Minh City". Accepted (October 2023).
2. **Binh Nguyen Le Nguyen**, Nam Anh Dang Nguyen, Duc Dang Khoi Nguyen, Le Duy Tan: AIoT System for Real-Time Air Quality Monitoring and Forecasting (Vietnamese). The 16th National Conference on Basic Research and Application of Information Technology (FAIR 2023). Accepted (September 2023).
3. Nam Anh Dang Nguyen, **Binh Nguyen Le Nguyen**, Le Duy Tan: AiMA - An AI-Based Mobile System to Assist College Students with Math-Related Issues, The Conference on The Digital Transformation Capacity for Vietnamese Youth 2023 – Vietnam. Accepted (May 2023).
4. Nam Anh Dang Nguyen, **Binh Nguyen Le Nguyen**, Le Duy Tan: AiMA - An AI-Powered Mobile System for Supporting Undergraduate Dealing with Mathematical Problems, The 7th International Student Science Forum 2023 (ISSF 2023). Proceeding (September 2023).

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
