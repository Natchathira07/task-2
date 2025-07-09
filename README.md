# task-2
#code
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Create Project and Task</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: url('https://cdn.pixabay.com/photo/2017/08/06/01/54/music-2588667_1280.jpg') no-repeat center center fixed;
      background-size: cover;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .form-container {
      background-color: rgba(0, 0, 0, 0.7);
      color: white;
      padding: 35px 40px;
      border-radius: 15px;
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.6);
      width: 90%;
      max-width: 500px;
      backdrop-filter: blur(6px);
    }

    h1, h2 {
      text-align: center;
      color: #ffeb3b;
    }

    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
      color: #ddd;
    }

    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 6px;
      border: none;
      border-radius: 6px;
      font-size: 14px;
      box-sizing: border-box;
      background-color: #f9f9f9;
      color: #000;
    }

    button {
      margin-top: 25px;
      padding: 12px;
      background-color: #ff4081;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      width: 100%;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #f50057;
    }
  </style>
</head>
<body>
  <div class="form-container">
    <h1>Create a New Project</h1>
    <form method="post">
      

      <label for="project_name">Project Name:</label>
      <input type="text" id="project_name" name="project_name" required>

      <h2>Add Task</h2>

      <label for="task_title">Task Title:</label>
      <input type="text" id="task_title" name="task_title" required>

      <label for="task_status">Status:</label>
      <select id="task_status" name="task_status">
        <option value="pending">Pending</option>
        <option value="in_progress">In Progress</option>
        <option value="completed">Completed</option>
      </select>

      <label for="due_date">Due Date:</label>
      <input type="date" id="due_date" name="due_date" required>

      <button type="submit">🚀 Create Project and Task</button>
    </form>
  </div>
</body>
</html>
```
#output
![Screenshot 2025-07-09 134857](https://github.com/user-attachments/assets/d268c118-42f4-47f8-a52e-99db180230a6)



