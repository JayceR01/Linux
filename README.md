# File permissions in Linux
# This project was done during the Google Cybersecurity certificate so they had files for us to dive into and use for this.

# Checking file and directory details
ls -la

# Change file permissions for the other group to no longer have write permissions for project_k.txt
chmod o-w project_k.txt
ls -la

# Change file permissions on a hidden file to remove write permissions for user and group, and add read permissions to group for project_x.txt
chmod u-w,g-w,g+r .project_x.txt
ls -la

# Change directory permissions so that group does not have execute permissions
chmod g-x drafts
ls -la

# A more in depth summary to what I was doing and why, as well as the outputs
[File permissions in Linux portfolio project.pdf](https://github.com/JayceR01/Linux/files/14378725/File.permissions.in.Linux.portfolio.project.pdf)
