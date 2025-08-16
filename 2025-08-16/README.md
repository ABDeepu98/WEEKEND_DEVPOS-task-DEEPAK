# WEEKEND DevSecOps Git Practice - Deepak JM
## Date: 2025-08-16

### 🔧 Git Configuration
Configured Git with my name and email:
```bash
git config --global user.name "Deepak JM"
git config --global user.email "your.email@example.com"
git config --list
📁 Repository Setup
Cloned the repository and created folder for today’s date:

bash
Copy code
git clone git@github.com:ABDeepu98/WEEKEND_DEVSECOPS-task-DEEPAK-JM.git
cd WEEKEND_DEVSECOPS-task-DEEPAK-JM
mkdir 2025-08-16
cd 2025-08-16
touch task1.txt task2.txt task3.txt README.md
📝 File Operations
Add content to files
bash
Copy code
echo "This is Task 1 content" >> task1.txt
echo "This is Task 2 content" >> task2.txt
echo "This is Task 3 content" >> task3.txt
Clear content of a file
bash
Copy code
> task2.txt       # empties task2.txt
Move files to another folder
bash
Copy code
mv task1.txt task2.txt 2025-08-16/   # moves multiple files into folder
📦 Staging and Committing
bash
Copy code
git status
git add .
git commit -m "Added tasks and performed file operations"
🚀 Push to GitHub
bash
Copy code
git push origin main
🔄 Pull Remote Changes
bash
Copy code
git [A[A[A[C[C[C[C[C[C[C[C[C[C[C[C[C





