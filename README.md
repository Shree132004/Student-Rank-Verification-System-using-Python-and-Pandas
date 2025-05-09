**Student Rank Checker** — 
Verify Academic Ranks with Data Transparency
This project is a lightweight Python-based utility designed to verify student rankings based on actual academic scores. Educational institutions and students often rely on declared ranks for admissions, scholarships, and recognition. But how do you ensure those ranks are calculated fairly?
That’s where this tool comes in.
Using a clean dataset of students' marks — including JEE scores, Class 12, and Class 10 board marks — the system computes a Total Score and assigns a computed rank by sorting students in descending order of their performance. It then allows users to input a Roll Number to view the student’s detailed academic profile, compare the declared rank with the recomputed one, and check for discrepancies.
This helps identify data inconsistencies or ranking errors and promotes transparency in student evaluation.

**🔍 Features:**

1.Load student data from CSV files.

2.Clean and normalize column names automatically.

3.Calculate a total score using:

    a.JEE Marks
    
    b.Class 12 Marks
    
    c.Class 10 Marks
    
4.Generate accurate rankings using the computed score.

5.Allow real-time lookup via Roll Number.

6.Provide a clear comparison between declared and computed ranks.

7.Friendly CLI output with informative messages.


**🛠️ Tech Stack:**

1.Python 3

2.Pandas (data processing)

3.Optional: Google Colab or Jupyter Notebook for demos


**📦 Use Cases:**

1.Internal audits of student ranking systems

2.Educational fairness checks

3.Institutional transparency

4.Student self-verification


Whether you're a school administrator, a student, or a data analyst, this program offers a simple but powerful way to verify academic rankings based on reliable metrics.Student-Rank-Verification-System-using-Python-and-Pandas
A simple Python program to verify student ranks by recalculating them based on JEE, Class 12, and Class 10 marks using pandas. Enter a roll number to view a student's details, total score, and validate whether their declared rank is correct.
