---
title: ""
permalink: /publications/
author_profile: true
---

<h2>Publications</h2>

Rasoul Akhavan Mahdavi, Faezeh Ebrahimianghazani, Thomas Humphries, <b>Bailey Kacsmar</b>, Emily Lepert, Xinda Li, Nils Lukas, John A. Premkumar, Simon Oya, Florian Kerschbaum. &quot;<a href="https://www.usenix.org/conference/usenixsecurity24/presentation/mahdavi">PEPSI: Practically Efficient Private Set Intersection in the Unbalanced Setting</a>&quot;. USENIX Security 2024, pp. 6453-6470.

Abdulrahman Diaa, Lucas Fenaux, Thomas Humphries, Marian Dietz, Faezeh Ebrahimianghazani, <b>Bailey Kacsmar</b>, Xinda Li, Nils Lukas, Rasoul Akhavan Mahdavi, Simon Oya, Ehsan Amjadian and Florian Kerschbaum. &quot;<a href="https://www.usenix.org/conference/usenixsecurity24/presentation/diaa">Fast and Private Inference of Deep Neural Networks by Co-designing Activation Functions</a>&quot;. USENIX Security 2024, pp. 2191-2208.

<b>Bailey Kacsmar</b>, Vasisht Duddu, Kyle Tilbury, Blase Ur, and Florian Kerschbaum. &quot;[Comprehension from Chaos: Towards Informed Consent for Private Computation](https://bkacsmar.github.io/files/comprehensionfromchaospreprint.pdf)&quot;. 2023 ACM SIGSAC Conference on Computer and Communications Security, pp 210-244. ([Slides](https://bkacsmar.github.io/files/BkacsmarCCS2023ComprehensionfromChaos.pdf))


 <b>Bailey Kacsmar</b>. &quot;[Improving Interactive Instruction: Faculty Engagement Requires Starting Small and Telling All](https://bkacsmar.github.io/files/bkacsmar_Koli_Calling_Short_preprint.pdf)&quot;. Koli Calling 22nd International Conference on Computing Education Research. November 2022. ACM. ([Slides](https://bkacsmar.github.io/files/pres_Koli2023.pdf))
 
 <b>Bailey Kacsmar</b>, Kyle Tilbury, Miti Mazmudar, Florian Kerschbaum.  &quot;[Caring about Sharing: User Perceptions of Multiparty Data Sharing](https://bkacsmar.github.io/files/caringsharingpaper.pdf)&quot;. USENIX Security 2022, pp. 899-916. ([Survey](https://bkacsmar.github.io/files/SurveyUsenix2022.pdf), [Slides](https://bkacsmar.github.io/files/caringUSENIXslides.pdf), [SOUPS Poster](https://bkacsmar.github.io/files/CaringSoupsPoster2022.pdf), [Conference Presentation Recording](https://www.youtube.com/watch?v=AMmDrLeJtgA)).
<br>


Rasoul Akhavan Mahdavi,  Thomas Humphries, <b>Bailey Kacsmar</b>, Simeon Krastnikov, Nils Lukas, John Premkumar,  Masoumeh Shafieinejad, Simon Oya, Florian Kerschbaum, Erik-Oliver Blass. &quot;[Practical Over-Threshold Multi-Party Private Set Intersection](https://bkacsmar.github.io/files/overthresholdPSI.pdf)&quot;. The Annual Computer Security Applications Conference (ACSAC 2020), pp. 772-783.



<b>Bailey Kacsmar</b>, Basit Khurram, Nils Lukas, Alexander Norton, Masoumeh Shafieinejad, Zhiwei Shang, Yasser Baseri, Maryam Sepehri, Simon Oya, and Florian Kerschbaum. &quot;[Differentially Private Two-Party Set Operations](https://bkacsmar.github.io/files/DiPSI.pdf)&quot;. The 5th IEEE European Symposium on Security and Privacy, (IEEE EuroS&P 2020). pp. 390-404. 

<b>Bailey Kacsmar</b>, Chelsea H. Komlo, Florian Kerschbaum, Ian Goldberg. &quot;[Mind the Gap: Ceremonies for Applied Secret Sharing](https://bkacsmar.github.io/files/mindthegap.pdf)&quot;. <i> Proceedings on Privacy Enhancing Technologies</i>. Vol. 2020, No. 2. 18 pages. April 2020. [(Slides)](https://bkacsmar.github.io/files/PoPETS_2020_Mindthegap.pdf)
<br>


<b>Bailey Kacsmar</b>, Douglas R. Stinson. &quot;[A Network Reliability Approach to the Analysis of Combinatorial Repairable Threshold Schemes](https://bkacsmar.github.io/files/networkReliability.pdf).&quot; <i>Advances in Mathematics of Communications, 2019</i>, 13 (4) : 601-612.
<br>


<b>Bailey Kacsmar</b>, Sarah Plosker, Ryan Henry. &quot;[Computing Low-Weight Discrete Logarithms](https://bkacsmar.github.io/files/Low_weight_DLP_ext.pdf)&quot;. The 24th Annual Conference on Selected Areas in Cryptography (SAC 2017), <i>International Conference on Selected Areas in Cryptography</i>, pp. 106-126. Springer, Cham. [(Slides)](https://bkacsmar.github.io/files/Computing_Low_Weight_DL.pdf)
<br>


Chenkuan Li, Changpin Li, <b>Bailey Kacsmar</b>, Roque Lacroix and Kyle Tilbury. &quot;[The Abel Integral Equations in Distribution](https://bkacsmar.github.io/files/abelIntegral.pdf)&quot;, Advances in Analysis, 2 (2017), pages 88-104.




<h2>Theses</h2>

[Perceptions and Practicalities for Private Machine Learning](https://uwspace.uwaterloo.ca/handle/10012/19830). UWSpace: PhD thesis, University of Waterloo, Waterloo, ON, Canada. 
<br>


[Designing Efficient Algorithms for Combinatorial Repairable Threshold Schemes](https://bkacsmar.github.io/files/DesigningEfficientAlgo.pdf). UWSpace: MMath
thesis, University of Waterloo, Waterloo, ON, Canada (October 2018). [(Slides)](https://bkacsmar.github.io/files/MastersThesis_presentation.pdf)



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
