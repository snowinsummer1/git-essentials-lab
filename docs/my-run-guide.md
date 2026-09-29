\# My Run Guide



\## Prerequisites



\- Git 2.23 or later

\- JDK 17 or later (both `java` and `javac` must be on PATH)

\- Python 3.9 or later



\## Run the demo



From the repository root, run:



&#x20;   python3 run.py demo



On Windows, use `py -3 run.py demo` if `python3` is not available.



\## What the demo does



`run.py demo` compiles the Java sources under `src/library/` into a temporary

directory and runs `library.Main`, a small console demo of the library

application (borrowing and returning books, loan periods, overdue fees,

catalog search and loan receipts). It does not change any file in the repository.

