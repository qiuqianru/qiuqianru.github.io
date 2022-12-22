---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<html>
  <head>
    <style>
    .card {
      box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
      margin: 10px;
      padding: 15px;
    }
    </style>
  </head>
<body>
  <h1>
    <center>
      Color Recommendation for Vector Graphic Documents based on Multi-Palette Representation
    </center>
  </h1>
  <div>
    <center>
      Qianru Qiu, <a href="https://xueting-wang.github.io/">Xueting Wang</a>, <a href="https://mayu-ot.github.io/">Mayu Otani</a>, Yuki Iwazaki
    </center>
  </div>
  <div>
    <center>
      <a href="https://cyberagent.ai/ailab/">CyberAgent AI Lab</a>
    </center>
  </div>
  <div>
    <center>
      <a href="https://arxiv.org/abs/2209.10820">Paper</a> | <a href="https://github.com/CyberAgentAILab/multipalette" >Code</a>
    </center>
  </div>
  
  <div class="card">
    <center><h3>Abstract</h3></center>
    <img src="figures/overview_v3.png" />
    <p>
      Vector graphic documents present multiple visual elements, such as images, shapes, and texts. Choosing appropriate colors for multiple visual elements is challenging but crucial for amateurs and professional designers. Instead of creating a single color palette for all elements, we extract multiple color palettes from each visual element of a graphic document, and then combine them into a color sequence. We propose a masked color model for color sequence completion and recommend the specified colors based on the color context in multi-palette with high prob- ability. We train the model and build a color recommen- dation system on a large-scale dataset of vector graphic documents. The proposed color recommendation method outperformed other state-of-the-art methods by quantita- tive and qualitative evaluations on color prediction and our color recommendation system received positive feedback from professional designers in an interview study.
    </p>
  </div>
  
  <div class="card">
    <center><h3>Method</h3></center>
    <img src="figures/method.png" />
    <p>
      <center>Masked color model for Image-SVG-Text color sequence</center>
    </p>
  </div>
  
  <div class="card">
    <center><h3>Results</h3></center>
    <img src="figures/recomm_samples.png" />
    <p>
      Color recommendation results with our proposed BERT-based models with and without segment embeddings, and the Word2Vec-based model. The three samples are recolored with one image color, one SVG color, and one text color.
    </p>
  </div>
</body>
</html>
