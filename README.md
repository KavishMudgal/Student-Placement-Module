# Student-Placement-Module

## What it does?
This is a Django-based web application that implements a **student placement management system**.  
The project allows **students to view and apply for job openings**, while the **admin can create, manage, and monitor placements** through a centralized dashboard.

It is designed to demonstrate **CRUD operations, authentication, role-based access, and database management** using the Django framework, making it suitable for **college projects, internships, and portfolio showcasing**.

**Keywords:** Django, Python, Placement Module, Student Management System, Job Portal, Web Application, CRUD, Admin Dashboard

## Instructions to use
Clone the repository:
$bash ~~
   >>>git clone <your-repo-url>
      cd Student-Placement-Module
      python -m venv .venv
      .venv\Scripts\activate          # For Windows. "source .venv/bin/activate" for Linux/Mac
      pip install -r requirements.txt
   
   >>>python manage.py migrate
      python manage.py createsuperuser
      python manage.py runserver

## Known Issues

* **Resume uploading is not fully efficient**  
  The resume upload feature currently works in a basic manner, but the field is not marked as required. When it is set as required, the system forces students to re-upload their resume every time they update their profile, which needs to be handled more efficiently.

* **Dashboard is not completed yet**  
  The dashboard page is still under development. The plan is to integrate a Power BI dashboard with live user interactions to provide better insights and analytics.


* **Admin needs to have more authority**  
  Admin controls are currently limited. Features like approving/rejecting applications, managing users, and role-based permissions need to be enhanced.

* **UI/UX can be improved**  
  The user interface is functional but basic. Responsiveness, layout consistency, and overall user experience can be improved.
  

## What's to come

* **Dedicated dashboards for admin and students**  
  Separate dashboards will be implemented to give students a clear view of applications and job status, and admins a centralized view of postings, applications, and system activity.

* **REST API integration**  
  A RESTful API using Django REST Framework (DRF) will be added to support frontend integration, mobile apps, and third-party services.


## Wanna Help?

* You are welcome to add new features or fix existing bugs
* Please follow clean coding practices and commit changes with clear messages
* Create a pull request for review before merging changes
* Suggestions and improvements are always appreciated







