---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  @media (min-width: 1024px) {
    #main {
      max-width: 1180px;
    }

    .page {
      padding-right: 0 !important;
    }
  }

  .home-intro {
    margin-bottom: 1.6rem;
    font-size: 0.82rem;
    line-height: 1.55;
  }

  .home-intro p {
    margin-bottom: 0.8rem;
    text-align: justify;
  }

  .home-section {
    margin-top: 1.9rem;
  }

  .home-section h2 {
    font-size: 1.18rem;
    line-height: 1.25;
    margin-bottom: 0.8rem;
  }

  .home-section h3 {
    font-size: 0.9rem;
  }

  .detail-section {
    margin-top: 2.2rem;
  }

  .detail-section h2 {
    display: flex;
    align-items: center;
    gap: 0.45rem;
    margin-bottom: 0.85rem;
    padding-bottom: 0.45rem;
    border-bottom: 1px solid #e8e8e8;
    color: #4b4f54;
    font-size: 1.28rem !important;
    font-weight: 800;
    line-height: 1.25;
  }

  .detail-section .section-icon {
    display: inline-flex;
    width: 1.25rem;
    justify-content: center;
    font-size: 1.05rem;
    line-height: 1;
  }

  .detail-section ul {
    margin-top: 0.85rem;
    padding-left: 2.15rem;
  }

  .detail-section li::marker {
    font-size: 0.85rem;
  }

  .detail-date {
    font-weight: 800;
  }

  .news-list li {
    margin-bottom: 0.55rem;
    font-size: 0.82rem;
    line-height: 1.5;
  }

  .news-date {
    font-weight: 700;
    font-style: italic;
    white-space: nowrap;
  }

  .experience-list li,
  .research-interest-list li,
  .service-list li,
  .honor-list li {
    margin-bottom: 0.55rem;
    font-size: 0.82rem;
    line-height: 1.5;
  }

  .publication-card {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: left;
    align-items: center;
    gap: 0;
    margin: 0;
    padding: 1.35rem 0;
    border-bottom: 1px solid #e8e8e8;
  }

  .publication-thumb {
    position: relative;
    display: flex;
    justify-content: left;
    flex: 0 0 40%;
    max-width: 40%;
  }

  .publication-thumb img {
    display: block;
    width: 100%;
    max-width: 400px;
    height: auto;
    object-fit: contain;
    border-radius: 6px;
    border: 1px solid #dedede;
    box-shadow: 3px 3px 6px rgba(0, 0, 0, 0.45);
  }

  .publication-badge {
    position: absolute;
    top: 0.7rem;
    left: -0.75rem;
    display: inline-flex;
    align-items: center;
    min-height: 1.45rem;
    padding: 0.18rem 0.65rem;
    background: #0642a3;
    color: #fff;
    font-size: 12px;
    font-weight: 700;
    line-height: 1.1;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.22);
  }

  .publication-body {
    flex: 0 0 60%;
    max-width: 60%;
    min-width: 0;
    padding-left: 2rem;
  }

  .publication-title {
    margin: 0 0 0.35rem;
    font-size: 13.5px !important;
    line-height: 1.35 !important;
  }

  .publication-authors,
  .publication-venue,
  .publication-note {
    margin: 0.2rem 0;
    font-size: 13.5px !important;
    line-height: 1.42 !important;
  }

  .publication-note {
    color: #555;
    text-align: justify;
  }

  .publication-award {
    color: #b00020;
    font-weight: 800;
    font-style: normal;
    white-space: nowrap;
  }

  .publication-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    margin-top: 0.55rem;
  }

  .publication-link {
    display: inline-flex;
    align-items: center;
    min-height: 1.9rem;
    padding: 0.25rem 0.55rem;
    border-radius: 6px;
    border: 1px solid #bdbdbd;
    font-size: 12px !important;
    line-height: 1.2 !important;
    text-decoration: none;
  }

  .publication-link:hover {
    text-decoration: none;
    background: #f4f4f4;
  }

  .compact-publications li {
    margin-bottom: 0.65rem;
    font-size: 0.8rem;
    line-height: 1.48;
  }

  .toggle-button {
    min-height: 2rem;
    padding: 0.35rem 0.7rem;
    border: 1px solid #bdbdbd;
    border-radius: 6px;
    background: #fff;
    color: #333;
    cursor: pointer;
  }

  .toggle-button:hover {
    background: #f4f4f4;
  }

  @media (max-width: 640px) {
    .publication-card {
      display: block;
      padding: 1.4rem 0;
    }

    .publication-thumb {
      display: block;
      max-width: 100%;
      margin-bottom: 0.85rem;
    }

    .publication-body {
      max-width: 100%;
      padding-left: 0;
    }

    .publication-badge {
      left: 0;
      top: 0.5rem;
      min-height: 1.75rem;
      padding: 0.22rem 0.75rem;
      font-size: 0.82rem;
    }
  }
</style>

<div class="home-intro">
  <p>
    I am currently a Ph.D. candidate at <a href="https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=zh-CN" target="_blank" rel="noopener">PCA Lab</a>, School of Computer Science and Engineering, Nanjing University of Science and Technology (NJUST), where I have been working since 2022 under the supervision of Prof. <a href="https://csjinxie.github.io/" target="_blank" rel="noopener">Jin Xie</a> and Prof. <a href="https://scholar.google.com/citations?hl=zh-CN&user=oLLDUM0AAAAJ&view_op=list_works&sortby=pubdate" target="_blank" rel="noopener">Jianjun Qian</a>. I was also fortunate to be advised by Associate Professor <a href="https://scholar.google.com/citations?user=se31JGQAAAAJ&hl=zh-CN&oi=ao" target="_blank" rel="noopener">Le Hui</a> of Northwestern Polytechnical University.
  </p>

  <p>
    From May 2025 to April 2026, I am also a visiting Ph.D. student at Singapore University of Technology and Design (SUTD), advised by Assistant Prof. <a href="https://na-z.github.io/" target="_blank" rel="noopener">Na Zhao</a>. Before that, I received my M.S. degree from Zhejiang University of Science and Technology in December 2021, advised by Prof. <a href="https://scholar.google.com/citations?user=fCGlirQAAAAJ&hl=zh-CN" target="_blank" rel="noopener">Wujie Zhou</a>.
  </p>

  <p>
    My research interests lie in visual perception, with a particular focus on:
  </p>
  <ul class="research-interest-list">
    <li>Salient object detection for multi-modal visual understanding.</li>
    <li>3D object detection and scene understanding.</li>
    <li>Embodied intelligence systems that perceive, reason about, and interact with physical spaces.</li>
  </ul>
  <p>
    My long-term goal is to develop reliable visual perception systems for spatially intelligent agents in the physical world.
  </p>
</div>

<div class="home-section" id="news">
  <h2>🔥 News</h2>
  <ul class="news-list">
    <li><span class="news-date">2026.02:</span> FI3Det was accepted to <em>CVPR 2026</em>.</li>
    <li><span class="news-date">2025.02:</span> WeatherGen was accepted to <em>CVPR 2025</em>.</li>
    <li><span class="news-date">2025.02:</span> Learning Class Prototypes for Unified Sparse-Supervised 3D Object Detection was accepted to <em>CVPR 2025</em> as a Highlight paper.</li>
    <li><span class="news-date">2024.12:</span> NaviFormer was accepted to <em>AAAI 2025</em>.</li>
    <li><span class="news-date">2024.03:</span> Dense Voxel Representation Network was accepted to <em>ICME 2024</em>.</li>
    <li><span class="news-date">2023.12:</span> SPGroup3D was accepted to <em>AAAI 2024</em>.</li>
    <li><span class="news-date">2023.02:</span> LSNet was published in <em>IEEE Transactions on Image Processing</em>.</li>
    <li><span class="news-date">2022.08:</span> APNet was published in <em>IEEE Transactions on Emerging Topics in Computational Intelligence</em>.</li>
    <li><span class="news-date">2021.05:</span> CCAFNet was published online in <em>IEEE Transactions on Multimedia</em>.</li>
    <li><span class="news-date">2021.04:</span> PEENet was published in <em>IEEE Signal Processing Letters</em>.</li>
  </ul>
</div>

<div class="home-section" id="publications">
  <h2>📝 Selected Publications</h2>

  <div class="publication-card">
    <div class="publication-thumb">
      <span class="publication-badge">CVPR 2026</span>
      <img src="/images/publications/fi3det-cvpr-2026.png" alt="FI3Det paper thumbnail">
    </div>
    <div class="publication-body">
      <h3 class="publication-title">Few-Shot Incremental 3D Object Detection in Dynamic Indoor Environments</h3>
      <p class="publication-authors"><strong>Yun Zhu</strong>, Jianjun Qian, Jian Yang, Jin Xie, Na Zhao</p>
      <p class="publication-venue"><em>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2026</em></p>
      <p class="publication-note">A few-shot incremental 3D detection framework that leverages vision-language models and multimodal prototype imprinting for dynamic indoor environments.</p>
      <div class="publication-links">
        <a class="publication-link" href="https://openaccess.thecvf.com/content/CVPR2026/html/Zhu_Few-Shot_Incremental_3D_Object_Detection_in_Dynamic_Indoor_Environments_CVPR_2026_paper.html" target="_blank" rel="noopener">Paper</a>
        <a class="publication-link" href="https://arxiv.org/abs/2604.07997" target="_blank" rel="noopener">arXiv</a>
        <a class="publication-link" href="https://github.com/zyrant/FI3Det" target="_blank" rel="noopener">Code</a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <span class="publication-badge">CVPR 2025</span>
      <img src="/images/publications/cpdet3d-cvpr-2025.png" alt="CPDet3D paper thumbnail">
    </div>
    <div class="publication-body">
      <h3 class="publication-title">Learning Class Prototypes for Unified Sparse-Supervised 3D Object Detection</h3>
      <p class="publication-authors"><strong>Yun Zhu</strong>, Le Hui, Hang Yang, Jianjun Qian, Jin Xie, Jian Yang</p>
      <p class="publication-venue"><em>IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025, <span class="publication-award">🏆 Highlight</span></em></p>
      <p class="publication-note">A unified sparse-supervised 3D detection method for both indoor and outdoor scenes through class prototype learning and unlabeled object mining.</p>
      <div class="publication-links">
        <a class="publication-link" href="https://openaccess.thecvf.com/content/CVPR2025/html/Zhu_Learning_Class_Prototypes_for_Unified_Sparse-Supervised_3D_Object_Detection_CVPR_2025_paper.html" target="_blank" rel="noopener">Paper</a>
        <a class="publication-link" href="https://arxiv.org/abs/2503.21099" target="_blank" rel="noopener">arXiv</a>
        <a class="publication-link" href="https://github.com/zyrant/CPDet3D" target="_blank" rel="noopener">Code</a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <span class="publication-badge">AAAI 2024</span>
      <img src="/images/publications/spgroup3d-aaai-2024.png" alt="SPGroup3D paper thumbnail">
    </div>
    <div class="publication-body">
      <h3 class="publication-title">SPGroup3D: Superpoint Grouping Network for Indoor 3D Object Detection</h3>
      <p class="publication-authors"><strong>Yun Zhu</strong>, Le Hui, Yaqi Shen, Jin Xie</p>
      <p class="publication-venue"><em>AAAI Conference on Artificial Intelligence (AAAI), 2024</em></p>
      <p class="publication-note">A superpoint grouping network that builds semantically consistent proposal representations for indoor one-stage 3D object detection.</p>
      <div class="publication-links">
        <a class="publication-link" href="https://ojs.aaai.org/index.php/AAAI/article/view/28616" target="_blank" rel="noopener">Paper</a>
        <a class="publication-link" href="https://arxiv.org/abs/2312.13641" target="_blank" rel="noopener">arXiv</a>
        <a class="publication-link" href="https://github.com/zyrant/SPGroup3D" target="_blank" rel="noopener">Code</a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <span class="publication-badge">TIP 2023</span>
      <img src="/images/publications/lsnet-tip-2023.png" alt="LSNet paper thumbnail">
    </div>
    <div class="publication-body">
      <h3 class="publication-title">LSNet: Lightweight Spatial Boosting Network for Detecting Salient Objects in RGB-Thermal Images</h3>
      <p class="publication-authors">Wujie Zhou, <strong>Yun Zhu</strong>, Jingsheng Lei, Rongwang Yang, Lu Yu</p>
      <p class="publication-venue"><em>IEEE Transactions on Image Processing (TIP), 2023, <span class="publication-award">🏆 ESI Highly Cited Paper</span></em></p>
      <p class="publication-note">A lightweight RGB-thermal salient object detection network with boundary boosting, attentive feature distillation, and efficient inference.</p>
      <div class="publication-links">
        <a class="publication-link" href="https://doi.org/10.1109/TIP.2023.3242775" target="_blank" rel="noopener">Paper</a>
        <a class="publication-link" href="https://github.com/zyrant/LSNet" target="_blank" rel="noopener">Code</a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-thumb">
      <span class="publication-badge">TMM 2022</span>
      <img src="/images/publications/ccafnet-tmm-2022.png" alt="CCAFNet paper thumbnail">
    </div>
    <div class="publication-body">
      <h3 class="publication-title">CCAFNet: Crossflow and Cross-Scale Adaptive Fusion Network for Detecting Salient Objects in RGB-D Images</h3>
      <p class="publication-authors">Wujie Zhou, <strong>Yun Zhu</strong>, Jingsheng Lei, Jian Wan, Lu Yu</p>
      <p class="publication-venue"><em>IEEE Transactions on Multimedia (TMM), 2022, <span class="publication-award">🏆 ESI Highly Cited Paper</span></em></p>
      <p class="publication-note">A crossflow and cross-scale adaptive fusion network for RGB-D salient object detection.</p>
      <div class="publication-links">
        <a class="publication-link" href="https://doi.org/10.1109/TMM.2021.3077767" target="_blank" rel="noopener">Paper</a>
        <a class="publication-link" href="https://github.com/zyrant/CCAFNet" target="_blank" rel="noopener">Code</a>
      </div>
    </div>
  </div>

  <div id="more-publications">
    <h3>Other Publications</h3>
    <ul class="compact-publications">
      <li>Hang Yang, Le Hui, <strong>Yun Zhu</strong>, Jianjun Qian, Yigong Zhang, Jin Xie. Discriminative Region Learning for Point Cloud-based Place Recognition. <em>Neural Networks</em>, 2026. <a href="https://doi.org/10.1016/j.neunet.2026.109001" target="_blank" rel="noopener">Paper</a></li>
      <li>Yang Wu, <strong>Yun Zhu</strong>, Kaihua Zhang, Jianjun Qian, Jin Xie, Jian Yang. WeatherGen: A Unified Diverse Weather Generator for LiDAR Point Clouds via Spider Mamba Diffusion. <em>CVPR</em>, 2025. <a href="https://openaccess.thecvf.com/content/CVPR2025/html/Wu_WeatherGen_A_Unified_Diverse_Weather_Generator_for_LiDAR_Point_Clouds_CVPR_2025_paper.html" target="_blank" rel="noopener">Paper</a> <a href="https://arxiv.org/abs/2504.13561" target="_blank" rel="noopener">arXiv</a></li>
      <li>Wei Xie, Haobo Jiang, <strong>Yun Zhu</strong>, Jianjun Qian, Jin Xie. NaviFormer: A Spatio-Temporal Context-Aware Transformer for Object Navigation. <em>AAAI</em>, 2025. <a href="https://ojs.aaai.org/index.php/AAAI/article/view/33612" target="_blank" rel="noopener">Paper</a></li>
      <li>Fan Dai, <strong>Yun Zhu</strong>, Yaqi Shen, Jin Xie, Jianjun Qian. Dense Voxel Representation Network for Implicit Scene Completion. <em>ICME</em>, 2024. <a href="https://doi.org/10.1109/ICME57554.2024.10687859" target="_blank" rel="noopener">Paper</a></li>
      <li>Wujie Zhou, <strong>Yun Zhu</strong>, Jingsheng Lei, Jian Wan, Lu Yu. APNet: Adversarial Learning Assistance and Perceived Importance Fusion Network for All-Day RGB-T Salient Object Detection. <em>IEEE Transactions on Emerging Topics in Computational Intelligence</em>, 2022. <a href="https://doi.org/10.1109/TETCI.2021.3118043" target="_blank" rel="noopener">Paper</a> <a href="https://github.com/zyrant/APNet" target="_blank" rel="noopener">Code</a></li>
      <li><strong>Yun Zhu</strong>, Wujie Zhou, Qiang Li, Lu Yu. Parallax-Estimation-Enhanced Network With Interweave Consistency Feature Fusion for Binocular Salient Object Detection. <em>IEEE Signal Processing Letters</em>, 2021. <a href="https://doi.org/10.1109/LSP.2021.3075610" target="_blank" rel="noopener">Paper</a></li>
    </ul>
  </div>
</div>

<div class="home-section detail-section" id="academic-services">
  <h2><span class="section-icon">🤝</span>Academic Services</h2>
  <ul class="service-list">
    <li><strong>Journal reviewer:</strong> IEEE Transactions on Image Processing, IEEE Transactions on Circuits and Systems for Video Technology, IEEE Internet of Things Journal, IEEE Sensors Journal, Neural Networks, Virtual Reality & Intelligent Hardware.</li>
    <li><strong>Conference reviewer:</strong> CVPR 2025-2026, ICCV 2025, ECCV 2026, AAAI 2027, ICME 2024-2026, BMVC 2026.</li>
  </ul>
</div>

<div class="home-section detail-section" id="honors-and-awards">
  <h2><span class="section-icon">🏆</span>Selected Honors & Awards</h2>
  <ul class="honor-list">
    <li><span class="detail-date">2021:</span> National Scholarship for Graduate Students.</li>
    <li><span class="detail-date">2022:</span> Outstanding Master's Graduate, Zhejiang University of Science and Technology.</li>
    <li><span class="detail-date">2022-2026:</span> Academic Scholarship, Nanjing University of Science and Technology.</li>
    <li><span class="detail-date">2019-2021:</span> Academic Scholarship, Zhejiang University of Science and Technology.</li>
  </ul>
</div>
