1.
Command:
mkdir ~/documents

Explanation:
This command creates a new directory named documents in my home folder.

2.
Command:
cd ~/documents

Explanation:
This command changes directory into documents.

3.
Command:
touch plan.txt

Explanation:
This command creates an empty file named plan.txt.

4.
Command:
echo "Complete linux lab work" > plan.txt

Explanation:
This command writes some sample text into plan.txt file.

5.
Command:
ls -l plan.txt

Explanation:
This command shows file permissions and ownership details of plan.txt.

6.
Command:
cp plan.txt plan_copy.txt

Explanation:
This command creates a copy of plan.txt with a new name.

7.
Command:
cd ~

Explanation:
This command moves back to the home directory.

8.
Command:
mv documents project_documents

Explanation:
This command renames the directory to project_documents.

9.
Command:
mkdir ~/project_documents/archive

Explanation:
This command creates a sub directory named archive inside project_documents.

10.
Command:
mv ~/project_documents/plan_copy.txt ~/project_documents/archive/

Explanation:
This command moves the copied file into archive folder.

11.
Command:
ls -R ~/project_documents

Explanation:
This command lists all files and folders recursively.

12.
Command:
realpath ~/project_documents/archive/plan_copy.txt

Explanation:
This command displays the absolute path of the moved file.
