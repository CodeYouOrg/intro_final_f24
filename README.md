# Code:You Intro Final Repo

**This assignment has *multiple* steps. Please *read* the steps *completely* and *thoroughly*. You may need to review, research, problem solve, and ask questions.**

![Starting Screenshot](https://github.com/CodeYouOrg/intro_final_f24/blob/main/mockup-start.jpg?raw=true)
*Screenshot of the start of the project with no changes made.*

## **Overview:**

You are tasked with updating and syncing the repository with updated information. (factual or fictional).

- [ ] Fork the repository.
- [ ] Clone the repository to your computer.
- [ ] Open the files in your code or text editor.
- [ ] Replace the placeholder image with another photo.
- [ ] Change button color to another color.
- [ ] Update name and bio text.
- [ ] Add JavaScript alert box.
- [ ] Modify JavaScript.
- [ ] Sync changes to GitHub.
- [ ] Turn in assignment.

## Instructions for Customizing Your Repo and Syncing to GitHub

### **Objective:**

Update the website with information.

### 1. **Fork the Repo**

1. Click the **Fork** button in the top right corner of the repository to create your own copy.
2. This will create a forked copy in your own GitHub account.

### 2. **Clone the Repo to Your Computer**

1. On your GitHub page, go to the newly forked repository.
2. Click the green **Code** button and copy the URL (either HTTPS or SSH).
3. Open **Git Bash** or **Terminal** and navigate to where you want to save the project:

   ```bash
   cd ~/Documents/Projects
   ```

4. Clone the repo to your local machine:

   ```bash
   git clone <URL you copied>
   ```

   Replace `<URL you copied>` with the repo URL.

### 3. **Open the Files in Your Code Editor**

1. Navigate to the project folder:

   ```bash
   cd <your-repo-name>
   ```

2. Open the project files:

   - Open the project in **Visual Studio Code** (VS Code), if it's installed.
   - Alternatively, open the `index.html` file in **Notepad** (Windows) or **TextEdit** (macOS).

### 4. **Replace the Placeholder Image with Another Photo**

1. **Download** or use your own photo and save it in the project’s `img` folder.
   - Make sure the `img` folder exists. If not, create it:
     - In the project folder, create a folder named `img`.
     - Move your image file into this folder.

2. In `index.html`, replace the placeholder image (`https://via.placeholder.com/150`) with your own:

   ```html
   <img src="img/your-photo.jpg" alt="Your Name">
   ```

   - Replace `your-photo.jpg` with the actual filename of your image.

### 5. **Change the Button Color to Green**

1. Open the `styles.css` file in your editor.
2. Find the `.link-btn` class in the CSS file:

   ```css
   .link-btn {
       background-color: #007bff; /* current blue color */
   }
   ```

3. Replace `#007bff` (the blue color) with a hex code for green.

   ```css
   background-color: #229954; /* new green color */
   ```

   - This changes the button to green.

### 6. **Update Name and Bio**

1. In `index.html`, locate this section:

   ```html
   <h2>John Doe</h2>
   <p>Hi, I'm John, a passionate software developer...</p>
   ```

2. Replace `John Doe` with your own name and update the bio text to reflect your personal details.

### 7. **Add a JavaScript Alert**

1. Open the `index.html` file and locate the `<body>` tag.
2. Just before the closing `</body>` tag, add the following JavaScript code to display an alert box:

   ```html
   <script>
       alert("Hello world");
   </script>
   ```

3. Save the file and open `index.html` in a browser. You should see a pop-up that says "Hello world". [More Information on Opening a HTML file](#Turn-In-Assignment-in-Google-Classroom)

### 8. **Modify the JavaScript Alert**

1. In the same `<script>` tag, change the alert text to display "Hello World, I'm a Developer":

   ```html
       alert("Hello World, I'm a Developer");
   ```

2. Save the file and refresh the browser to see the new alert.

### 9. **Sync Your Changes to GitHub**

1. After making the changes, open **Git Bash** or **Terminal**.
2. Make sure you are in the project folder:

   ```bash
   cd ~/Documents/Projects/<your-repo-name>
   ```

3. Check the current status of your changes:

   ```bash
   git status
   ```

4. Add the modified files:

   ```bash
   git add .
   ```

5. Commit the changes with a message:

   ```bash
   git commit -m "Updated bio, image, button color, and added JavaScript alert"
   ```

6. Push the changes to GitHub:

   ```bash
   git push origin main
   ```

   - This will sync your changes to your GitHub repository.

### 10. Turn In Assignment in Google Classroom

1. Login to Google Classroom.
2. Turn in assignment.

---

## Instructions for Opening HTML file in a Browser to Check Changes

After making changes to your `index.html` file, follow these steps to open it in a browser and verify that your updates are working:

### 1. **Open file in a Browser**

#### **Open the `index.html` File**
  
1. Locate the `index.html` file. (`~\Documents\Projects\<your-repo-name>`)
2. Right-click (or Control-click) on the `index.html` file.
3. Choose **Open With** and select a browser (e.g., Edge, Safari, Chrome, Firefox).

You will need to save your file and refresh(F5) the page every time you make changes to the html, css files.

#### **OR**

#### **Visual Studio Code with Live Server Plugin (Alternative)**

Live Server installation: https://code-you.org/students/resources/guides/install-live-server-in-vs-code/

- If your code editor is **Visual Studio Code** and the "*Live Server*" extension is installed, you can also:
  1. Right-click `index.html` in the VS Code file explorer.
  2. Select **Open with Live Server**. This will automatically open the file in your default browser.

### 2. **View Your Changes**

- Once opened, you should see your bio with the updated image, green buttons, and JavaScript alert message pop up.
  
- If the browser does not refresh automatically after you make changes, press **Ctrl + R** (Windows) or **Command + R** (macOS) to refresh the page and load the latest version.

This will let you see all the changes made to the page in real time.
#intro_final_f24
