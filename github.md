---
layout: page
title: Leaderboard
permalink: /board/
---


<h3>🌟 All leaderboards allow sorting via single-click on column headers.</h3>
<br>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 8px;
            text-align: center;
            border-bottom: 1px solid #ddd;
        }
        th {
            cursor: pointer;
            background-color: #f2f2f2;
        }
        th:hover {
            background-color: #ddd;
        }
        /* 新增合并单元格的样式 */
        .group-header {
            text-align: center;
            background-color: #e0e0e0;
        }
    </style>
</head>
<body>

<h3>Closed-Environment Rank v.s. Feature-Shift Rank</h3>

<table id="sortableTable2">
    <thead>
        <tr>
            <th onclick="sortTable2(0)">Model</th>
            <th onclick="sortTable2(1)">Closed-Environment Rank</th>
            <th onclick="sortTable2(2)">Feature-Shift Rank</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>LightGBM</td><td>4</td><td>12</td></tr>
<tr><td>XGBoost</td><td>3</td><td>17</td></tr>
<tr><td>CatBoost</td><td>2</td><td>3</td></tr>
<tr><td>TabPFN</td><td>9</td><td>13</td></tr>
<tr><td>TabPFNv2</td><td>5</td><td>5</td></tr>
<tr><td>DANets</td><td>21</td><td>21</td></tr>
<tr><td>MLP</td><td>13</td><td>7</td></tr>
<tr><td>NODE</td><td>23</td><td>22</td></tr>
<tr><td>ResNet</td><td>10</td><td>8</td></tr>
<tr><td>SwitchTab</td><td>17</td><td>16</td></tr>
<tr><td>TabCaps</td><td>18</td><td>11</td></tr>
<tr><td>TabNet</td><td>22</td><td>23</td></tr>
<tr><td>TANGOS</td><td>11</td><td>4</td></tr>
<tr><td>AutoInt</td><td>20</td><td>20</td></tr>
<tr><td>DCNv2</td><td>12</td><td>6</td></tr>
<tr><td>FT-Transformer</td><td>16</td><td>18</td></tr>
<tr><td>GrowNet</td><td>24</td><td>25</td></tr>
<tr><td>Saint</td><td>15</td><td>14</td></tr>
<tr><td>SNN</td><td>19</td><td>19</td></tr>
<tr><td>TabTransformer</td><td>25</td><td>24</td></tr>
<tr><td>TabR</td><td>7</td><td>9</td></tr>
<tr><td>ModernNCA</td><td>1</td><td>15</td></tr>
<tr><td>Llama3-8B</td><td>14</td><td>10</td></tr>
<tr><td>TabLLM</td><td>6</td><td>2</td></tr>
<tr><td>UniPredict</td><td>8</td><td>1</td></tr>
    </tbody>
</table>
<br>

<h3>Feature-Shift Performance Gap</h3>

<table id="sortableTable1">
    <thead>
        <!-- 新增合并行 -->
        <tr>
          <th colspan="1" class="group-header">Shift</th>
            <th colspan="5" class="group-header">Binary Classification</th>
          <th colspan="5" class="group-header">Multi Classification</th>
          <th colspan="5" class="group-header">Regression</th>
        </tr>
        <!-- 原有表头行 -->
        <tr>
            <th onclick="sortTable1(0)">Model</th>
            <th onclick="sortTable1(1)">20%</th>
            <th onclick="sortTable1(2)">40%</th>
          <th onclick="sortTable1(3)">60%</th>
            <th onclick="sortTable1(4)">80%</th>
            <th onclick="sortTable1(5)">100%</th>
                      <th onclick="sortTable1(6)">20%</th>
            <th onclick="sortTable1(7)">40%</th>
          <th onclick="sortTable1(8)">60%</th>
            <th onclick="sortTable1(9)">80%</th>
            <th onclick="sortTable1(10)">100%</th>
                      <th onclick="sortTable1(11)">20%</th>
            <th onclick="sortTable1(12)">40%</th>
          <th onclick="sortTable1(13)">60%</th>
            <th onclick="sortTable1(14)">80%</th>
            <th onclick="sortTable1(15)">100%</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>LightGBM</td><td>-0.065</td><td>-0.192</td><td>-0.249</td><td>-0.31</td><td>-0.353</td><td>-0.047</td><td>-0.144</td><td>-0.274</td><td>-0.398</td><td>-0.552</td><td>0.237</td><td>0.599</td><td>0.793</td><td>1.159</td><td>1.405</td></tr>
<tr><td>XGBoost</td><td>-0.076</td><td>-0.218</td><td>-0.261</td><td>-0.328</td><td>-0.375</td><td>-0.043</td><td>-0.125</td><td>-0.228</td><td>-0.342</td><td>-0.496</td><td>0.233</td><td>0.592</td><td>0.84</td><td>1.197</td><td>1.49</td></tr>
<tr><td>CatBoost</td><td>-0.035</td><td>-0.105</td><td>-0.155</td><td>-0.238</td><td>-0.332</td><td>-0.043</td><td>-0.123</td><td>-0.232</td><td>-0.374</td><td>-0.516</td><td>0.25</td><td>0.642</td><td>0.916</td><td>1.345</td><td>1.669</td></tr>
<tr><td>TabPFN</td><td>-0.048</td><td>-0.118</td><td>-0.165</td><td>-0.235</td><td>-0.309</td><td>-0.02</td><td>-0.069</td><td>-0.132</td><td>-0.228</td><td>-0.388</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>TabPFNv2</td><td>-0.043</td><td>-0.127</td><td>-0.217</td><td>-0.296</td><td>-0.369</td><td>-0.058</td><td>-0.153</td><td>-0.277</td><td>-0.421</td><td>-0.592</td><td>-0.016</td><td>-0.044</td><td>-0.056</td><td>-0.084</td><td>-0.089</td></tr>
<tr><td>DANets</td><td>-0.022</td><td>-0.056</td><td>-0.09</td><td>-0.154</td><td>-0.226</td><td>-0.015</td><td>-0.052</td><td>-0.097</td><td>-0.178</td><td>-0.287</td><td>0.001</td><td>0.003</td><td>0.004</td><td>0.007</td><td>0.011</td></tr>
<tr><td>MLP</td><td>-0.024</td><td>-0.062</td><td>-0.107</td><td>-0.185</td><td>-0.271</td><td>-0.023</td><td>-0.065</td><td>-0.123</td><td>-0.203</td><td>-0.36</td><td>0.028</td><td>0.076</td><td>0.128</td><td>0.184</td><td>0.25</td></tr>
<tr><td>NODE</td><td>-0.009</td><td>-0.031</td><td>-0.061</td><td>-0.109</td><td>-0.179</td><td>-0.002</td><td>-0.023</td><td>-0.045</td><td>-0.084</td><td>-0.143</td><td>0.001</td><td>0.003</td><td>0.005</td><td>0.007</td><td>0.009</td></tr>
<tr><td>ResNet</td><td>-0.031</td><td>-0.085</td><td>-0.15</td><td>-0.233</td><td>-0.315</td><td>-0.034</td><td>-0.09</td><td>-0.171</td><td>-0.279</td><td>-0.488</td><td>0.054</td><td>0.133</td><td>0.208</td><td>0.293</td><td>0.38</td></tr>
<tr><td>SwitchTab</td><td>-0.01</td><td>-0.031</td><td>-0.063</td><td>-0.123</td><td>-0.235</td><td>-0.019</td><td>-0.049</td><td>-0.096</td><td>-0.164</td><td>-0.347</td><td>0.001</td><td>0.003</td><td>0.005</td><td>0.006</td><td>0.013</td></tr>
<tr><td>TabCaps</td><td>-0.02</td><td>-0.051</td><td>-0.09</td><td>-0.157</td><td>-0.263</td><td>-0.012</td><td>-0.044</td><td>-0.084</td><td>-0.13</td><td>-0.232</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>TabNet</td><td>-0.015</td><td>-0.055</td><td>-0.099</td><td>-0.161</td><td>-0.21</td><td>-0.025</td><td>-0.07</td><td>-0.108</td><td>-0.165</td><td>-0.27</td><td>0.004</td><td>0.018</td><td>0.14</td><td>0.027</td><td>0.029</td></tr>
<tr><td>TANGOS</td><td>-0.026</td><td>-0.069</td><td>-0.121</td><td>-0.203</td><td>-0.286</td><td>-0.03</td><td>-0.082</td><td>-0.15</td><td>-0.236</td><td>-0.423</td><td>0.001</td><td>0.003</td><td>0.005</td><td>0.006</td><td>0.013</td></tr>
      <tr><td>AutoInt</td><td>-0.028</td><td>-0.065</td><td>-0.115</td><td>-0.188</td><td>-0.269</td><td>-0.015</td><td>-0.071</td><td>-0.145</td><td>-0.262</td><td>-0.383</td><td>0.012</td><td>0.034</td><td>0.063</td><td>0.095</td><td>0.163</td></tr>
<tr><td>DCNv2</td><td>-0.026</td><td>-0.07</td><td>-0.12</td><td>-0.201</td><td>-0.285</td><td>-0.025</td><td>-0.067</td><td>-0.135</td><td>-0.216</td><td>-0.362</td><td>0.039</td><td>0.102</td><td>0.18</td><td>0.244</td><td>0.317</td></tr>
<tr><td>FT-Transformer</td><td>-0.028</td><td>-0.077</td><td>-0.138</td><td>-0.232</td><td>-0.305</td><td>-0.017</td><td>-0.067</td><td>-0.145</td><td>-0.272</td><td>-0.464</td><td>0.007</td><td>0.025</td><td>0.049</td><td>0.078</td><td>0.112</td></tr>
<tr><td>GrowNet</td><td>-0.01</td><td>-0.041</td><td>-0.077</td><td>-0.138</td><td>-0.198</td><td>-0.008</td><td>-0.026</td><td>-0.045</td><td>-0.077</td><td>-0.105</td><td>0.003</td><td>0.005</td><td>0.009</td><td>0.016</td><td>0.018</td></tr>
<tr><td>Saint</td><td>-0.016</td><td>-0.042</td><td>-0.072</td><td>-0.142</td><td>-0.247</td><td>-0.031</td><td>-0.095</td><td>-0.192</td><td>-0.32</td><td>-0.44</td><td>0.017</td><td>0.051</td><td>0.087</td><td>0.131</td><td>0.167</td></tr>
<tr><td>SNN</td><td>-0.018</td><td>-0.048</td><td>-0.086</td><td>-0.143</td><td>-0.226</td><td>-0.017</td><td>-0.055</td><td>-0.102</td><td>-0.164</td><td>-0.275</td><td>0.013</td><td>0.038</td><td>0.05</td><td>0.066</td><td>0.059</td></tr>
<tr><td>TabTransformer</td><td>-0.016</td><td>-0.044</td><td>-0.078</td><td>-0.133</td><td>-0.203</td><td>-0.009</td><td>-0.032</td><td>-0.056</td><td>-0.086</td><td>-0.15</td><td>0.001</td><td>0.002</td><td>0.002</td><td>0.003</td><td>0.006</td></tr>
<tr><td>TabR</td><td>-0.062</td><td>-0.158</td><td>-0.214</td><td>-0.263</td><td>-0.318</td><td>-0.046</td><td>-0.126</td><td>-0.221</td><td>-0.355</td><td>-0.525</td><td>0.022</td><td>0.064</td><td>0.119</td><td>0.244</td><td>0.392</td></tr>
<tr><td>ModernNCA</td><td>-0.161</td><td>-0.271</td><td>-0.301</td><td>-0.329</td><td>-0.357</td><td>-0.087</td><td>-0.206</td><td>-0.344</td><td>-0.462</td><td>-0.62</td><td>0.163</td><td>0.369</td><td>0.559</td><td>0.795</td><td>1</td></tr>
<tr><td>Llama3-8B</td><td>-0.045</td><td>-0.118</td><td>-0.176</td><td>-0.244</td><td>-0.351</td><td>0.056</td><td>-0.101</td><td>-0.217</td><td>-0.291</td><td>-0.429</td><td>-0.233</td><td>0.444</td><td>0.595</td><td>0.359</td><td>0.669</td></tr>
<tr><td>TabLLM</td><td>-0.022</td><td>-0.042</td><td>-0.056</td><td>-0.066</td><td>-0.08</td><td>-0.007</td><td>-0.017</td><td>-0.103</td><td>-0.314</td><td>-0.245</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>UniPredict</td><td>-0.019</td><td>-0.038</td><td>-0.058</td><td>-0.074</td><td>-0.094</td><td>-0.135</td><td>-0.137</td><td>-0.123</td><td>-0.139</td><td>-0.176</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
    </tbody>
</table>
<br>

<h3>Feature-Shift Performance Rank</h3>

<table id="sortableTable" style="text-align: center;">
    <thead>
        <!-- 新增合并行 -->
        <tr>
          <th colspan="1" class="group-header">Rank</th>
            <th colspan="6" class="group-header">Binary Classification</th>
          <th colspan="6" class="group-header">Multi Classification</th>
          <th colspan="6" class="group-header">Regression</th>
        </tr>
        <!-- 原有表头行 -->
        <tr>
            <th onclick="sortTable(0)">Model</th>
          <th onclick="sortTable(1)">0%</th>
            <th onclick="sortTable(2)">20%</th>
            <th onclick="sortTable(3)">40%</th>
          <th onclick="sortTable(4)">60%</th>
            <th onclick="sortTable(5)">80%</th>
            <th onclick="sortTable(6)">100%</th>
          <th onclick="sortTable(7)">0%</th>
                      <th onclick="sortTable(8)">20%</th>
            <th onclick="sortTable(9)">40%</th>
          <th onclick="sortTable(10)">60%</th>
            <th onclick="sortTable(11)">80%</th>
            <th onclick="sortTable(12)">100%</th>
          <th onclick="sortTable(13)">0%</th>
                      <th onclick="sortTable(14)">20%</th>
            <th onclick="sortTable(15)">40%</th>
          <th onclick="sortTable(16)">60%</th>
            <th onclick="sortTable(17)">80%</th>
            <th onclick="sortTable(18)">100%</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>LightGBM</td><td>0.838</td><td>0.811</td><td>0.695</td><td>0.645</td><td>0.589</td><td>0.550</td><td>0.800</td><td>0.640</td><td>0.589</td><td>0.496</td><td>0.412</td><td>0.308</td><td>0.975</td><td>0.886</td><td>0.785</td><td>0.692</td><td>0.618</td><td>0.539</td></tr>
<tr><td>XGBoost</td><td>0.842</td><td>0.803</td><td>0.674</td><td>0.636</td><td>0.577</td><td>0.534</td><td>0.802</td><td>0.642</td><td>0.601</td><td>0.525</td><td>0.449</td><td>0.346</td><td>0.972</td><td>0.877</td><td>0.772</td><td>0.650</td><td>0.570</td><td>0.461</td></tr>
<tr><td>CatBoost</td><td>0.869</td><td>0.860</td><td>0.797</td><td>0.751</td><td>0.675</td><td>0.588</td><td>0.837</td><td>0.690</td><td>0.647</td><td>0.564</td><td>0.459</td><td>0.355</td><td>0.992</td><td>0.920</td><td>0.836</td><td>0.710</td><td>0.648</td><td>0.550</td></tr>
<tr><td>TabPFN</td><td>0.831</td><td>0.823</td><td>0.757</td><td>0.718</td><td>0.652</td><td>0.587</td><td>0.785</td><td>0.609</td><td>0.597</td><td>0.550</td><td>0.489</td><td>0.383</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>TabPFNv2</td><td>0.852</td><td>0.886</td><td>0.786</td><td>0.662</td><td>0.572</td><td>0.526</td><td>0.709</td><td>0.684</td><td>0.649</td><td>0.548</td><td>0.437</td><td>0.301</td><td>0.928</td><td>0.929</td><td>0.894</td><td>0.885</td><td>0.856</td><td>0.859</td></tr>
<tr><td>DANets</td><td>0.753</td><td>0.783</td><td>0.753</td><td>0.725</td><td>0.670</td><td>0.605</td><td>0.535</td><td>0.558</td><td>0.542</td><td>0.505</td><td>0.462</td><td>0.379</td><td>0.666</td><td>0.481</td><td>0.580</td><td>0.509</td><td>0.580</td><td>0.549</td></tr>
<tr><td>MLP</td><td>0.805</td><td>0.814</td><td>0.777</td><td>0.740</td><td>0.670</td><td>0.595</td><td>0.723</td><td>0.623</td><td>0.607</td><td>0.563</td><td>0.514</td><td>0.409</td><td>0.797</td><td>0.651</td><td>0.694</td><td>0.606</td><td>0.632</td><td>0.565</td></tr>
<tr><td>NODE</td><td>0.690</td><td>0.726</td><td>0.705</td><td>0.687</td><td>0.645</td><td>0.590</td><td>0.527</td><td>0.516</td><td>0.507</td><td>0.490</td><td>0.474</td><td>0.440</td><td>0.671</td><td>0.487</td><td>0.583</td><td>0.512</td><td>0.582</td><td>0.549</td></tr>
<tr><td>ResNet</td><td>0.811</td><td>0.814</td><td>0.764</td><td>0.708</td><td>0.633</td><td>0.564</td><td>0.764</td><td>0.644</td><td>0.616</td><td>0.556</td><td>0.486</td><td>0.342</td><td>0.844</td><td>0.718</td><td>0.729</td><td>0.642</td><td>0.642</td><td>0.568</td></tr>
<tr><td>SwitchTab</td><td>0.797</td><td>0.807</td><td>0.787</td><td>0.762</td><td>0.708</td><td>0.616</td><td>0.747</td><td>0.628</td><td>0.620</td><td>0.582</td><td>0.543</td><td>0.422</td><td>0.662</td><td>0.474</td><td>0.574</td><td>0.501</td><td>0.574</td><td>0.541</td></tr>
<tr><td>TabCaps</td><td>0.771</td><td>0.789</td><td>0.762</td><td>0.730</td><td>0.673</td><td>0.584</td><td>0.693</td><td>0.574</td><td>0.573</td><td>0.538</td><td>0.517</td><td>0.448</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>TabNet</td><td>0.714</td><td>0.746</td><td>0.711</td><td>0.668</td><td>0.613</td><td>0.565</td><td>0.561</td><td>0.550</td><td>0.531</td><td>0.502</td><td>0.474</td><td>0.402</td><td>0.672</td><td>0.457</td><td>0.575</td><td>0.517</td><td>0.590</td><td>0.550</td></tr>
<tr><td>TANGOS</td><td>0.813</td><td>0.819</td><td>0.779</td><td>0.734</td><td>0.659</td><td>0.587</td><td>0.723</td><td>0.635</td><td>0.615</td><td>0.565</td><td>0.511</td><td>0.378</td><td>0.844</td><td>0.728</td><td>0.744</td><td>0.646</td><td>0.643</td><td>0.570</td></tr>
<tr><td>AutoInt</td><td>0.765</td><td>0.796</td><td>0.762</td><td>0.719</td><td>0.654</td><td>0.579</td><td>0.527</td><td>0.580</td><td>0.549</td><td>0.498</td><td>0.429</td><td>0.333</td><td>0.726</td><td>0.551</td><td>0.630</td><td>0.546</td><td>0.599</td><td>0.525</td></tr>
<tr><td>DCNv2</td><td>0.807</td><td>0.809</td><td>0.768</td><td>0.727</td><td>0.654</td><td>0.583</td><td>0.751</td><td>0.635</td><td>0.620</td><td>0.568</td><td>0.518</td><td>0.418</td><td>0.815</td><td>0.686</td><td>0.708</td><td>0.615</td><td>0.627</td><td>0.562</td></tr>
<tr><td>FT-Transformer</td><td>0.785</td><td>0.799</td><td>0.755</td><td>0.703</td><td>0.621</td><td>0.557</td><td>0.703</td><td>0.620</td><td>0.603</td><td>0.543</td><td>0.464</td><td>0.331</td><td>0.723</td><td>0.538</td><td>0.626</td><td>0.541</td><td>0.602</td><td>0.550</td></tr>
<tr><td>GrowNet</td><td>0.689</td><td>0.735</td><td>0.708</td><td>0.679</td><td>0.628</td><td>0.573</td><td>0.404</td><td>0.454</td><td>0.450</td><td>0.433</td><td>0.418</td><td>0.379</td><td>0.675</td><td>0.493</td><td>0.587</td><td>0.515</td><td>0.581</td><td>0.547</td></tr>
<tr><td>Saint</td><td>0.821</td><td>0.837</td><td>0.812</td><td>0.787</td><td>0.722</td><td>0.630</td><td>0.744</td><td>0.646</td><td>0.619</td><td>0.546</td><td>0.459</td><td>0.376</td><td>0.736</td><td>0.543</td><td>0.624</td><td>0.527</td><td>0.584</td><td>0.528</td></tr>
<tr><td>SNN</td><td>0.728</td><td>0.735</td><td>0.711</td><td>0.679</td><td>0.635</td><td>0.568</td><td>0.696</td><td>0.599</td><td>0.587</td><td>0.552</td><td>0.517</td><td>0.447</td><td>0.700</td><td>0.528</td><td>0.598</td><td>0.524</td><td>0.580</td><td>0.550</td></tr>
<tr><td>TabTransformer</td><td>0.643</td><td>0.718</td><td>0.690</td><td>0.665</td><td>0.617</td><td>0.551</td><td>0.406</td><td>0.532</td><td>0.512</td><td>0.492</td><td>0.478</td><td>0.419</td><td>0.662</td><td>0.484</td><td>0.578</td><td>0.511</td><td>0.576</td><td>0.543</td></tr>
<tr><td>TabR</td><td>0.840</td><td>0.802</td><td>0.716</td><td>0.664</td><td>0.620</td><td>0.572</td><td>0.761</td><td>0.662</td><td>0.618</td><td>0.545</td><td>0.454</td><td>0.332</td><td>0.843</td><td>0.730</td><td>0.768</td><td>0.684</td><td>0.663</td><td>0.555</td></tr>
<tr><td>ModernNCA</td><td>0.869</td><td>0.730</td><td>0.630</td><td>0.600</td><td>0.577</td><td>0.553</td><td>0.906</td><td>0.723</td><td>0.632</td><td>0.523</td><td>0.426</td><td>0.310</td><td>0.940</td><td>0.846</td><td>0.800</td><td>0.693</td><td>0.630</td><td>0.529</td></tr>
<tr><td>Llama3-8B</td><td>0.838</td><td>0.828</td><td>0.761</td><td>0.710</td><td>0.648</td><td>0.556</td><td>0.749</td><td>0.642</td><td>0.563</td><td>0.489</td><td>0.438</td><td>0.359</td><td>0.727</td><td>0.909</td><td>0.702</td><td>0.686</td><td>0.609</td><td>0.410</td></tr>
<tr><td>TabLLM</td><td>0.813</td><td>0.816</td><td>0.803</td><td>0.786</td><td>0.782</td><td>0.768</td><td>0.832</td><td>0.696</td><td>0.696</td><td>0.652</td><td>0.517</td><td>0.571</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>UniPredict</td><td>0.790</td><td>0.831</td><td>0.809</td><td>0.798</td><td>0.779</td><td>0.763</td><td>0.829</td><td>0.702</td><td>0.700</td><td>0.708</td><td>0.701</td><td>0.674</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td>
<td>\\</td><td>\\</td></tr>
    </tbody>
</table>
<br>
<br>

<script>
function sortTable2(n) {
    var table, rows, switching, i, x, y, shouldSwitch, dir, switchcount = 0;
    table = document.getElementById("sortableTable2");
    switching = true;
    dir = "asc"; 
    while (switching) {
        switching = false;
        rows = table.rows;
        for (i = 1; i < (rows.length - 1); i++) {
            shouldSwitch = false;
            x = rows[i].getElementsByTagName("TD")[n];
            y = rows[i + 1].getElementsByTagName("TD")[n];
            if (dir == "asc") {
                if (x.innerHTML.toLowerCase() > y.innerHTML.toLowerCase()) {
                    shouldSwitch = true;
                    break;
                }
            } else if (dir == "desc") {
                if (x.innerHTML.toLowerCase() < y.innerHTML.toLowerCase()) {
                    shouldSwitch = true;
                    break;
                }
            }
        }
        if (shouldSwitch) {
            rows[i].parentNode.insertBefore(rows[i + 1], rows[i]);
            switching = true;
            switchcount ++; 
        } else {
            if (switchcount == 0 && dir == "asc") {
                dir = "desc";
                switching = true;
            }
        }
    }
}
    
function sortTable1(n) {
    var table, rows, switching, i, x, y, shouldSwitch, dir, switchcount = 0;
    table = document.getElementById("sortableTable1");
    switching = true;
    dir = "asc"; 
    while (switching) {
        switching = false;
        rows = table.rows;
        for (i = 2; i < (rows.length - 1); i++) {
            shouldSwitch = false;
            x = rows[i].getElementsByTagName("TD")[n];
            y = rows[i + 1].getElementsByTagName("TD")[n];
            if (dir == "asc") {
                if (x.innerHTML.toLowerCase() > y.innerHTML.toLowerCase()) {
                    shouldSwitch = true;
                    break;
                }
            } else if (dir == "desc") {
                if (x.innerHTML.toLowerCase() < y.innerHTML.toLowerCase()) {
                    shouldSwitch = true;
                    break;
                }
            }
        }
        if (shouldSwitch) {
            rows[i].parentNode.insertBefore(rows[i + 1], rows[i]);
            switching = true;
            switchcount ++; 
        } else {
            if (switchcount == 0 && dir == "asc") {
                dir = "desc";
                switching = true;
            }
        }
    }
}
    
function sortTable(n) {
    var table, rows, switching, i, x, y, shouldSwitch, dir, switchcount = 0;
    table = document.getElementById("sortableTable");
    switching = true;
    dir = "asc"; 
    while (switching) {
        switching = false;
        rows = table.rows;
        for (i = 2; i < (rows.length - 1); i++) {
            shouldSwitch = false;
            x = rows[i].getElementsByTagName("TD")[n];
            y = rows[i + 1].getElementsByTagName("TD")[n];
            if (dir == "asc") {
                if (x.innerHTML.toLowerCase() > y.innerHTML.toLowerCase()) {
                    shouldSwitch = true;
                    break;
                }
            } else if (dir == "desc") {
                if (x.innerHTML.toLowerCase() < y.innerHTML.toLowerCase()) {
                    shouldSwitch = true;
                    break;
                }
            }
        }
        if (shouldSwitch) {
            rows[i].parentNode.insertBefore(rows[i + 1], rows[i]);
            switching = true;
            switchcount ++; 
        } else {
            if (switchcount == 0 && dir == "asc") {
                dir = "desc";
                switching = true;
            }
        }
    }
}
</script>

</body>
</html>
