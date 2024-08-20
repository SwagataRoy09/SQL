# SQL
<!DOCTYPE html>
<html>
Detailed schema and notes to understand SQL and practice from beginner to advanced
<head>
<style> 
table {
        border: solid 1px #aaa999;
        border-collapse: collapse;
        border-spacing: 0;
      }
      table tr th {
        border: solid 1px #aaa999;
      }
      table tr td {
        border: solid 1px #aaa999;
        }
      caption{
        font-size : 20px
      }
</style>
</head>
<body>
<H1> Relational Model </H1>
<H2> Schemas we consider for example </h2>
<table>
<caption>Customer Relation
  <tr>
    <th>Customer_id</th>
    <th>Customer_name</th>
    <th>Customer_street</th>
    <th>Customer_city</th>
  </tr>
  <!first>
  <tr>
    <td>1</td>
    <td>Johnson</td>
    <td>12 Alma Street</td>
    <td>Palo Alto</td>
  </tr>
  <!second>
  <tr>
    <td>1</td>
    <td>Hayes</td>
    <td>3 Main St</td>
    <td>Palo Alto</td>
  </tr>
</table>
<!-- Symbols and names of symbols-->
<table>
<tr>
<th> Operation 
<th> Symbol
</tr>
<tr>
<td>Select
<td><strong>σ
</tr>
<tr>
<td>And
<td><strong>^
</tr>
<tr>
<td>Or
<td><strong>
</tr>
<tr>
<td>Not
<td>
</tr>
<tr>
<td>Projection
<td><strong>π
</tr>
<tr>
<td>Union
<td><strong>U
</tr>
<tr>
<td>Intersection
<td><strong>∩
</tr>
<tr>
<td>Set Difference
<td><strong>-
</tr>
<tr>
<td>Cartesian Product
<td><strong>X
</tr>
<tr>
<td>Rename
<td><strong>ρ
</tr>
<tr>
<td>Natural Join
<td><strong>⋈
</tr>
<tr>
<td>Full Outer Join
<td>
</tr>
<tr>
<td>Right Outer Join
<td>
</tr>
<tr>
<td>Left Outer Join
<td><strong>⟕
</tr>
</body>
</html>