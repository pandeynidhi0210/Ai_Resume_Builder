1. Landing Page
The user opens the AutoCV website.
The home page introduces the AI Resume Generator.
The user clicks the "Get Started" button to begin creating a resume.
2. AI Resume Description Input
The user enters a detailed description about themselves in natural language.
Example includes:
Education
Skills
Experience
Projects
Certifications
Career Objective
The user clicks Generate Resume.
3. AI Processing (OpenAI API)
The frontend sends the user's description to the Spring Boot backend.
The backend calls the OpenAI API.
The AI analyzes the description and extracts structured resume information such as:
Personal Details
Professional Summary
Skills
Education
Experience
Projects
Certifications
Achievements
Languages
Interests
4. Resume Form Auto-Fill
The AI-generated data is returned from the backend.
All resume fields are automatically filled in the editable resume form.
Users can:
Modify generated content
Add new sections
Remove unwanted entries
Update information before finalizing
5. Resume Submission
After reviewing the generated content, the user clicks Submit.
The application validates the data.
The structured resume information is stored in the MySQL database.
6. Resume Preview
The backend fetches the stored data.
The resume is rendered using a professional HTML/CSS template.
Users can preview the complete resume before downloading.
7. PDF Generation
When the user clicks Print/Download, the Spring Boot backend converts the HTML resume into a PDF.
A professional ATS-friendly resume PDF is generated.
8. Download Resume
The generated PDF is automatically downloaded.
The user receives a ready-to-use resume that can be submitted for job applications.

![image alt](https://github.com/pandeynidhi0210/Ai_Resume_Builder/blob/a5282395332c60c3c52ace0e382ea0eac59498fb/Landing_page.png)



<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> </p>
