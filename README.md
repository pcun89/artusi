# artusi
# 🖥️ Artusi Project — Command Line File Editing with Bash

The **Artusi Project** is a hands-on command-line simulation designed to help developers gain practical experience with file editing, navigation, and basic scripting using Bash and Unix shell commands.

This project is part of Codecademy's Developer Tools curriculum and aims to build comfort and fluency with the command-line interface (CLI), empowering users to perform development tasks faster and more efficiently than with a GUI.

---

## 📌 Project Goals

- Build confidence using the command line for file manipulation
- Navigate nested directory structures
- Edit and inspect files using CLI tools
- Practice Bash and Unix command-line skills in a real-world context
- Gain foundational tools for software development workflows

---

## 🧠 Skills Practiced

| Skill                     | Tools / Commands Used           |
|--------------------------|---------------------------------|
| Directory navigation     | `cd`, `pwd`, `ls`, `tree`       |
| File editing             | `nano`, `vim`, `echo`, `cat`    |
| File management          | `touch`, `mv`, `cp`, `rm`       |
| File viewing             | `less`, `head`, `tail`          |
| Permissions (optional)   | `chmod`, `ls -l`                |
| Scripting (advanced)     | `bash`, `sh`, or `.bashrc`      |

---

## 🗂️ Sample Tasks

- Open a folder called `artusi_project`
- Create and edit a file named `manifesto.txt`
- Add a header and bullet points using `echo` or a terminal editor
- Create a `notes/` directory and move relevant files there
- Use `cat`, `head`, or `tail` to verify file content
- Optionally create a `.sh` script that prints or appends to the files

---

## 💻 Sample Commands

```bash
# Navigate to project directory
cd artusi_project

# Create and edit a text file
touch manifesto.txt
echo "Welcome to Artusi" > manifesto.txt

# Append to file
echo "- Learn the CLI" >> manifesto.txt
echo "- Build developer confidence" >> manifesto.txt

# Create a subdirectory and move file
mkdir notes
mv manifesto.txt notes/

# View contents
cat notes/manifesto.txt

# Optional script creation
echo 'echo "Artusi is working."' > run_artusi.sh
chmod +x run_artusi.sh
./run_artusi.sh
