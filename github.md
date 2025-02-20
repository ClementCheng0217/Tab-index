---
layout: page
title: Leaderboard
permalink: /board/
---

# 可排序表格示例

以下是一个支持列名排序的表格：

<table id="sortableTable">
    <thead>
        <tr>
            <th colspan="3">Information</th>
        </tr>
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
    function sortTable(columnIndex) {
        const table = document.getElementById("sortableTable");
        const tbody = table.querySelector("tbody");
        const rows = Array.from(tbody.querySelectorAll("tr"));

        // 判断当前排序方向
        const isAscending = table.getAttribute(`data-sort-direction-${columnIndex}`) === "asc";
        const newDirection = isAscending ? "desc" : "asc";
        table.setAttribute(`data-sort-direction-${columnIndex}`, newDirection);

        // 排序逻辑
        rows.sort((rowA, rowB) => {
            const cellA = rowA.querySelectorAll("td")[columnIndex].textContent.trim();
            const cellB = rowB.querySelectorAll("td")[columnIndex].textContent.trim();

            if (!isNaN(cellA) && !isNaN(cellB)) {
                // 如果是数字，按数字排序
                return isAscending ? cellA - cellB : cellB - cellA;
            } else {
                // 如果是文本，按字母排序
                return isAscending ? cellA.localeCompare(cellB) : cellB.localeCompare(cellA);
            }
        });

        // 清空并重新插入排序后的行
        tbody.innerHTML = "";
        rows.forEach(row => tbody.appendChild(row));
    }
</script>
