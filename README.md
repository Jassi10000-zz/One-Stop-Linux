# One-Stop-Linux 🐧

<p align="center">
    <img src="https://github.com/Jassi10000/One-Stop-Linux/blob/main/Giphy/64db7ce4f02865fb2da34a66b24df251.gif" width="320" height="300"/>
</p>  

#### As already described in About section , <strong><i> One-Stop-Linux 🐧 </i></strong> will be a one stop resource which can help you get a walkthrough of basic Linux Commands 👨‍💻, whether you are noob or experienced this resource would definitely help you get on the track 🏋️‍♂️

## Files and Navigating ▶

Command      | What it does |
| ----------- | ----------- |
| <code> ls </code>      | directory listing ( list all files / folders on current dir ) |
| <code> ls -l </code>    | formatted listing  |
| <code> ls -la </code>    | formatted listing including hidden files |
| <code> cd dir </code>    | change directory to dir ( dir will be directory name ) |
| <code> cd .. </code>    | change to parent directory  |
| <code> cd ../dir </code> | change to dir in parent directory  |
| <code> cd </code> | change to home directory |
| <code> pwd </code> | show current directory |
| <code> mkdir dir </code> | create a directory dir |
| <code> rm file </code> | delete file |
| <code> rm -f dir </code> | force remove file |
| <code> rm -r dir </code> | delete directory dir |
| <code> rm -rf dir </code> | remove directory dir |
| <code> rm -rf / </code> | launch some neuclear bombs targetting your system |
| <code> cp file1 file2 </code> | copy file1 to file2 |
| <code> mv file1 file2 </code> | rename file1 to file2 |
| <code> mv file1 dir/file2 </code> | move file1 to dir as file2 |
| <code> touch file </code> | create or update file |
| <code> cat file </code> | output contents of file |
| <code> cat > file </code> | write standard input into file |
| <code> cat >> file </code> | append standard input into file |
| <code> tail -f file </code> | output contents of file as it grows |

## Networking ▶

Command      | What it does |
| ----------- | ----------- |
| <code> ping host </code> | ping host |
| <code> whois domain </code> | get whois for domain |
| <code> dig domain </code> | get DNS for domain |
| <code> dig -x host </code> | reserve lookup host |
| <code> wget file </code> | download file |
| <code> wget -c file </code> | continue stopped download |
| <code> wget -r url </code> | recursively download files from url |
| <code> curl url </code> | outputs the webpage from url |
| <code> curl -o meh.html url </code> | writes the page to meh.html |
| <code> ssh user@host </code> | connect to host as user | 
| <code> ssh -p port user@host </code> | connect using port |
| <code> ssh -D user@host </code> | connect & use bind part |


## Processes ▶

Command      | What it does |
| ----------- | ----------- |
| <code> ps </code > | display currently active processes |
| <code> ps aux </code> | detailed outputs |
| <code> kill pid </code> | kill process with process id ( pid ) |
| <code> killall proc </code> | kill all processes named proc | 

## System Info ▶

Command      | What it does |
| ----------- | ----------- |
| <code> date </code> | show current date / time |
| <code> uptime </code> | show uptime |
| <code> whoami </code> | who you're logged in as |
| <code> w </code> | display who is online |
| <code> cat/proc/cpuinfo </code> | display cpu info |
| <code> cat/proc/meminfo </code> | memory info |
| <code> free </code> | show memory and swap usage |
| <code> du </code> | show directory space usage |
| <code> du-sh </code> | displays readable sizes in GB |
| <code> df </code> | show disk usage |
| <code> unname -a | show karnel config |


## Compressing ▶

Command      | What it does |
| ----------- | ----------- |
| <code> tar cf file.tar files </code> | tar files into file.tar |
| <code> tar xf file.tar </code> | untar into current directory |
| <code> tar tf file.tar </code>  | show contents of archive |

### Options : 
    c - create archive
    r - table of contents
    x - extract 
    z - use zip / gzip 
    f - specify filename 
    j - bzip2 compression
    w - ask for confirmation
    k - do not overwrite
    T - files from files
    v - verbose
    
    
## Permissions ▶

Command      | What it does |
| ----------- | ----------- |
| <code> chmod octal file </code> | change permissions of file |
    
    4 - read ( r )
    2 - write ( w ) 
    1 - execute ( x )
    
    order: owner/group/world
    
    chmod 777 - rwx for everyone
    chmod 755 - rw for owner , rx for group world

## Some Others ▶

Command      | What it does |
| ----------- | ----------- |
| <code> grep pattern files </code> | search in files for pattern |
| <code> grep -r pattern dir </code> | search for pattern recursively in dir |
| <code> locate file </code> | find all instances of file |
| <code> whereis app </code> | show possible locations of app |
| <code> man command </code> | show manual page for command |
