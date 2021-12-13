System Basic:

date Show date and time
uptime Display system uptime
cal Show calendar
w Display who is logged in
whoami Display effective username
finger user Show info about user
uname -a Show kernel info
man cmd Show man page for cmd
df Display free disk space
du Display disk usage stats
free Show memory and swap usage
whereis app Show where app location is
which app Show which app

Directories Basic:
ls -l List current dir contents (long format)
ls List current dir contents
ls -a List current dir contents including hidden
ls -t List current dir contents sorted by mod date
cd Change to home dir
cd dir Change to directory 'dir'
pwd Show current directory
mkdir dir Make directory 'dir'
rm -r dir Remove directory 'dir'
rm -rf dir Remove directory 'dir' (force)
cp -r dir1 dir 2Copy 'dir1' to 'dir2'
cd - Change to previous working dir

Files Basic:
rm file Remove 'file'
rm -f file Remove 'file' (force)
cp file1 file2 Copy 'file1' to 'file2'
mv file1 file2 Rename or move file1 to file2
ln -s file1 link1 Create symbolic 'link1' to 'file1'
touch file Create or update 'file'
cat>file Put standard output into 'file'
more file Output file 'file'
head file Output first 10 lines of 'file'
tail file Output last 10 lines of 'file'
tail -f file Output 'file' as it grows

Search Basic:
grep pattern files Search for 'pattern' in 'files'
grep -r pattern dir Search recursively for 'pattern' in dir
cmd | grep pattern Search for 'pattern' in output of cmd
locate file Find file names quickly

Shortcuts:
ctrl+c Halt current command
[!] ctrl+z Background current command
[!] ctrl+d Delete char infront of cursor or logout
[!] ctrl+u Erase line
[!] ctrl+r Search recent commands
ctrl+a Move to beginning of line
ctrl+e Move to end of line
[!] ctrl+h Delete char behind cursor (backspace)
[!] UP Move to previous command
[!] DOWN Move to next command

Processes:
[!] ps Display your active processes
[!] top Display all processes
kill 5 Terminate process id of 5
[!] kill -9 5 Terminate (KILL) process id of 5
[!] killall proc Terminate all processes named 'proc'
bg List background jobs
fg Bring most recent job to foreground
fg 2 Bring job 2 to foreground

Command History:
!! Repeat last command
sudo !! Repeat last command as root
[!] UP Move to previous command
[!] DOWN Move to next command
!3 Execute command 3 in history
history Show command history

Compression:
tar cf file.tar files Create a tar 'file.tar' with 'files'
tar xf file.tar Extract files from 'file.tar'
tar czf file.tar.gz files Create tar with gzip compression
tar xzf file.tar.gz Extract files from file.tar.gz
gzip file Compress 'file' with gzip
gzip -d file.gz Decompress file.gz
