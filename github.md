---
layout: page
title: Leaderboard
permalink: /board/
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sortable Table</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 8px;
            text-align: left;
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

<h2>Sortable Table</h2>

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
        <tr><td>LGB</td><td>-0.065</td><td>-0.192</td><td>-0.249</td><td>-0.31</td><td>-0.353</td><td>-0.047</td><td>-0.144</td><td>-0.274</td><td>-0.398</td><td>-0.552</td><td>0.237</td><td>0.599</td><td>0.793</td><td>1.159</td><td>1.405</td></tr>
<tr><td>XGB</td><td>-0.076</td><td>-0.218</td><td>-0.261</td><td>-0.328</td><td>-0.375</td><td>-0.043</td><td>-0.125</td><td>-0.228</td><td>-0.342</td><td>-0.496</td><td>0.233</td><td>0.592</td><td>0.84</td><td>1.197</td><td>1.49</td></tr>
<tr><td>CATB</td><td>-0.035</td><td>-0.105</td><td>-0.155</td><td>-0.238</td><td>-0.332</td><td>-0.043</td><td>-0.123</td><td>-0.232</td><td>-0.374</td><td>-0.516</td><td>0.25</td><td>0.642</td><td>0.916</td><td>1.345</td><td>1.669</td></tr>
<tr><td>PFN</td><td>-0.048</td><td>-0.118</td><td>-0.165</td><td>-0.235</td><td>-0.309</td><td>-0.02</td><td>-0.069</td><td>-0.132</td><td>-0.228</td><td>-0.388</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>DAN</td><td>-0.022</td><td>-0.056</td><td>-0.09</td><td>-0.154</td><td>-0.226</td><td>-0.015</td><td>-0.052</td><td>-0.097</td><td>-0.178</td><td>-0.287</td><td>0.001</td><td>0.003</td><td>0.004</td><td>0.007</td><td>0.011</td></tr>
<tr><td>MLP</td><td>-0.024</td><td>-0.062</td><td>-0.107</td><td>-0.185</td><td>-0.271</td><td>-0.023</td><td>-0.065</td><td>-0.123</td><td>-0.203</td><td>-0.36</td><td>0.028</td><td>0.076</td><td>0.128</td><td>0.184</td><td>0.25</td></tr>
<tr><td>NODE</td><td>-0.009</td><td>-0.031</td><td>-0.061</td><td>-0.109</td><td>-0.179</td><td>-0.002</td><td>-0.023</td><td>-0.045</td><td>-0.084</td><td>-0.143</td><td>0.001</td><td>0.003</td><td>0.005</td><td>0.007</td><td>0.009</td></tr>
<tr><td>RES</td><td>-0.031</td><td>-0.085</td><td>-0.15</td><td>-0.233</td><td>-0.315</td><td>-0.034</td><td>-0.09</td><td>-0.171</td><td>-0.279</td><td>-0.488</td><td>0.054</td><td>0.133</td><td>0.208</td><td>0.293</td><td>0.38</td></tr>
<tr><td>SWI</td><td>-0.01</td><td>-0.031</td><td>-0.063</td><td>-0.123</td><td>-0.235</td><td>-0.019</td><td>-0.049</td><td>-0.096</td><td>-0.164</td><td>-0.347</td><td>0.001</td><td>0.003</td><td>0.005</td><td>0.006</td><td>0.013</td></tr>
<tr><td>CAP</td><td>-0.02</td><td>-0.051</td><td>-0.09</td><td>-0.157</td><td>-0.263</td><td>-0.012</td><td>-0.044</td><td>-0.084</td><td>-0.13</td><td>-0.232</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td><td>\\</td></tr>
<tr><td>NET</td><td>-0.015</td><td>-0.055</td><td>-0.099</td><td>-0.161</td><td>-0.21</td><td>-0.025</td><td>-0.07</td><td>-0.108</td><td>-0.165</td><td>-0.27</td><td>0.004</td><td>0.018</td><td>0.14</td><td>0.027</td><td>0.029</td></tr>
<tr><td>GOS</td><td>-0.026</td><td>-0.069</td><td>-0.121</td><td>-0.203</td><td>-0.286</td><td>-0.03</td><td>-0.082</td><td>-0.15</td><td>-0.236</td><td>-0.423</td><td>0.001</td><td>0.003</td><td>0.005</td><td>0.006</td><td>0.013</td></tr>
    </tbody>
</table>

<script>
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
