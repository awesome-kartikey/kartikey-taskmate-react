# Frequently Asked Questions (FAQ)

**Q1: How is my task data stored?**

A1: Your tasks are stored directly in your web browser's `localStorage`. This means the data is saved on your local machine and tied to the specific browser you are using.

**Q2: Will my tasks remain if I close the browser or refresh the page?**

A2: Yes. Since the tasks are saved in `localStorage`, they will persist across browser sessions (closing and reopening the browser) and page refreshes, as long as you are using the same browser on the same device and haven't cleared your browser's storage.

**Q3: Can I access my tasks from another computer or browser?**

A3: No. `localStorage` is specific to the browser and device where the data was created. There is no backend server to synchronize your tasks across different devices or browsers.

**Q4: Is there a limit to how many tasks I can add?**

A4: `localStorage` typically has a storage limit of around 5-10MB per domain, which is quite large for text-based tasks. You should be able to store thousands of tasks without hitting the limit, but it's technically possible.

**Q5: How do I edit a task that I've already added?**

A5: Find the task you wish to edit in the list. Click the pencil icon (`bi-pencil-square`) next to the task. The task's current name will appear in the input field at the top. Modify the name as needed and click the "Update" button.

**Q6: How can I change the application's theme?**

A6: In the header section (top bar), you will see several small colored circles. Clicking on any of these circles will instantly change the application's theme. Your theme preference is also saved in `localStorage` and will be remembered the next time you open the app.

**Q7: What happens when I click "Clear All"? Can I undo it?**

A7: Clicking the "Clear All" button permanently removes all tasks from your list and from `localStorage`. This action cannot be undone. Please use it with caution.

**Q8: Does this application work offline?**

A8: Yes. Once the application is loaded in your browser, it works entirely offline as all data is stored locally and all logic runs in the browser. You only need an internet connection initially to load the application files.
