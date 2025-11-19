TryHackMe Write-up: Linux Fundamentals Part 1

Room Status: Completed
Focus: Command Line Fundamentals, File Systems, and Permissions
Objective: Document command-line mastery for foundational penetration testing, ensuring the skills required for an 8-12 LPA career path.
GitHub Repository: om-prakash-dev/tryhackme-writeups

1. Core System Interaction (Initial Access)

These are the essential commands used for connecting and gaining initial context on a Linux target.

whoami: Confirms the current user context. Essential for privilege awareness.

hostname: Displays the machine's network name.

echo: Prints text or variables. Used for simple output and script testing.

man: Displays the manual page for any command (e.g., man ls). This is the primary learning tool.

2. File System Navigation and Inspection

This section covers the commands used to move around the system and read file contents.

pwd (Print Working Directory): Shows the absolute path to the current location.

ls (List): Lists contents of a directory.

Key Flag: ls -la is crucial for security assessments, as it lists all files (including hidden ones) in long format.

cd (Change Directory): Used to move between directories, using both absolute and relative paths.

cat (Concatenate): Used to read the entire contents of a file at once.

find: Searches the file system for files based on various criteria (e.g., name, size).

3. Understanding File Permissions

File permissions are read using the long list format (ls -l). They define who (User, Group, Others) can read (r), write (w), and execute (x) a file or directory.

Significance: Understanding permissions is the first step in identifying misconfigurations that allow hackers to gain access or elevate privileges during a penetration test.

4. File Manipulation and Integrity

These commands are used to manage files and confirm their type, which is critical during assessment.

cp (Copy): Used to copy files or directories.

mv (Move/Rename): Used to move or rename files.

file: Determines the file type (e.g., ASCII text, executable binary) regardless of its extension. Essential for confirming file integrity.

5. Flags and Challenge Answers (YOU MUST EDIT THESE)

INSTRUCTION: Replace the [YOUR ANSWER HERE] placeholders below with the actual answers you retrieved from the TryHackMe room.

Task 3: Basic Commands

Command Used: cat <filename>

Answer: [YOUR ANSWER HERE - e.g., THM{ABC_XYZ}]

Task 4: Hidden File Contents

Command Used: ls -la and cat <hidden_file>

Answer: [YOUR ANSWER HERE - e.g., THM{ABC_XYZ}]

Task 6: The File Type

Command Used: file <filename>

Answer: [YOUR ANSWER HERE - e.g., ASCII text]

Task 6: Final Path

Command Used: pwd (after navigating)

Answer: [YOUR ANSWER HERE - e.g., /var/www/html/secret-dir]

Conclusion & Next Steps

Linux Fundamentals Part 1 establishes the command-line discipline required for technical roles. The next focus will be on dynamic system interaction, managing processes, controlling services, and handling software packages, as covered in Linux Fundamentals Part 2.
