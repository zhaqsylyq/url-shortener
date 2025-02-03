Full Stack URL shortening Application using Spring Boot + JWT + React

ERD of the Application:
![erd](https://github.com/user-attachments/assets/1fe9de71-ec45-4ec0-a9cc-c3ffcee935ba)


To test locally:
1) docker run -d \
  --name mysql-container \
  -e MYSQL_ROOT_PASSWORD=MyNewPass@123 \
  -e MYSQL_DATABASE=urlshortenerdb \
  -p 3306:3306 \
  mysql:latest

2) Run the backend server
3) Run the frontend (npm run dev)
4) Access localhost:5173
