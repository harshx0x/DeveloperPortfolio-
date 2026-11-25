# 💻 DeveloperPortfolio — CS Fundamentals Capstone

> A beginner developer ecosystem portfolio showcasing my semester learning, practical Linux skills, Bash automation, API integration, Git/GitHub workflow, and professional development.

---

## 👨‍💻 About the Project

**DeveloperPortfolio** is my Computer Science Fundamentals Capstone project. It brings together the practical skills I developed throughout the semester and documents my journey as a beginner developer.

This repository demonstrates my understanding of Linux commands, system documentation, shell scripting, Git and GitHub, REST API interaction, JSON processing, Python programming, technical resume preparation, career planning, and portfolio website development.

The goal of this project is to build a structured, professional portfolio that demonstrates both my technical skills and my continuous learning journey.

---

## 🎯 Project Objectives

- Understand and use Linux command-line tools.
- Collect and document system hardware and software information.
- Automate tasks using Bash shell scripts.
- Use Git and GitHub for version control.
- Fetch and analyse data using REST APIs.
- Process JSON data using `jq` and Python.
- Prepare a technical resume and career learning roadmap.
- Build and publish a personal portfolio website.
- Document projects and learning progress professionally.

---

## 📂 Repository Structure

```text
DeveloperPortfolio-/
│
├── API/
│   ├── github_profile.json
│   ├── sample_posts.json
│   ├── api_summary.md
│   └── api_analysis.py
│
├── Linux/
│   ├── system_profile.md
│   └── commands_output.txt
│
├── Portfolio/
│   ├── resume.pdf
│   └── learning_roadmap.md
│
├── ShellScripts/
│   ├── sysinfo.sh
│   ├── sysinfo_output.txt
│   ├── backup.sh
│   ├── backup_output.txt
│   └── backup.log
│
├── Screenshots/
│   ├── backup_demo.png
│   ├── github_profile.png
│   ├── linkedin_profile.png
│   └── portfolio_website.png
│
├── index.html
├── .gitignore
└── README.md
```

---

# 🧪 Capstone Sections

## Q1 — Linux Commands & System Documentation

This section demonstrates my understanding of Linux commands and system information collection.

### Work Completed

- CPU model and number of cores
- RAM information
- Storage information
- Operating system details
- Kernel version
- Linux command execution
- Decimal-to-binary conversion
- Binary-to-decimal conversion
- Explanation of binary representation

### Commands Used

| Command | Purpose |
|---|---|
| `lscpu` | Displays CPU information |
| `nproc` | Displays the number of CPU processing units |
| `free -h` | Displays memory usage |
| `lsblk` | Lists storage devices |
| `df -h` | Displays disk usage |
| `uname -a` | Displays kernel and system information |
| `cat /etc/os-release` | Displays operating system details |
| `ls -la` | Lists files with permissions |
| `ps aux` | Displays running processes |

---

## Q2 — Shell Scripting & Automation

This section demonstrates Bash scripting and task automation.

### Script 1: `sysinfo.sh`

A Bash script that generates a formatted system information report.

**Features:**

- Displays author name and roll number
- Displays current date
- Reports CPU model and core count
- Displays total and used memory
- Lists top processes by CPU usage
- Displays a completion message

Run the script:

```bash
./ShellScripts/sysinfo.sh
```

---

### Script 2: `backup.sh`

A Bash script that creates timestamped compressed backups of a specified directory.

**Features:**

- Validates command-line arguments
- Checks whether the source directory exists
- Creates a backup directory automatically
- Generates timestamped backup filenames
- Creates compressed `.tar.gz` archives
- Displays backup filename and size
- Records backup status in a log file
- Handles invalid input

Run the script:

```bash
./ShellScripts/backup.sh ~/DeveloperPortfolio-
```

Example backup filename:

```text
backup_YYYY-MM-DD_HH-MM-SS.tar.gz
```

---

## Q3 — GitHub Repository & API Interaction

This section demonstrates version control and interaction with REST APIs.

### GitHub REST API

API endpoint:

```text
https://api.github.com/users/harshx0x
```

The API is used to retrieve publicly available GitHub profile information.

Information analysed:

- Name
- GitHub username
- Public repositories
- Followers
- Account creation date

### JSONPlaceholder API

API endpoint:

```text
https://jsonplaceholder.typicode.com/posts
```

This API provides sample JSON data used for learning API requests and data analysis.

### Tools Used

- `curl` — Fetch API data
- `jq` — Extract and process JSON fields
- Python — Analyse API response data
- Git — Track changes
- GitHub — Host the repository

### HTTP Status Codes

| Status Code | Meaning |
|---|---|
| 200 | Request successful |
| 404 | Requested resource not found |

---

## Q4 — Developer Portfolio & Career Roadmap

This section focuses on professional development and career preparation.

### Technical Resume

A one-page technical resume containing:

- Professional introduction
- Education
- Technical skills
- Projects
- GitHub profile
- LinkedIn profile

### Learning Roadmap

My learning roadmap includes:

**Semester 1 — Foundations**
- Linux
- Python fundamentals
- Git and GitHub
- HTML
- Bash scripting
- API fundamentals

**Semester 2 — Development Skills**
- Data Structures and Algorithms
- SQL and databases
- JavaScript
- Web development
- Flask
- Practical projects

**Future Specialisation — AI & Machine Learning**
- Advanced Python
- NumPy and Pandas
- Statistics and Probability
- Machine Learning
- Deep Learning
- AI-based projects

### Professional Profiles

- GitHub profile development
- LinkedIn profile development
- Skills and education documentation
- Project portfolio presentation

---

# 🌐 Portfolio Website

My portfolio website presents my introduction, technical skills, projects, and professional contact links.

### Website Features

- About Me section
- Technical Skills section
- Projects section
- Contact section
- GitHub profile link
- LinkedIn profile link
- Responsive layout

### Technologies

- HTML5
- CSS3

### Live Website

🚀 **Visit My Portfolio:**  
[Open my portfolio website](https://harshx0x.github.io/DeveloperPortfolio-/)

---

# 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Ubuntu Linux | Operating system and command-line environment |
| Bash | Shell scripting and automation |
| Git | Version control |
| GitHub | Repository hosting and collaboration |
| Python | API data analysis |
| curl | HTTP API requests |
| jq | JSON processing |
| Markdown | Technical documentation |
| HTML5 | Portfolio website structure |
| CSS3 | Portfolio website styling |

---

# 📸 Project Screenshots

Screenshots demonstrating project execution, scripts, profiles, and website deployment are stored in the `Screenshots/` directory.

Examples include:

- Linux command execution
- System information script
- Backup script execution
- GitHub profile
- LinkedIn profile
- Portfolio website

---

# 📚 Learning Outcomes

Through this capstone, I gained practical experience in:

- Using Linux commands confidently
- Understanding system hardware and software information
- Writing and executing Bash scripts
- Automating directory backups
- Using Git for version control
- Managing repositories on GitHub
- Fetching data from REST APIs
- Processing JSON using `jq`
- Analysing API data using Python
- Writing structured Markdown documentation
- Creating a professional technical resume
- Planning a semester-wise learning roadmap
- Building and deploying a personal portfolio website

---

# 🚀 Future Improvements

- Add more Python projects.
- Build interactive web applications.
- Improve frontend development skills.
- Learn database management.
- Develop AI and Machine Learning projects.
- Contribute to open-source repositories.
- Add more projects and achievements to the portfolio.

---

# 👨‍🎓 Author

**Harsh**

Computer Science Student  
Aspiring Developer | AI & Machine Learning Enthusiast

### Connect With Me

- **GitHub:** [harshx0x](https://github.com/harshx0x)
- **Repository:** [DeveloperPortfolio-](https://github.com/harshx0x/DeveloperPortfolio-)
- **LinkedIn:** Add your LinkedIn profile URL here.
- **Portfolio:** [Visit my portfolio](https://harshx0x.github.io/DeveloperPortfolio-/)

---

> *Learning by building. Improving through practice. Creating with technology.*

⭐ Thank you for visiting my DeveloperPortfolio repository!
