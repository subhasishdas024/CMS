Here's task description :
--------------------------------

Looking for an individual to develop a CMS solution on which:

There will be two types of user:

1- Student

2- Institution

- Student can register and apply for admissions in multiple institutions

- Student can search for institutes/courses/scholarships

- Institutes can add and manage courses

- Institutions can view the student applications, accept or reject those applications. If an application is accepted, the institution should be able to send an offer letter to the student

- There should be a separate Dashboard for the Student and Institution

---

![Laravel students courses list](https://laraveldaily.com/wp-content/uploads/2019/11/Screen-Shot-2019-11-05-at-9.46.36-AM.png)

![Laravel students registration form](https://laraveldaily.com/wp-content/uploads/2019/11/Screen-Shot-2019-11-05-at-9.48.27-AM.png)

![Laravel students adminpanel](https://laraveldaily.com/wp-content/uploads/2019/11/Screen-Shot-2019-11-05-at-9.47.36-AM.png)

---

## Procedures:

- First Clone the repository using git clone
- Then Copy __.env.example__ file to __.env__ and edit database credentials there
- After that Run __composer install__
- Then Run __php artisan key:generate__
- Finally Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- You can login to adminpanel by going go `/login` URL and login with credentials __admin@admin.com__ - __password__ or institution user __institution@institution.com__ - __password__ 

---

