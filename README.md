# Student Attendance Manager

An all-in-one student attendance manager built with HTML, CSS, and JavaScript. This application allows you to manage students (CRUD operations), mark daily attendance with a date picker, and export attendance data to a CSV file. All data is stored locally using `localStorage`, ensuring privacy and persistence between sessions.

## Features

- **Student Management (CRUD):**
  - **Create:** Add new students with name and registration number.
  - **Read:** View a list of all students.
  - **Update:** Edit existing student information.
  - **Delete:** Remove students from the list.

- **Daily Attendance Tracking:**
  - Select a date using the date picker.
  - Mark students as present or absent for the selected date.
  - Attendance data is stored per date.

- **Export to Excel-Compatible CSV:**
  - Export all attendance data to a CSV file.
  - The CSV includes date, student name, registration number, and attendance status.

- **Local Data Storage:**
  - All data is stored in `localStorage`, ensuring persistence between sessions.

- **Single File Application:**
  - The entire application is contained within one HTML file.

## How to Use

1. **Download the Project:**
   - Clone the repository or download the `index.html` file.

2. **Open the Application:**
   - Open the `index.html` file in a modern web browser (Chrome, Firefox, etc.).

3. **Add Students:**
   - Click the **"Add Student"** button to open the student form.
   - Enter the student's name and registration number.
   - Click **"Save"** to add the student to the list.

4. **Edit or Delete Students:**
   - In the **Students** table, use the **"Edit"** button to modify a student's information.
   - Use the **"Delete"** button to remove a student from the list.

5. **Mark Attendance:**
   - Select a date using the **"Select Date"** date picker. It defaults to today's date.
   - The **Daily Attendance** table will display all students.
   - Use the checkboxes to mark each student as present or absent.
   - Changes are saved automatically in `localStorage`.

6. **Export Data to Excel (CSV):**
   - Click the **"Export Attendance to CSV"** button to download the attendance data.
   - The file `attendance.csv` will be downloaded, which can be opened in Excel.

7. **Data Persistence:**
   - All data is stored in your browser's `localStorage`.
   - Your data will remain intact even after refreshing or closing the browser, as long as you use the same browser on the same device.

## Technologies Used

- **HTML5**: Structure of the application.
- **CSS3**: Styling and layout.
- **JavaScript**: Functionality and interactivity.
- **LocalStorage**: Data persistence in the browser.
- **CSV Export**: Exporting data to a CSV file for Excel compatibility.

## Customization

- **Styling:**
  - Modify the CSS within the `<style>` tags to change fonts, colors, and layout.

- **Additional Fields:**
  - To add more fields to the student data (e.g., class, section), update the student form, data structure, and rendering functions accordingly.

- **Validation:**
  - Currently, basic validation checks for empty fields.
  - You can enhance validation as needed (e.g., unique registration numbers).

## Limitations

- **Browser Compatibility:**
  - Use a modern browser that supports `localStorage` and the standard HTML5 APIs.

- **Data Portability:**
  - Since data is stored locally, it doesn't sync across devices or browsers.
  - To transfer data, you can export the CSV and import it into another instance manually.

- **Privacy Note:**
  - Data is stored unencrypted in the browser's `localStorage`.
  - Be cautious when using the application on shared computers.

## License

This project is open-source and available under the [MIT License](LICENSE).
