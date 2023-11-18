# TASK3-CODEALPHA
<!DOCTYPE html>
<html lang="en">

<head>
</head>

  <meta charset="UTF-8">
  <title>Issue Tracker System</title>

  <!-- Include CSS -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Issue Tracker System</h1>

    <!-- Issue Creation Form -->
    <form id="issueForm">
      <input type="text" id="title" placeholder="Issue Title">
      <textarea id="description" placeholder="Issue Description"></textarea>
      <select id="priority">
        <option value="low">Low</option>
        <option value="medium">Medium</option>
        <option value="high">High</option>
      </select>
      <input type="file" id="attachment">
      <button type="button" onclick="createIssue()">Create Issue</button>
    </form>

    <!-- Display Issues -->
     <div id="issueList">

      <!-- Issues will be displayed here -->
      </div>
  </div>

  <!-- Include JavaScript -->
  <script src="script.js"></script>

</body>
</html>
