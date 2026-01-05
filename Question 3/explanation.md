1. I created sample_data.txt to act as my main data file for this exercise.

2. I created a hard link called sample_hard.txt which points directly to the file's data on the disk.

3. I created a soft link called sample_soft.txt which acts as a shortcut pointing to the file name.

4. I used ls -i to show the inode numbers, which are the unique identity numbers of files.

5. I found that the hard link shares the same inode as the original because they share the same data spot.

6. I used the stat command to view detailed metadata like when the file was created and modified.

7. I used du -sh to see the total disk space my home folder is using in a human-readable format.

8. I used ls -lh to see the size of every file in my folder in Kilobytes or Megabytes.

9. I deleted the soft link and checked the original file to prove that deleting a shortcut doesn't delete the data.

10. I used df -h to check the overall health and available space on the entire system's storage drive.
