Q1) Find whether the number is odd or even.

Q2) Find the factorial of any number you like number.

Q3) Fibonacci series using for and while loop both.

Q4) Find whether the number is prime or not (2).

Q5) Compare 2 files whether they have text in tht nd delete if it is duplicate.

Q6) Write a script to check whether a number is palindrome.

Q7) Write a script to rint multiplication table.

Q8)Write log_finder.sh that searches a directory tree for recently modified log files and produces a summary report.

    The script must:

        Accept a directory path as the first argument

        Find all .log files under that directory (recursively) that were modified in the last 7 days

        Count the total number of lines across all found files

        Print a formatted summary with:

        Number of log files found

        Total lines across all files

        A sorted list of filenames with their individual line counts

          USAGE
          ./log_finder.sh /var/log

          <img width="846" height="382" alt="image" src="https://github.com/user-attachments/assets/d5bbb89c-2e14-4ee8-9333-51bfbd854560" />

  Q9) Write sys_report.sh that collects system health information and saves it to a timestamped file. This simulates a common sysadmin task — periodic system snapshots that help you spot anomalies.

  <img width="1348" height="592" alt="image" src="https://github.com/user-attachments/assets/5c19c88d-6de4-442b-85f2-509d840da7a6" />

  Hints
Use date +%Y%m%d_%H%M%S for the filename timestamp

Use SECONDS bash variable or date +%s.%N to measure generation time

ps aux --sort=-%cpu | head -6 gives top 5 by CPU (plus header)

Wrap section commands in functions for cleaner code

command -v <cmd> checks if a command exists


Q10) Password generator

Write gen_pass.sh that generates cryptographically random passwords with configurable options. This teaches you about randomness sources in Linux, argument parsing, and file I/O.

<img width="981" height="531" alt="image" src="https://github.com/user-attachments/assets/b59c445c-cb70-4c49-9031-8dd230d7d4b9" />









