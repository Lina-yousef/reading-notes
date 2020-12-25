 **Revisions and the Cloud**

Version Control (VCS): a system  allows to revisit various versions by recording changes. 
Local Version Control: database on your hard desk that stores changes to files.
Centralized Version Control (CVCS) :entails a single server storing all changed file versions , which can be access by various clients.
Distributed Version Control (DVCS) :addresses for major CVS, but if server failed CVS goes down.

Git What is it ?
-Snapshots : stores data in file system for every changed version.
-Local Operation : most information can be found in local resources and allow to work anytime.
-Tracking changes : every change applied i tracked by Git.
-Loss of data: Git minimize the possibility of damage file by taking snapshot. 
-Status : files can reside in three main stages (Commit , Modified, Stages). 

We can get Git by installing it and perform some customized steps. 

Local Git has three components :
1. Working directory : has actual files.
2.  Index : area used for staging.
3. Head : points to the most recent commit.

Tracking and Staging a new file :
- for single file: $ git add filename l| for all files :$ git add*  
- now files ready to commit :
   single file : $ git commit - " made change x, y ,z" || all files : $ git commit -a 
- Push changes:$ git push origin master         

Cloning repository : git will automatically named

  - "origin " :to server from which you clone. 
  - "master ": to your local branch.
  
[Previous](Read02.md)  | [Home](README.md) | [Next](Read04.md)
