
## Startup procedure

1. Create a 'democrud' database in postgres.

1. In Visual Studio Code, open the project. 


1. Start Command Prompt and move to the following directory of the project.  

   ```
   cd CRUD-Application-Go-Vue

   ```

2. Start the backend  

   ```
   go run backend.go
   ```

1. Start the command prompt and move to the following directory of the project.  

   ```
   cd ./frontend
   ```

2. Launch the frontend  

   ```
   npm run serve
   ```

3. Access with a Chronium-like browser such as Edge/Safari.    
   (When npm run serve completes the build, the following URL is displayed.)  
   App running at:
   [http://localhost:8080/](http//localhost:8080/)  


## Library Used

1. Gorm ( gorm.io/gorm)
2. Gorilla Mux (github.com/gorilla/mux)
3.  Postgres (gorm.io/driver/postgres)
