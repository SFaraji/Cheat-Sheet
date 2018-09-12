# TERMINAL-cheat-sheet
This is a cheat sheet sheet served with all the important commands used in the mac os terminal.


<h2 align="center" id="index">INDEX</h2>

<pre>
<ul>
<li><h2><a href="#shortcuts" >SHORTCUTS</a></h2></li>
<li><h2><a href="#directory">DIRECTORY MANIPULATION COMMANDS</a></h2></li>
<li><h2><a href="#file">FILE MANIPULATION COMMANDS</a></h2></li>
<li><h2><a href="#network">NETWORKING COMMANDS</a></h2></li>
<li><h2><a href="#system">SYSTEM COMMANDS</a></h2></li>
<li><h2><a href="#performance">PERFORMANCE COMMANDS</a></h2></li>
</ul>
</pre>


<h2 align="center" id="shortcuts">SHORTCUTS</h2>

<table>
  <tr>
    <th>KEYS                               </th>
    <th>description                                                          </th>
  </tr>
  <tr>
    <td>Ctrl + A</td>
    <td>Go to the beginning of the line you are currently typing on.</td> 
  </tr>
   <tr>
    <td>Ctrl + E</td>
    <td>Go to the end of the line you are currently typing on.</td> 
  </tr>
   <tr>
    <td>Ctrl + L</td>
    <td>Clears the Screen, similar to the clear command.</td> 
  </tr>
   <tr>
    <td>⌘Cmd + K</td>
    <td>Clears the Screen, similar to the clear command.</td> 
  </tr>
   <tr>
    <td>Ctrl + U</td>
    <td>Clears the line before the cursor position.If you are at the end of the line,clears the entire line.</td> 
  </tr>
   <tr>
    <td>Ctrl + W</td>
    <td>cuts one word backward.</td> 
  </tr>
  <tr>
    <td>Ctrl + T</td>
    <td>Swap the last two characters before the cursor.</td> 
  </tr>
   <tr>
    <td>Esc + T</td>
    <td>Swap the last two words before the cursor.</td> 
  </tr>
   <tr>
    <td>Ctrl + H</td>
    <td>backspace</td> 
  </tr>
   <tr>
    <td>Ctrl + Y</td>
    <td>Paste whatever was cut by the last cut command.</td> 
  </tr>
   <tr>
    <td>Ctrl + F</td>
    <td>Move cursor one character forward.</td> 
  </tr> 
  <tr>
    <td>Ctrl + B</td>
    <td>Move cursor one character backward.</td> 
  </tr> 
  <tr>
    <td>Esc + F</td>
    <td>Move cursor one word forward.</td> 
  </tr> 
  <tr>
    <td>Esc + B</td>
    <td>Move cursor one word backward.</td> 
  </tr> 
  <tr>
    <td>Ctrl + R</td>
    <td>Let’s you search through previously used commands.</td> 
  </tr>
   <tr>
    <td>Ctrl + C</td>
    <td>Kill whatever you are running.</td> 
  </tr>
   <tr>
    <td>Ctrl + D</td>
    <td>Exit the current shell.</td> 
  </tr>
  <tr>
    <td>Ctrl + Z</td>
    <td>Puts whatever you are running into a suspended background process.fg restores it.</td> 
  </tr>
</table>
<h4 align="center"><a href="#index">Back to index</a></h4>


<h2 id="directory" align="center">DIRECTORY MANIPULATION COMMANDS</h2>
<table>
  <tr>
    <th>COMMAND                           </th>
    <th>description                                                          </th>
  </tr>
  <tr>
    <td>pwd</td>
    <td>Display the present working directory.</td> 
  </tr>
  <tr>
    <td>ls</td>
    <td>lists the files and directories present in the working directory.</td> 
  </tr>
   <tr>
    <td>cd</td>
    <td>takes to the home directory.</td> 
  </tr>
   <tr>
    <td>cd directory-name</td>
    <td>changes the path to the given directory.</td> 
  </tr>
   <tr>
    <td>cd ..</td>
    <td>takes to the the previous directory.</td> 
  </tr>
   <tr>
    <td>mkdir directory-name</td>
    <td>creates a new directory.</td> 
  </tr>
   <tr>
    <td>rmdir -r directory-name</td>
    <td>removes the directory.</td> 
  </tr>
  <tr>
    <td>rm -rf directory-name</td>
    <td>Forcefully remove directory recursively.</td> 
  </tr>
   <tr>
    <td>cp -r source_directory-name destination_directory-name</td>
    <td>Copy source_directory recursively to destination.</td> 
  </tr>
   
</table>
<h4 align="center"><a href="#index">Back to index</a></h4>


<h2 id="file" align="center">FILE MANIPULATION COMMANDS</h2>
<table>
  <tr>
    <th>COMMAND                           </th>
    <th>description                                                          </th>
  </tr>
  <tr>
    <td>touch file-name</td>
    <td>Create an empty file or update the access and modification times of file.</td> 
  </tr>
  <tr>
    <td>rm file-name</td>
    <td>Remove (delete) file.</td> 
  </tr>
   <tr>
    <td>rm -f file</td>
    <td>Force removal of file without prompting for confirmation.</td> 
  </tr>
   <tr>
    <td>cp file1 file2</td>
    <td>Copy file1 to file2.</td> 
  </tr>
   <tr>
    <td>mv file1 file2</td>
    <td>Rename or move file1 to file2. If file2 is an existing directory, move file1 into directory file2.</td> 
  </tr>
   <tr>
    <td>cat file-name</td>
    <td>View the contents of file.</td> 
  </tr>
   <tr>
    <td>less file-name</td>
    <td>Browse through a text file.</td> 
  </tr>
  <tr>
    <td>head file-name</td>
    <td>Display the first 10 lines of file.</td> 
  </tr>
   <tr>
    <td>tail file-name</td>
    <td>Display the last 10 lines of file.</td> 
  </tr>
  <tr>
    <td>chown user-name file-name</td>
    <td>changes the owner of a file.</td> 
  </tr>
  <tr>
    <td>sudo command</td>
    <td>exicutes the command as super user.</td> 
  </tr>
  <tr>
    <td>chmod permissions file-name</td>
    <td>changes the permissions of the file.</td> 
  </tr>
   
</table>
<h4 align="center"><a href="#index">Back to index</a></h4>


<h2 id="network" align="center">NETWORK COMMANDS</h2>
<table>
  <tr>
    <th>COMMAND                           </th>
    <th>description                                                          </th>
  </tr>
  <tr>
    <td>ifconfig</td>
    <td>Display all network interfaces and ip address.</td> 
  </tr>
  <tr>
    <td>ifconfig eth0</td>
    <td>Display eth0 address and details.</td> 
  </tr>
   <tr>
    <td>ping host-name</td>
    <td>Send ICMP echo request to host.</td> 
  </tr>
   <tr>
    <td>whois domain-name</td>
    <td>Display whois information for domain.</td> 
  </tr>
   <tr>
    <td>dig domain-name</td>
    <td>Display DNS information for domain.</td> 
  </tr>
   <tr>
    <td>dig -x IP_ADDRESS</td>
    <td>Reverse lookup of IP_ADDRESS.</td> 
  </tr>
   <tr>
    <td>host domain-name</td>
    <td>Display DNS ip address for domain.</td> 
  </tr>  
</table>
<h4 align="center"><a href="#index">Back to index</a></h4>


<h2 id="system" align="center">SYSTEM COMMANDS</h2>
<table>
  <tr>
    <th>COMMAND                           </th>
    <th>description                                                          </th>
  </tr>
  <tr>
    <td>uname</td>
    <td>Display the kernal name.</td> 
  </tr>
  <tr>
    <td>uname -r</td>
    <td>Display kernel release information.</td> 
  </tr>
   <tr>
    <td>uptime</td>
    <td>Show how long the system has been running.</td> 
  </tr>
   <tr>
    <td>hostname</td>
    <td>Show system host name.</td> 
  </tr>
   <tr>
    <td>last reboot</td>
    <td>Show system reboot history.</td> 
  </tr>
   <tr>
    <td>date</td>
    <td>Show the current date and time.</td> 
  </tr>
   <tr>
    <td>cal</td>
    <td>Show this month's calendar.</td> 
  </tr>
  <tr>
    <td>w</td>
    <td>Display who is online.</td> 
  </tr>
  <tr>
    <td>whoami</td>
    <td>Who you are logged in as.</td> 
  </tr>
</table>
<h4 align="center"><a href="#index">Back to index</a></h4>

<h2 id="performance" align="center">PERFORMANCE COMMANDS</h2>
<table>
  <tr>
    <th>COMMAND                           </th>
    <th>description                                                          </th>
  </tr>
  <tr>
    <td>top</td>
    <td>Display and manage the top processes.</td> 
  </tr>
  <tr>
    <td>lsof</td>
    <td>List all open files on the system.</td> 
  </tr>
   <tr>
    <td>lsof -u user-name</td>
    <td>List files opened by user.</td> 
  </tr>
</table>
<h4 align="center"><a href="#index">Back to index</a></h4>




