# CODETECH-Task-2

Name : Utsav D K

Company : CODETECH IT SOLUTIONS

ID : CT08DS6645

Domain : PYTHON PROGRAMMING

Duration : August to September 2024

Mentor :  Muzammil Ahmed

OVERVIEW

**Objective:**  
Develop a Python program to track and manage student grades. The program should:
- Allow the user to input grades for different subjects or assignments.
- Calculate the average grade.
- Display the overall grade along with additional information (such as letter grade or GPA).

### **Solution Overview:**

We'll create a console-based grade tracker that:
1. **Inputs:** Accepts multiple subject names and their corresponding grades from the user.
2. **Storage:** Stores the data in a dictionary for easy access and manipulation.
3. **Computation:** Calculates the average grade.
4. **Grade Assignment:** Determines the letter grade based on the average.
5. **Output:** Displays a comprehensive grade report.
6. **Error Handling:** Validates inputs to ensure grades are within a logical range.
7. ### **Explanation of the Code:**

1. **Data Storage:**
   - A dictionary named `grades` is used to store subject names as keys and their corresponding grades as values.

2. **Input Functions:**
   - `get_grade(subject)`: Prompts the user to enter a grade for a given subject, ensuring the input is a numeric value between 0 and 100.

3. **Input Loop:**
   - Continuously prompts the user to enter subject names and their grades.
   - Allows the user to type `'done'` to finish entering grades.
   - Checks for duplicate subjects and offers the option to overwrite existing grades.

4. **Computation:**
   - Calculates the total sum of grades and computes the average.
   - Determines the letter grade based on the average using `get_letter_grade(avg)`.
   - Maps the letter grade to GPA points using `get_gpa_point(letter)`.

5. **Output:**
   - Displays a formatted grade report listing each subject and its grade.
   - Shows the calculated average grade, corresponding letter grade, and GPA.

6. **Error Handling:**
   - Ensures that subject names are not empty.
   - Validates that grades are numeric and within the 0-100 range.

### **Running the Program:**

1. **Save the Code:**
   - Save the above code in a file named `student_grade_tracker.py`.

2. **Execute the Program:**
   - Open a terminal or command prompt.
   - Navigate to the directory containing `student_grade_tracker.py`.
   - Run the program using the command:
     ```
     python student_grade_tracker.py
     ```

3. **Usage:**
   - Follow the on-screen prompts to enter subject names and their corresponding grades.
   - Type `'done'` when you have finished entering all subjects.
   - Review the generated grade report.

### **Enhancements and Considerations:**

- **Persistent Storage:** To retain grade data between sessions, consider implementing file I/O operations (e.g., reading from and writing to a JSON or CSV file).

- **Multiple Students:** Extend the program to handle multiple students by introducing a student identifier and storing grades accordingly.

- **Advanced GPA Calculations:** Incorporate credit hours for each subject to calculate weighted GPAs.

- **Graphical User Interface (GUI):** Utilize libraries like Tkinter or PyQt to create a user-friendly interface.

- **Error Logging:** Implement logging mechanisms to track errors or invalid inputs for debugging purposes.
  
## **Outputs**

 <img width="862" alt="image" src="https://github.com/user-attachments/assets/cd8168bc-14a0-40ef-8862-4683fed0ce8b">
 
<img width="423" alt="image" src="https://github.com/user-attachments/assets/3928ba97-46ef-4bff-bc9d-945e9e21bf08">

- 

