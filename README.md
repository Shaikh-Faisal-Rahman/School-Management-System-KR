Project Overview 
Traditional databases only store data, but this ontology understands the relationships and logic 
behind the data. Using the HermiT Reasoner, it can automatically identify "At-Risk" students 
based on attendance and "Honor Roll" students based on grades. 
Key Components 
1. Class Hierarchy (Entities) 
The ontology includes a rich hierarchy of classes: 
• Person: Subclasses include Student, Teacher, Staff, and Parent/Guardian. 
• Academic: Course, Subject, Class Section, Term/Semester, and Academic Year. 
• Records: Attendance Record, Grade Record, Fee Account, and Payment. 
• Inferred Classes: At-Risk Student and Honor Roll Student. 
2. Object Properties (Relationships) 
Logic-based connections between entities: 
• enrollment for student, teaching for course, is parent of. 
• has attendance status, has grade letter, borrowing of book. 
3. Data Properties (Attributes) 
Specific data points for individuals: 
• Employee/Student ID: empID, student id, teacher id. 
• Details: salary, attendance date, score, has email, date of birth. 
4. Individuals (Sample Data) 
The project includes pre-defined individuals to test the reasoning: 
• Student: Himel (Student). 
• Teacher: Mr. Rossi, Mr. Rahman. 
• Examples: 10A MATH101, Attendance: Himel 2026-02-02, Grade: Himel - MATH101 
Midterm. 
How to Run 
1. Open protégé Desktop. 
2. Go to File > Open and select the file. 
3. Go to the Reasoner menu, select HermiT, and click Start Reasoner. 
