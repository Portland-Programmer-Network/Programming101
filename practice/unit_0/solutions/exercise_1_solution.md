# Unit 0 Practice Solutions

## Exercise 1

This solution was created using a Linux terminal. A terminal on a Mac OS will look similar. If you're on Windows, instead of

    [myComputer Desktop]$

You may see something more like:

    C:\Users\currentUser\Desktop>

### 1.1

**Solution**

Make sure the terminal is navigated on the `Desktop`

    [myComputer Desktop]$

If you type `ls`, you should see the contents of the `Desktop`.

If you are not on the `Desktop` or would like to place your `ppn_code` directory somewhere else, use `cd <DIRECTORY_NAME>` to change directory.

    [myComputer ~]$ ls
    Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos

    [myComputer ~]$ cd Desktop

    [myComputer Desktop]$

Once you've navigated to the desired directory, use the command `mkdir` to create a directory named `ppn_code`.

    [myComputer Desktop]$ mkdir ppn_code

    [myComputer Desktop]$ ls
    ppn_code

Now we can navigate into our `ppn_code` directory

    [myComputer Desktop]$ cd ppn_code

    [myComputer ppn_code]$

Inside your directory, create a directory for `programming_101` and a directory called `extra`

    [myComputer ppn_code]$ mkdir programming_101 extra

Notice `mkdir` is only executed once, but multiple directories are created by separating their names with spaces

Now if we type `ls` we see our new directories

    [myComputer ppn_code]$ ls
    extra programming_101

Navigate into the `programming_101` directory

    [myComputer ppn_code]$ cd programming_101

    [myComputer programming_101]$

Inside the `programming_101` directory, create directories for each of the five units for the course: `unit_1`, `unit_2`, `unit_3`, `unit_4` and `unit_5`. Type `ls` to see the new directories.

    [myComputer programming_101]$ mkdir unit_1 unit_2 unit_3 unit_4 unit_5

    [myComputer programming_101]$ ls
    unit_1 unit_2 unit_3 unit_4 unit_5

Using `cd ..` navigate back up to the `ppn_code` directory. The `..` refers to the parent directory of the current directory

    [myComputer programming_101]$ cd ..

    [myComputer ppn_code]$

Create a `programming_102` directory. Create a directory for each unit in Programming 102: `unit_1`, `unit_2`, `unit_3`, `unit_4` and `unit_5`

    [myComputer ppn_code]$ mkdir programming_102

    [myComputer ppn_code]$ ls
    extra programming_101 programming_102

    [myComputer ppn_code]$ cd programming_102

    [myComputer programming_102]$ mkdir unit_1 unit_2 unit_3 unit_4 unit_5

We actually don't need our `extra` directory. Navigate to the `ppn_code` directory using the terminal and delete it using `rm -r <DIRECTORY_NAME>`.

    [myComputer programming_102]$ cd ..

    [myComputer ppn_code]$ ls
    extra programming_101 programming_102

    [myComputer programming_102]$ rm -r extra

    [myComputer programming_102]$ ls
    programming_101 programming_102

## [< Exercise 1](../exercise_1.md)

### [<< Back to syllabus](../../)
