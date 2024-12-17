This Java project demonstrates a simple Hospital Management System using object-oriented programming principles such as inheritance, polymorphism, and encapsulation.

Features
HospitalStaff Base Class:
A general class to represent common attributes (name, age) and methods for hospital staff.

Doctor and Nurse Subclasses:
Specialized classes that extend HospitalStaff:

Doctor: Includes a specialization field and overrides the work() method to specify the doctor's tasks.
Nurse: Includes yearsOfExperience and overrides the work() method to describe the nurse's responsibilities.
Polymorphism in Action:
The HospitalManagementSystem class demonstrates polymorphism by referencing specific roles (Doctor, Nurse) through a HospitalStaff reference and calling their overridden work() methods.

Usage
Run the HospitalManagementSystem class to see the behavior of the system:

A nurse's work is described based on their years of experience.
A doctor’s work is detailed along with their specialization.
