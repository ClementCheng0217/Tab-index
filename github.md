---
layout: page
title: Leaderboard
permalink: /board/
---

  <head>
    <meta charset="utf-8">
    <script type="text/javascript">
      function sortTable(columnIndex) {
  var table = document.getElementById("myTable");
  var rows = Array.from(table.getElementsByTagName("tr"));
  var ascending = true;
  rows.shift(); // 移除表头行
  rows.sort(function(a, b) {
    var aCellValue = a.cells[columnIndex].textContent;
    var bCellValue = b.cells[columnIndex].textContent;
    if (columnIndex === 0 || columnIndex === 1) {
      // 字符串排序
      return ascending ? aCellValue.localeCompare(bCellValue) : bCellValue.localeCompare(aCellValue);
    } else {
      // 数字排序
      return ascending ? Number(aCellValue) - Number(bCellValue) : Number(bCellValue) - Number(aCellValue);
    }
  });
  ascending = !ascending; // 切换排序顺序
  // 将排序后的行重新插入表格
  rows.forEach(function(row) {
    table.appendChild(row);
  });
}
    </script>
      </head>
  <body>

      <table id="myTable">
  <thead>
    <tr>
      <th onclick="sortTable(0)">姓名</th>
      <th onclick="sortTable(1)">年龄</th>
      <th onclick="sortTable(2)">成绩</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>张三</td>
      <td>25</td>
      <td>90</td>
    </tr>
    <tr>
      <td>李四</td>
      <td>21</td>
      <td>85</td>
    </tr>
    <tr>
      <td>王五</td>
      <td>23</td>
      <td>95</td>
    </tr>
  </tbody>
</table>
  </body>

