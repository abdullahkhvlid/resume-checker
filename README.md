# Resume Skill Matcher – Python Project

This is a Python-based script that analyzes a resume (in `.txt` format) and checks how well it matches a predefined set of required skills. It calculates the number of matching skills, gives a match percentage, and determines whether the applicant qualifies for the job based on the skills present.

---

## Features

- Reads `.txt` format resume files
- Compares resume content with a predefined list of required skills
- Case-insensitive skill matching
- Calculates total number and percentage of matched skills
- Determines job eligibility based on matching criteria
- Basic error handling for file and input issues

---

## Technologies Used

- Python (3.x)
- File handling (`open`, `read`)
- List and string operations
- Conditional logic
- Error handling (`try-except`)

---

## How It Works

1. The user is prompted to upload and provide the name of a `.txt` file containing the resume.
2. The script reads the content of the file.
3. It checks for each required skill (case-insensitive) in the resume.
4. Outputs:
   - List of matched skills
   - Number and percentage of matched skills
   - Eligibility decision

---

## Required Skills List (Editable)

```python
reqskills = [
    "Data science", "Django", "Generative AI", "Pandas", "Numpy",
    "logic building", "SQL", "Machine learning", "MLOps"
]
