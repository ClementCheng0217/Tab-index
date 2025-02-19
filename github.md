---
layout: page
title: Leaderboard
permalink: /board/
---

<head>
    <meta charset="UTF-8">
    <title>Sortable Table</title>
    <link rel="stylesheet" href="https://cdn.datatables.net/1.11.3/css/jquery.dataTables.min.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.datatables.net/1.11.3/js/jquery.dataTables.min.js"></script>
</head>
<body>

<table id="example" class="display" style="width:100%">
    <caption>Average performance gap in different tasks. We attribute the different feature-shift degree for each dataset to 20%, 40%, 60%, 80% and 100%. Then compute the model's performance gap for each degree of feature shifts, task by task. '\' means this model can't handle the regression task. For classification tasks, we choose accuracy. For regression tasks, we choose RMSE. Model abbreviations are in Appendix~ref{appendix:C}.</caption>
    <thead>
        <tr>
            <th>Task</th>
            <th>Shift</th>
            <th>LGB</th>
            <th>XGB</th>
            <th>CATB</th>
            <th>PFN</th>
            <th>DAN</th>
            <th>MLP</th>
            <th>NODE</th>
            <th>RES</th>
            <th>SWI</th>
            <th>CAP</th>
            <th>NET</th>
            <th>GOS</th>
            <th>INT</th>
            <th>DCN</th>
            <th>FTT</th>
            <th>GRO</th>
            <th>SAT</th>
            <th>SNN</th>
            <th>TTF</th>
            <th>TABR</th>
            <th>NCA</th>
            <th>LMA</th>
            <th>TLLM</th>
            <th>UNI</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="5">Binary Classification</td>
            <td>20%</td>
            <td>-0.065</td>
            <td>-0.076</td>
            <td>-0.035</td>
            <td>-0.048</td>
            <td>-0.022</td>
            <td>-0.024</td>
            <td>-0.009</td>
            <td>-0.031</td>
            <td>-0.010</td>
            <td>-0.020</td>
            <td>-0.015</td>
            <td>-0.026</td>
            <td>-0.028</td>
            <td>-0.026</td>
            <td>-0.028</td>
            <td>-0.010</td>
            <td>-0.016</td>
            <td>-0.018</td>
            <td>-0.016</td>
            <td>-0.062</td>
            <td>-0.161</td>
            <td>-0.045</td>
            <td>-0.022</td>
            <td>-0.019</td>
        </tr>
        <tr>
            <td>40%</td>
            <td>-0.192</td>
            <td>-0.218</td>
            <td>-0.105</td>
            <td>-0.118</td>
            <td>-0.056</td>
            <td>-0.062</td>
            <td>-0.031</td>
            <td>-0.085</td>
            <td>-0.031</td>
            <td>-0.051</td>
            <td>-0.055</td>
            <td>-0.069</td>
            <td>-0.065</td>
            <td>-0.070</td>
            <td>-0.077</td>
            <td>-0.041</td>
            <td>-0.042</td>
            <td>-0.048</td>
            <td>-0.044</td>
            <td>-0.158</td>
            <td>-0.271</td>
            <td>-0.118</td>
            <td>-0.042</td>
            <td>-0.038</td>
        </tr>
        <tr>
            <td>60%</td>
            <td>-0.249</td>
            <td>-0.261</td>
            <td>-0.155</td>
            <td>-0.165</td>
            <td>-0.090</td>
            <td>-0.107</td>
            <td>-0.061</td>
            <td>-0.150</td>
            <td>-0.063</td>
            <td>-0.090</td>
            <td>-0.099</td>
            <td>-0.121</td>
            <td>-0.115</td>
            <td>-0.120</td>
            <td>-0.138</td>
            <td>-0.077</td>
            <td>-0.072</td>
            <td>-0.086</td>
            <td>-0.078</td>
            <td>-0.214</td>
            <td>-0.301</td>
            <td>-0.176</td>
            <td>-0.056</td>
            <td>-0.058</td>
        </tr>
        <tr>
            <td>80%</td>
            <td>-0.310</td>
            <td>-0.328</td>
            <td>-0.238</td>
            <td>-0.235</td>
            <td>-0.154</td>
            <td>-0.185</td>
            <td>-0.109</td>
            <td>-0.233</td>
            <td>-0.123</td>
            <td>-0.157</td>
            <td>-0.161</td>
            <td>-0.203</td>
            <td>-0.188</td>
            <td>-0.201</td>
            <td>-0.232</td>
            <td>-0.138</td>
            <td>-0.142</td>
            <td>-0.143</td>
            <td>-0.133</td>
            <td>-0.263</td>
            <td>-0.329</td>
            <td>-0.244</td>
            <td>-0.066</td>
            <td>-0.074</td>
        </tr>
        <tr>
            <td>100%</td>
            <td>-0.353</td>
            <td>-0.375</td>
            <td>-0.332</td>
            <td>-0.309</td>
            <td>-0.226</td>
            <td>-0.271</td>
            <td>-0.179</td>
            <td>-0.315</td>
            <td>-0.235</td>
            <td>-0.263</td>
            <td>-0.210</td>
            <td>-0.286</td>
            <td>-0.269</td>
            <td>-0.285</td>
            <td>-0.305</td>
            <td>-0.198</td>
            <td>-0.247</td>
            <td>-0.226</td>
            <td>-0.203</td>
            <td>-0.318</td>
            <td>-0.357</td>
            <td>-0.351</td>
            <td>-0.080</td>
            <td>-0.094</td>
        </tr>
    </tbody>
</table>

<script>
    $(document).ready(function() {
        $('#example').DataTable();
    });
</script>

</body>
</html>





  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>TabularBench | TabularBench: Adversarial robustness benchmark for tabular data</title>
<meta name="generator" content="Jekyll v3.10.0" />
<meta property="og:title" content="TabularBench" />
<meta property="og:locale" content="en_US" />
<meta name="description" content="TabularBench: Adversarial robustness benchmark for tabular data" />
<meta property="og:description" content="TabularBench: Adversarial robustness benchmark for tabular data" />
<link rel="canonical" href="https://serval-uni-lu.github.io/tabularbench/" />
<meta property="og:url" content="https://serval-uni-lu.github.io/tabularbench/" />
<meta property="og:site_name" content="TabularBench" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="TabularBench" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","description":"TabularBench: Adversarial robustness benchmark for tabular data","headline":"TabularBench","name":"TabularBench","url":"https://serval-uni-lu.github.io/tabularbench/"}</script>
<!-- End Jekyll SEO tag -->

    <link rel="stylesheet" href="/tabularbench/assets/css/style.css?v=f49c338261027e530fa18cee9c230835ee251e30">
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/tabularbench/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      
      <h1><a href="https://serval-uni-lu.github.io/tabularbench/">TabularBench</a></h1>
      

      <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.21/css/jquery.dataTables.min.css" />

<script src="https://code.jquery.com/jquery-3.5.1.js"></script>

<script src="https://cdn.datatables.net/1.10.21/js/jquery.dataTables.min.js"></script>

<p>TabularBench: Adversarial robustness benchmark for tabular data.</p>

<p><a href="https://serval-uni-lu.github.io/tabularbench/doc">Documentation</a>.</p>

<h2 id="leaderboard">Leaderboard</h2>

<p>You are currently viewing results of the leaderboard. View MOEVA attack results <a href="moeva">here</a>.</p>

<p>Among models that demonstrate strong robustness to constrained adversarial attacks (high ADV+CTR), we observe that some achieve this robustness solely by consistently predicting the “1” class.
This behavior is evident in their poor accuracy and precision.
Therefore, we <strong>rank</strong> models based on their average performance across clean accuracy (Accuracy) and constrained adversarial accuracy (ADV+CTR).</p>

<p>Jump to dataset:</p>

<ul>
  <li><a href="#ctu">CTU</a></li>
  <li><a href="#lcld">LCLD</a></li>
  <li><a href="#malware">Malware</a></li>
  <li><a href="#url">URL</a></li>
  <li><a href="#wids">WIDS</a></li>
</ul>

<h3 id="ctu">CTU</h3>

<p><a href="#">^ back to top</a></p>

<table>
  <thead>
    <tr>
      <th style="text-align: right">Rank</th>
      <th style="text-align: left">Architecture</th>
      <th style="text-align: left">Training</th>
      <th style="text-align: left">Augmentation</th>
      <th style="text-align: left">ID</th>
      <th style="text-align: left">ADV+CTR</th>
      <th style="text-align: left">ADV</th>
      <th style="text-align: left">AUC</th>
      <th style="text-align: left">Accuracy</th>
      <th style="text-align: left">Precision</th>
      <th style="text-align: left">Recall</th>
      <th style="text-align: left">MCC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right">1</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">97.49%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9903</td>
      <td style="text-align: left">99.90%</td>
      <td style="text-align: left">89.62%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9345</td>
    </tr>
    <tr>
      <td style="text-align: right">2</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">97.44%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9901</td>
      <td style="text-align: left">99.92%</td>
      <td style="text-align: left">92.33%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9486</td>
    </tr>
    <tr>
      <td style="text-align: right">3</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">97.30%</td>
      <td style="text-align: left">97.05%</td>
      <td style="text-align: left">97.30%</td>
      <td style="text-align: left">0.9898</td>
      <td style="text-align: left">99.90%</td>
      <td style="text-align: left">90.41%</td>
      <td style="text-align: left">97.30%</td>
      <td style="text-align: left">0.9374</td>
    </tr>
    <tr>
      <td style="text-align: right">4</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">96.76%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9875</td>
      <td style="text-align: left">98.57%</td>
      <td style="text-align: left">33.82%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.5700</td>
    </tr>
    <tr>
      <td style="text-align: right">5</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9869</td>
      <td style="text-align: left">99.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9762</td>
    </tr>
    <tr>
      <td style="text-align: right">6</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9885</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">98.73%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9699</td>
    </tr>
    <tr>
      <td style="text-align: right">7</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9788</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">8</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9796</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">9</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9836</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">10</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9816</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">11</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9864</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">12</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9861</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">13</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9801</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">14</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9861</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">15</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9884</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">16</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9847</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">17</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9846</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">18</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.28%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9791</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">98.73%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9699</td>
    </tr>
    <tr>
      <td style="text-align: right">19</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">95.58%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.58%</td>
      <td style="text-align: left">0.9904</td>
      <td style="text-align: left">99.88%</td>
      <td style="text-align: left">89.02%</td>
      <td style="text-align: left">95.58%</td>
      <td style="text-align: left">0.9218</td>
    </tr>
    <tr>
      <td style="text-align: right">20</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">96.66%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9923</td>
      <td style="text-align: left">98.50%</td>
      <td style="text-align: left">32.73%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.5605</td>
    </tr>
    <tr>
      <td style="text-align: right">21</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.18%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9785</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">99.74%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9749</td>
    </tr>
    <tr>
      <td style="text-align: right">22</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9845</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9749</td>
    </tr>
    <tr>
      <td style="text-align: right">23</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9865</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">99.23%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9712</td>
    </tr>
    <tr>
      <td style="text-align: right">24</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9832</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.47%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9674</td>
    </tr>
    <tr>
      <td style="text-align: right">25</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">96.56%</td>
      <td style="text-align: left">95.04%</td>
      <td style="text-align: left">96.56%</td>
      <td style="text-align: left">0.9906</td>
      <td style="text-align: left">99.88%</td>
      <td style="text-align: left">88.71%</td>
      <td style="text-align: left">96.56%</td>
      <td style="text-align: left">0.9250</td>
    </tr>
    <tr>
      <td style="text-align: right">26</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">94.94%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9767</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9675</td>
    </tr>
    <tr>
      <td style="text-align: right">27</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">94.59%</td>
      <td style="text-align: left">94.55%</td>
      <td style="text-align: left">94.59%</td>
      <td style="text-align: left">0.9845</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">94.59%</td>
      <td style="text-align: left">0.9724</td>
    </tr>
    <tr>
      <td style="text-align: right">28</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">94.25%</td>
      <td style="text-align: left">94.74%</td>
      <td style="text-align: left">0.9759</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">99.74%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9737</td>
    </tr>
    <tr>
      <td style="text-align: right">29</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">95.63%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9936</td>
      <td style="text-align: left">98.57%</td>
      <td style="text-align: left">33.84%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.5702</td>
    </tr>
    <tr>
      <td style="text-align: right">30</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">94.00%</td>
      <td style="text-align: left">94.20%</td>
      <td style="text-align: left">0.9825</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">99.74%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9737</td>
    </tr>
    <tr>
      <td style="text-align: right">31</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">93.91%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9776</td>
      <td style="text-align: left">99.95%</td>
      <td style="text-align: left">98.72%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9687</td>
    </tr>
    <tr>
      <td style="text-align: right">32</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">97.79%</td>
      <td style="text-align: left">94.00%</td>
      <td style="text-align: left">97.79%</td>
      <td style="text-align: left">0.9906</td>
      <td style="text-align: left">99.82%</td>
      <td style="text-align: left">81.89%</td>
      <td style="text-align: left">97.79%</td>
      <td style="text-align: left">0.8941</td>
    </tr>
    <tr>
      <td style="text-align: right">33</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">97.30%</td>
      <td style="text-align: left">93.22%</td>
      <td style="text-align: left">97.30%</td>
      <td style="text-align: left">0.9883</td>
      <td style="text-align: left">98.71%</td>
      <td style="text-align: left">36.16%</td>
      <td style="text-align: left">97.30%</td>
      <td style="text-align: left">0.5891</td>
    </tr>
    <tr>
      <td style="text-align: right">34</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">96.31%</td>
      <td style="text-align: left">96.07%</td>
      <td style="text-align: left">96.31%</td>
      <td style="text-align: left">0.9768</td>
      <td style="text-align: left">94.27%</td>
      <td style="text-align: left">11.10%</td>
      <td style="text-align: left">96.31%</td>
      <td style="text-align: left">0.3166</td>
    </tr>
    <tr>
      <td style="text-align: right">35</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">96.07%</td>
      <td style="text-align: left">96.02%</td>
      <td style="text-align: left">95.92%</td>
      <td style="text-align: left">0.9863</td>
      <td style="text-align: left">92.96%</td>
      <td style="text-align: left">9.19%</td>
      <td style="text-align: left">96.07%</td>
      <td style="text-align: left">0.2855</td>
    </tr>
    <tr>
      <td style="text-align: right">36</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">85.50%</td>
      <td style="text-align: left">89.39%</td>
      <td style="text-align: left">0.9788</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">99.74%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9737</td>
    </tr>
    <tr>
      <td style="text-align: right">37</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">96.31%</td>
      <td style="text-align: left">96.07%</td>
      <td style="text-align: left">96.31%</td>
      <td style="text-align: left">0.9841</td>
      <td style="text-align: left">89.01%</td>
      <td style="text-align: left">6.10%</td>
      <td style="text-align: left">96.31%</td>
      <td style="text-align: left">0.2274</td>
    </tr>
    <tr>
      <td style="text-align: right">38</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">81.43%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9924</td>
      <td style="text-align: left">99.88%</td>
      <td style="text-align: left">88.03%</td>
      <td style="text-align: left">97.54%</td>
      <td style="text-align: left">0.9261</td>
    </tr>
    <tr>
      <td style="text-align: right">39</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">66.98%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9840</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">99.74%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9737</td>
    </tr>
    <tr>
      <td style="text-align: right">40</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">98.28%</td>
      <td style="text-align: left">98.28%</td>
      <td style="text-align: left">98.28%</td>
      <td style="text-align: left">0.9741</td>
      <td style="text-align: left">60.87%</td>
      <td style="text-align: left">1.82%</td>
      <td style="text-align: left">98.28%</td>
      <td style="text-align: left">0.1030</td>
    </tr>
    <tr>
      <td style="text-align: right">41</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">98.28%</td>
      <td style="text-align: left">98.28%</td>
      <td style="text-align: left">98.23%</td>
      <td style="text-align: left">0.9811</td>
      <td style="text-align: left">43.56%</td>
      <td style="text-align: left">1.27%</td>
      <td style="text-align: left">98.28%</td>
      <td style="text-align: left">0.0717</td>
    </tr>
    <tr>
      <td style="text-align: right">42</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">40.84%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9873</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">99.74%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9737</td>
    </tr>
    <tr>
      <td style="text-align: right">43</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">35.04%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9907</td>
      <td style="text-align: left">99.96%</td>
      <td style="text-align: left">99.74%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">0.9737</td>
    </tr>
    <tr>
      <td style="text-align: right">44</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">22.85%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9771</td>
      <td style="text-align: left">99.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">0.9762</td>
    </tr>
    <tr>
      <td style="text-align: right">45</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.9768</td>
      <td style="text-align: left">1.57%</td>
      <td style="text-align: left">0.75%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.0079</td>
    </tr>
    <tr>
      <td style="text-align: right">46</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.9496</td>
      <td style="text-align: left">0.75%</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.0010</td>
    </tr>
    <tr>
      <td style="text-align: right">47</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.7411</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">48</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.9724</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">49</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.7273</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">50</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.9764</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">51</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">1.47%</td>
      <td style="text-align: left">1.43%</td>
      <td style="text-align: left">1.43%</td>
      <td style="text-align: left">0.9930</td>
      <td style="text-align: left">99.27%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">1.47%</td>
      <td style="text-align: left">0.1210</td>
    </tr>
    <tr>
      <td style="text-align: right">52</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">96.07%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">96.07%</td>
      <td style="text-align: left">0.9963</td>
      <td style="text-align: left">99.94%</td>
      <td style="text-align: left">95.83%</td>
      <td style="text-align: left">96.07%</td>
      <td style="text-align: left">0.9592</td>
    </tr>
    <tr>
      <td style="text-align: right">53</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">0.25%</td>
      <td style="text-align: left">0.20%</td>
      <td style="text-align: left">0.20%</td>
      <td style="text-align: left">0.9781</td>
      <td style="text-align: left">99.26%</td>
      <td style="text-align: left">50.00%</td>
      <td style="text-align: left">0.25%</td>
      <td style="text-align: left">0.0347</td>
    </tr>
    <tr>
      <td style="text-align: right">54</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.9823</td>
      <td style="text-align: left">99.26%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">55</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.9861</td>
      <td style="text-align: left">99.26%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">56</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.9865</td>
      <td style="text-align: left">99.26%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">57</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.9823</td>
      <td style="text-align: left">99.26%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">58</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.9868</td>
      <td style="text-align: left">99.26%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.0000</td>
    </tr>
    <tr>
      <td style="text-align: right">59</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">94.40%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.6272</td>
      <td style="text-align: left">4.49%</td>
      <td style="text-align: left">0.77%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.0170</td>
    </tr>
    <tr>
      <td style="text-align: right">60</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">94.40%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.6304</td>
      <td style="text-align: left">4.38%</td>
      <td style="text-align: left">0.77%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.0168</td>
    </tr>
    <tr>
      <td style="text-align: right">61</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">96.31%</td>
      <td style="text-align: left">96.07%</td>
      <td style="text-align: left">96.31%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">62</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">63</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">64</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">65</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.23%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">66</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">95.18%</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">67</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">68</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">94.99%</td>
      <td style="text-align: left">94.89%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">69</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">76.90%</td>
      <td style="text-align: left">95.09%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">70</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">95.33%</td>
      <td style="text-align: left">72.33%</td>
      <td style="text-align: left">76.56%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
  </tbody>
</table>

<h3 id="lcld">LCLD</h3>

<p><a href="#">^ back to top</a></p>

<table>
  <thead>
    <tr>
      <th style="text-align: right">Rank</th>
      <th style="text-align: left">Architecture</th>
      <th style="text-align: left">Training</th>
      <th style="text-align: left">Augmentation</th>
      <th style="text-align: left">ID</th>
      <th style="text-align: left">ADV+CTR</th>
      <th style="text-align: left">ADV</th>
      <th style="text-align: right">AUC</th>
      <th style="text-align: left">Accuracy</th>
      <th style="text-align: left">Precision</th>
      <th style="text-align: left">Recall</th>
      <th style="text-align: right">MCC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right">1</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">82.00%</td>
      <td style="text-align: left">81.16%</td>
      <td style="text-align: left">82.00%</td>
      <td style="text-align: right">0.7002</td>
      <td style="text-align: left">50.50%</td>
      <td style="text-align: left">26.61%</td>
      <td style="text-align: left">83.28%</td>
      <td style="text-align: right">0.2118</td>
    </tr>
    <tr>
      <td style="text-align: right">2</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">79.50%</td>
      <td style="text-align: left">78.50%</td>
      <td style="text-align: left">79.50%</td>
      <td style="text-align: right">0.6945</td>
      <td style="text-align: left">52.63%</td>
      <td style="text-align: left">27.09%</td>
      <td style="text-align: left">80.27%</td>
      <td style="text-align: right">0.2119</td>
    </tr>
    <tr>
      <td style="text-align: right">3</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">72.50%</td>
      <td style="text-align: left">70.96%</td>
      <td style="text-align: left">72.50%</td>
      <td style="text-align: right">0.7016</td>
      <td style="text-align: left">59.56%</td>
      <td style="text-align: left">29.41%</td>
      <td style="text-align: left">72.33%</td>
      <td style="text-align: right">0.2299</td>
    </tr>
    <tr>
      <td style="text-align: right">4</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">78.90%</td>
      <td style="text-align: left">76.84%</td>
      <td style="text-align: left">78.90%</td>
      <td style="text-align: right">0.7009</td>
      <td style="text-align: left">53.50%</td>
      <td style="text-align: left">27.49%</td>
      <td style="text-align: left">80.30%</td>
      <td style="text-align: right">0.2203</td>
    </tr>
    <tr>
      <td style="text-align: right">5</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">68.90%</td>
      <td style="text-align: left">67.80%</td>
      <td style="text-align: left">68.90%</td>
      <td style="text-align: right">0.7056</td>
      <td style="text-align: left">62.53%</td>
      <td style="text-align: left">30.68%</td>
      <td style="text-align: left">68.69%</td>
      <td style="text-align: right">0.239</td>
    </tr>
    <tr>
      <td style="text-align: right">6</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">69.40%</td>
      <td style="text-align: left">68.20%</td>
      <td style="text-align: left">69.40%</td>
      <td style="text-align: right">0.6979</td>
      <td style="text-align: left">61.58%</td>
      <td style="text-align: left">30.04%</td>
      <td style="text-align: left">68.68%</td>
      <td style="text-align: right">0.229</td>
    </tr>
    <tr>
      <td style="text-align: right">7</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">73.90%</td>
      <td style="text-align: left">70.28%</td>
      <td style="text-align: left">73.90%</td>
      <td style="text-align: right">0.7111</td>
      <td style="text-align: left">59.01%</td>
      <td style="text-align: left">29.33%</td>
      <td style="text-align: left">73.83%</td>
      <td style="text-align: right">0.2333</td>
    </tr>
    <tr>
      <td style="text-align: right">8</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">67.80%</td>
      <td style="text-align: left">66.12%</td>
      <td style="text-align: left">67.80%</td>
      <td style="text-align: right">0.7054</td>
      <td style="text-align: left">62.79%</td>
      <td style="text-align: left">30.81%</td>
      <td style="text-align: left">68.41%</td>
      <td style="text-align: right">0.2401</td>
    </tr>
    <tr>
      <td style="text-align: right">9</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">68.70%</td>
      <td style="text-align: left">66.50%</td>
      <td style="text-align: left">68.70%</td>
      <td style="text-align: right">0.7024</td>
      <td style="text-align: left">61.96%</td>
      <td style="text-align: left">30.36%</td>
      <td style="text-align: left">69.09%</td>
      <td style="text-align: right">0.2353</td>
    </tr>
    <tr>
      <td style="text-align: right">10</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">67.00%</td>
      <td style="text-align: left">64.34%</td>
      <td style="text-align: left">67.00%</td>
      <td style="text-align: right">0.7079</td>
      <td style="text-align: left">63.55%</td>
      <td style="text-align: left">31.20%</td>
      <td style="text-align: left">67.61%</td>
      <td style="text-align: right">0.2435</td>
    </tr>
    <tr>
      <td style="text-align: right">11</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">69.50%</td>
      <td style="text-align: left">63.04%</td>
      <td style="text-align: left">69.48%</td>
      <td style="text-align: right">0.7158</td>
      <td style="text-align: left">62.75%</td>
      <td style="text-align: left">30.93%</td>
      <td style="text-align: left">69.28%</td>
      <td style="text-align: right">0.2448</td>
    </tr>
    <tr>
      <td style="text-align: right">12</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">62.70%</td>
      <td style="text-align: left">60.08%</td>
      <td style="text-align: left">62.70%</td>
      <td style="text-align: right">0.6995</td>
      <td style="text-align: left">65.68%</td>
      <td style="text-align: left">31.83%</td>
      <td style="text-align: left">62.07%</td>
      <td style="text-align: right">0.2352</td>
    </tr>
    <tr>
      <td style="text-align: right">13</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">61.30%</td>
      <td style="text-align: left">59.68%</td>
      <td style="text-align: left">61.30%</td>
      <td style="text-align: right">0.6991</td>
      <td style="text-align: left">65.73%</td>
      <td style="text-align: left">31.80%</td>
      <td style="text-align: left">61.69%</td>
      <td style="text-align: right">0.2336</td>
    </tr>
    <tr>
      <td style="text-align: right">14</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">63.60%</td>
      <td style="text-align: left">60.54%</td>
      <td style="text-align: left">63.60%</td>
      <td style="text-align: right">0.6988</td>
      <td style="text-align: left">64.49%</td>
      <td style="text-align: left">31.18%</td>
      <td style="text-align: left">63.62%</td>
      <td style="text-align: right">0.2307</td>
    </tr>
    <tr>
      <td style="text-align: right">15</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">66.50%</td>
      <td style="text-align: left">62.84%</td>
      <td style="text-align: left">66.50%</td>
      <td style="text-align: right">0.6879</td>
      <td style="text-align: left">61.49%</td>
      <td style="text-align: left">29.57%</td>
      <td style="text-align: left">66.36%</td>
      <td style="text-align: right">0.2144</td>
    </tr>
    <tr>
      <td style="text-align: right">16</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">56.80%</td>
      <td style="text-align: left">53.22%</td>
      <td style="text-align: left">56.80%</td>
      <td style="text-align: right">0.7032</td>
      <td style="text-align: left">68.53%</td>
      <td style="text-align: left">33.37%</td>
      <td style="text-align: left">56.88%</td>
      <td style="text-align: right">0.2393</td>
    </tr>
    <tr>
      <td style="text-align: right">17</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">60.80%</td>
      <td style="text-align: left">56.44%</td>
      <td style="text-align: left">60.80%</td>
      <td style="text-align: right">0.694</td>
      <td style="text-align: left">65.11%</td>
      <td style="text-align: left">31.25%</td>
      <td style="text-align: left">61.43%</td>
      <td style="text-align: right">0.2251</td>
    </tr>
    <tr>
      <td style="text-align: right">18</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">56.30%</td>
      <td style="text-align: left">53.68%</td>
      <td style="text-align: left">56.30%</td>
      <td style="text-align: right">0.6955</td>
      <td style="text-align: left">67.66%</td>
      <td style="text-align: left">32.66%</td>
      <td style="text-align: left">57.40%</td>
      <td style="text-align: right">0.2318</td>
    </tr>
    <tr>
      <td style="text-align: right">19</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">57.00%</td>
      <td style="text-align: left">52.86%</td>
      <td style="text-align: left">57.00%</td>
      <td style="text-align: right">0.7006</td>
      <td style="text-align: left">68.21%</td>
      <td style="text-align: left">33.19%</td>
      <td style="text-align: left">57.51%</td>
      <td style="text-align: right">0.239</td>
    </tr>
    <tr>
      <td style="text-align: right">20</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.6829</td>
      <td style="text-align: left">20.09%</td>
      <td style="text-align: left">20.09%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">21</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">61.70%</td>
      <td style="text-align: left">53.04%</td>
      <td style="text-align: left">61.70%</td>
      <td style="text-align: right">0.6994</td>
      <td style="text-align: left">65.96%</td>
      <td style="text-align: left">32.00%</td>
      <td style="text-align: left">61.77%</td>
      <td style="text-align: right">0.2367</td>
    </tr>
    <tr>
      <td style="text-align: right">22</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">66.40%</td>
      <td style="text-align: left">53.60%</td>
      <td style="text-align: left">66.40%</td>
      <td style="text-align: right">0.7087</td>
      <td style="text-align: left">64.56%</td>
      <td style="text-align: left">31.67%</td>
      <td style="text-align: left">65.99%</td>
      <td style="text-align: right">0.2452</td>
    </tr>
    <tr>
      <td style="text-align: right">23</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">64.90%</td>
      <td style="text-align: left">50.50%</td>
      <td style="text-align: left">64.90%</td>
      <td style="text-align: right">0.7063</td>
      <td style="text-align: left">65.17%</td>
      <td style="text-align: left">31.87%</td>
      <td style="text-align: left">64.53%</td>
      <td style="text-align: right">0.2436</td>
    </tr>
    <tr>
      <td style="text-align: right">24</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">58.10%</td>
      <td style="text-align: left">47.02%</td>
      <td style="text-align: left">58.10%</td>
      <td style="text-align: right">0.7058</td>
      <td style="text-align: left">68.34%</td>
      <td style="text-align: left">33.40%</td>
      <td style="text-align: left">57.99%</td>
      <td style="text-align: right">0.2432</td>
    </tr>
    <tr>
      <td style="text-align: right">25</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">51.00%</td>
      <td style="text-align: left">44.22%</td>
      <td style="text-align: left">51.00%</td>
      <td style="text-align: right">0.7016</td>
      <td style="text-align: left">71.04%</td>
      <td style="text-align: left">34.88%</td>
      <td style="text-align: left">50.91%</td>
      <td style="text-align: right">0.2378</td>
    </tr>
    <tr>
      <td style="text-align: right">26</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">73.70%</td>
      <td style="text-align: left">54.34%</td>
      <td style="text-align: left">73.70%</td>
      <td style="text-align: right">0.7036</td>
      <td style="text-align: left">58.20%</td>
      <td style="text-align: left">29.04%</td>
      <td style="text-align: left">74.90%</td>
      <td style="text-align: right">0.2317</td>
    </tr>
    <tr>
      <td style="text-align: right">27</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">37.60%</td>
      <td style="text-align: left">36.20%</td>
      <td style="text-align: left">37.60%</td>
      <td style="text-align: right">0.7033</td>
      <td style="text-align: left">75.83%</td>
      <td style="text-align: left">39.26%</td>
      <td style="text-align: left">37.10%</td>
      <td style="text-align: right">0.2316</td>
    </tr>
    <tr>
      <td style="text-align: right">28</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">57.70%</td>
      <td style="text-align: left">43.28%</td>
      <td style="text-align: left">57.70%</td>
      <td style="text-align: right">0.7037</td>
      <td style="text-align: left">67.74%</td>
      <td style="text-align: left">33.05%</td>
      <td style="text-align: left">59.08%</td>
      <td style="text-align: right">0.2422</td>
    </tr>
    <tr>
      <td style="text-align: right">29</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">68.80%</td>
      <td style="text-align: left">47.88%</td>
      <td style="text-align: left">68.80%</td>
      <td style="text-align: right">0.7045</td>
      <td style="text-align: left">62.94%</td>
      <td style="text-align: left">30.83%</td>
      <td style="text-align: left">67.95%</td>
      <td style="text-align: right">0.239</td>
    </tr>
    <tr>
      <td style="text-align: right">30</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">83.30%</td>
      <td style="text-align: left">59.50%</td>
      <td style="text-align: left">83.30%</td>
      <td style="text-align: right">0.7053</td>
      <td style="text-align: left">50.26%</td>
      <td style="text-align: left">26.63%</td>
      <td style="text-align: left">84.07%</td>
      <td style="text-align: right">0.2149</td>
    </tr>
    <tr>
      <td style="text-align: right">31</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">66.10%</td>
      <td style="text-align: left">40.18%</td>
      <td style="text-align: left">66.10%</td>
      <td style="text-align: right">0.7054</td>
      <td style="text-align: left">64.58%</td>
      <td style="text-align: left">31.56%</td>
      <td style="text-align: left">65.29%</td>
      <td style="text-align: right">0.2414</td>
    </tr>
    <tr>
      <td style="text-align: right">32</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">61.40%</td>
      <td style="text-align: left">37.74%</td>
      <td style="text-align: left">61.40%</td>
      <td style="text-align: right">0.7047</td>
      <td style="text-align: left">66.93%</td>
      <td style="text-align: left">32.61%</td>
      <td style="text-align: left">60.60%</td>
      <td style="text-align: right">0.2412</td>
    </tr>
    <tr>
      <td style="text-align: right">33</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">35.20%</td>
      <td style="text-align: left">22.16%</td>
      <td style="text-align: left">35.20%</td>
      <td style="text-align: right">0.7068</td>
      <td style="text-align: left">76.60%</td>
      <td style="text-align: left">40.38%</td>
      <td style="text-align: left">34.66%</td>
      <td style="text-align: right">0.2312</td>
    </tr>
    <tr>
      <td style="text-align: right">34</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">67.80%</td>
      <td style="text-align: left">31.96%</td>
      <td style="text-align: left">67.80%</td>
      <td style="text-align: right">0.71</td>
      <td style="text-align: left">64.41%</td>
      <td style="text-align: left">31.66%</td>
      <td style="text-align: left">66.63%</td>
      <td style="text-align: right">0.2472</td>
    </tr>
    <tr>
      <td style="text-align: right">35</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">15.60%</td>
      <td style="text-align: left">12.08%</td>
      <td style="text-align: left">15.60%</td>
      <td style="text-align: right">0.6788</td>
      <td style="text-align: left">78.82%</td>
      <td style="text-align: left">43.19%</td>
      <td style="text-align: left">17.18%</td>
      <td style="text-align: right">0.1699</td>
    </tr>
    <tr>
      <td style="text-align: right">36</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">11.60%</td>
      <td style="text-align: left">11.36%</td>
      <td style="text-align: left">11.70%</td>
      <td style="text-align: right">0.6522</td>
      <td style="text-align: left">73.18%</td>
      <td style="text-align: left">22.51%</td>
      <td style="text-align: left">13.72%</td>
      <td style="text-align: right">0.0226</td>
    </tr>
    <tr>
      <td style="text-align: right">37</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">2.90%</td>
      <td style="text-align: left">2.12%</td>
      <td style="text-align: left">3.00%</td>
      <td style="text-align: right">0.6874</td>
      <td style="text-align: left">78.45%</td>
      <td style="text-align: left">26.96%</td>
      <td style="text-align: left">4.25%</td>
      <td style="text-align: right">0.031</td>
    </tr>
    <tr>
      <td style="text-align: right">38</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">1.30%</td>
      <td style="text-align: left">1.04%</td>
      <td style="text-align: left">1.40%</td>
      <td style="text-align: right">0.6887</td>
      <td style="text-align: left">79.30%</td>
      <td style="text-align: left">25.50%</td>
      <td style="text-align: left">1.59%</td>
      <td style="text-align: right">0.0152</td>
    </tr>
    <tr>
      <td style="text-align: right">39</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.6998</td>
      <td style="text-align: left">79.91%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0.003</td>
    </tr>
    <tr>
      <td style="text-align: right">40</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.6649</td>
      <td style="text-align: left">79.91%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">41</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.6727</td>
      <td style="text-align: left">79.91%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">42</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.6879</td>
      <td style="text-align: left">79.91%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">43</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.6959</td>
      <td style="text-align: left">79.91%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">44</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.6375</td>
      <td style="text-align: left">79.91%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">45</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.6947</td>
      <td style="text-align: left">79.91%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">46</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.656</td>
      <td style="text-align: left">79.91%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">47</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.10%</td>
      <td style="text-align: right">0.6667</td>
      <td style="text-align: left">79.89%</td>
      <td style="text-align: left">24.84%</td>
      <td style="text-align: left">0.04%</td>
      <td style="text-align: right">0.0022</td>
    </tr>
    <tr>
      <td style="text-align: right">48</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">65.50%</td>
      <td style="text-align: left">10.36%</td>
      <td style="text-align: left">65.50%</td>
      <td style="text-align: right">0.7127</td>
      <td style="text-align: left">65.13%</td>
      <td style="text-align: left">32.05%</td>
      <td style="text-align: left">65.71%</td>
      <td style="text-align: right">0.2499</td>
    </tr>
    <tr>
      <td style="text-align: right">49</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">69.30%</td>
      <td style="text-align: left">10.14%</td>
      <td style="text-align: left">69.30%</td>
      <td style="text-align: right">0.7096</td>
      <td style="text-align: left">63.62%</td>
      <td style="text-align: left">31.28%</td>
      <td style="text-align: left">67.77%</td>
      <td style="text-align: right">0.2452</td>
    </tr>
    <tr>
      <td style="text-align: right">50</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">52.30%</td>
      <td style="text-align: left">2.00%</td>
      <td style="text-align: left">52.30%</td>
      <td style="text-align: right">0.7101</td>
      <td style="text-align: left">71.04%</td>
      <td style="text-align: left">35.26%</td>
      <td style="text-align: left">52.83%</td>
      <td style="text-align: right">0.2485</td>
    </tr>
    <tr>
      <td style="text-align: right">51</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">68.90%</td>
      <td style="text-align: left">7.88%</td>
      <td style="text-align: left">68.90%</td>
      <td style="text-align: right">0.7122</td>
      <td style="text-align: left">63.82%</td>
      <td style="text-align: left">31.48%</td>
      <td style="text-align: left">68.10%</td>
      <td style="text-align: right">0.2493</td>
    </tr>
    <tr>
      <td style="text-align: right">52</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">69.50%</td>
      <td style="text-align: left">7.88%</td>
      <td style="text-align: left">69.50%</td>
      <td style="text-align: right">0.7172</td>
      <td style="text-align: left">63.32%</td>
      <td style="text-align: left">31.42%</td>
      <td style="text-align: left">69.87%</td>
      <td style="text-align: right">0.2542</td>
    </tr>
    <tr>
      <td style="text-align: right">53</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">67.70%</td>
      <td style="text-align: left">7.30%</td>
      <td style="text-align: left">67.70%</td>
      <td style="text-align: right">0.7115</td>
      <td style="text-align: left">63.80%</td>
      <td style="text-align: left">31.41%</td>
      <td style="text-align: left">67.73%</td>
      <td style="text-align: right">0.247</td>
    </tr>
    <tr>
      <td style="text-align: right">54</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">72.40%</td>
      <td style="text-align: left">8.14%</td>
      <td style="text-align: left">72.40%</td>
      <td style="text-align: right">0.7111</td>
      <td style="text-align: left">61.44%</td>
      <td style="text-align: left">30.42%</td>
      <td style="text-align: left">71.46%</td>
      <td style="text-align: right">0.2438</td>
    </tr>
    <tr>
      <td style="text-align: right">55</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">70.10%</td>
      <td style="text-align: left">5.54%</td>
      <td style="text-align: left">70.10%</td>
      <td style="text-align: right">0.7108</td>
      <td style="text-align: left">63.44%</td>
      <td style="text-align: left">31.27%</td>
      <td style="text-align: left">68.43%</td>
      <td style="text-align: right">0.2472</td>
    </tr>
    <tr>
      <td style="text-align: right">56</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">70.30%</td>
      <td style="text-align: left">4.82%</td>
      <td style="text-align: left">70.30%</td>
      <td style="text-align: right">0.7155</td>
      <td style="text-align: left">63.41%</td>
      <td style="text-align: left">31.39%</td>
      <td style="text-align: left">69.27%</td>
      <td style="text-align: right">0.2517</td>
    </tr>
    <tr>
      <td style="text-align: right">57</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">60.70%</td>
      <td style="text-align: left">0.46%</td>
      <td style="text-align: left">60.70%</td>
      <td style="text-align: right">0.708</td>
      <td style="text-align: left">67.62%</td>
      <td style="text-align: left">33.23%</td>
      <td style="text-align: left">60.63%</td>
      <td style="text-align: right">0.2495</td>
    </tr>
    <tr>
      <td style="text-align: right">58</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">64.40%</td>
      <td style="text-align: left">0.50%</td>
      <td style="text-align: left">64.40%</td>
      <td style="text-align: right">0.7139</td>
      <td style="text-align: left">66.62%</td>
      <td style="text-align: left">32.83%</td>
      <td style="text-align: left">63.25%</td>
      <td style="text-align: right">0.2527</td>
    </tr>
    <tr>
      <td style="text-align: right">59</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">67.00%</td>
      <td style="text-align: left">2.38%</td>
      <td style="text-align: left">67.00%</td>
      <td style="text-align: right">0.7142</td>
      <td style="text-align: left">64.46%</td>
      <td style="text-align: left">31.79%</td>
      <td style="text-align: left">67.13%</td>
      <td style="text-align: right">0.2506</td>
    </tr>
    <tr>
      <td style="text-align: right">60</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">66.80%</td>
      <td style="text-align: left">0.74%</td>
      <td style="text-align: left">66.80%</td>
      <td style="text-align: right">0.7138</td>
      <td style="text-align: left">65.36%</td>
      <td style="text-align: left">32.23%</td>
      <td style="text-align: left">65.69%</td>
      <td style="text-align: right">0.2524</td>
    </tr>
    <tr>
      <td style="text-align: right">61</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">67.40%</td>
      <td style="text-align: left">0.42%</td>
      <td style="text-align: left">67.40%</td>
      <td style="text-align: right">0.7224</td>
      <td style="text-align: left">65.60%</td>
      <td style="text-align: left">32.62%</td>
      <td style="text-align: left">66.83%</td>
      <td style="text-align: right">0.2615</td>
    </tr>
    <tr>
      <td style="text-align: right">62</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">65.90%</td>
      <td style="text-align: left">0.66%</td>
      <td style="text-align: left">65.90%</td>
      <td style="text-align: right">0.7081</td>
      <td style="text-align: left">64.83%</td>
      <td style="text-align: left">31.83%</td>
      <td style="text-align: left">65.76%</td>
      <td style="text-align: right">0.2468</td>
    </tr>
    <tr>
      <td style="text-align: right">63</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">67.90%</td>
      <td style="text-align: left">0.52%</td>
      <td style="text-align: left">67.90%</td>
      <td style="text-align: right">0.7125</td>
      <td style="text-align: left">64.40%</td>
      <td style="text-align: left">31.69%</td>
      <td style="text-align: left">66.82%</td>
      <td style="text-align: right">0.2483</td>
    </tr>
    <tr>
      <td style="text-align: right">64</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">67.30%</td>
      <td style="text-align: left">0.02%</td>
      <td style="text-align: left">67.30%</td>
      <td style="text-align: right">0.7169</td>
      <td style="text-align: left">64.84%</td>
      <td style="text-align: left">32.09%</td>
      <td style="text-align: left">67.19%</td>
      <td style="text-align: right">0.2552</td>
    </tr>
    <tr>
      <td style="text-align: right">65</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">69.30%</td>
      <td style="text-align: left">0.14%</td>
      <td style="text-align: left">69.30%</td>
      <td style="text-align: right">0.7118</td>
      <td style="text-align: left">64.25%</td>
      <td style="text-align: left">31.64%</td>
      <td style="text-align: left">67.21%</td>
      <td style="text-align: right">0.2488</td>
    </tr>
    <tr>
      <td style="text-align: right">66</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">68.30%</td>
      <td style="text-align: left">0.02%</td>
      <td style="text-align: left">68.30%</td>
      <td style="text-align: right">0.7187</td>
      <td style="text-align: left">64.13%</td>
      <td style="text-align: left">31.78%</td>
      <td style="text-align: left">68.51%</td>
      <td style="text-align: right">0.255</td>
    </tr>
    <tr>
      <td style="text-align: right">67</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">70.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">70.00%</td>
      <td style="text-align: right">0.7173</td>
      <td style="text-align: left">63.33%</td>
      <td style="text-align: left">31.40%</td>
      <td style="text-align: left">69.66%</td>
      <td style="text-align: right">0.2531</td>
    </tr>
    <tr>
      <td style="text-align: right">68</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">68.90%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">68.90%</td>
      <td style="text-align: right">0.7152</td>
      <td style="text-align: left">63.26%</td>
      <td style="text-align: left">31.29%</td>
      <td style="text-align: left">69.31%</td>
      <td style="text-align: right">0.2504</td>
    </tr>
    <tr>
      <td style="text-align: right">69</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">70.50%</td>
      <td style="text-align: left">0.12%</td>
      <td style="text-align: left">70.50%</td>
      <td style="text-align: right">0.7094</td>
      <td style="text-align: left">61.96%</td>
      <td style="text-align: left">30.57%</td>
      <td style="text-align: left">70.27%</td>
      <td style="text-align: right">0.2422</td>
    </tr>
    <tr>
      <td style="text-align: right">70</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">77.30%</td>
      <td style="text-align: left">1.76%</td>
      <td style="text-align: left">77.30%</td>
      <td style="text-align: right">0.7061</td>
      <td style="text-align: left">57.09%</td>
      <td style="text-align: left">28.71%</td>
      <td style="text-align: left">76.61%</td>
      <td style="text-align: right">0.2313</td>
    </tr>
  </tbody>
</table>

<h3 id="malware">Malware</h3>

<p><a href="#">^ back to top</a></p>

<table>
  <thead>
    <tr>
      <th style="text-align: right">Rank</th>
      <th style="text-align: left">Architecture</th>
      <th style="text-align: left">Training</th>
      <th style="text-align: left">Augmentation</th>
      <th style="text-align: left">ID</th>
      <th style="text-align: left">ADV+CTR</th>
      <th style="text-align: left">ADV</th>
      <th style="text-align: left">AUC</th>
      <th style="text-align: left">Accuracy</th>
      <th style="text-align: left">Precision</th>
      <th style="text-align: left">Recall</th>
      <th style="text-align: left">MCC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right">1</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">0.9893</td>
      <td style="text-align: left">95.49%</td>
      <td style="text-align: left">96.09%</td>
      <td style="text-align: left">95.01%</td>
      <td style="text-align: left">0.9098</td>
    </tr>
    <tr>
      <td style="text-align: right">2</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">93.00%</td>
      <td style="text-align: left">92.80%</td>
      <td style="text-align: left">93.00%</td>
      <td style="text-align: left">0.9907</td>
      <td style="text-align: left">94.88%</td>
      <td style="text-align: left">96.90%</td>
      <td style="text-align: left">92.93%</td>
      <td style="text-align: left">0.8985</td>
    </tr>
    <tr>
      <td style="text-align: right">3</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">90.20%</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">0.9926</td>
      <td style="text-align: left">97.08%</td>
      <td style="text-align: left">97.81%</td>
      <td style="text-align: left">96.43%</td>
      <td style="text-align: left">0.9417</td>
    </tr>
    <tr>
      <td style="text-align: right">4</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">89.80%</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">0.9941</td>
      <td style="text-align: left">97.46%</td>
      <td style="text-align: left">98.33%</td>
      <td style="text-align: left">96.65%</td>
      <td style="text-align: left">0.9493</td>
    </tr>
    <tr>
      <td style="text-align: right">5</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">99.00%</td>
      <td style="text-align: left">80.20%</td>
      <td style="text-align: left">99.00%</td>
      <td style="text-align: left">0.9944</td>
      <td style="text-align: left">96.78%</td>
      <td style="text-align: left">96.32%</td>
      <td style="text-align: left">97.40%</td>
      <td style="text-align: left">0.9356</td>
    </tr>
    <tr>
      <td style="text-align: right">6</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">99.00%</td>
      <td style="text-align: left">99.00%</td>
      <td style="text-align: left">99.00%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">7</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">96.00%</td>
      <td style="text-align: left">95.20%</td>
      <td style="text-align: left">96.00%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">8</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">94.20%</td>
      <td style="text-align: left">95.00%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">9</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">93.00%</td>
      <td style="text-align: left">92.80%</td>
      <td style="text-align: left">93.00%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
    <tr>
      <td style="text-align: right">10</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">92.00%</td>
      <td style="text-align: left">92.00%</td>
      <td style="text-align: left">92.00%</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
      <td style="text-align: left">-</td>
    </tr>
  </tbody>
</table>

<h3 id="url">URL</h3>

<p><a href="#">^ back to top</a></p>

<table>
  <thead>
    <tr>
      <th style="text-align: right">Rank</th>
      <th style="text-align: left">Architecture</th>
      <th style="text-align: left">Training</th>
      <th style="text-align: left">Augmentation</th>
      <th style="text-align: left">ID</th>
      <th style="text-align: left">ADV+CTR</th>
      <th style="text-align: left">ADV</th>
      <th style="text-align: right">AUC</th>
      <th style="text-align: left">Accuracy</th>
      <th style="text-align: left">Precision</th>
      <th style="text-align: left">Recall</th>
      <th style="text-align: right">MCC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right">1</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">94.30%</td>
      <td style="text-align: left">89.96%</td>
      <td style="text-align: left">90.32%</td>
      <td style="text-align: right">0.9485</td>
      <td style="text-align: left">86.22%</td>
      <td style="text-align: left">81.17%</td>
      <td style="text-align: left">94.31%</td>
      <td style="text-align: right">0.7341</td>
    </tr>
    <tr>
      <td style="text-align: right">2</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">93.00%</td>
      <td style="text-align: left">89.70%</td>
      <td style="text-align: left">89.64%</td>
      <td style="text-align: right">0.9348</td>
      <td style="text-align: left">86.05%</td>
      <td style="text-align: left">81.45%</td>
      <td style="text-align: left">93.35%</td>
      <td style="text-align: right">0.7287</td>
    </tr>
    <tr>
      <td style="text-align: right">3</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">95.40%</td>
      <td style="text-align: left">89.34%</td>
      <td style="text-align: left">89.38%</td>
      <td style="text-align: right">0.9469</td>
      <td style="text-align: left">86.05%</td>
      <td style="text-align: left">80.16%</td>
      <td style="text-align: left">95.80%</td>
      <td style="text-align: right">0.735</td>
    </tr>
    <tr>
      <td style="text-align: right">4</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">93.80%</td>
      <td style="text-align: left">89.08%</td>
      <td style="text-align: left">89.16%</td>
      <td style="text-align: right">0.9495</td>
      <td style="text-align: left">86.13%</td>
      <td style="text-align: left">81.29%</td>
      <td style="text-align: left">93.88%</td>
      <td style="text-align: right">0.7315</td>
    </tr>
    <tr>
      <td style="text-align: right">5</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">90.10%</td>
      <td style="text-align: left">89.90%</td>
      <td style="text-align: left">89.90%</td>
      <td style="text-align: right">0.9428</td>
      <td style="text-align: left">85.26%</td>
      <td style="text-align: left">81.93%</td>
      <td style="text-align: left">90.46%</td>
      <td style="text-align: right">0.709</td>
    </tr>
    <tr>
      <td style="text-align: right">6</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">89.80%</td>
      <td style="text-align: left">89.60%</td>
      <td style="text-align: left">89.60%</td>
      <td style="text-align: right">0.9562</td>
      <td style="text-align: left">85.26%</td>
      <td style="text-align: left">82.14%</td>
      <td style="text-align: left">90.11%</td>
      <td style="text-align: right">0.7085</td>
    </tr>
    <tr>
      <td style="text-align: right">7</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">93.20%</td>
      <td style="text-align: left">89.56%</td>
      <td style="text-align: left">89.60%</td>
      <td style="text-align: right">0.934</td>
      <td style="text-align: left">85.13%</td>
      <td style="text-align: left">80.26%</td>
      <td style="text-align: left">93.18%</td>
      <td style="text-align: right">0.7118</td>
    </tr>
    <tr>
      <td style="text-align: right">8</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">93.90%</td>
      <td style="text-align: left">85.62%</td>
      <td style="text-align: left">86.04%</td>
      <td style="text-align: right">0.9542</td>
      <td style="text-align: left">88.23%</td>
      <td style="text-align: left">84.25%</td>
      <td style="text-align: left">94.05%</td>
      <td style="text-align: right">0.7699</td>
    </tr>
    <tr>
      <td style="text-align: right">9</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">94.00%</td>
      <td style="text-align: left">87.22%</td>
      <td style="text-align: left">86.98%</td>
      <td style="text-align: right">0.9418</td>
      <td style="text-align: left">86.44%</td>
      <td style="text-align: left">81.67%</td>
      <td style="text-align: left">93.96%</td>
      <td style="text-align: right">0.7372</td>
    </tr>
    <tr>
      <td style="text-align: right">10</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">89.60%</td>
      <td style="text-align: left">87.76%</td>
      <td style="text-align: left">87.50%</td>
      <td style="text-align: right">0.9382</td>
      <td style="text-align: left">85.78%</td>
      <td style="text-align: left">83.04%</td>
      <td style="text-align: left">89.94%</td>
      <td style="text-align: right">0.7181</td>
    </tr>
    <tr>
      <td style="text-align: right">11</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">94.20%</td>
      <td style="text-align: left">81.16%</td>
      <td style="text-align: left">81.28%</td>
      <td style="text-align: right">0.9628</td>
      <td style="text-align: left">89.63%</td>
      <td style="text-align: left">86.24%</td>
      <td style="text-align: left">94.31%</td>
      <td style="text-align: right">0.7961</td>
    </tr>
    <tr>
      <td style="text-align: right">12</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">92.10%</td>
      <td style="text-align: left">80.86%</td>
      <td style="text-align: left">81.62%</td>
      <td style="text-align: right">0.9558</td>
      <td style="text-align: left">88.76%</td>
      <td style="text-align: left">86.19%</td>
      <td style="text-align: left">92.30%</td>
      <td style="text-align: right">0.7771</td>
    </tr>
    <tr>
      <td style="text-align: right">13</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">93.90%</td>
      <td style="text-align: left">79.78%</td>
      <td style="text-align: left">80.28%</td>
      <td style="text-align: right">0.9589</td>
      <td style="text-align: left">89.55%</td>
      <td style="text-align: left">86.33%</td>
      <td style="text-align: left">93.96%</td>
      <td style="text-align: right">0.794</td>
    </tr>
    <tr>
      <td style="text-align: right">14</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">95.70%</td>
      <td style="text-align: left">79.52%</td>
      <td style="text-align: left">80.40%</td>
      <td style="text-align: right">0.9608</td>
      <td style="text-align: left">88.93%</td>
      <td style="text-align: left">84.34%</td>
      <td style="text-align: left">95.63%</td>
      <td style="text-align: right">0.7857</td>
    </tr>
    <tr>
      <td style="text-align: right">15</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">93.90%</td>
      <td style="text-align: left">74.52%</td>
      <td style="text-align: left">75.92%</td>
      <td style="text-align: right">0.9623</td>
      <td style="text-align: left">90.33%</td>
      <td style="text-align: left">87.60%</td>
      <td style="text-align: left">93.96%</td>
      <td style="text-align: right">0.8088</td>
    </tr>
    <tr>
      <td style="text-align: right">16</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">99.40%</td>
      <td style="text-align: left">94.82%</td>
      <td style="text-align: left">94.78%</td>
      <td style="text-align: right">0.951</td>
      <td style="text-align: left">69.90%</td>
      <td style="text-align: left">62.52%</td>
      <td style="text-align: left">99.39%</td>
      <td style="text-align: right">0.4929</td>
    </tr>
    <tr>
      <td style="text-align: right">17</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">91.90%</td>
      <td style="text-align: left">73.68%</td>
      <td style="text-align: left">74.92%</td>
      <td style="text-align: right">0.9551</td>
      <td style="text-align: left">90.42%</td>
      <td style="text-align: left">89.15%</td>
      <td style="text-align: left">92.04%</td>
      <td style="text-align: right">0.8088</td>
    </tr>
    <tr>
      <td style="text-align: right">18</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">93.40%</td>
      <td style="text-align: left">69.80%</td>
      <td style="text-align: left">72.68%</td>
      <td style="text-align: right">0.973</td>
      <td style="text-align: left">92.48%</td>
      <td style="text-align: left">91.75%</td>
      <td style="text-align: left">93.35%</td>
      <td style="text-align: right">0.8496</td>
    </tr>
    <tr>
      <td style="text-align: right">19</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">99.50%</td>
      <td style="text-align: left">91.82%</td>
      <td style="text-align: left">91.88%</td>
      <td style="text-align: right">0.9472</td>
      <td style="text-align: left">70.03%</td>
      <td style="text-align: left">62.62%</td>
      <td style="text-align: left">99.39%</td>
      <td style="text-align: right">0.495</td>
    </tr>
    <tr>
      <td style="text-align: right">20</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">92.00%</td>
      <td style="text-align: left">68.56%</td>
      <td style="text-align: left">70.68%</td>
      <td style="text-align: right">0.9673</td>
      <td style="text-align: left">91.78%</td>
      <td style="text-align: left">91.49%</td>
      <td style="text-align: left">92.13%</td>
      <td style="text-align: right">0.8355</td>
    </tr>
    <tr>
      <td style="text-align: right">21</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">92.20%</td>
      <td style="text-align: left">69.26%</td>
      <td style="text-align: left">77.04%</td>
      <td style="text-align: right">0.9673</td>
      <td style="text-align: left">90.99%</td>
      <td style="text-align: left">89.80%</td>
      <td style="text-align: left">92.48%</td>
      <td style="text-align: right">0.8201</td>
    </tr>
    <tr>
      <td style="text-align: right">22</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">94.10%</td>
      <td style="text-align: left">68.78%</td>
      <td style="text-align: left">73.28%</td>
      <td style="text-align: right">0.9692</td>
      <td style="text-align: left">91.29%</td>
      <td style="text-align: left">89.20%</td>
      <td style="text-align: left">93.96%</td>
      <td style="text-align: right">0.8271</td>
    </tr>
    <tr>
      <td style="text-align: right">23</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">93.90%</td>
      <td style="text-align: left">66.10%</td>
      <td style="text-align: left">66.54%</td>
      <td style="text-align: right">0.9688</td>
      <td style="text-align: left">92.65%</td>
      <td style="text-align: left">91.63%</td>
      <td style="text-align: left">93.88%</td>
      <td style="text-align: right">0.8533</td>
    </tr>
    <tr>
      <td style="text-align: right">24</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">91.00%</td>
      <td style="text-align: left">66.92%</td>
      <td style="text-align: left">69.00%</td>
      <td style="text-align: right">0.9651</td>
      <td style="text-align: left">91.21%</td>
      <td style="text-align: left">91.32%</td>
      <td style="text-align: left">91.08%</td>
      <td style="text-align: right">0.8242</td>
    </tr>
    <tr>
      <td style="text-align: right">25</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">93.00%</td>
      <td style="text-align: left">66.00%</td>
      <td style="text-align: left">66.42%</td>
      <td style="text-align: right">0.9625</td>
      <td style="text-align: left">91.60%</td>
      <td style="text-align: left">90.33%</td>
      <td style="text-align: left">93.18%</td>
      <td style="text-align: right">0.8324</td>
    </tr>
    <tr>
      <td style="text-align: right">26</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">92.50%</td>
      <td style="text-align: left">65.54%</td>
      <td style="text-align: left">75.20%</td>
      <td style="text-align: right">0.97</td>
      <td style="text-align: left">91.29%</td>
      <td style="text-align: left">90.27%</td>
      <td style="text-align: left">92.56%</td>
      <td style="text-align: right">0.8262</td>
    </tr>
    <tr>
      <td style="text-align: right">27</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">99.80%</td>
      <td style="text-align: left">95.18%</td>
      <td style="text-align: left">95.34%</td>
      <td style="text-align: right">0.9462</td>
      <td style="text-align: left">61.24%</td>
      <td style="text-align: left">56.35%</td>
      <td style="text-align: left">99.74%</td>
      <td style="text-align: right">0.3523</td>
    </tr>
    <tr>
      <td style="text-align: right">28</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">89.70%</td>
      <td style="text-align: left">64.98%</td>
      <td style="text-align: left">70.52%</td>
      <td style="text-align: right">0.966</td>
      <td style="text-align: left">90.99%</td>
      <td style="text-align: left">91.87%</td>
      <td style="text-align: left">89.94%</td>
      <td style="text-align: right">0.82</td>
    </tr>
    <tr>
      <td style="text-align: right">29</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">88.70%</td>
      <td style="text-align: left">64.54%</td>
      <td style="text-align: left">65.16%</td>
      <td style="text-align: right">0.96</td>
      <td style="text-align: left">90.64%</td>
      <td style="text-align: left">92.27%</td>
      <td style="text-align: left">88.71%</td>
      <td style="text-align: right">0.8134</td>
    </tr>
    <tr>
      <td style="text-align: right">30</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">93.80%</td>
      <td style="text-align: left">62.46%</td>
      <td style="text-align: left">62.78%</td>
      <td style="text-align: right">0.9727</td>
      <td style="text-align: left">92.52%</td>
      <td style="text-align: left">91.40%</td>
      <td style="text-align: left">93.88%</td>
      <td style="text-align: right">0.8507</td>
    </tr>
    <tr>
      <td style="text-align: right">31</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">89.90%</td>
      <td style="text-align: left">63.60%</td>
      <td style="text-align: left">71.08%</td>
      <td style="text-align: right">0.9643</td>
      <td style="text-align: left">90.81%</td>
      <td style="text-align: left">91.54%</td>
      <td style="text-align: left">89.94%</td>
      <td style="text-align: right">0.8164</td>
    </tr>
    <tr>
      <td style="text-align: right">32</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">94.30%</td>
      <td style="text-align: left">60.78%</td>
      <td style="text-align: left">60.86%</td>
      <td style="text-align: right">0.9769</td>
      <td style="text-align: left">93.31%</td>
      <td style="text-align: left">92.38%</td>
      <td style="text-align: left">94.40%</td>
      <td style="text-align: right">0.8663</td>
    </tr>
    <tr>
      <td style="text-align: right">33</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">93.40%</td>
      <td style="text-align: left">61.20%</td>
      <td style="text-align: left">61.54%</td>
      <td style="text-align: right">0.9692</td>
      <td style="text-align: left">92.48%</td>
      <td style="text-align: left">91.67%</td>
      <td style="text-align: left">93.44%</td>
      <td style="text-align: right">0.8497</td>
    </tr>
    <tr>
      <td style="text-align: right">34</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">84.80%</td>
      <td style="text-align: left">66.54%</td>
      <td style="text-align: left">66.64%</td>
      <td style="text-align: right">0.9387</td>
      <td style="text-align: left">86.79%</td>
      <td style="text-align: left">87.99%</td>
      <td style="text-align: left">85.21%</td>
      <td style="text-align: right">0.7361</td>
    </tr>
    <tr>
      <td style="text-align: right">35</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">94.10%</td>
      <td style="text-align: left">59.80%</td>
      <td style="text-align: left">60.22%</td>
      <td style="text-align: right">0.9762</td>
      <td style="text-align: left">92.74%</td>
      <td style="text-align: left">91.65%</td>
      <td style="text-align: left">94.05%</td>
      <td style="text-align: right">0.8551</td>
    </tr>
    <tr>
      <td style="text-align: right">36</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">93.30%</td>
      <td style="text-align: left">57.98%</td>
      <td style="text-align: left">59.60%</td>
      <td style="text-align: right">0.9729</td>
      <td style="text-align: left">91.95%</td>
      <td style="text-align: left">90.81%</td>
      <td style="text-align: left">93.35%</td>
      <td style="text-align: right">0.8393</td>
    </tr>
    <tr>
      <td style="text-align: right">37</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">93.90%</td>
      <td style="text-align: left">56.72%</td>
      <td style="text-align: left">57.80%</td>
      <td style="text-align: right">0.9743</td>
      <td style="text-align: left">93.09%</td>
      <td style="text-align: left">92.27%</td>
      <td style="text-align: left">94.05%</td>
      <td style="text-align: right">0.8619</td>
    </tr>
    <tr>
      <td style="text-align: right">38</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">95.20%</td>
      <td style="text-align: left">56.20%</td>
      <td style="text-align: left">56.62%</td>
      <td style="text-align: right">0.9768</td>
      <td style="text-align: left">93.31%</td>
      <td style="text-align: left">91.67%</td>
      <td style="text-align: left">95.28%</td>
      <td style="text-align: right">0.8668</td>
    </tr>
    <tr>
      <td style="text-align: right">39</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">92.70%</td>
      <td style="text-align: left">56.94%</td>
      <td style="text-align: left">58.02%</td>
      <td style="text-align: right">0.97</td>
      <td style="text-align: left">92.13%</td>
      <td style="text-align: left">91.62%</td>
      <td style="text-align: left">92.74%</td>
      <td style="text-align: right">0.8426</td>
    </tr>
    <tr>
      <td style="text-align: right">40</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">91.30%</td>
      <td style="text-align: left">55.46%</td>
      <td style="text-align: left">55.68%</td>
      <td style="text-align: right">0.9714</td>
      <td style="text-align: left">92.48%</td>
      <td style="text-align: left">93.31%</td>
      <td style="text-align: left">91.51%</td>
      <td style="text-align: right">0.8497</td>
    </tr>
    <tr>
      <td style="text-align: right">41</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">93.30%</td>
      <td style="text-align: left">54.70%</td>
      <td style="text-align: left">55.24%</td>
      <td style="text-align: right">0.9764</td>
      <td style="text-align: left">92.74%</td>
      <td style="text-align: left">92.29%</td>
      <td style="text-align: left">93.26%</td>
      <td style="text-align: right">0.8548</td>
    </tr>
    <tr>
      <td style="text-align: right">42</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">92.70%</td>
      <td style="text-align: left">54.76%</td>
      <td style="text-align: left">91.00%</td>
      <td style="text-align: right">0.9678</td>
      <td style="text-align: left">91.56%</td>
      <td style="text-align: left">90.60%</td>
      <td style="text-align: left">92.74%</td>
      <td style="text-align: right">0.8314</td>
    </tr>
    <tr>
      <td style="text-align: right">43</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">91.70%</td>
      <td style="text-align: left">54.14%</td>
      <td style="text-align: left">55.44%</td>
      <td style="text-align: right">0.9645</td>
      <td style="text-align: left">91.51%</td>
      <td style="text-align: left">91.30%</td>
      <td style="text-align: left">91.78%</td>
      <td style="text-align: right">0.8303</td>
    </tr>
    <tr>
      <td style="text-align: right">44</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">92.20%</td>
      <td style="text-align: left">51.86%</td>
      <td style="text-align: left">90.54%</td>
      <td style="text-align: right">0.9685</td>
      <td style="text-align: left">91.73%</td>
      <td style="text-align: left">91.26%</td>
      <td style="text-align: left">92.30%</td>
      <td style="text-align: right">0.8347</td>
    </tr>
    <tr>
      <td style="text-align: right">45</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">92.50%</td>
      <td style="text-align: left">49.54%</td>
      <td style="text-align: left">53.26%</td>
      <td style="text-align: right">0.9736</td>
      <td style="text-align: left">92.78%</td>
      <td style="text-align: left">92.89%</td>
      <td style="text-align: left">92.65%</td>
      <td style="text-align: right">0.8556</td>
    </tr>
    <tr>
      <td style="text-align: right">46</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">92.50%</td>
      <td style="text-align: left">46.66%</td>
      <td style="text-align: left">91.34%</td>
      <td style="text-align: right">0.9706</td>
      <td style="text-align: left">92.21%</td>
      <td style="text-align: left">92.07%</td>
      <td style="text-align: left">92.39%</td>
      <td style="text-align: right">0.8443</td>
    </tr>
    <tr>
      <td style="text-align: right">47</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">87.60%</td>
      <td style="text-align: left">46.86%</td>
      <td style="text-align: left">57.52%</td>
      <td style="text-align: right">0.9677</td>
      <td style="text-align: left">90.77%</td>
      <td style="text-align: left">93.31%</td>
      <td style="text-align: left">87.84%</td>
      <td style="text-align: right">0.8168</td>
    </tr>
    <tr>
      <td style="text-align: right">48</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">90.90%</td>
      <td style="text-align: left">44.36%</td>
      <td style="text-align: left">88.58%</td>
      <td style="text-align: right">0.9685</td>
      <td style="text-align: left">91.38%</td>
      <td style="text-align: left">91.93%</td>
      <td style="text-align: left">90.73%</td>
      <td style="text-align: right">0.8277</td>
    </tr>
    <tr>
      <td style="text-align: right">49</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">89.30%</td>
      <td style="text-align: left">44.50%</td>
      <td style="text-align: left">85.70%</td>
      <td style="text-align: right">0.9598</td>
      <td style="text-align: left">90.03%</td>
      <td style="text-align: left">90.81%</td>
      <td style="text-align: left">89.06%</td>
      <td style="text-align: right">0.8007</td>
    </tr>
    <tr>
      <td style="text-align: right">50</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">87.50%</td>
      <td style="text-align: left">42.98%</td>
      <td style="text-align: left">75.04%</td>
      <td style="text-align: right">0.9626</td>
      <td style="text-align: left">90.46%</td>
      <td style="text-align: left">93.02%</td>
      <td style="text-align: left">87.49%</td>
      <td style="text-align: right">0.8107</td>
    </tr>
    <tr>
      <td style="text-align: right">51</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">89.80%</td>
      <td style="text-align: left">40.90%</td>
      <td style="text-align: left">42.08%</td>
      <td style="text-align: right">0.9669</td>
      <td style="text-align: left">91.91%</td>
      <td style="text-align: left">93.55%</td>
      <td style="text-align: left">90.03%</td>
      <td style="text-align: right">0.8387</td>
    </tr>
    <tr>
      <td style="text-align: right">52</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">85.00%</td>
      <td style="text-align: left">40.30%</td>
      <td style="text-align: left">40.36%</td>
      <td style="text-align: right">0.9563</td>
      <td style="text-align: left">89.98%</td>
      <td style="text-align: left">93.69%</td>
      <td style="text-align: left">85.74%</td>
      <td style="text-align: right">0.8025</td>
    </tr>
    <tr>
      <td style="text-align: right">53</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">75.50%</td>
      <td style="text-align: left">42.66%</td>
      <td style="text-align: left">42.24%</td>
      <td style="text-align: right">0.9543</td>
      <td style="text-align: left">84.21%</td>
      <td style="text-align: left">90.90%</td>
      <td style="text-align: left">76.03%</td>
      <td style="text-align: right">0.6935</td>
    </tr>
    <tr>
      <td style="text-align: right">54</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">79.40%</td>
      <td style="text-align: left">39.74%</td>
      <td style="text-align: left">44.36%</td>
      <td style="text-align: right">0.9596</td>
      <td style="text-align: left">86.70%</td>
      <td style="text-align: left">92.42%</td>
      <td style="text-align: left">79.97%</td>
      <td style="text-align: right">0.7408</td>
    </tr>
    <tr>
      <td style="text-align: right">55</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">94.20%</td>
      <td style="text-align: left">25.28%</td>
      <td style="text-align: left">87.98%</td>
      <td style="text-align: right">0.9761</td>
      <td style="text-align: left">93.31%</td>
      <td style="text-align: left">92.67%</td>
      <td style="text-align: left">94.05%</td>
      <td style="text-align: right">0.8662</td>
    </tr>
    <tr>
      <td style="text-align: right">56</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">94.20%</td>
      <td style="text-align: left">21.94%</td>
      <td style="text-align: left">85.50%</td>
      <td style="text-align: right">0.9803</td>
      <td style="text-align: left">93.92%</td>
      <td style="text-align: left">93.80%</td>
      <td style="text-align: left">94.05%</td>
      <td style="text-align: right">0.8784</td>
    </tr>
    <tr>
      <td style="text-align: right">57</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">93.50%</td>
      <td style="text-align: left">21.44%</td>
      <td style="text-align: left">91.12%</td>
      <td style="text-align: right">0.9824</td>
      <td style="text-align: left">94.01%</td>
      <td style="text-align: left">94.51%</td>
      <td style="text-align: left">93.44%</td>
      <td style="text-align: right">0.8802</td>
    </tr>
    <tr>
      <td style="text-align: right">58</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">93.60%</td>
      <td style="text-align: left">20.02%</td>
      <td style="text-align: left">88.68%</td>
      <td style="text-align: right">0.9804</td>
      <td style="text-align: left">93.44%</td>
      <td style="text-align: left">93.44%</td>
      <td style="text-align: left">93.44%</td>
      <td style="text-align: right">0.8688</td>
    </tr>
    <tr>
      <td style="text-align: right">59</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">95.20%</td>
      <td style="text-align: left">16.84%</td>
      <td style="text-align: left">90.10%</td>
      <td style="text-align: right">0.9783</td>
      <td style="text-align: left">93.66%</td>
      <td style="text-align: left">92.50%</td>
      <td style="text-align: left">95.01%</td>
      <td style="text-align: right">0.8735</td>
    </tr>
    <tr>
      <td style="text-align: right">60</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">93.40%</td>
      <td style="text-align: left">11.04%</td>
      <td style="text-align: left">29.86%</td>
      <td style="text-align: right">0.9862</td>
      <td style="text-align: left">94.58%</td>
      <td style="text-align: left">95.37%</td>
      <td style="text-align: left">93.70%</td>
      <td style="text-align: right">0.8917</td>
    </tr>
    <tr>
      <td style="text-align: right">61</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">94.40%</td>
      <td style="text-align: left">10.84%</td>
      <td style="text-align: left">90.14%</td>
      <td style="text-align: right">0.9843</td>
      <td style="text-align: left">94.53%</td>
      <td style="text-align: left">94.49%</td>
      <td style="text-align: left">94.58%</td>
      <td style="text-align: right">0.8906</td>
    </tr>
    <tr>
      <td style="text-align: right">62</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">94.10%</td>
      <td style="text-align: left">8.62%</td>
      <td style="text-align: left">92.56%</td>
      <td style="text-align: right">0.9834</td>
      <td style="text-align: left">94.36%</td>
      <td style="text-align: left">94.47%</td>
      <td style="text-align: left">94.23%</td>
      <td style="text-align: right">0.8871</td>
    </tr>
    <tr>
      <td style="text-align: right">63</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">93.60%</td>
      <td style="text-align: left">8.92%</td>
      <td style="text-align: left">82.50%</td>
      <td style="text-align: right">0.9809</td>
      <td style="text-align: left">94.01%</td>
      <td style="text-align: left">94.28%</td>
      <td style="text-align: left">93.70%</td>
      <td style="text-align: right">0.8802</td>
    </tr>
    <tr>
      <td style="text-align: right">64</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">94.20%</td>
      <td style="text-align: left">8.14%</td>
      <td style="text-align: left">91.24%</td>
      <td style="text-align: right">0.9825</td>
      <td style="text-align: left">94.14%</td>
      <td style="text-align: left">93.91%</td>
      <td style="text-align: left">94.40%</td>
      <td style="text-align: right">0.8828</td>
    </tr>
    <tr>
      <td style="text-align: right">65</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">93.00%</td>
      <td style="text-align: left">4.90%</td>
      <td style="text-align: left">5.10%</td>
      <td style="text-align: right">0.9737</td>
      <td style="text-align: left">93.09%</td>
      <td style="text-align: left">93.16%</td>
      <td style="text-align: left">93.00%</td>
      <td style="text-align: right">0.8618</td>
    </tr>
    <tr>
      <td style="text-align: right">66</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">93.60%</td>
      <td style="text-align: left">3.88%</td>
      <td style="text-align: left">3.88%</td>
      <td style="text-align: right">0.9776</td>
      <td style="text-align: left">93.83%</td>
      <td style="text-align: left">93.72%</td>
      <td style="text-align: left">93.96%</td>
      <td style="text-align: right">0.8766</td>
    </tr>
    <tr>
      <td style="text-align: right">67</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">91.00%</td>
      <td style="text-align: left">3.90%</td>
      <td style="text-align: left">3.90%</td>
      <td style="text-align: right">0.9802</td>
      <td style="text-align: left">93.35%</td>
      <td style="text-align: left">95.25%</td>
      <td style="text-align: left">91.25%</td>
      <td style="text-align: right">0.8678</td>
    </tr>
    <tr>
      <td style="text-align: right">68</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">90.40%</td>
      <td style="text-align: left">1.82%</td>
      <td style="text-align: left">68.70%</td>
      <td style="text-align: right">0.9675</td>
      <td style="text-align: left">93.04%</td>
      <td style="text-align: left">95.39%</td>
      <td style="text-align: left">90.46%</td>
      <td style="text-align: right">0.862</td>
    </tr>
    <tr>
      <td style="text-align: right">69</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">89.90%</td>
      <td style="text-align: left">2.00%</td>
      <td style="text-align: left">2.00%</td>
      <td style="text-align: right">0.9754</td>
      <td style="text-align: left">92.83%</td>
      <td style="text-align: left">95.45%</td>
      <td style="text-align: left">89.94%</td>
      <td style="text-align: right">0.8579</td>
    </tr>
    <tr>
      <td style="text-align: right">70</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">0.80%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0.9291</td>
      <td style="text-align: left">50.39%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">0.79%</td>
      <td style="text-align: right">0.0629</td>
    </tr>
  </tbody>
</table>

<h3 id="wids">WIDS</h3>

<p><a href="#">^ back to top</a></p>

<table>
  <thead>
    <tr>
      <th style="text-align: right">Rank</th>
      <th style="text-align: left">Architecture</th>
      <th style="text-align: left">Training</th>
      <th style="text-align: left">Augmentation</th>
      <th style="text-align: left">ID</th>
      <th style="text-align: left">ADV+CTR</th>
      <th style="text-align: left">ADV</th>
      <th style="text-align: right">AUC</th>
      <th style="text-align: left">Accuracy</th>
      <th style="text-align: left">Precision</th>
      <th style="text-align: left">Recall</th>
      <th style="text-align: right">MCC</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right">1</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">78.28%</td>
      <td style="text-align: left">69.14%</td>
      <td style="text-align: left">77.44%</td>
      <td style="text-align: right">0.8575</td>
      <td style="text-align: left">77.70%</td>
      <td style="text-align: left">25.64%</td>
      <td style="text-align: left">78.21%</td>
      <td style="text-align: right">0.3581</td>
    </tr>
    <tr>
      <td style="text-align: right">2</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">77.47%</td>
      <td style="text-align: left">71.05%</td>
      <td style="text-align: left">77.21%</td>
      <td style="text-align: right">0.8543</td>
      <td style="text-align: left">75.65%</td>
      <td style="text-align: left">23.72%</td>
      <td style="text-align: left">77.40%</td>
      <td style="text-align: right">0.3321</td>
    </tr>
    <tr>
      <td style="text-align: right">3</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">76.50%</td>
      <td style="text-align: left">67.52%</td>
      <td style="text-align: left">75.49%</td>
      <td style="text-align: right">0.8534</td>
      <td style="text-align: left">78.42%</td>
      <td style="text-align: left">26.05%</td>
      <td style="text-align: left">76.44%</td>
      <td style="text-align: right">0.3573</td>
    </tr>
    <tr>
      <td style="text-align: right">4</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">74.72%</td>
      <td style="text-align: left">66.71%</td>
      <td style="text-align: left">74.30%</td>
      <td style="text-align: right">0.8578</td>
      <td style="text-align: left">79.04%</td>
      <td style="text-align: left">26.39%</td>
      <td style="text-align: left">74.68%</td>
      <td style="text-align: right">0.3555</td>
    </tr>
    <tr>
      <td style="text-align: right">5</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">76.01%</td>
      <td style="text-align: left">66.06%</td>
      <td style="text-align: left">75.43%</td>
      <td style="text-align: right">0.8605</td>
      <td style="text-align: left">79.69%</td>
      <td style="text-align: left">27.29%</td>
      <td style="text-align: left">75.96%</td>
      <td style="text-align: right">0.3698</td>
    </tr>
    <tr>
      <td style="text-align: right">6</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">77.96%</td>
      <td style="text-align: left">66.61%</td>
      <td style="text-align: left">77.31%</td>
      <td style="text-align: right">0.8667</td>
      <td style="text-align: left">78.90%</td>
      <td style="text-align: left">26.76%</td>
      <td style="text-align: left">77.88%</td>
      <td style="text-align: right">0.3701</td>
    </tr>
    <tr>
      <td style="text-align: right">7</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">78.12%</td>
      <td style="text-align: left">68.07%</td>
      <td style="text-align: left">77.63%</td>
      <td style="text-align: right">0.8592</td>
      <td style="text-align: left">76.90%</td>
      <td style="text-align: left">24.91%</td>
      <td style="text-align: left">78.21%</td>
      <td style="text-align: right">0.3493</td>
    </tr>
    <tr>
      <td style="text-align: right">8</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">77.63%</td>
      <td style="text-align: left">67.62%</td>
      <td style="text-align: left">77.60%</td>
      <td style="text-align: right">0.8583</td>
      <td style="text-align: left">77.00%</td>
      <td style="text-align: left">24.90%</td>
      <td style="text-align: left">77.56%</td>
      <td style="text-align: right">0.3471</td>
    </tr>
    <tr>
      <td style="text-align: right">9</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">77.31%</td>
      <td style="text-align: left">65.06%</td>
      <td style="text-align: left">76.66%</td>
      <td style="text-align: right">0.8694</td>
      <td style="text-align: left">79.44%</td>
      <td style="text-align: left">27.23%</td>
      <td style="text-align: left">77.24%</td>
      <td style="text-align: right">0.3733</td>
    </tr>
    <tr>
      <td style="text-align: right">10</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">76.50%</td>
      <td style="text-align: left">65.19%</td>
      <td style="text-align: left">75.88%</td>
      <td style="text-align: right">0.8638</td>
      <td style="text-align: left">78.75%</td>
      <td style="text-align: left">26.38%</td>
      <td style="text-align: left">76.44%</td>
      <td style="text-align: right">0.3611</td>
    </tr>
    <tr>
      <td style="text-align: right">11</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">68.07%</td>
      <td style="text-align: left">59.87%</td>
      <td style="text-align: left">67.52%</td>
      <td style="text-align: right">0.8586</td>
      <td style="text-align: left">83.37%</td>
      <td style="text-align: left">30.73%</td>
      <td style="text-align: left">68.11%</td>
      <td style="text-align: right">0.3793</td>
    </tr>
    <tr>
      <td style="text-align: right">12</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">72.61%</td>
      <td style="text-align: left">62.20%</td>
      <td style="text-align: left">72.41%</td>
      <td style="text-align: right">0.8576</td>
      <td style="text-align: left">80.58%</td>
      <td style="text-align: left">27.71%</td>
      <td style="text-align: left">72.44%</td>
      <td style="text-align: right">0.363</td>
    </tr>
    <tr>
      <td style="text-align: right">13</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">77.63%</td>
      <td style="text-align: left">63.79%</td>
      <td style="text-align: left">77.31%</td>
      <td style="text-align: right">0.8658</td>
      <td style="text-align: left">78.23%</td>
      <td style="text-align: left">26.05%</td>
      <td style="text-align: left">77.56%</td>
      <td style="text-align: right">0.3608</td>
    </tr>
    <tr>
      <td style="text-align: right">14</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">85.25%</td>
      <td style="text-align: left">73.78%</td>
      <td style="text-align: left">85.25%</td>
      <td style="text-align: right">0.8412</td>
      <td style="text-align: left">66.79%</td>
      <td style="text-align: left">19.32%</td>
      <td style="text-align: left">85.10%</td>
      <td style="text-align: right">0.2928</td>
    </tr>
    <tr>
      <td style="text-align: right">15</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">67.75%</td>
      <td style="text-align: left">59.81%</td>
      <td style="text-align: left">67.68%</td>
      <td style="text-align: right">0.8451</td>
      <td style="text-align: left">80.74%</td>
      <td style="text-align: left">27.08%</td>
      <td style="text-align: left">67.79%</td>
      <td style="text-align: right">0.341</td>
    </tr>
    <tr>
      <td style="text-align: right">16</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">72.12%</td>
      <td style="text-align: left">61.78%</td>
      <td style="text-align: left">72.12%</td>
      <td style="text-align: right">0.8461</td>
      <td style="text-align: left">78.74%</td>
      <td style="text-align: left">25.64%</td>
      <td style="text-align: left">72.12%</td>
      <td style="text-align: right">0.3389</td>
    </tr>
    <tr>
      <td style="text-align: right">17</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">77.47%</td>
      <td style="text-align: left">60.94%</td>
      <td style="text-align: left">77.15%</td>
      <td style="text-align: right">0.8695</td>
      <td style="text-align: left">79.56%</td>
      <td style="text-align: left">27.38%</td>
      <td style="text-align: left">77.40%</td>
      <td style="text-align: right">0.3755</td>
    </tr>
    <tr>
      <td style="text-align: right">18</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">75.85%</td>
      <td style="text-align: left">62.11%</td>
      <td style="text-align: left">75.53%</td>
      <td style="text-align: right">0.8573</td>
      <td style="text-align: left">77.60%</td>
      <td style="text-align: left">25.16%</td>
      <td style="text-align: left">75.80%</td>
      <td style="text-align: right">0.3448</td>
    </tr>
    <tr>
      <td style="text-align: right">19</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">80.23%</td>
      <td style="text-align: left">62.11%</td>
      <td style="text-align: left">79.58%</td>
      <td style="text-align: right">0.8676</td>
      <td style="text-align: left">77.59%</td>
      <td style="text-align: left">25.86%</td>
      <td style="text-align: left">80.29%</td>
      <td style="text-align: right">0.3673</td>
    </tr>
    <tr>
      <td style="text-align: right">20</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">71.47%</td>
      <td style="text-align: left">60.62%</td>
      <td style="text-align: left">71.47%</td>
      <td style="text-align: right">0.8451</td>
      <td style="text-align: left">79.07%</td>
      <td style="text-align: left">25.87%</td>
      <td style="text-align: left">71.47%</td>
      <td style="text-align: right">0.3395</td>
    </tr>
    <tr>
      <td style="text-align: right">21</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">68.88%</td>
      <td style="text-align: left">56.60%</td>
      <td style="text-align: left">68.85%</td>
      <td style="text-align: right">0.8531</td>
      <td style="text-align: left">82.94%</td>
      <td style="text-align: left">30.19%</td>
      <td style="text-align: left">68.75%</td>
      <td style="text-align: right">0.3762</td>
    </tr>
    <tr>
      <td style="text-align: right">22</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">70.18%</td>
      <td style="text-align: left">59.19%</td>
      <td style="text-align: left">69.89%</td>
      <td style="text-align: right">0.8403</td>
      <td style="text-align: left">80.18%</td>
      <td style="text-align: left">26.83%</td>
      <td style="text-align: left">70.03%</td>
      <td style="text-align: right">0.3455</td>
    </tr>
    <tr>
      <td style="text-align: right">23</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">76.99%</td>
      <td style="text-align: left">58.70%</td>
      <td style="text-align: left">76.66%</td>
      <td style="text-align: right">0.8698</td>
      <td style="text-align: left">80.16%</td>
      <td style="text-align: left">27.97%</td>
      <td style="text-align: left">76.92%</td>
      <td style="text-align: right">0.3805</td>
    </tr>
    <tr>
      <td style="text-align: right">24</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">78.77%</td>
      <td style="text-align: left">66.00%</td>
      <td style="text-align: left">78.77%</td>
      <td style="text-align: right">0.8368</td>
      <td style="text-align: left">72.70%</td>
      <td style="text-align: left">21.75%</td>
      <td style="text-align: left">78.69%</td>
      <td style="text-align: right">0.31</td>
    </tr>
    <tr>
      <td style="text-align: right">25</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">74.55%</td>
      <td style="text-align: left">58.35%</td>
      <td style="text-align: left">74.39%</td>
      <td style="text-align: right">0.8634</td>
      <td style="text-align: left">80.00%</td>
      <td style="text-align: left">27.37%</td>
      <td style="text-align: left">74.36%</td>
      <td style="text-align: right">0.3656</td>
    </tr>
    <tr>
      <td style="text-align: right">26</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">59.97%</td>
      <td style="text-align: left">50.76%</td>
      <td style="text-align: left">59.94%</td>
      <td style="text-align: right">0.8508</td>
      <td style="text-align: left">86.75%</td>
      <td style="text-align: left">35.78%</td>
      <td style="text-align: left">60.10%</td>
      <td style="text-align: right">0.3952</td>
    </tr>
    <tr>
      <td style="text-align: right">27</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">78.77%</td>
      <td style="text-align: left">58.93%</td>
      <td style="text-align: left">78.61%</td>
      <td style="text-align: right">0.8683</td>
      <td style="text-align: left">77.34%</td>
      <td style="text-align: left">25.36%</td>
      <td style="text-align: left">78.53%</td>
      <td style="text-align: right">0.3557</td>
    </tr>
    <tr>
      <td style="text-align: right">28</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">77.47%</td>
      <td style="text-align: left">57.37%</td>
      <td style="text-align: left">77.47%</td>
      <td style="text-align: right">0.8656</td>
      <td style="text-align: left">78.16%</td>
      <td style="text-align: left">25.95%</td>
      <td style="text-align: left">77.40%</td>
      <td style="text-align: right">0.3592</td>
    </tr>
    <tr>
      <td style="text-align: right">29</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">74.23%</td>
      <td style="text-align: left">57.24%</td>
      <td style="text-align: left">73.91%</td>
      <td style="text-align: right">0.8512</td>
      <td style="text-align: left">78.05%</td>
      <td style="text-align: left">25.31%</td>
      <td style="text-align: left">74.20%</td>
      <td style="text-align: right">0.3416</td>
    </tr>
    <tr>
      <td style="text-align: right">30</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">87.84%</td>
      <td style="text-align: left">71.22%</td>
      <td style="text-align: left">87.68%</td>
      <td style="text-align: right">0.852</td>
      <td style="text-align: left">63.83%</td>
      <td style="text-align: left">18.34%</td>
      <td style="text-align: left">87.82%</td>
      <td style="text-align: right">0.2845</td>
    </tr>
    <tr>
      <td style="text-align: right">31</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">67.75%</td>
      <td style="text-align: left">49.82%</td>
      <td style="text-align: left">67.10%</td>
      <td style="text-align: right">0.861</td>
      <td style="text-align: left">84.56%</td>
      <td style="text-align: left">32.61%</td>
      <td style="text-align: left">67.63%</td>
      <td style="text-align: right">0.3955</td>
    </tr>
    <tr>
      <td style="text-align: right">32</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">72.12%</td>
      <td style="text-align: left">52.09%</td>
      <td style="text-align: left">72.12%</td>
      <td style="text-align: right">0.8581</td>
      <td style="text-align: left">81.74%</td>
      <td style="text-align: left">29.08%</td>
      <td style="text-align: left">71.96%</td>
      <td style="text-align: right">0.3759</td>
    </tr>
    <tr>
      <td style="text-align: right">33</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">71.80%</td>
      <td style="text-align: left">50.15%</td>
      <td style="text-align: left">71.80%</td>
      <td style="text-align: right">0.8641</td>
      <td style="text-align: left">82.79%</td>
      <td style="text-align: left">30.47%</td>
      <td style="text-align: left">71.63%</td>
      <td style="text-align: right">0.389</td>
    </tr>
    <tr>
      <td style="text-align: right">34</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">62.56%</td>
      <td style="text-align: left">45.19%</td>
      <td style="text-align: left">62.56%</td>
      <td style="text-align: right">0.8645</td>
      <td style="text-align: left">87.54%</td>
      <td style="text-align: left">38.15%</td>
      <td style="text-align: left">62.66%</td>
      <td style="text-align: right">0.4244</td>
    </tr>
    <tr>
      <td style="text-align: right">35</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">72.29%</td>
      <td style="text-align: left">50.34%</td>
      <td style="text-align: left">71.31%</td>
      <td style="text-align: right">0.8652</td>
      <td style="text-align: left">82.29%</td>
      <td style="text-align: left">29.84%</td>
      <td style="text-align: left">72.12%</td>
      <td style="text-align: right">0.3842</td>
    </tr>
    <tr>
      <td style="text-align: right">36</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">77.31%</td>
      <td style="text-align: left">52.54%</td>
      <td style="text-align: left">75.04%</td>
      <td style="text-align: right">0.8638</td>
      <td style="text-align: left">79.74%</td>
      <td style="text-align: left">27.58%</td>
      <td style="text-align: left">77.40%</td>
      <td style="text-align: right">0.3778</td>
    </tr>
    <tr>
      <td style="text-align: right">37</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">62.56%</td>
      <td style="text-align: left">46.39%</td>
      <td style="text-align: left">62.33%</td>
      <td style="text-align: right">0.8548</td>
      <td style="text-align: left">85.48%</td>
      <td style="text-align: left">33.45%</td>
      <td style="text-align: left">62.50%</td>
      <td style="text-align: right">0.3844</td>
    </tr>
    <tr>
      <td style="text-align: right">38</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">72.61%</td>
      <td style="text-align: left">50.57%</td>
      <td style="text-align: left">72.61%</td>
      <td style="text-align: right">0.8582</td>
      <td style="text-align: left">80.84%</td>
      <td style="text-align: left">28.05%</td>
      <td style="text-align: left">72.60%</td>
      <td style="text-align: right">0.3671</td>
    </tr>
    <tr>
      <td style="text-align: right">39</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">54.30%</td>
      <td style="text-align: left">43.50%</td>
      <td style="text-align: left">53.52%</td>
      <td style="text-align: right">0.8486</td>
      <td style="text-align: left">87.75%</td>
      <td style="text-align: left">37.42%</td>
      <td style="text-align: left">54.33%</td>
      <td style="text-align: right">0.3852</td>
    </tr>
    <tr>
      <td style="text-align: right">40</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">69.85%</td>
      <td style="text-align: left">47.65%</td>
      <td style="text-align: left">69.37%</td>
      <td style="text-align: right">0.8572</td>
      <td style="text-align: left">83.30%</td>
      <td style="text-align: left">30.89%</td>
      <td style="text-align: left">69.71%</td>
      <td style="text-align: right">0.3865</td>
    </tr>
    <tr>
      <td style="text-align: right">41</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">75.53%</td>
      <td style="text-align: left">51.22%</td>
      <td style="text-align: left">75.36%</td>
      <td style="text-align: right">0.861</td>
      <td style="text-align: left">79.56%</td>
      <td style="text-align: left">27.04%</td>
      <td style="text-align: left">75.32%</td>
      <td style="text-align: right">0.365</td>
    </tr>
    <tr>
      <td style="text-align: right">42</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">55.27%</td>
      <td style="text-align: left">42.27%</td>
      <td style="text-align: left">55.27%</td>
      <td style="text-align: right">0.8528</td>
      <td style="text-align: left">88.15%</td>
      <td style="text-align: left">38.76%</td>
      <td style="text-align: left">55.29%</td>
      <td style="text-align: right">0.3994</td>
    </tr>
    <tr>
      <td style="text-align: right">43</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">70.18%</td>
      <td style="text-align: left">49.14%</td>
      <td style="text-align: left">69.69%</td>
      <td style="text-align: right">0.8492</td>
      <td style="text-align: left">81.15%</td>
      <td style="text-align: left">27.99%</td>
      <td style="text-align: left">70.03%</td>
      <td style="text-align: right">0.3581</td>
    </tr>
    <tr>
      <td style="text-align: right">44</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">77.63%</td>
      <td style="text-align: left">49.30%</td>
      <td style="text-align: left">76.27%</td>
      <td style="text-align: right">0.871</td>
      <td style="text-align: left">80.12%</td>
      <td style="text-align: left">28.03%</td>
      <td style="text-align: left">77.56%</td>
      <td style="text-align: right">0.3832</td>
    </tr>
    <tr>
      <td style="text-align: right">45</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">53.16%</td>
      <td style="text-align: left">41.17%</td>
      <td style="text-align: left">52.32%</td>
      <td style="text-align: right">0.8512</td>
      <td style="text-align: left">88.04%</td>
      <td style="text-align: left">38.05%</td>
      <td style="text-align: left">53.04%</td>
      <td style="text-align: right">0.3847</td>
    </tr>
    <tr>
      <td style="text-align: right">46</td>
      <td style="text-align: left">STG</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">56.73%</td>
      <td style="text-align: left">38.54%</td>
      <td style="text-align: left">55.92%</td>
      <td style="text-align: right">0.8626</td>
      <td style="text-align: left">88.47%</td>
      <td style="text-align: left">39.95%</td>
      <td style="text-align: left">56.73%</td>
      <td style="text-align: right">0.4142</td>
    </tr>
    <tr>
      <td style="text-align: right">47</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">70.99%</td>
      <td style="text-align: left">43.44%</td>
      <td style="text-align: left">70.50%</td>
      <td style="text-align: right">0.8662</td>
      <td style="text-align: left">83.51%</td>
      <td style="text-align: left">31.41%</td>
      <td style="text-align: left">70.83%</td>
      <td style="text-align: right">0.3955</td>
    </tr>
    <tr>
      <td style="text-align: right">48</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">75.53%</td>
      <td style="text-align: left">45.87%</td>
      <td style="text-align: left">74.55%</td>
      <td style="text-align: right">0.8738</td>
      <td style="text-align: left">80.97%</td>
      <td style="text-align: left">28.68%</td>
      <td style="text-align: left">75.48%</td>
      <td style="text-align: right">0.3835</td>
    </tr>
    <tr>
      <td style="text-align: right">49</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">76.17%</td>
      <td style="text-align: left">47.16%</td>
      <td style="text-align: left">75.85%</td>
      <td style="text-align: right">0.8623</td>
      <td style="text-align: left">78.80%</td>
      <td style="text-align: left">26.37%</td>
      <td style="text-align: left">76.12%</td>
      <td style="text-align: right">0.36</td>
    </tr>
    <tr>
      <td style="text-align: right">50</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">77.96%</td>
      <td style="text-align: left">44.05%</td>
      <td style="text-align: left">77.63%</td>
      <td style="text-align: right">0.8682</td>
      <td style="text-align: left">79.90%</td>
      <td style="text-align: left">27.86%</td>
      <td style="text-align: left">78.04%</td>
      <td style="text-align: right">0.383</td>
    </tr>
    <tr>
      <td style="text-align: right">51</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">78.61%</td>
      <td style="text-align: left">38.35%</td>
      <td style="text-align: left">73.26%</td>
      <td style="text-align: right">0.8726</td>
      <td style="text-align: left">80.46%</td>
      <td style="text-align: left">28.55%</td>
      <td style="text-align: left">78.37%</td>
      <td style="text-align: right">0.3916</td>
    </tr>
    <tr>
      <td style="text-align: right">52</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">75.04%</td>
      <td style="text-align: left">37.60%</td>
      <td style="text-align: left">75.04%</td>
      <td style="text-align: right">0.8688</td>
      <td style="text-align: left">80.78%</td>
      <td style="text-align: left">28.35%</td>
      <td style="text-align: left">74.84%</td>
      <td style="text-align: right">0.3778</td>
    </tr>
    <tr>
      <td style="text-align: right">53</td>
      <td style="text-align: left">TabTransformer</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">76.34%</td>
      <td style="text-align: left">37.63%</td>
      <td style="text-align: left">76.34%</td>
      <td style="text-align: right">0.8664</td>
      <td style="text-align: left">79.67%</td>
      <td style="text-align: left">27.32%</td>
      <td style="text-align: left">76.28%</td>
      <td style="text-align: right">0.3713</td>
    </tr>
    <tr>
      <td style="text-align: right">54</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.8618</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">55</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.4821</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">56</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">GOGGLE</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.8562</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">57</td>
      <td style="text-align: left">VIME</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.4816</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">58</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.8636</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">59</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.8599</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">60</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TableGAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.8643</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">61</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.8525</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">62</td>
      <td style="text-align: left">RLN</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.4246</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">63</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CT-GAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0.8627</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">64</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">99.16%</td>
      <td style="text-align: left">99.64%</td>
      <td style="text-align: right">0.8554</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">65</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0.8658</td>
      <td style="text-align: left">91.03%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: right">0</td>
    </tr>
    <tr>
      <td style="text-align: right">66</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">79.74%</td>
      <td style="text-align: left">5.28%</td>
      <td style="text-align: left">73.06%</td>
      <td style="text-align: right">0.8704</td>
      <td style="text-align: left">77.69%</td>
      <td style="text-align: left">25.86%</td>
      <td style="text-align: left">79.65%</td>
      <td style="text-align: right">0.3652</td>
    </tr>
    <tr>
      <td style="text-align: right">67</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">WGAN</td>
      <td style="text-align: left">78.61%</td>
      <td style="text-align: left">0.00%</td>
      <td style="text-align: left">45.58%</td>
      <td style="text-align: right">0.865</td>
      <td style="text-align: left">79.47%</td>
      <td style="text-align: left">27.49%</td>
      <td style="text-align: left">78.69%</td>
      <td style="text-align: right">0.3809</td>
    </tr>
    <tr>
      <td style="text-align: right">68</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">None</td>
      <td style="text-align: left">98.38%</td>
      <td style="text-align: left">58.38%</td>
      <td style="text-align: left">82.50%</td>
      <td style="text-align: right">0.8348</td>
      <td style="text-align: left">10.41%</td>
      <td style="text-align: left">8.98%</td>
      <td style="text-align: left">98.40%</td>
      <td style="text-align: right">0.003</td>
    </tr>
    <tr>
      <td style="text-align: right">69</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Std</td>
      <td style="text-align: left">TVAE</td>
      <td style="text-align: left">98.38%</td>
      <td style="text-align: left">40.62%</td>
      <td style="text-align: left">47.49%</td>
      <td style="text-align: right">0.8569</td>
      <td style="text-align: left">10.41%</td>
      <td style="text-align: left">8.98%</td>
      <td style="text-align: left">98.40%</td>
      <td style="text-align: right">0.003</td>
    </tr>
    <tr>
      <td style="text-align: right">70</td>
      <td style="text-align: left">TabNet</td>
      <td style="text-align: left">Adv</td>
      <td style="text-align: left">CutMix</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: left">37.44%</td>
      <td style="text-align: left">67.07%</td>
      <td style="text-align: right">0.8587</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">8.97%</td>
      <td style="text-align: left">100.00%</td>
      <td style="text-align: right">0</td>
    </tr>
  </tbody>
</table>

<script>
    var table = $('table').DataTable(
        {
            "bPaginate": false,
            "language": {
                searchPlaceholder: 'Architectures, training methods, etc.'
            },
            // "autoWidth": true,
        }
    );
    table.columns.adjust().draw();

    $(document).ready(function () {
        function updateFilterMargins() {
            $('.dataTables_wrapper').each(function () {
                var $wrapper = $(this);
                var $dataTable = $wrapper.find('.dataTable'); // Find the dataTable within the wrapper
                var $filter = $wrapper.find('.dataTables_filter'); // Find the filter within the wrapper
                if ($dataTable.length && $filter.length) {
                    // Get the computed right margin of the dataTable
                    var tableMarginRight = parseFloat($dataTable.css('margin-right')) || 0;
                    // Apply the same margin to the filter
                    $filter.css('margin-right', tableMarginRight);
                }
            });
        }

        // Update margins initially
        updateFilterMargins();

        // Listen for resize events on the window to update margins dynamically
        $(window).on('resize', function () {
            updateFilterMargins();
        });
    });
</script>



      
      <div class="footer border-top border-gray-light mt-5 pt-3 text-right text-gray">
        This site is open source. <a href="https://github.com/serval-uni-lu/tabularbench/edit/main/docs/index.md">Improve this page</a>.
      </div>
      
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  </body>
</html>
