# sen201_sdlc
# Student Result Management System
## Course: SEN 201 
## Name: Adeyemo Emmanuel
## matric: 25/18074
## Programming Language: Python


---

## Project Description
This project is a simple Python application that collects a student’s name and score, computes the grade, and displays the result.  
The project follows the complete Software Development Life Cycle (SDLC).

---

## Software Development Life Cycle (SDLC)

### 1. Planning
The objective of this project is to design a simple system that automatically calculates student grades based on their scores.
- flowchart
  <img width="357" height="864" alt="image" src="https://github.com/user-attachments/assets/77cb977a-5e70-4a26-a880-faed46139de6" />

---

### 2. Requirement Analysis
The system requires the following inputs:
- Student name
- Student score

The system should:
- Calculate grades correctly
- Display accurate results
- Be easy to use

---

### 3. System Design
The system is divided into three main parts:
- Input module
- Processing module
- Output module

Grade allocation logic:
- Score ≥ 70 → Grade A  
- Score ≥ 60 → Grade B  
- Score ≥ 50 → Grade C  
- Score < 50 → Grade F
  

All variable names used in the design are the same as those used in the implementation.


---

### 4. Implementation
The system was implemented using Python programming language.

```python
name = input("Enter student name: ")
score = int(input("Enter score: "))

if score >= 70:
    grade = "A"
elif score >= 60:
    grade = "B"
elif score >= 50:
    grade = "C"
else:
    grade = "F"

print("Student Name:", name)
print("Score:", score)
print("Grade:", grade)
```
## 5. Testing

The program was tested using different test cases to ensure accurate grading.

| Input Score | Expected Output |
|------------|----------------|
| 85         | Grade A        |
| 65         | Grade B        |
| 55         | Grade C        |
| 40         | Grade F        |

All test cases produced correct results.

## 6. Deployment

The project was deployed by uploading the source code to a **GitHub repository**, making it accessible for review.

## 7. Maintenance

Future improvements may include:  
- Supporting multiple students  
- Saving results to a file  
- Adding GPA calculation  

## 8. How to Run the Program

1. **Install Python** (if not already installed)  
2. **Download or clone the repository**:  
   ```bash
   git clone https://github.com/emma2e/sen201-hello-world.git

