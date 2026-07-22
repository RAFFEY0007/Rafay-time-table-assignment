# Rafay-time-table-assignment
<!DOCTYPE html>
<html>
<head>
  <title>Time Table</title>

  <!-- CSS Coding Start -->
  <style>
    body {
      font-family: Arial, sans-serif;
    }

    h2 {
      text-align: center;
    }

    table {
      border-collapse: collapse;
      margin: auto;
      width: 700px;
    }

    th, td {
      border: 1px solid black;
      padding: 12px;
      text-align: center;
    }

    th {
      background-color: #f2f2f2;
    }

    .lunch {
      background-color: #dddddd;
      font-weight: bold;
    }
  </style>
  <!-- CSS Coding End -->

</head>

<body>

  <!-- HTML Coding Start -->

  <h2>Time Table</h2>

  <table>

    <tr>
      <th colspan="6">Time Table</th>
    </tr>

    <tr>
      <th rowspan="6">Hours</th>
      <th>mon</th>
      <th>tues</th>
      <th>Wed</th>
      <th>Thrus</th>
      <th>Fri</th>
    </tr>

    <tr>
      <td>Science</td>
      <td>Maths</td>
      <td>Science</td>
      <td>Maths</td>
      <td rowspan="2">Arts</td>
    </tr>

    <tr>
      <td>Science</td>
      <td>Maths</td>
      <td>Science</td>
      <td>Maths</td>
    </tr>

    <tr>
      <td class="lunch" colspan="5">Lunch</td>
    </tr>

    <tr>
      <td>Science</td>
      <td>Maths</td>
      <td>Science</td>
      <td>Maths</td>
      <td rowspan="2">Project</td>
    </tr>

    <tr>
      <td>Science</td>
      <td>Maths</td>
      <td>Science</td>
      <td>Maths</td>
    </tr>

  </table>

  <!-- HTML Coding End -->

</body>
</html>
