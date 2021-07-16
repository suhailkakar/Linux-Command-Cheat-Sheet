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
