Efficient Backups
-------
Git is an efficient version control system.  It works by only storing the differences between one revision and the next instead of a copy of every file.  Currently, the backup system copies the files completely instead of only storing the backups.  Change the backup scripts so that our backup system only stores the differences between each file rather than a copy of each file.  You will need (1) A time-stamped base state from to which the first differences will be applied and then time-stamped folders containing the successive differences.  Submit your script and make sure your new backup system is working and that you can restore the backed-up files.

If you cannot implement the above, modify the script instead to check if the files are the same and then only back up the files that have been changed.  Also, create a folder that has links to the most recent files.  Submit your script.

If you cannot do either of the above, research how you would do it and submit a written plan.
