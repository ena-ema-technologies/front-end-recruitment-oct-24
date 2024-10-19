### **"Dynamic Task Management Application with Basic Backend Integration"**

---

### Important Notice:

    - You can ignore this assessment task, if you are not agree with our offered salary 10,000 - 12,500 BDT
    - Please note: Completing the task does **not** guarantee that you will move on to the next step. Conversely, not completing the task **does not** necessarily mean you won’t proceed.
    - If you have not completed the entire task, that’s acceptable. We value the quality and effort you put into the part you did complete. If it shows you genuinely tried and worked hard on  your own, you may still move on to the next step.

---

**Task overview:**
Develop a Task Management application focusing on frontend development using Next.js while integrating a simple backend. The goal is to provide a dynamic, interactive, and user-friendly interface for managing tasks. The task evaluates your skills in frontend development with Next.js, UI design using raw CSS (without libraries), state management with Redux Toolkit, and basic API integration. Aim to structure the backend logically and handle API effectively, ensuring a seamless user experience in this single-page application.

**Functional Requirements:**

1. **Task Creation:**

   - Users should be able to create custom tags when adding a task.
   - Tasks should be added to the task list and stored in the backend (Node.js, Express, MongoDB).
   - Basic validation for each field (e.g., task name is required, due date must be in the future).
   - Users must input the task name, description, due date, priority level (low, medium, high), and category tags (e.g., Work, Personal, Shopping).

2. **Task List Display:**

   - Display tasks dynamically in a list showing the task name, due date, priority, and tags.
   - Color-code tasks based on priority:
     - Low: Green
     - Medium: Yellow
     - High: Red
   - Each task should include options for **Edit**, **Delete**, and a **Mark as Complete** button.
   - Completed tasks should be styled differently (e.g., strikethrough or greyed out) and moved to the bottom of the list.

3. **Task Filtering and Searching:**

   - Users can filter tasks based on:
     - Status (All, Completed, Pending)
     - Priority (Low, Medium, High)
     - Custom category tags
   - Users should be able to search tasks by keyword in the task name or description.
   - Filtered and searched tasks should update dynamically in real-time.

4. **Task Editing:**

   - Allow users to edit tasks with pre-filled existing values.
   - Users can change any field, including the category tags.
   - Changes should update the frontend and sync with the backend.

5. **Task Deletion with Undo Option:**

   - Implement an "Undo" option for task deletion. After a task is deleted, show a notification allowing users to restore it within 5 seconds.
   - If users do not undo within the timescale, the task should be permanently deleted from the backend.

6. **Simple Task Reminders:**

   - Add a reminder toggle for each task (on/off). If toggled on, highlight tasks nearing their due date (e.g., due in less than 24 hours) using a visual indicator (e.g., different border color).

7. **Task Categories View:**

   - Allow users to view tasks grouped by their category tags (e.g., All, Work, Personal).
   - Display each group in a collapsible section that users can expand/collapse.

8. **Redux Toolkit for State Management:**

   - Use Redux Toolkit to manage the application state efficiently.
   - Define actions and reducers using createSlice to handle tasks, including creation, updates, deletion, filtering, and reminders.
   - Utilize the built-in redux-thunk middleware for effectively managing asynchronous operations and interactions with the backend API.
   - Ensure that Redux slices are well-organized and located in appropriate directories to maintain a clean and maintainable codebase.

9. **Responsive and Accessible Design:**

   - Ensure the application is fully responsive and works seamlessly on both desktop and mobile devices.
   - Follow accessibility best practices (e.g., ARIA roles, keyboard navigation, etc.).
   - Style the application using either plain CSS to create a modern, user-friendly design.

**Backend Integration:**

- The backend should be built using Node.js and Express.js, with MongoDB for data storage.
- Create simple API endpoints for:
  - Creating a task (`POST /api/tasks`)
  - Retrieving tasks (`GET /api/tasks`)
  - Updating a task (`PUT /api/tasks/:id`)
  - Deleting a task (`DELETE /api/tasks/:id`)
- Document the API endpoints in the README.

**Restrictions:**

- Please don't use any CSS libraries
- Please use Next.js as frontEnd frameworks
- Please make this a single-page application
- Style your application using raw CSS / inline styles

**Non-Functional Requirements:**

- Code should be clean, modular, and maintainable, with appropriate comments explaining key parts.
- The application must be a single-page application and fully functional without page reloads.
- Avoid using unnecessary dependencies; only use essential packages.

**Submission Guidelines:**

- Submit the application as a Git repository, by replying the email
- Include a README file detailing the application setup, how to run it, and any known issues or limitations.
- All code must be original, and candidates should refrain from using online solutions or tutorials.

**Evaluation Criteria:**

- Quality of the frontend code and UI/UX design.
- Proper integration with the backend API endpoints and use of Redux for state management.
- Responsiveness, accessibility, and user-friendliness of the application.
- Cleanliness, modularity, and maintainability of the codebase.
- Creativity and problem-solving in adhering to task requirements.

### Timeline:

- You will have **3-4 days** to complete this task. Please send your completed task, Deployment link, by replying to the email we sent you. Thank you!
