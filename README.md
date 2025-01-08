# **Exercise 1: Build a Simple Personal Webpage**

**Due Date:** January 20th, 11:59 PM  
**Total Marks:** 100  

---

## **Objective**

In this exercise, you will create a simple personal webpage using **HTML** and host it on **GitHub Pages** using SFU's **GitHub Enterprise** platform. This exercise will introduce you to the basics of structuring content for the web and managing version control with GitHub Desktop. The goal is to create a well-organized, visually clear webpage that highlights your skills, education, and interests.

---

## **Instructions**

### **Getting Started with GitHub Desktop**

1. **Create a New Repository on GitHub Enterprise:**
   - Navigate to [GitHub SFU](https://github.sfu.ca/).
   - Create a new repository named `E1-PersonalWebpage`.  

2. **Clone the Repository Locally Using GitHub Desktop:**
   - Open GitHub Desktop and sign in with your GitHub Enterprise account.
   - Click **File → Clone Repository**.
   - Select the `E1-PersonalWebpage` repository and choose a local folder to save it.

---

### **Building Your Website**

1. **Set Up Your Project Files Locally:**
   - Inside your cloned repository folder, create the file structure:
     ```bash
     E1-PersonalWebpage/
     └── index.html
     ```

2. **Structure Your HTML:**
   Your `index.html` should include the following sections:

   - **Header:**  
     - Your full name as the main heading (`<h1>`).  
     - A short tagline or introduction about yourself (`<p>`).  

   - **About Me Section:**  
     - A short paragraph about your background, interests, or goals.

   - **Education Section:**  
     - A list of your educational achievements using the `<ul>` or `<ol>` tag.  
     - Example:  
       - Bachelor of Science in Interactive Arts & Technology (In Progress)  
       - High School Diploma  

   - **Skills Section:**  
     - Use an HTML table (`<table>`) to display your skills.  
     - Example:  

       | Skill            | Proficiency   |  
       |------------------|---------------|  
       | HTML             | Beginner      |  

   - **Contact Section:**  
     - Provide a way for visitors to contact you, such as an email address or a link to your GitHub profile. Use appropriate tags like `<a>` for links.  

   - **Footer:**  
     - Add a copyright notice (e.g., "© 2025 Your Name").  

---

### **Pushing Your Changes with GitHub Desktop**

1. **Stage and Commit Your Changes:**
   - After creating your `index.html` file, open GitHub Desktop.
   - You should see your changes listed in the "Changes" tab.
   - Write a meaningful commit message (e.g., "Add index.html with basic structure") and click **Commit to main**.

2. **Push Your Changes to GitHub Enterprise:**
   - Click **Push origin** to upload your changes to the remote repository.

---

### **Enable GitHub Pages**

1. Go to your repository on [GitHub SFU](https://github.sfu.ca/).  
2. Click on **Settings** → **Pages**.  
3. Under **Source**, select the `main` branch and click **Save**.  
4. Your webpage will be accessible at `https://github.sfu.ca/yourusername/E1-PersonalWebpage`.

---

## **Submission Instructions**

1. **Submit Your GitHub Repository Link:**
   - Copy the link to your repository on GitHub SFU (e.g., `https://github.sfu.ca/yourusername/E1-PersonalWebpage`) and submit it on the **Exercise 1** submission page on Canvas.

2. **Ensure the Webpage is Live:**
   - Make sure your GitHub Pages site is live and accessible via the link `https://github.sfu.ca/yourusername/E1-PersonalWebpage`.

---

## **Tips**

- **Focus on Structure:** Don't worry about styling or interactivity for now; we’ll cover those in later exercises.
- **Commit Often:** Save your progress frequently with meaningful commit messages.

---

## **Marking Rubric (100 Marks)**

| **Criteria**                      | **0%**                  | **25%-75%**                  | **100%**                  | **Marks** |
|-----------------------------------|------------------------------|------------------------------|------------------------------|-----------|
| **Correct use of HTML structure** | Minimal HTML structure with missing tags or poor hierarchy. | Adequate structure with minor issues or redundancies. | Well-organized and semantic HTML with proper hierarchy. | 25       |
| **Inclusion of all required sections (Header, About, Education, Skills, Contact, Footer)** | Few sections included or incomplete content. | Most sections included with relevant content but missing minor details. | All sections present, detailed, and well-organized. | 50      |
| **Hosted webpage is live on GitHub Pages** | Website not live or link broken. | Website live but with errors (e.g., broken links). | Website live, functional, and error-free. | 25       |

---

## **Learning Resources**

- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)  
- [MDN Web Docs: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)  
- [GitHub Pages Documentation](https://docs.github.com/en/pages)  
- [GitHub Desktop Documentation](https://docs.github.com/en/desktop)  
