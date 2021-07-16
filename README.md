
<p align="center">
    <img width="200" height="auto" src="https://i.ibb.co/ss17KG0/c7b8113247fecd83bd9b5ed5bd3f34d5-removebg-preview.png" alt="Linux Logo" />
</p>
   
The Linux command is a utility of the Linux operating system. All basic and advanced tasks can be done by executing commands. The commands are executed on the Linux terminal.The terminal is a command-line interface to interact with the system, which is similar to the command prompt in the Windows OS.





## File Permission commands

<table>

<thead>

<tr>

<th width="50%">Command</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>ls-l</td>

<td>to show file type and access permission</td>

</tr>

<tr>

<td>r</td>

<td>read permission</td>

</tr>

<tr>

<td>w</td>

<td>write permission</td>

</tr>

<tr>

<td>x</td>

<td>execute permission</td>

</tr>

<tr>

<td>-=</td>

<td>no permission</td>

</tr>

<tr>

<td>Chown user</td>

<td>For changing the ownership of a file/directory</td>

</tr>

<tr>

<td>Chown user:group filename</td>

<td>change the user as well as group for a file or directory</td>

</tr>

</tbody>

</table>
<br />

## Basic Linux commands

<table>

<thead>

<tr>

<th width="50%">Command</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>ls</td>

<td>Lists all files and directories in the present working directory</td>

</tr>

<tr>

<td>ls-R</td>

<td>Lists files in sub-directories as well</td>

</tr>

<tr>

<td>ls-a</td>

<td>Lists hidden files as well</td>

</tr>

<tr>

<td>ls-al</td>

<td>Lists files and directories with detailed information like permissions,size, owner, etc.</td>

</tr>

<tr>

<td>cd or cd ~</td>

<td>Navigate to HOME directory</td>

</tr>

<tr>

<td>cd ..</td>

<td>Move one level up</td>

</tr>

<tr>

<td>cd</td>

<td>To change to a particular directory</td>

</tr>

<tr>

<td>cd /</td>

<td>Move to the root directory</td>

</tr>

<tr>

<td>cat > filename</td>

<td>Creates a new file</td>

</tr>

<tr>

<td>cat filename</td>

<td>Displays the file content</td>

</tr>

<tr>

<td>cat file1 file2 > file3</td>

<td>Joins two files (file1, file2) and stores the output in a new file (file3)</td>

</tr>

<tr>

<td>mv file "new file path"</td>

<td>Moves the files to the new location</td>

</tr>

<tr>

<td>mv filename new_file_name</td>

<td>Renames the file to a new filename</td>

</tr>

<tr>

<td>sudo</td>

<td>Allows regular users to run programs with the security privileges of the superuser or root</td>

</tr>

<tr>

<td>rm filename</td>

<td>Deletes a file</td>

</tr>

<tr>

<td>man</td>

<td>Gives help information on a command</td>

</tr>

<tr>

<td>history</td>

<td>Gives a list of all past commands typed in the current terminal session</td>

</tr>

<tr>

<td>clear</td>

<td>Clears the terminal</td>

</tr>

<tr>

<td>mkdir directoryname</td>

<td>Creates a new directory in the present working directory or a at the specified path</td>

</tr>

<tr>

<td>rmdir</td>

<td>Deletes a directory</td>

</tr>

<tr>

<td>mv</td>

<td>Renames a directory</td>

</tr>

<tr>

<td>pr -x</td>

<td>Divides the file into x columns</td>

</tr>

<tr>

<td>pr -h</td>

<td>Assigns a header to the file</td>

</tr>

<tr>

<td>pr -n</td>

<td>Denotes the file with Line Numbers</td>

</tr>

<tr>

<td>lp -nc , lpr c</td>

<td>Prints "c" copies of the File</td>

</tr>

<tr>

<td> lp-d lp-P</td>

<td>Specifies name of the printer</td>

</tr>

<tr>

<td>apt-get</td>

<td>Command used to install and update packages</td>

</tr>

<tr>

<td>mail -s 'subject' -c 'cc-address' -b 'bcc-address' 'to-address'</td>

<td>Command to send email</td>

</tr>

<tr>

<td>mail -s "Subject" to-address < Filename</td>

<td>Command to send email with attachment</td>

</tr>

</tbody>

</table>

<br />

## Environment Variables command


<table class="table1 table-striped">

<thead>

<tr>

<th width="50%">Command</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>echo $VARIABLE</td>

<td>To display value of a variable</td>

</tr>

<tr>

<td>env</td>

<td>Displays all environment variables</td>

</tr>

<tr>

<td>VARIABLE_NAME= variable_value</td>

<td>Create a new variable</td>

</tr>

<tr>

<td>Unset</td>

<td>Remove a variable</td>

</tr>

<tr>

<td>export Variable=value</td>

<td>To set value of an environment variable</td>

</tr>

</tbody>

</table>

<br />

## User management commands of linux

<table class="table1 table-striped">

<thead>

<tr>

<th width="50%">Command</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>sudo adduser username</td>

<td>To display value of a variable</td>

</tr>

<tr>

<td>sudo passwd -l 'username'</td>

<td>Displays all environment variables</td>

</tr>

<tr>

<td>sudo userdel -r 'username'</td>

<td>Create a new variable</td>

</tr>

<tr>

<td>sudo usermod -a -G GROUPNAME USERNAME</td>

<td>Remove a variable</td>

</tr>

<tr>

<td>sudo deluser USER GROUPNAME</td>

<td>To set value of an environment variable</td>

</tr>

<tr>

<td>finger</td>

<td>Gives information on all logged in user</td>

</tr>

<tr>

<td>finger username</td>

<td>Gives information of a particular user</td>

</tr>

</tbody>

</table>

<br />

## Networking command

<table class="table1 table-striped">

<thead>

<tr>

<th width="50%">Command</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>SSH username@ip-address or hostname</td>

<td>login into a remote Linux machine using SSH</td>

</tr>

<tr>

<td>Ping hostname="" or =""</td>

<td>To ping and Analyzing network and host connections</td>

</tr>

<tr>

<td>dir</td>

<td>Display files in the current directory of a remote computer</td>

</tr>

<tr>

<td>cd "dirname"</td>

<td>change directory to "dirname" on a remote computer</td>

</tr>

<tr>

<td>put file</td>

<td>upload 'file' from local to remote computer</td>

</tr>

<tr>

<td>get file</td>

<td>Download 'file' from remote to local computer</td>

</tr>

<tr>

<td>quit</td>

<td>Logout</td>

</tr>

</tbody>

</table>

<br />

## Process command

<table class="table1 table-striped">

<thead>

<tr>

<th width="50%">Command</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>bg</td>

<td>To send a process to the background</td>

</tr>

<tr>

<td>fg</td>

<td>To run a stopped process in the foreground</td>

</tr>

<tr>

<td>top</td>

<td>Details on all Active Processes</td>

</tr>

<tr>

<td>ps</td>

<td>Give the status of processes running for a user</td>

</tr>

<tr>

<td>ps PID</td>

<td>Gives the status of a particular process</td>

</tr>

<tr>

<td>pidof</td>

<td>Gives the Process ID (PID) of a process</td>

</tr>

<tr>

<td>kill PID</td>

<td>Kills a process</td>

</tr>

<tr>

<td>nice</td>

<td>Starts a process with a given priority</td>

</tr>

<tr>

<td>renice</td>

<td>Changes priority of an already running process</td>

</tr>

<tr>

<td>df</td>

<td>Gives free hard disk space on your system</td>

</tr>

<tr>

<td>free</td>

<td>Gives free RAM on your system</td>

</tr>

</tbody>

</table>

<br />

## VI Editing Commands

<table class="table1 table-striped">

<thead>

<tr>

<th width="50%">Command</th>

<th>Description</th>

</tr>

</thead>

<tbody>

<tr>

<td>i</td>

<td>Insert at cursor (goes into insert mode)</td>

</tr>

<tr>

<td>a</td>

<td>Write after cursor (goes into insert mode)</td>

</tr>

<tr>

<td>A</td>

<td>Write at the end of line (goes into insert mode)</td>

</tr>

<tr>

<td>ESC</td>

<td>Terminate insert mode</td>

</tr>

<tr>

<td>u</td>

<td>Undo last change</td>

</tr>

<tr>

<td>U</td>

<td>Undo all changes to the entire line</td>

</tr>

<tr>

<td>o</td>

<td>Open a new line (goes into insert mode)</td>

</tr>

<tr>

<td>dd</td>

<td>Delete line</td>

</tr>

<tr>

<td>3dd</td>

<td>Delete 3 lines</td>

</tr>

<tr>

<td>D</td>

<td>Delete contents of line after the cursor</td>

</tr>

<tr>

<td>C</td>

<td>Delete contents of a line after the cursor and insert new text. Press ESC key to end insertion.</td>

</tr>

<tr>

<td>dw</td>

<td>Delete word</td>

</tr>

<tr>

<td>4dw</td>

<td>Delete 4 words</td>

</tr>

<tr>

<td>cw</td>

<td>Change word</td>

</tr>

<tr>

<td>x</td>

<td>Delete character at the cursor</td>

</tr>

<tr>

<td>r</td>

<td>Replace character</td>

</tr>

<tr>

<td>R</td>

<td>Overwrite characters from cursor onward</td>

</tr>

<tr>

<td>s</td>

<td>Substitute one character under cursor continue to insert</td>

</tr>

<tr>

<td>S</td>

<td>Substitute entire line and begin to insert at the beginning of the line</td>

</tr>

<tr>

<td>~</td>

<td>Change case of individual character</td>

</tr>

</tbody>

</table>
