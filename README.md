# Submission Reminder App – Abdull-Kudus

This is a simple shell-based reminder app to check student assignment submissions and update assignment information. It’s designed for beginners learning shell scripting and basic Git/GitHub workflows.

---

# App Project Folder Structure

```bash
submission_reminder_app_Abdull-Kudus/
│
├── create_environment.sh              # Script to generate project folder and files
├── copilot_shell_script.sh           # Script to check and update student assignment
├── README.md                          # This file (documentation)
│
└── submission_reminder_Abdull-Kudus/ # Created by create_environment.sh
    ├── startup.sh                     # Script to show who hasn't submitted
    ├── config/
    │   └── config.env                 # Stores the ASSIGNMENT value
    └── assets/
        └── submissions.txt           # Contains list of student submissions
```

---

# Prerequisites

- A Unix/Linux terminal (Ubuntu, WSL, macOS, etc.)
- Git installed
- Basic knowledge of terminal commands

---

# Step-by-Step Instructions

# Step 1: Set Up the Environment

This will generate all the necessary folders and files.

```bash
bash create_environment.sh
```

# You’ll see a folder named `submission_reminder_Abdull-Kudus` with the required files inside.

---

# Step 2: Run the Reminder System

Navigate into the generated folder and run:

```bash
cd submission_reminder_Abdull-Kudus
./startup.sh
```

 This will print a list of students who have **not submitted** their assignments yet.

---

# Step 3: Use the Copilot Shell Script

Run the copilot script to check if a specific student has submitted and to update the assignment name:

```bash
cd ..
bash copilot_shell_script.sh
```

It will:

1. Prompt you to enter:
   - The assignment name
   - The student name
2. Check if that student hasn’t submitted
3. Update the `ASSIGNMENT` value in `config/config.env`

 It will show a confirmation message after updating the config file.

---

# Final Cleanup (for GitHub Main Branch)

Before merging to the `main` branch, remove all generated folders and files **except**:

- `create_environment.sh`
- `copilot_shell_script.sh`
- `README.md`

You can do:

```bash
rm -rf submission_reminder_Abdull-Kudus
```

Then push to main branch and merge your work.

---

# Author
**Abdull-Kudus**  
Shell Scripting Project For Summative | ALU Software Engineering

---

# This is an Application that helps to track assignment submissions!

