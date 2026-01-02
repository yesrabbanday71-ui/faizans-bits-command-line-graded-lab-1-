1.
Command:
echo "sample data for testing" > sample_data.txt

Explanation:
This command creates a file and adds sample content into it.

2.
Command:
ln sample_data.txt sample_hard.txt

Explanation:
This command creates a hard link pointing to the same data.

3.
Command:
ln -s sample_data.txt sample_soft.txt

Explanation:
This command creates a symbolic link to the original file.

4.
Command:
ls -i sample_data.txt sample_hard.txt sample_soft.txt

Explanation:
This command shows inode numbers of all the files.

5.
Explanation:
sample_data.txt and sample_hard.txt have same inode because both refer to same file data. Soft link has different inode.

6.
Command:
ls -l sample_data.txt

Explanation:
This command shows detailed file information like size and permissions.

7.
Command:
du -sh ~

Explanation:
This command shows disk usage of home directory in readable format.

8.
Command:
ls -lh ~

Explanation:
This command lists files with their sizes in home directory.

9.
Command:
rm sample_soft.txt

Explanation:
This command deletes the symbolic link only, original file remains safe.

10.
Command:
du -h
df -h

Explanation:
du shows directory space usage and df shows total filesystem disk usage.
