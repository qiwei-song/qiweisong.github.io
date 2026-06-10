---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is <span class="accent-text">Qiwei Song</span>. I am a PhD Candidate in Architecture and a Computational Social Science Lab Fellow at <i class="fas fa-university"></i> **Chinese University of Hong Kong**. I am jointly supervised by Prof. Jeroen van Ameijde and Prof. Thomas Chung. Previously, I earned my Master of Landscape Archiecture degree from <i class="fas fa-university"></i> **University of Toronto** and Bachelor's of Engineering degree in Landscape Architecture from <i class="fas fa-university"></i> **Zhejiang A & F University**. I am a visiting PhD student at Senseable City Laboratory at <i class="fas fa-university"></i> **Massachusetts Institute of Technology**, where I have the privilege of working with Principal Scientist <a href="https://scholar.google.com/citations?user=345-ILkAAAAJ&hl=en" class="link-accent">Dr. Paolo Santi</a>.
Before pursuing my PhD, I gained valuable working experience in the design industry as registered landscape architect (liciensed in Ontario, Canada) and project manager at internationally acclaimed design consulting firms such as ARCADIS IBI Group, MT Planners, Gustafson Porter & Bowman and several others.

<div class="quote-accent">
I study the complex interplay between the perceptions of built environment and human behaviour using <span class="primary-gradient-text">new data and computational methods</span>, including spatial and statistical analysis, mapping, and deep learning algorithms including Large Language Models. I am currently developing data-driven computational methods to comprehensively evaluate the walking accessibility to amenities and the quality of life in the high-density urban contexts towards the X-minute City vision. 
</div>

Feel free to reach out if you'd like to discuss research or explore potential collaboration!

<div class="highlight-blocks">
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-microscope"></i> Urban Researcher</h3>
    <ul>
      <li>Research focus on <span class="accent-text">computational methods</span></li>
      <li>Internships at <span class="primary-gradient-text">top institutions</span></li>
      <li>Publications at <span class="accent-text">LANDUP</span>, <span class="accent-text">TRPD</span></li>, etc.
    </ul>
  </div>
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-pen-fancy"></i> Content Creator</h3>
    <ul>
      <li>Technical blogs with <span class="accent-text">500K+ views</span></li>
      <li>Active on <a href="https://www.xiaohongshu.com/user/profile/60c47bae000000000100b07e" class="link-accent">Xiaohongshu</a></li>
      <li><a href="https://mp.weixin.qq.com/s/5wn3NvB2FBpJD1jK0L4qbQ" class="link-accent">Articles</a> about <span class="primary-gradient-text">Tech & Humanities</span></li>
    </ul>
  </div>
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-globe-asia"></i> Life Explorer</h3>
    <ul>
      <li>Visited <span class="accent-text">9 countries</span> worldwide</li>
      <li>Traveled to <span class="accent-text">32 provinces</span> in China</li>
      <li>Rich experience in <span class="primary-gradient-text">social work</span></li>
    </ul>
  </div>
</div>

<!-- # <i class="fas fa-fire"></i> News
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by The 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025). <span class="accent-text">See you in Philadelphia!</span>
- *2024.08*: &nbsp;I have joined <span class="primary-gradient-text">Microsoft</span> as a Research Intern under the guidance of Principal Researcher Justin Ding, where I focus on evaluating and enhancing LLM outputs. -->

# <i class="fas fa-file-alt"></i> Selected Publications (as First# & Corresponding* Author)


<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">LANDUP</div>
    <img src='images/1 Beyond Sentiment_thumnail.jpg' alt="DSGram Framework Overview" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Beyond sentiment: Using large language models to decode multidimensional urban park perceptions for enhanced equality</h3>
    <div class="authors"><strong>Qiwei Song#</strong>, Siyu Tian, Lingwei Zheng, Yuxuan Zheng, Lin Qiu, Bo Huang, Jeroen van Ameijde* </div>
    <div class="venue">Landscape and Urban Planning, 2026, 268: 105571.</div>
    <div class="links">
      <a href="https://www.sciencedirect.com/science/article/pii/S0169204625002786" class="btn-accent"><i class="fas fa-file-alt"></i> Website</a>
      <a href="files/song et al 2026_Beyond Sentiment_LANDUP.pdf" class="btn-accent"><i class="fab fa-github"></i> PDF</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">TRPA</div>
    <img src='images/Desirable bikeshare routes_Cai et al_TRA2026.jpg' alt="DSGram Framework Overview" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Desirable bikeshare routes: Nonlinear impacts of micro-level street environments</h3>
    <div class="authors"><strong>Yuxuan Cai#, Qiwei Song#</strong>, Yiming Cheng, Anzhi Chen, Yuankai Wang, Wenjing Li, Waishan Qiu* </div>
    <div class="venue">Transportation Research Part A: Policy and Practice, 2026, 208: 104962.</div>
    <div class="links">
      <a href="https://www.sciencedirect.com/science/article/pii/S0965856426001035" class="btn-accent"><i class="fas fa-file-alt"></i> Website</a>
      <a href="files/Desirable bikeshare routes_Cai et al_TRA2026.pdf" class="btn-accent"><i class="fab fa-github"></i> PDF</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">JUM</div>
    <img src='images/Tan2026_JUM.jpg' alt="DSGram Framework Overview" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Visual perception-informed urban design toolkit: Computational urban morphology optimisation to inform real-time perceived safety</h3>
    <div class="authors"><strong>Xinyu Tan#, Qiwei Song#</strong>, Xun Liu, Waishan Qiu* </div>
    <div class="venue">Journal of Urban Management, 2026, 15(2): 600-616.</div>
    <div class="links">
      <a href="https://www.sciencedirect.com/science/article/pii/S2226585625001426" class="btn-accent"><i class="fas fa-file-alt"></i> Website</a>
      <a href="files/Tan2026_JUM.pdf" class="btn-accent"><i class="fab fa-github"></i> PDF</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">EPB</div>
    <img src='images/Song EPB2025.jpg' alt="DSGram Framework Overview" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Exploring the coherence and divergence between the objective and subjective measurement of streetscape perceptions at the neighborhood level: A case study in Shanghai</h3>
    <div class="authors"><strong>Qiwei Song#</strong>, Yuxian Fang, Meikang Li, Jeroen van Ameijde, Waishan Qiu* </div>
    <div class="venue">Environment and Planning B: Urban Analytics and City Science, 2025, 52(5): 1231–1251.</div>
    <div class="links">
      <a href="https://journals.sagepub.com/doi/abs/10.1177/23998083241292680" class="btn-accent"><i class="fas fa-file-alt"></i> Website</a>
      <a href="files/Song EPB2025.pdf" class="btn-accent"><i class="fab fa-github"></i> PDF</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">CUS</div>
    <img src='images/Machine learning‑based urban densification_Li 2025_CUS.jpg' alt="DSGram Framework Overview" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Machine learning-based urban densification: extending roof ridge lines for sustainable housing extension using generative adversarial networks</h3>
    <div class="authors"><strong>Yangzhi Li#*</strong>, Jingwei Li,  Qiwei Song* </div>
    <div class="venue">Computational Urban Science, 2025, 5:48.</div>
    <div class="links">
      <a href="https://link.springer.com/article/10.1007/s43762-025-00205-w" class="btn-accent"><i class="fas fa-file-alt"></i> Website</a>
      <a href="files/Machine learning‑based urban densification_Li 2025_CUS.pdf" class="btn-accent"><i class="fab fa-github"></i> PDF</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">TRPD</div>
    <img src='images/song_trd2024.jpg' alt="DSGram Framework Overview" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Unraveling the effects of micro-level street environment on dockless bikeshare in Ithaca</h3>
    <div class="authors"><strong>Qiwei Song#</strong>, Yulu Huang, Wenjing Li, Faan Chen, Waishan Qiu* </div>
    <div class="venue">Transportation research part D: transport and environment, 2024, 132:104256.</div>
    <div class="links">
      <a href="https://www.sciencedirect.com/science/article/pii/S136192092400213X" class="btn-accent"><i class="fas fa-file-alt"></i> Website</a>
      <a href="files/song_trd2024.pdf" class="btn-accent"><i class="fab fa-github"></i> PDF</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">AI</div>
    <img src='images/Song_architectural inte2023.jpg' alt="DSGram Framework Overview" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>The evaluation of urban spatial quality and utility trade-offs for Post-COVID working preferences: a case study of Hong Kong</h3>
    <div class="authors"><strong>Qiwei Song#</strong>, Zhiyi Dou, Waishan Qiu, Wenjing Li, Jingsong Wang, Jeroen van Ameijde, Dan Luo* </div>
    <div class="venue">Architectural Intelligence, 2023, 2:1.</div>
    <div class="links">
      <a href="https://link.springer.com/article/10.1007/s44223-022-00020-x" class="btn-accent"><i class="fas fa-file-alt"></i> Website</a>
      <a href="files/Song_architectural inte2023.pdf" class="btn-accent"><i class="fab fa-github"></i> PDF</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">LAND</div>
    <img src='images/song_land2022.jpg' alt="DSGram Framework Overview" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>The evaluation of urban spatial quality and utility trade-offs for Post-COVID working preferences: a case study of Hong Kong</h3>
    <div class="authors"><strong>Qiwei Song#</strong>, Yifeng Liu, Waishan Qiu, Ruijun Liu, Meikang Li* </div>
    <div class="venue">Land, 2022, 11(11):2002.</div>
    <div class="links">
      <a href="https://www.mdpi.com/2073-445X/11/11/2002" class="btn-accent"><i class="fas fa-file-alt"></i> Website</a>
      <a href="files/song_land2022.pdf" class="btn-accent"><i class="fab fa-github"></i> PDF</a>
    </div>
  </div>
</div>


- Yulu Huang#, **Qiwei Song#**, Weixuan Wei, Waishan Qiu*. Elevated habitats of urban avian communities? Assessing the influence of multidimensional structural characteristics of green roofs in Shanghai. **Under Revision**.
- **Qiwei Song#**, Meikang Li, Waishan Qiu, Kaihang Zhang, Jeroen van Ameijde. Leveraging street experiments to promote active travel during and after the pandemic – Revealing the causal influence through the case of CaféTO program using Spatial Difference-in-difference model. **Under Review**.

# <i class="fas fa-graduation-cap"></i> Education
- *2025.11 - 2026.07*: &nbsp;Visiting PhD Student at <span class="primary-gradient-text">Senseable City Laboratory, Massachusetts Institute of Technology</span>.
- *2023.09 - Present*: &nbsp;Doctor of Philosophy in Architecture (Computational Social Science Fellow) at <span class="primary-gradient-text">School of Architecture, The Chinese University of Hong Kong</span>.
- *2016.08 - 2018.06*: &nbsp;Master of Landscape Architecture at <span class="primary-gradient-text">Daniels Faculty of Architecture, Landscape and Design, University of Toronto</span>.
- *2012.09 - 2016.07*: &nbsp;Bachelor of Engineering in Landscape Architecture, <span class="primary-gradient-text">Zhejiang A & F University</span>.

# <i class="fas fa-laptop-code"></i> Selected Professional Experience (Post-graduation)
- *2021 - 2023*: &nbsp;Project Manager / Landscape Architect / Student Intern Mentor, **<a href="https://www.arcadis.com/en" class="link-accent">Arcadis (formerly IBI Group)</a>**, Toronto, Canada.
- *2019 - 2021*: &nbsp;Landscape and Urban Designer, **<a href="https://mtplanners.com/" class="link-accent">Moriyama & Teshima Planners</a>**, Toronto, Canada.
- *2018 - 2019*: &nbsp;Landscape Architect Intern/Assistant, **<a href="https://www.gp-b.com/" class="link-accent">Gustafson Porter + Bowman</a>**, London, UK.

# <i class="fas fa-laptop-code"></i> Selected Professional Registrations & Credentials
- *2021 - Present*: &nbsp; Registered LA, OALA (Ontario Association of Landscape Architects)Full Member with Stamp.
- *2021 - Present*: &nbsp; Registered LA, CSLA (Canadian Society of Landscape Architects) Full Member.
- *2021 - Present*: &nbsp; Sustainable SITES Accredited Professional (SITES AP), Sustainable SITES Initiative, GBCI.

# <i class="fas fa-graduation-cap"></i> Selected Honors & Awards
- *2025*: 2025 IACP Best Student Paper Award, International Association for China Planning (IACP)
- *2024*: Young CAADRIA Award, The Association for Computer-Aided Architectural Design Research in Asia (CAADRIA)
- *2024*: 2023-2024 Design Talent Scholarship, The Chinese University of Hong Kong
- *2024*: 2023-2024 Reaching Out Award, The Chinese University of Hong Kong
- *2023-2027*: Vice-chancellor PhD Scholarship, The Chinese University of Hong Kong
- *2023-2027*: Computational Social Science PhD Fellowship, The Chinese University of Hong Kong
- *2021*: First Award, Urban Design (Concept), 2021 Rethinking the Future Awards
- *2020*: Best of best, Urban Planning Category, 2020 Architecture MasterPrize - Student Architectural Design Award
- *2020*: Award of Excellence, 2020 Canada National Urban Design Awards, Student Project Category
- *2020*: Certificate of Merit, 2020 Canada National Urban Design Awards, Student Project Category
- *2019*: Winner, Grand Site Tour Eiffel Competition（affiliated with Gustafson Porter+Bowman）
- *2019*: 2019 WLA Award Merit Award, Student Category
- *2018*: 2018 ASLA (American Society of Landscape Architects) Student Honor Award, Analysis and Planning Category
- *2018*: 2018 ASLA (American Society of Landscape Architects) Certificate of Merit


# <i class="fas fa-blog"></i> Blogs

<div class="blog-grid">
  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">November, 2025</div>
      <img src="images/claude-pipeline.png" alt="Claude Code Skills 和 Subagents 的个人实践">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">Claude Code Skills and Subagents in Practice</div>
      <div class="blog-description">Two production-grade systems: a paywall-crossing paper harvester and a self-iterating AI Scientist, showing how Skills + Subagents scale LLM workflows.</div>
      <div class="blog-links">
        <a href="https://mp.weixin.qq.com/s/_rHrBpRZX_U2Zmt8vRZ22Q" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://jxtse.medium.com/from-chat-tools-to-research-infrastructure-building-production-grade-workflows-with-claude-code-7da19194ab34" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

<div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">June, 2025</div>
      <img src="images/pic06.jpg" alt="The Limits of My Language Mean the Limits of My World">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">The Limits of My Language Mean the Limits of My World</div>
      <div class="blog-description">Drawing on Wittgenstein's philosophy, a recent paper argues that our existing language might be the fundamental bottleneck.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/discovery/item/683c300d000000000f03b1ca?source=webshare&xhsshare=pc_web&xsec_token=AB0PoaiA05YKKE_dU2SOcfxhEzDIPcLsNtqo4slfNuuXw=&xsec_source=pc_share" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://jxtse.medium.com/the-limits-of-my-language-are-the-limits-of-my-world-can-we-ever-truly-understand-ai-f7cc72327dac" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">January, 2025</div>
      <img src="images/pic04.jpg" alt="Beyond the Future of AI">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">Beyond the Future of AI: The Dreams and Deceptions of Cryptocurrency</div>
      <div class="blog-description">My vision of the future: from Bitcoin to an AGI-driven decentralized society. We must design a more sophisticated trust mechanism than blockchain to install “guardrails” for AI.</div>
      <div class="blog-links">
        <a href="https://mp.weixin.qq.com/s/luu2qEzPnYAuryJ9mYoJ6Q" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://jxtse.medium.com/beyond-the-future-of-ai-the-dreams-and-deceptions-of-cryptocurrency-5da8d4bbf69e" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">November, 2024</div>
      <img src="images/pic05.jpg" alt="LexiMind">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">LexiMind: An Open-Source LLM-Powered Vocabulary Builder</div>
      <div class="blog-description">LexiMind is an AI-powered vocabulary builder that integrates LLM-based translation with smart word retention.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/explore/67a48f0d000000001800721c?xsec_token=ABXUfGRE_zHTnXbEyaNmuelNX3M4527lw3zirVu2KJUKA=&xsec_source=pc_user" class="blog-link">
          <i class="fas fa-info-circle"></i> Introduction
        </a>
        <a href="https://github.com/jxtse/LexiMind" class="blog-link">
          <i class="fab fa-github"></i> Project
        </a>
      </div>
    </div>
  </div>

  <!-- <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">July, 2024</div>
      <img src="images/pic02.jpg" alt="NLP Learning Path">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">My NLP Learning Path as a Mathematics Undergraduate Student</div>
      <div class="blog-description">I share my learning path and some insights on natural language processing as a mathematics undergraduate student.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/explore/668a35c8000000001e010600?xsec_token=ABl3IEpctnnXxbjsYlUul3nZBcA622VEEpS6zNOEPrxVI=&xsec_source=pc_user" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://www.linkedin.com/posts/jinxiang-xie_naturallanguageprocessing-nlp-learningpath-activity-7215638435393359872-dPr8?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEmWk88Bhyvl-E41lfo1McNlpiC4YSsk7WQ" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div> -->

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">November, 2023</div>
      <img src="images/pic03.jpg" alt="LLMs Technology">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">LLMs: Cutting-Edge Technology and Future Applications</div>
      <div class="blog-description">My notes from a presentation on LLMs at the Gaoling School of Artificial Intelligence, Renmin University of China.</div>
      <div class="blog-links">
        <a href="https://mp.weixin.qq.com/s?__biz=Mzg5NzczMzM3MA==&mid=2247483926&idx=1&sn=c6dcaf93ec8d7ecaa760df4682589b21" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">August, 2023</div>
      <img src="images/pic01.jpg" alt="Prompt Engineering">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">Prompt Engineering: How to Better Ask LLMs</div>
      <div class="blog-description">Introduce a number of methods for optimizing the output of large language models and reducing the probability of irrelevant or incorrect responses.</div>
      <div class="blog-links">
        <a href="https://sspai.com/post/82322" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
      </div>
    </div>
  </div>
</div>
