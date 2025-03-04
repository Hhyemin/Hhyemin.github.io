---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* More works coming soon...

* [An Empirical Study of Suppressed Static Analysis Warnings](files/FSE25_suppression_study.pdf)
  Huimin Hu, Yingying Wang, Julia Rubin, Michael Pradel
  The ACM International Conference on the Foundations of Software Engineering (FSE), 2025

* Applying Token Tagging to Augment Dataset for Automatic Program Repair  
  Huimin Hu, Byungjeong Lee.  
  Journal of Information Precessing Systems, JIPS, October 2022.

* **PATENT**: APPARATUS AND METHOD FOR REPAIRING SOURCE CODE BUG OF PROGRAM  
  Byungjeong Lee, Jisung Kim, Huimin Hu.

* [멀티 라인 버그 정정을 위하여 버기 블록에 CodeBERT 활용](https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=%EB%A9%80%ED%8B%B0+%EB%9D%BC%EC%9D%B8+%EB%B2%84%EA%B7%B8+%EC%A0%95%EC%A0%95%EC%9D%84+%EC%9C%84%ED%95%98%EC%97%AC+%EB%B2%84%EA%B8%B0+%EB%B8%94%EB%A1%9D%EC%97%90+CodeBERT+%ED%99%9C%EC%9A%A9&btnG=)  
  (Towards Multi-Chunk Bug Repair with Buggy Block and CodeBERT)  
  Jisung Kim, Huimin Hu, Geunseok Yang, Byungjeong Lee.  
  Proceedings of the 24rd Korea Conference on Software Engineering, KCSE, 2022.

* 멀티 청크 버그 정정을 위한 버기 블럭과 CodeBERT 활용  
  (Towards Utilizing CodeBERT with Buggy Block for Multi-Line Bug Repair)  
  Jisung Kim, Huimin Hu, Byungjeong Lee.  
  The 65th Annual Scientific Meeting of The Korean Society of Cardiology, KSC, 2021.

* [코드 블록과 NMT 모델을 활용한 자동 프로그램 정정](https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=%EC%BD%94%EB%93%9C+%EB%B8%94%EB%A1%9D%EA%B3%BC+NMT+%EB%AA%A8%EB%8D%B8%EC%9D%84+%ED%99%9C%EC%9A%A9%ED%95%9C+%EC%9E%90%EB%8F%99+%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8+%EC%A0%95%EC%A0%95&btnG=)  
  (Automated Program Repair using Code blocks and NMT model)  
  Huimin Hu, Jisung Kim, Byungjeong Lee, Byungdo Kang.  
  Korea Computer Congress, KCC, 2021.

* [웨어러블 센서를 사용한 심전도 모니터링 애플리케이션 디자인](https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=%EC%9B%A8%EC%96%B4%EB%9F%AC%EB%B8%94+%EC%84%BC%EC%84%9C%EB%A5%BC+%EC%82%AC%EC%9A%A9%ED%95%9C+%EC%8B%AC%EC%A0%84%EB%8F%84+%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81+%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98+%EB%94%94%EC%9E%90%EC%9D%B8&btnG=)  
  (Bounce: Designing an EKG Monitoring Application Using a Wearable Sensor through a Design Thinking Process)  
  Shinsil Kang, Youngsoo Song, Huimin Hu, Hyunggu Jung.  
  The HCI Society of Korea, HCI, 2021.

* **PATENT**: APPARATUS AND METHOD FOR REPAIRING BUG SOURCE CODE FOR PROGRAM  
  Byungjeong Lee, Huimin Hu, Geunseok Yang.  

* [코드 블록과 장단기 메모리를 활용한 프로그램 버그 정정 기법](http://kcse2021.userinsight.co.kr/static/book/KCSE2021tocv7.pdf)  
  (A Novel Technique of Program Bug Repair by using Code Block and LSTM Algorithm)  
  Huimin Hu, Geunseok Yang, Byungjeong Lee.  
  Proceedings of the 23rd Korea Conference on Software Engineering, KCSE, 2021.  

* [코드 블록과 GAN 알고리즘을 활용한 자동 프로그램 버그 정정 기법](https://scholar.google.co.kr/scholar?hl=ko&as_sdt=0%2C5&q=%EC%BD%94%EB%93%9C+%EB%B8%94%EB%A1%9D%EA%B3%BC+GAN+%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EC%9D%84+%ED%99%9C%EC%9A%A9%ED%95%9C+%EC%9E%90%EB%8F%99+%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8+%EB%B2%84%EA%B7%B8+%EC%A0%95%EC%A0%95+%EA%B8%B0%EB%B2%95&btnG=)  
  (Towards Automatic Program Repair Based on Code Block and GAN Algorithm)  
  Huimin Hu, Geunseok Yang, Byungjeong Lee.  
  The 64th Annual Scientific Meeting of The Korean Society of Cardiology, KSC, 2020.  