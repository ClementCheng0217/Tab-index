---
layout: page
title: Leaderboard
permalink: /board/
---

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

<h2>Closed-Environment Rank v.s. Feature-Shift Rank</h2>

<table id="sortableTable">
    <thead>
        <tr>
            <th onclick="sortTable2(0)">Model</th>
            <th onclick="sortTable2(1)">Closed-Environment Rank</th>
            <th onclick="sortTable2(2)">Feature-Shift Rank</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>LightGBM</td><td>4</td><td>15</td></tr>
<tr><td>XGBoost</td><td>3</td><td>16</td></tr>
<tr><td>CatBoost</td><td>1</td><td>3</td></tr>
<tr><td>TabPFN</td><td>7</td><td>9</td></tr>
<tr><td>DANets</td><td>21</td><td>20</td></tr>
<tr><td>MLP</td><td>14</td><td>6</td></tr>
<tr><td>NODE</td><td>22</td><td>21</td></tr>
<tr><td>ResNet</td><td>8</td><td>8</td></tr>
<tr><td>SwitchTab</td><td>16</td><td>11</td></tr>
<tr><td>TabCaps</td><td>19</td><td>14</td></tr>
<tr><td>TabNet</td><td>20</td><td>22</td></tr>
<tr><td>TANGOS</td><td>11</td><td>4</td></tr>
<tr><td>AutoInt</td><td>17</td><td>19</td></tr>
<tr><td>DCNv2</td><td>12</td><td>5</td></tr>
<tr><td>FT-Transformer</td><td>15</td><td>17</td></tr>
<tr><td>GrowNet</td><td>23</td><td>23</td></tr>
<tr><td>Saint</td><td>13</td><td>7</td></tr>
<tr><td>SNN</td><td>17</td><td>17</td></tr>
<tr><td>TabTransformer</td><td>24</td><td>24</td></tr>
<tr><td>TabR</td><td>6</td><td>10</td></tr>
<tr><td>ModernNCA</td><td>2</td><td>12</td></tr>
<tr><td>Llama3-8B</td><td>9</td><td>13</td></tr>
<tr><td>TabLLM</td><td>5</td><td>2</td></tr>
<tr><td>UniPredict</td><td>10</td><td>1</td></tr>
    </tbody>
</table>
<br>

<h2>Performance Gap</h2>

<table id="sortableTable">
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
            <th onclick="sortTable(0)">Model</th>
            <th onclick="sortTable(1)">20%</th>
            <th onclick="sortTable(2)">40%</th>
          <th onclick="sortTable(3)">60%</th>
            <th onclick="sortTable(4)">80%</th>
            <th onclick="sortTable(5)">100%</th>
                      <th onclick="sortTable(6)">20%</th>
            <th onclick="sortTable(7)">40%</th>
          <th onclick="sortTable(8)">60%</th>
            <th onclick="sortTable(9)">80%</th>
            <th onclick="sortTable(10)">100%</th>
                      <th onclick="sortTable(11)">20%</th>
            <th onclick="sortTable(12)">40%</th>
          <th onclick="sortTable(13)">60%</th>
            <th onclick="sortTable(14)">80%</th>
            <th onclick="sortTable(15)">100%</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>LightGBM</td><td>-0.065</td><td>-0.192</td><td>-0.249</td><td>-0.31</td><td>-0.353</td><td>-0.047</td><td>-0.144</td><td>-0.274</td><td>-0.398</td><td>-0.552</td><td>0.237</td><td>0.599</td><td>0.793</td><td>1.159</td><td>1.405</td></tr>
<tr><td>XGBoost</td><td>-0.076</td><td>-0.218</td><td>-0.261</td><td>-0.328</td><td>-0.375</td><td>-0.043</td><td>-0.125</td><td>-0.228</td><td>-0.342</td><td>-0.496</td><td>0.233</td><td>0.592</td><td>0.84</td><td>1.197</td><td>1.49</td></tr>
<tr><td>CatBoost</td><td>-0.035</td><td>-0.105</td><td>-0.155</td><td>-0.238</td><td>-0.332</td><td>-0.043</td><td>-0.123</td><td>-0.232</td><td>-0.374</td><td>-0.516</td><td>0.25</td><td>0.642</td><td>0.916</td><td>1.345</td><td>1.669</td></tr>
<tr><td>TabPFN</td><td>-0.048</td><td>-0.118</td><td>-0.165</td><td>-0.235</td><td>-0.309</td><td>-0.02</td><td>-0.069</td><td>-0.132</td><td>-0.228</td><td>-0.388</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
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

<h2>Performance Rank</h2>

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
        <tr><td>LightGBM</td><td>5</td><td>10</td><td>21</td><td>22</td><td>22</td><td>23</td><td>6</td><td>10</td><td>15</td><td>20</td><td>24</td><td>24</td><td>2</td><td>3</td><td>3</td><td>3</td><td>8</td><td>15</td></tr>
<tr><td>XGBoost</td><td>3</td><td>13</td><td>23</td><td>23</td><td>24</td><td>24</td><td>5</td><td>8</td><td>13</td><td>15</td><td>19</td><td>18</td><td>3</td><td>4</td><td>4</td><td>6</td><td>20</td><td>19</td></tr>
<tr><td>CatBoost</td><td>2</td><td>1</td><td>4</td><td>5</td><td>5</td><td>8</td><td>2</td><td>4</td><td>3</td><td>6</td><td>17</td><td>17</td><td>1</td><td>1</td><td>1</td><td>1</td><td>2</td><td>6</td></tr>
<tr><td>TabPFN</td><td>7</td><td>5</td><td>13</td><td>12</td><td>12</td><td>9</td><td>7</td><td>16</td><td>14</td><td>10</td><td>9</td><td>11</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>DANets</td><td>19</td><td>18</td><td>15</td><td>10</td><td>7</td><td>5</td><td>20</td><td>20</td><td>20</td><td>17</td><td>15</td><td>13</td><td>18</td><td>18</td><td>17</td><td>19</td><td>17</td><td>11</td></tr>
<tr><td>MLP</td><td>13</td><td>9</td><td>7</td><td>6</td><td>8</td><td>6</td><td>15</td><td>14</td><td>11</td><td>7</td><td>7</td><td>9</td><td>9</td><td>10</td><td>10</td><td>10</td><td>5</td><td>3</td></tr>
<tr><td>NODE</td><td>22</td><td>23</td><td>20</td><td>16</td><td>14</td><td>7</td><td>22</td><td>23</td><td>23</td><td>22</td><td>12</td><td>5</td><td>17</td><td>16</td><td>16</td><td>17</td><td>14</td><td>10</td></tr>
<tr><td>ResNet</td><td>11</td><td>8</td><td>9</td><td>14</td><td>16</td><td>18</td><td>8</td><td>7</td><td>9</td><td>8</td><td>10</td><td>19</td><td>6</td><td>8</td><td>7</td><td>8</td><td>4</td><td>2</td></tr>
<tr><td>SwitchTab</td><td>14</td><td>12</td><td>5</td><td>4</td><td>4</td><td>4</td><td>12</td><td>13</td><td>5</td><td>3</td><td>2</td><td>6</td><td>20</td><td>19</td><td>20</td><td>20</td><td>19</td><td>14</td></tr>
<tr><td>TabCaps</td><td>17</td><td>17</td><td>11</td><td>8</td><td>6</td><td>11</td><td>18</td><td>19</td><td>17</td><td>14</td><td>6</td><td>3</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>TabNet</td><td>21</td><td>19</td><td>17</td><td>19</td><td>21</td><td>17</td><td>19</td><td>21</td><td>21</td><td>18</td><td>13</td><td>10</td><td>16</td><td>20</td><td>19</td><td>15</td><td>12</td><td>8</td></tr>
<tr><td>TANGOS</td><td>10</td><td>6</td><td>6</td><td>7</td><td>9</td><td>10</td><td>14</td><td>11</td><td>10</td><td>5</td><td>8</td><td>14</td><td>5</td><td>7</td><td>6</td><td>7</td><td>3</td><td>1</td></tr>
<tr><td>AutoInt</td><td>18</td><td>16</td><td>10</td><td>11</td><td>10</td><td>13</td><td>21</td><td>18</td><td>19</td><td>19</td><td>21</td><td>20</td><td>12</td><td>11</td><td>11</td><td>11</td><td>11</td><td>18</td></tr>
<tr><td>DCNv2</td><td>12</td><td>11</td><td>8</td><td>9</td><td>11</td><td>12</td><td>10</td><td>12</td><td>6</td><td>4</td><td>3</td><td>8</td><td>8</td><td>9</td><td>8</td><td>9</td><td>7</td><td>4</td></tr>
<tr><td>FT-Transformer</td><td>16</td><td>15</td><td>14</td><td>15</td><td>18</td><td>19</td><td>16</td><td>15</td><td>12</td><td>13</td><td>14</td><td>22</td><td>13</td><td>13</td><td>12</td><td>12</td><td>10</td><td>7</td></tr>
<tr><td>GrowNet</td><td>23</td><td>20</td><td>19</td><td>18</td><td>17</td><td>14</td><td>24</td><td>24</td><td>24</td><td>24</td><td>23</td><td>12</td><td>15</td><td>15</td><td>15</td><td>16</td><td>15</td><td>12</td></tr>
<tr><td>Saint</td><td>8</td><td>2</td><td>1</td><td>2</td><td>3</td><td>3</td><td>13</td><td>6</td><td>7</td><td>11</td><td>16</td><td>15</td><td>10</td><td>12</td><td>13</td><td>13</td><td>13</td><td>17</td></tr>
<tr><td>SNN</td><td>20</td><td>21</td><td>18</td><td>17</td><td>15</td><td>16</td><td>17</td><td>17</td><td>16</td><td>9</td><td>5</td><td>4</td><td>14</td><td>14</td><td>14</td><td>14</td><td>16</td><td>9</td></tr>
<tr><td>TabTransformer</td><td>24</td><td>24</td><td>22</td><td>20</td><td>20</td><td>22</td><td>23</td><td>22</td><td>22</td><td>21</td><td>11</td><td>7</td><td>19</td><td>17</td><td>18</td><td>18</td><td>18</td><td>13</td></tr>
<tr><td>TabR</td><td>4</td><td>14</td><td>16</td><td>21</td><td>19</td><td>15</td><td>9</td><td>5</td><td>8</td><td>12</td><td>18</td><td>21</td><td>7</td><td>6</td><td>5</td><td>5</td><td>1</td><td>5</td></tr>
<tr><td>ModernNCA</td><td>1</td><td>22</td><td>24</td><td>24</td><td>23</td><td>21</td><td>1</td><td>1</td><td>4</td><td>16</td><td>22</td><td>23</td><td>4</td><td>5</td><td>2</td><td>2</td><td>6</td><td>16</td></tr>
<tr><td>Llama3-8B</td><td>6</td><td>4</td><td>12</td><td>13</td><td>13</td><td>20</td><td>11</td><td>9</td><td>18</td><td>23</td><td>20</td><td>16</td><td>11</td><td>2</td><td>9</td><td>4</td><td>9</td><td>20</td></tr>
<tr><td>TabLLM</td><td>9</td><td>7</td><td>3</td><td>3</td><td>1</td><td>1</td><td>3</td><td>3</td><td>2</td><td>2</td><td>4</td><td>2</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>UniPredict</td><td>15</td><td>3</td><td>2</td><td>1</td><td>2</td><td>2</td><td>4</td><td>2</td><td>1</td><td>1</td><td>1</td><td>1</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
    </tbody>
</table>

<script>
    function sortTable2(n) {
    var table, rows, switching, i, x, y, shouldSwitch, dir, switchcount = 0;
    table = document.getElementById("sortableTable");
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
