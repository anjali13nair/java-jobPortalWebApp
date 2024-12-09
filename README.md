# Job Portal Web Application

Welcome to the **Job Portal Web Application** repository! This project is a dynamic platform built using **Spring Boot 3**, **Spring MVC**, **Thymeleaf**, **Hibernate/JPA**, and **Spring Security**. It is designed to streamline the process of job recruitment and job searching, providing separate functionalities for **Recruiters** and **Job Candidates**.

---

## Features and Functionalities

### Recruiter Features:
- **Post New Job**: Create and publish job openings for potential candidates.  
- **View Our Jobs**: See the list of jobs you have posted.  
- **View List of Applicants**: Check the details of candidates who have applied for a specific job.  
- **Edit Profile**: Update your profile details and upload a profile photo.  

### Candidate Features:
- **Search for Jobs**: Browse and search for jobs that match your preferences.  
- **Apply for Jobs**: Submit applications for jobs of interest.  
- **View Applied Jobs**: Review the list of jobs you have applied for.  
- **Edit Profile**: Update your profile details and upload a profile photo.  
- **Upload Resume/CV**: Attach your resume or CV for recruiters to review.  

---

## Technology Stack
The project is developed using the following technologies and tools:
- **Backend**: Spring Boot 3, Spring MVC, Hibernate/JPA  
- **Frontend**: Thymeleaf (server-side rendering)  
- **Security**: Spring Security  
- **Database**: MySQL  
- **Build Tool**: Maven  

---

## How to Run the Application
1. **Clone the repository**:
   ```bash
   git clone https://github.com/anjali13nair/java-jobPortalWebApp.git
   cd java-jobPortalWebApp
2. **Configure the database**:
   - Update the `application.properties` file located in the `src/main/resources` directory with your MySQL credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/job_portal
     spring.datasource.username=<your-username>
     spring.datasource.password=<your-password>
     ```
   - Run the SQL scripts to set up the database schema and initial data:
     - **Step 1**: Create a database named `job_portal` in MySQL:
       ```sql
       CREATE DATABASE job_portal;
       ```
     - **Step 2**: Use the provided SQL scripts `create-user.sql` and `jobPortal.sql` located in the `src/main/resource` directory or write your schema and insert statements to create the required tables and populate sample data according to your requirements.  
   - Ensure the database server is running before starting the application.
---

## Future Enhancements
Here are some features and improvements planned for future updates:
- **Advanced Search Filters**: Enable candidates to search for jobs based on location, skills, experience, and salary range.
- **Job Recommendations**: Use AI algorithms to recommend jobs based on candidate profiles and preferences.
- **Recruiter Notifications**: Notify recruiters via email or the application dashboard when candidates apply for their jobs.
- **Two-Factor Authentication**: Enhance security by adding two-factor authentication for both recruiters and candidates.

---

## Contribution
We welcome contributions to make this project better! Here's how you can contribute:
1. **Fork** the repository by clicking the "Fork" button at the top of this page.
2. **Clone** your forked repository:
   ```bash
   git clone https://github.com/<your-username>/java-jobPortalWebApp.git
3. **Build the application**:
   - Open a terminal and navigate to the root directory of the project.
   - Run the following command to build the application:
     ```bash
     mvn clean install
     ```

4. **Run the application**:
   - Start the application using the Spring Boot Maven plugin:
     ```bash
     mvn spring-boot:run
     ```

5. **Access the application**:
   - Once the application starts successfully, open your browser and navigate to:
     ```text
     http://localhost:8080
     ```

6. **Test the application**:
   - Use the application as a recruiter or candidate:
     - **Recruiter**: Log in to post jobs, view applicants, and manage your profile.
     - **Candidate**: Search for jobs using job title or location, apply, manage profile and upload your resume.

---

## Contact
If you have any questions, suggestions, or feedback, feel free to reach out:  
- **GitHub**: [@anjali13nair](https://github.com/anjali13nair)
- **Email**: anjalinnair13@gmail.com
- **LinkedIn**:[Anjali Nair](https://www.linkedin.com/in/anjalinnair13/)

