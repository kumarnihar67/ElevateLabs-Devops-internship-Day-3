🚀 DevOps Version-Controlled Project Report
🧩 Project Title:

Task 3 – Build a Version-Controlled DevOps Project with Git

🎯 Objective

The main goal of this project was to manage a DevOps project using Git and GitHub following best practices — including proper branching, version control, pull requests, tagging, and documentation.
This project demonstrates the foundation of collaborative DevOps workflows and release management. 💡

🛠️ Tools & Technologies Used
Tool	Purpose
🧰 Git	Version control and source code management
☁️ GitHub	Remote repository hosting and collaboration
🧾 Markdown (.md)	Documentation and reporting
💻 Command Line (CLI)	Executing Git commands efficiently
🪄 Steps Followed
1️⃣ Repository Setup

Initialized a new Git repository locally using git init.

Created a remote repository on GitHub and linked it.

Added an initial README.md and pushed it to the main branch.
<img width="1920" height="1080" alt="task3 4" src="https://github.com/user-attachments/assets/558dc22c-50bb-40c7-ab53-833a9301be20" />

2️⃣ Branching Strategy

Created three key branches:

main → Stable production code 🧱

dev → Testing and integration branch 🧪

feature/setup-ci → For developing new features ⚙️

This structure ensures clean, organized, and isolated development.

3️⃣ Feature Development & Commits

Added a sample file ci-config.yml to demonstrate Continuous Integration setup.

Committed changes using meaningful commit messages.

Example:

git commit -m "Add initial CI configuration"

4️⃣ Pull Requests & Merging

Created a Pull Request (PR) to merge feature/setup-ci → dev.
<img width="1920" height="1080" alt="task3 1" src="https://github.com/user-attachments/assets/d1763400-c304-429a-8035-2120cbbff37a" />

Reviewed and merged the feature branch after testing.
<img width="1920" height="1080" alt="task3 2" src="https://github.com/user-attachments/assets/fbf448b3-1b37-447b-8110-c3f14f91be52" />

Later merged dev → main for a stable release. ✅
<img width="1920" height="1080" alt="task3 3" src="https://github.com/user-attachments/assets/21c38863-71e1-471f-805c-9adb7453793a" />

5️⃣ Adding .gitignore

Added a .gitignore file to exclude unnecessary files such as:

6️⃣ Tagging the Release

Created a version tag to mark the first stable release:

git tag -a v1.0 -m "First stable release"
git push origin v1.0


Tagging helps identify specific versions and milestones of the project 🏷️.
<img width="1920" height="1080" alt="task3 7" src="https://github.com/user-attachments/assets/a192d215-4c4c-41a6-ba0f-afd560d25082" />

7️⃣ Documentation

Created TASKS.md to record all activities and steps completed.

Updated README.md to include a full summary of the project.

This README_project-summary.md provides a formal report for submission. 📝
<img width="1920" height="1080" alt="task3 8" src="https://github.com/user-attachments/assets/833ae869-76fa-43e9-b5c2-aa85e78b9a29" />

🌿 Branch Overview
Branch	Purpose	Status
main	Stable production-ready branch	✅ Completed
dev	Integration and testing branch	✅ Merged
feature/	Feature development branch	✅ Merged
🧾 Deliverables

GitHub repository initialized and pushed

Proper branching structure (main, dev, feature/*)

Pull Requests created and merged

.gitignore file added

Tag created (v1.0)

Complete documentation (README.md + TASKS.md)
