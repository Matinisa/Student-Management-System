# Student-Management-System
Manage the Registration of studentd

# Single Responsibility Principle
Each class has one responsibility:

Student → defines shared structure
UndergraduateStudent → handles undergrad logic
GraduateStudent → handles graduate logic
Each Builder → handles object construction only

# Open and Closed Principle (OCP)
The system is open for extension but closed for modification:

I can add PartTimeStudent 
No changes required in existing classes
I can extend Student and add a Builder
