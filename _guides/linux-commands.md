---
title: "Linux commands"
---

Basic Commands:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>ls -l</code> 
  <span style="margin-left: 10px; color: #555;"># List directory contents in long format, file type and permissions</span>
  <br>
  <code>ls -a</code>
  <span style="margin-left: 10px; color: #555;"># Shows all files, even hidden ones</span>
  <br>
  <code>ls -h</code> 
  <span style="margin-left: 10px; color: #555;"># Displays file sizes in a human-readable format</span>
  <br>
  <code>ls -R</code> 
  <span style="margin-left: 10px; color: #555;"># Displays subdirectories</span>
  <br>
  <code>cd /path/to/directory</code>  
  <span class="command-description"># Change directory</span>
  <br>
  <code>cd or cd ~ </code>  
  <span class="command-description"># HOME directory</span>
  <br>
  <code>cd .. </code>  
  <span class="command-description"># Move one level up </span>
  <br>
  <code>cd / </code>  
  <span class="command-description"># Root directory</span>
  <br>
  <code>cat > filename </code>  
  <span class="command-description"># Create a new file </span>
  <br>
  <code>cat filename </code>  
  <span class="command-description">#Display file </span>
  <br>
  <code>cat filename1 filename2 > filename3 </code>  
  <span class="command-description"># Merges two files and saves it as a new file </span>
  <br>
  <code>mv file "new path" </code>  
  <span class="command-description"># Moves file to a new path </span>
  <br>
  <code>mv file newfile </code>  
  <span class="command-description"># Rename file </span>
  <br>
  <code>mkdir directoryname  </code>  
  <span class="command-description"># Make a new directory</span>
  <br>
  <code>rm filename </code>  
  <span class="command-description"># Delete file</span>
  <br>
  <code>rmdir directoryname </code>  
  <span class="command-description"># Delete directory </span>
  <br>
  <code>pr -x </code>  
  <span class="command-description"># Divides the file into x columns</span>
  <br>
  <code>pr -h </code>  
  <span class="command-description"># Assigns a header to file</span>
  <br>
  <code>pr -n </code>  
  <span class="command-description"># Denotes the file with Line numbers</span>
  <br>
</div>
File Permission Commands:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>r </code> 
  <span style="margin-left: 10px; color: #555;"># Read permission</span>
  <br>
  <code>w </code> 
  <span style="margin-left: 10px; color: #555;"># Write permission</span>
  <br>
  <code>x </code> 
  <span style="margin-left: 10px; color: #555;"># Execute permission</span>
  <br>
  <code>-= </code> 
  <span style="margin-left: 10px; color: #555;"># No permission</span>
  <br>
  <code>chown user </code> 
  <span style="margin-left: 10px; color: #555;"># For changing the ownership of a file/directory</span>
  <br>
  <code>chown user:group filename </code> 
  <span style="margin-left: 10px; color: #555;"># Change user and group for a file/directory</span>
  <br>
  <code> </code> 
  <span style="margin-left: 10px; color: #555;"># </span>
  <br>
</div>
Environment Variables Commands:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>echo $VARIABLE </code> 
  <span style="margin-left: 10px; color: #555;"># Display value of variable</span>
  <br>
  <code>env </code> 
  <span style="margin-left: 10px; color: #555;"># Displays all environment variables</span>
  <br>
  <code>VARIABLE_NAME= var_name </code> 
  <span style="margin-left: 10px; color: #555;"># Create new variable</span>
  <br>
  <code>Unset </code> 
  <span style="margin-left: 10px; color: #555;"># Remove a variable</span>
  <br>
  <code>export Variable=value </code> 
  <span style="margin-left: 10px; color: #555;"># To set value of an environment variable</span>
  <br>
  <code> </code> 
  <span style="margin-left: 10px; color: #555;"># </span>
  <br>
</div>
User management Commands:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>sudo adduser username </code> 
  <span style="margin-left: 10px; color: #555;"># Add a new user</span>
  <br>
  <code>sudo passwd -l 'username' </code> 
  <span style="margin-left: 10px; color: #555;"># Change user password</span>
  <br>
  <code>sudo userdel -r 'username' </code> 
  <span style="margin-left: 10px; color: #555;"># Remove user</span>
  <br>
  <code>sudo usermod -a -G GROUP USERNAME </code> 
  <span style="margin-left: 10px; color: #555;"># Add user to a group</span>
  <br>
  <code>sudo deluser USER GROUP </code> 
  <span style="margin-left: 10px; color: #555;"># Remove user from a group</span>
  <br>
  <code>finger </code> 
  <span style="margin-left: 10px; color: #555;"># Displays user information of those logged in</span>
  <br>
  <code>finger username </code> 
  <span style="margin-left: 10px; color: #555;"># Shows information of user </span>
  <br>
</div>
Networking Commands:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>SSH username@ip_address or hostname </code> 
  <span style="margin-left: 10px; color: #555;"># Remote in using SSH</span>
  <br>
  <code>Ping hostname = "" or = "" </code> 
  <span style="margin-left: 10px; color: #555;"># To ping and analyzing network and host connections</span>
  <br>
  <code>dir </code> 
  <span style="margin-left: 10px; color: #555;"># Display files in directory</span>
  <br>
  <code>put file </code> 
  <span style="margin-left: 10px; color: #555;"># Upload a file from local to remote computer</span>
  <br>
  <code>get file </code> 
  <span style="margin-left: 10px; color: #555;"># Download file from remote computer to local</span>
  <br>
  <code>quit </code> 
  <span style="margin-left: 10px; color: #555;"># Logout</span>
  <br>
  <code> </code> 
  <span style="margin-left: 10px; color: #555;"># </span>
  <br>
</div>
Process Commands:

<div style="background-color: #f5f5f5; border: 1px solid #ccc; padding: 10px; margin-bottom: 10px; display: inline-block; font-family: 'Courier New', Courier, monospace;">
  <code>bg </code> 
  <span style="margin-left: 10px; color: #555;"># Send a process to the background</span>
  <br>
  <code>fg </code> 
  <span style="margin-left: 10px; color: #555;"># To run a process to the background</span>
  <br>
  <code>top </code> 
  <span style="margin-left: 10px; color: #555;"># Details on all active processes</span>
  <br>
  <code>ps </code> 
  <span style="margin-left: 10px; color: #555;"># Give the status of processes ID (PID) of a process</span>
  <br>
  <code>ps PID </code> 
  <span style="margin-left: 10px; color: #555;"># Give the status of a particular process</span>
  <br>
  <code>pidof </code> 
  <span style="margin-left: 10px; color: #555;"># Gives process ID (PID) of a process</span>
  <br>
  <code>kill PID# </code> 
  <span style="margin-left: 10px; color: #555;"># Kills a process</span>
  <br>
  <code>nice </code> 
  <span style="margin-left: 10px; color: #555;"># Starts a process with priority</span>
  <br>
  <code>renice </code> 
  <span style="margin-left: 10px; color: #555;"># Changes priority of an already running process</span>
  <br>
  <code>df </code> 
  <span style="margin-left: 10px; color: #555;"># Gives free hard disk space on your system</span>
  <br>
  <code>free </code> 
  <span style="margin-left: 10px; color: #555;"># Gives free RAM on your system</span>
  <br>
</div>


