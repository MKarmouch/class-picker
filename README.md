# 🎓 Student Picker Tool

A professional, cloud-synced tool designed for teachers to randomly select students for activities, questions, or groups. 

Built with **React** and powered by **Firebase**, this tool allows teachers to manage multiple classes and ensures that student data is saved securely in the cloud.

---

### ✨ Key Features

*   **Secure Teacher Login:** Sign in with Google or Email to access your private data from any device.
*   **Multiple Classes:** Create and manage different classes (e.g., Grade 6-A, Grade 7-B).
*   **Smart Drawing:** 
    *   Pick 1 to 10 students at a time.
    *   **"No-Repeat" mode:** The tool remembers who was already picked until the whole class has participated.
*   **Easy Data Entry:** Import your student lists via CSV files or type them in manually.
*   **History Log:** View a record of the most recent draws for each class.

---

### 🚀 How to Use

1.  **Sign In:** Open the tool and click "Continue with Google" or create an account with your email.
2.  **Add a Class:** Type your class name (e.g., *Math 101*) in the sidebar and click **Add Class**.
3.  **Add Students:** 
    *   Select your class from the list.
    *   Use the **Manual Add** box to paste names (one per line or separated by commas).
    *   Or, upload a **CSV file** with your student roster.
4.  **Start Picking:** 
    *   Choose how many students you want to pick (1-10).
    *   Click the **Draw Names** button.
    *   The tool will animate and display the selected students on the screen.
5.  **Manage:** Use the **Undo** button if you made a mistake, or **Reset** the pool once every student has had a turn.

---

### 🔒 Privacy & Security

This tool respects teacher privacy. Your student lists are stored in a private Firebase database. Only **you** can see the data for the classes you create. No data is shared with third parties.

---

### 🛠 Technical Details

*   **Frontend:** React.js, Tailwind CSS
*   **Backend:** Firebase Authentication & Firestore Database
*   **Hosting:** GitHub Pages
*   **Domain:** [picker.karmouch.me](https://picker.karmouch.me)

**Developed by:** Mehdi Karmouch
