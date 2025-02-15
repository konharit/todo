# todo
@@ -0,0 +1,29 @@
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>To-Do List Web App</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>To-Do List Web App</h1>
    <div class="form-section">
      <input type="text" id="taskTitle" placeholder="Title" required>
      <textarea id="taskDescription" placeholder="Description" required></textarea>
      <button id="addTaskBtn">Add Task</button>
    </div>
    <div class="list-section">
      <h2>Pending Tasks</h2>
      <ul id="pendingTasksList"></ul>
      <h2>Completed Tasks</h2>
      <ul id="completedTasksList"></ul>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
