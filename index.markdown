---
layout: default
---

## Video Presentation

{% if site.video %}
<div class="video-wrapper">
  <iframe src="{{site.video}}&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
{% endif %}

------

## Bibtex
<pre>
@inproceedings{kim2023evallm,
title={EvalLM: Interactive Evaluation of Large Language Model Prompts on User-Defined Criteria}, 
author={Tae Soo Kim and Yoonjoo Lee and Jamin Shin and Young-Ho Kim and Juho Kim},
year={2023},
eprint={2309.13633},
archivePrefix={arXiv},
primaryClass={cs.HC}
}
</pre>

------

{: .logos}
[![Logo of KIXLAB](/assets/img/kixlab_logo.png)](https://kixlab.org)
[![Logo of KAIST](/assets/img/kaist_logo.png)](https://kaist.ac.kr)
[![Logo of NAVER](/assets/img/naver_logo.png)](https://www.facebook.com/NAVERAILAB)

{: .center .acknowledgement}
This research was supported by the **KAIST-NAVER Hypercreative AI Center**.