pwd - prints the absolute path name of the current working directory

ls - Display the contents list of your current directory.

cd ~ - changes the working directory to the user’s home directory.

ls -l - Display current directory contents in a long format

ls -al - Display current directory contents, including hidden files (starting with .). Use the long format.

ls -al - Display current directory contents.
Long format
with user and group IDs displayed numerically
And hidden files (starting with .)

mkdir /tmp/my_first_directory/ -  creates a directory named my_first_directory in the /tmp/ directory.

mv /tmp/betty /tmp/my_first_directory/betty - Move the file betty.

rm /tmp/my_first_directory/betty - Delete the file betty.

rm -rf /tmp/my_first_directory - Delete the directory my_first_directory that is in the /tmp directory.

cd - changes the working directory to the previous one

ls -la . .. /boot - lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file /tmp/iamafile -  prints the type of the file named iamafile

ln -s /bin/ls __ls__ - symbolic link to /bin/ls, named __ls__

cp -u *.html .. -  copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

mv [[:upper:]]* /tmp/u - moves all files beginning with an uppercase letter to the directory /tmp/u

mkdir -p welcome/to/school - creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

ls -xamp - lists all the files and directories of the current directory, separated by commas (,).

o string SCHOOL School data
!:mime School                 - file school.mgc that can be used with the command file to detect School data files.
