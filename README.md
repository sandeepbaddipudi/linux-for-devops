Here is a practical Linux Commands Cheat Sheet for DevOps Engineers. use this as the foundation for linux-for-devops.


1. File & Directory Management

    • pwd. Prints the current working directory path.
    
    • ls. Lists files and folders (ls -la shows hidden files and detailed permissions).
    
    • cd. Changes the current directory (e.g., cd /var/log or cd .. to go up one level).
    
    • mkdir. Creates a new directory (mkdir -p creates nested directories at once).
    
    • touch. Creates an empty file or updates an existing file's timestamp.
    
    • cp. Copies files or directories (cp -r copies folders recursively).
    
    • mv. Moves or renames files and directories.
   
    • rm. Deletes files (rm -rf forcefully removes directories and their contents).
   
    • ln. Creates hard or symbolic links (ln -s target link_name).

2. Viewing, Editing & Searching Text
   
    • cat. Displays the entire contents of a file in the terminal.
   
    • less / more. Views long files one page at a time.
   
    • head / tail. Shows the first or last 10 lines of a file (tail -f monitors live log updates).
   
    • grep. Searches for text patterns inside files or command outputs.
   
    • find. Searches for files and directories matching specific criteria (name, size, date).
   
    • sed / awk. Streams and transforms text or processes structured columns of data.
   
    • sort / uniq / wc. Sorts lines, filters duplicates, and counts lines, words, or characters.
   
    • nano / vim. Terminal-based text editors for modifying files directly.


3. Permissions & User Management

    • sudo. Executes a single command with superuser (root) privileges.
   
    • chmod. Modifies file read, write, and execute permissions (e.g., chmod 755 script.sh).
   
    • chown. Changes the user and group ownership of a file or directory.
   
    • whoami / id. Displays your current username, user ID (UID), and group memberships.
   
    • useradd / usermod / passwd. Creates user accounts, modifies them, and updates passwords.

4. System Monitoring & Process Control

    • top / htop. Displays a real-time, interactive view of running processes and resource usage.
    
    • ps. Lists active processes (ps aux shows all running processes on the system).
    
    • kill / pkill. Terminates processes by Process ID (PID) or name.
    
    • df / du. Checks free disk space on filesystems (df -h) and directory sizes (du -sh).
    
    • free. Displays available and used system RAM (free -h).
    
    • uname. Prints kernel and OS architecture details (uname -a).
    
    • systemctl. Starts, stops, enables, and checks the status of system services.
    
    
5. Networking & File Transfer
    
    • ip / ifconfig. Displays and configures network interfaces and IP addresses.
    
    • ping. Tests network connectivity to a remote host.
    
    • ss / netstat. Lists active network connections and listening ports.
    
    • ssh. Connects securely to a remote Linux server.
    
    • scp / rsync. Securely copies or synchronizes files between local and remote machines.
    
    • curl / wget. Transfers data from URLs or downloads files from the web.
    
    
6. Archives & Package Management
    
    • tar. Creates or extracts .tar and .tar.gz archives (tar -xzvf file.tar.gz).
    
    • zip / unzip. Compresses and extracts .zip archives.
    
    • apt / dnf / pacman. Installs, updates, and removes software packages depending on your distribution (Debian/Ubuntu, RHEL/Fedora, or Arch).

7. Linux directory structure
<img width="900" height="490" alt="image" src="https://github.com/user-attachments/assets/50a36fcd-a18f-4598-8f9d-eb78a1ae641d" />

   
