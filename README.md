## Bookings and Reservations

# Situation:  
Need to have experiences about GoLang

# Task:  
Build a bed & breakfast inn web project that has search reservation and make reservation 

# Action:

Need following packages:

•	Interface with database (server-side session), plan to use PostgreSQL
•	A router for building Go HTTP services.
•	Prevent Cross-Site Request Forgery attacks (for security to protect make reservation transaction)

Research on Google/Github/Stack Overflow, found the following packages with examples:

	github.com/alexedwards/scs/v2 v2.5.0 // indirect
	github.com/go-chi/chi/v5 v5.0.7 // indirect
	github.com/justinas/nosurf v1.1.1 // indirect

# Result:
Complete the full stack application that has 

•	Front end (HTML, Javascript, css)
•	Middleware:
      		Interface with database (server-side session)
     		 A router for building Go HTTP services
•	Database, which is PostgreSQL

![image](https://github.com/user-attachments/assets/ef51bd5e-2f2d-4f78-a3d9-de7bf0aeafd7)


This is the repository for my bookings and reservations project.

- Build in Go version 1.15
- Uses the [chi router](https://github.com/go-chi/chi)
- Uses [alex edwards SCS](https://github.com/alexedwards/scs/v2) session management
- Uses [nosurf](https://github.com/justinas/nosurf)
