# My Linux DevOps Learning Journey

Over the course of this project, I have dived deep into essential Linux skills that form the foundation for any DevOps engineer. Starting with user and group management, I created a user named `devops_user` and set up a dedicated group called `devops_team`. I ensured proper permissions by adding the user to the group, setting a secure password, granting sudo access, and even configuring SSH restrictions to control who can access the system remotely.

Next, I focused on mastering file and directory permissions. I created a workspace directory `/devops_workspace` along with a file `project_notes.txt`. To practice permission management, I set the directory and file so that the owner can read and write, the group can only read, and others have no access. I verified these settings using standard Linux commands, gaining confidence in managing access controls effectively.

To better understand log analysis—a critical skill in monitoring and troubleshooting—I downloaded the `Linux_2k.log` file from the LogHub repository. Using powerful command-line tools like `grep`, `awk`, and `sed`, I extracted all instances of errors, isolated timestamps and log levels, and sanitized sensitive data by redacting IP addresses. I also explored techniques to identify the most frequent log entries, sharpening my ability to derive insights from large log files.

Finally, I explored process management by running a background process that continuously pings Google, and then monitored it using various tools such as `ps`, `top`, and `htop`. I learned how to track resource usage in real-time and gracefully terminate processes when needed.

Throughout this journey, I captured screenshots to document my progress and preserved my Linux command history for reference. This repository contains all these materials as a testament to my hands-on learning experience.

I look forward to continuing this path, applying these skills in real-world DevOps environments, and expanding my Linux expertise further.

---

Feel free to explore the screenshots and command history to see exactly how each task was accomplished. Your feedback and suggestions are always welcome!
