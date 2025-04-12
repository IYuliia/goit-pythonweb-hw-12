
### Technical Description of the Task

1. **Creating Documentation Using Sphinx**: Create documentation for your application using Sphinx. To do this, add docstrings to the necessary functions and methods of classes in the main modules.
  
2. **Unit Testing**: Cover your application’s repository modules with unit tests.

3. **Integration Testing**: Cover the routes of your application with integration tests using the pytest framework.

4. **Test Coverage Above 75%**: Ensure that your application is covered by tests for over 75%. Use the pytest-cov package for control.

5. **Redis Caching Implementation**: Implement caching using the Redis database. Cache the current user during authentication so that the `get_current_user` function retrieves the user from the cache and does not query the database every time.

6. **Password Reset Mechanism**: Implement a password reset mechanism for your REST API application.

7. **User Roles and Access**: Implement role-based access for users: "user" and "admin". Ensure that only administrators can change their default avatar.

---

### General Requirements for Completing the Homework

1. **Code Documentation**:  
   All major functions and methods of classes must have appropriate docstrings for generating documentation using Sphinx.

2. **Testing**:  
   Test modules should be organized according to the structure of your application.  
   Use pytest to write unit and integration tests.  
   Ensure that your application has test coverage of at least 75%. Use pytest-cov to check coverage.

3. **Redis Caching**:  
   Set up Redis as a caching service for your application.  
   When implementing user caching, ensure the security and freshness of the data.

4. **Password Reset**:  
   Implement a secure password reset mechanism with confirmation via email or another method.

5. **Role Management**:  
   Implement a role system for users.  
   Ensure access control checks for operations that are only available to administrators.

6. **Confidential Data Storage**:  
   All sensitive data and configurations should be stored in a `.env` file. Do not include sensitive data in the codebase.

7. **Containerization**:  
   Use Docker Compose to run all services and databases of your application.

