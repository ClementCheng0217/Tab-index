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
            <th colspan="3" class="group-header">People</th>
        </tr>
        <!-- 原有表头行 -->
        <tr>
            <th onclick="sortTable(0)">Name</th>
            <th onclick="sortTable(1)">Age</th>
            <th onclick="sortTable(2)">City</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John Doe</td>
            <td>28</td>
            <td>New York</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>34</td>
            <td>Los Angeles</td>
        </tr>
        <tr>
            <td>Mike Johnson</td>
            <td>45</td>
            <td>Chicago</td>
        </tr>
        <tr>
            <td>Anna Lee</td>
            <td>29</td>
            <td>Houston</td>
        </tr>
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
