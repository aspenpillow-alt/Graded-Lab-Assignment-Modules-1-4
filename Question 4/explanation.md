1. I ran the `uptime` command to see how long the system has been running since the last restart and to check the current system load average.

2. I used the `ps -u $USER` command to list all programs and tasks currently running under my specific user account.

3. I used the `top` utility to see a live view of system resources, which helped me identify which processes were using the most CPU power.

4. I started a `sleep` command in the background using the ampersand (`&`) symbol and then used the `jobs` command to confirm that it was still running without blocking the terminal.

5. I used the `renice` command to change the priority (niceness) of a running process, which tells the Linux kernel how to prioritize CPU time for that task.

6. I used the `free -h` command to display the system’s RAM usage in a human-readable format to see how much memory is currently free.

7. I used the `df -h ~` command to show the disk space usage for the filesystem where my home directory is located.

8. I used the `echo $SHELL` command to identify which shell environment I am currently using.

9. I redirected the output of the `uname -a` command into a file named `system_report.txt` instead of printing it to the screen.

10. I used the `ncdu` tool to get an interactive view of disk usage and see which files and folders are consuming the most disk space.
