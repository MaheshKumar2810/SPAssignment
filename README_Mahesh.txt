Name: Mahesh N Kumar
USN : 1PI12IS049

Team member:Akarsh
USN        :1PI12IS006

Question No.: 3
Question Title: Username, Password Reading from a file and matching the same.

My team member Akarsh has submitted source code file and Data file which is a text document,

asn2_3.c
Data.txt

*We have tried and succeeded in implementing whatever was asked,i.e, we have implemented getopt,
and also Log file will be generated which logs the code operations in the specified file.

*Input format will be ./a.out -f <filename> -l <logfilename>
We have validated the arguments that user passes, i.e, if the above format is violated,
appropriate messages are displayed and program is made to terminate

*Data.txt includes set of usernames and passwords.

*We had used strcmpi() for username which matches usernames irrespective of case, but some compilers
don't support it, when we tested on ubuntu gcc we got an error, so we have used strcmp().

*Once execution begins program will ask for username and password which will be matched
with the Data.txt contents, appropriate messages are displayed accordingly based on match/mismatch.

*We tried our level best to mask the password with ****, but we failed in implementing that.

*I hope I haven't missed anything, hoping for the best :p,

 Thank you, we learnt manythings while doing the assignment. 
