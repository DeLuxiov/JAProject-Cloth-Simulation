# Cloth-Simulation – Project Description

Project Objective:
The goal of the project is to develop a cloth simulation application in a high-level language (C++ or C#), accompanied by two dynamically linked libraries (DLLs):
one implemented in C/C++, the other in x86/x64 Assembly utilizing vector instructions (SSE4/AVX2).
The project aims to compare the performance of the algorithm across different implementations and to support parallel processing with multiple threads (up to 64).

Project Implementation Process:
- The student proposes a project topic and obtains approval from the supervisor.
- The student conducts a theoretical analysis of the algorithm and prepares a presentation (PPT/PDF) explaining the implemented method, mathematical approach, or theoretical solution.
- The student implements the algorithm in Microsoft Visual Studio.
- The student prepares a final project report.

Project Requirements:
- The project targets Intel x86/x64 processor architecture.
- Development environment: Visual Studio 2017/2019.

The Visual Studio solution should include:
- User Interface Application: Any high-level language (C++, C#), with a windowed interface allowing parameterization and control of the simulation process.
- C/C++ DLL: Functions dynamically callable from the main application.
- Assembly DLL: Functions dynamically callable from the main application, using vector instructions.

User Interface Requirements:
- Options (checkboxes) to choose between executing the high-level language implementation or the Assembly implementation.
- Status display elements (e.g., progress bar, execution time measurement for DLL functions).
- Ability to dynamically switch DLLs during runtime without restarting the application.
- Input validation to prevent invalid data.
- Optional multi-threaded execution to analyze performance depending on the number of threads.

Code Documentation:
- All source files (C, C++, C#, ASM) must include:
- Project title, brief algorithm description, date, semester/year, author’s name, current version, and change history.
- All procedures, constants, and variables must be appropriately commented.
- ASM code lines must include descriptive comments for clarity.

Program Output:
- The program must be tested with different input data sizes and thread counts.
- Execution times for both high-level and Assembly implementations must be recorded and presented as charts (e.g., Excel) in the final report.
- Charts should include results with time optimization and memory optimization.

Final Report:
- The report should include:
- Brief description of the implemented algorithm.
- Input parameters description.
- Selected fragment of Assembly code with comments.
- Screenshots of the UI before and during execution.
- Performance analysis charts.
- Testing and execution description.
- Conclusions and interpretation of execution times depending on input data size and complexity.

Project Submission:
- Presentation (PDF), ASM source code (PDF), and final report (PDF) must be submitted to the designated repository (ZMITAC, Microsoft Teams, or Platform).
- Deadlines and grading policies are determined by the supervisor; timely completion is rewarded with a higher grade.
