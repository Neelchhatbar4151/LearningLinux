<h1>General Commands</h1>
<ul>
    <li>pwd → stands for print working directory, used for printing current working directory.</li>
    <li>cd → used to change the current working directory</li>
    <li>ls → used to list items of current working directory</li>
    <li>ls -R → used to list items recursively means list all directories and file in current directory and also list all the files and directories inside those directories.</li>
    <li>ls -a → to list files along with hidden files</li>
    <li>ls -l →to list all files with more details like read,wrie, execute permissions , Owner, group of users, creation time etc.., First character of each line denotes type of file, First Line of output says "total [Some number]". this number indicates that the total number of disk blocks that the files in the current directory have occupied, The next nine characters following the file type character are the file permissions. Each column in succession gives the number of links, owner name, group name, size of file in bytes, date and time when the file was last modified, and finally the file name. And number of links means number of different file names that points to the same file.
        <ul>
            <li>- → Ordinary File</li>
            <li>d → Directory File</li>
            <li>c → Character Special File(used to handle character oriented devices like terminal.These kind of files are found in /dev directory)</li>
            <li>b → Block Special File(used to handle block oriented devices like disks. These kind of files are found in /dev directory.)</li>
            <li>l → Symbolic Link</li>
            <li>s → Semaphore</li>
            <li>p → Named Pipe</li>
            <li>m → Shared memory File</li>
        </ul>
    </li>
    <li>ls [String]* → This command lets you search for a file in pwd which starts with given string in command. this String can be subset of Filename String or equals to fileName String (if the asterisk is before [String] then it'll return files having filenames ending with that String.)</li>
    <li>ls [?ain] → This command will return the Files which has fileNameLength of 4 and last 3 letters of fileName are "ain".</li>
    <li>ls [[aeiou]*] → This command will return the Files for which fileNames starts with vowel. (if the asterisk is before the [String] then it will return files for which fileNames ends with one of the letters.)</li>
    <li>ls [[!aeiou]*] → This command will return the Files for which fileNames does not starts with a vowel. (if the asterisk is before the [String] then it will return files for which fileNames not ends with one of the letters given in String.)</li>
    <li>ls [[a-m][c-z][4-9]??] → This will list all fileNames in the current directory whose first letter is in the range a to m, the second letter is in the range to c to z, the third letter is in the range 4 to 9, whereas the fourth and fifth letter can be any valid characters.</li>
    <li>chmod [number] [filename] → to change the read, write, execute permissions for owner,group of users and others.</li>
    <li>clear → for cleaning terminal view</li>
    <li>history → to check command history</li>
    <li>echo [string] → to printing something</li>
    <li>wc -l [file name] → It returns the numbers of lines exist in the given file</li>
</ul>
