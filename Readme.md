# Task Management

<p align="center">
  <b style="color: blue;  ">Visitor count</b>
  <br>
  <a style="" href="https://github.com/akashdeep023">
  <img src="https://profile-counter.glitch.me/task-management/count.svg" />
  </a>
</p>

## A task management app, where users can organise their personal and team-based tasks, track progress, and share task updates. Users can manage their task boards with features to create, edit, assign, and delete tasks for themselves and other members.


<p align="center">Register Page</p>
<a style="" href="https://task-management-org.vercel.app/login">
     
![Macbook-Air-localhost (1)](https://github.com/user-attachments/assets/d05bd3e9-e349-469b-a4d2-d828e3e76414)

</a>
<p align="center">Dashboard Page</p>
<a style="" href="https://task-management-org.vercel.app/">
     
![Macbook-Air-localhost](https://github.com/user-attachments/assets/5643d5a6-b8ad-4516-a3dd-d12b0d9793e3)

</a>
<p align="center">Public View</p>
<a style="" href="https://task-management-org.vercel.app/task/67421bb3a90e252d2d4cb42e">
     
![Macbook-Air-localhost (2)](https://github.com/user-attachments/assets/cde4fcb3-80c4-410d-9763-50281c9b2233)

</a>

---

## Checklist:

-   Users can register and log in to the platform; only authenticated users can create and manage tasks.
-   Users can create tasks with properties such as priority, optional due dates, task categories, and can share their tasks with others. Shared tasks will have read-only public access.
-   Users can update their personal information, including their name and password. For password changes, both old and new passwords are required.
-   An analytics section is available to review data for all tasks created by users on the platform.
-   Users can manually change the status of tasks across four categories: backlog, to-do, in-progress, and done.
-   When a task passes its due date, its card’s due date will turn red in the backlog, to-do, or in-progress sections.
-   If a task is marked as done, the due date will change to green. If it is moved back to an active state, the color will revert to red or gray based on the due date.
-   Users can delete tasks.
-   Users can edit existing tasks.
-   Users can filter tasks by today, this week, or this month. By default, the app will filter tasks for the current week.
    Toast messages will appear for notifications and alerts throughout the app.
-   Mandatory fields for creating tasks include title, priority, and checklist. Due dates are optional.
-   Task titles displayed on the task board will be truncated with “…” if they exceed a certain character limit. Hovering over the title will display the full title using a tooltip or HTML title attribute.
-   Mandatory fields will be marked with a red asterisk (\*).
    Filters for tasks will define “this week” and “this month.
    Users can add members to their task boards and assign them to different tasks during creation.
-   If a user updates their email or password, they will be logged out of the system after the update.
-   The settings page will have pre-filled user information, including name and email, with options to update them.
-   Users can update either their name, email, or password (with both old and new passwords) on the settings page.

---

## Environment Variables

-   backend/.env

```bash

MONGODB_URI=mongodb://127.0.0.1:27017/task_management
FRONTEND_URL=http://localhost:5173
PORT=9000
JWT_SECRET=secret-kJKJllKKJJghLjOiUfcHGkMLgdJlLKDtrdyKLBJbRdesEkj

```

-   frontend/.env

```bash

VITE_BACKEND_URL=http://localhost:9000
VITE_FRONTEND_URL=http://localhost:5173

```
