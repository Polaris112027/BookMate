# How to start: 
1. Open your mysql and create a database
2. Create the books table and the issued_books table in the database
![image](https://github.com/Polaris112027/BookMate/assets/113433202/76f6b3be-5aef-4779-8509-c3f8d1eac739)
![image](https://github.com/Polaris112027/BookMate/assets/113433202/484a84b9-6553-43d0-9b09-b7652f21de6a)
3. Change mypass and mydatabase in all .py files to your own mysql password and the name of the created database 
4. Run the main.py file
   
# Function introduction: 
1. Main menu
![image](https://github.com/Polaris112027/BookMate/assets/113433202/9082f268-d33d-4601-bb79-da62a47836a9)
2. Add books Details
![image](https://github.com/Polaris112027/BookMate/assets/113433202/546a9d80-0e53-4218-b491-02283cd60201)
3. View book list
![image](https://github.com/Polaris112027/BookMate/assets/113433202/e5df45f7-be90-49ab-94f5-30fffa3d1530)
4. Issue Book to Student
![image](https://github.com/Polaris112027/BookMate/assets/113433202/734f976d-a630-469c-8f36-8cd2e0b30b7c)
5. Return Book
![image](https://github.com/Polaris112027/BookMate/assets/113433202/1a43cb3e-abc1-47f8-b73f-ecff65fdd63d)
6. Delete Book
![image](https://github.com/Polaris112027/BookMate/assets/113433202/ad9c3fa2-74d9-4875-a13d-ba685725c594)

# SOLID principles:

1. Single Responsibility Principle: Each module in the code has a clear and specific function, such as adding books, deleting books, etc.

2. Open/Closed Principle: The code is open for extension as it can easily accommodate adding new features (like new buttons and corresponding functionalities) without major modifications to the existing code.

3. Liskov Substitution Principle: This principle mainly pertains to object-oriented design guidelines, but since the project does not involve class inheritance relationships and polymorphism, it is currently difficult to assess.

4. Interface Segregation Principle: The interfaces and functionalities are clearly segregated, with each button performing a specific function, hence complying with the Interface Segregation Principle.

5. Dependency Inversion Principle: The GUI relies on lower-level modules like business logic and database operations, but it achieves a certain level of decoupling through function calls and similar methods. If the specific implementation of lower-level modules is altered, the GUI does not need direct modifications, just the invocation of corresponding abstract interfaces or functions. Therefore, it can be said that to some extent, it adheres to the Dependency Inversion Principle as the higher-level module (GUI) depends on abstractions rather than concrete implementations.
