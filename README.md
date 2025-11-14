"# demo-git-command-practice correct process refer it feature" 

Microsoft Windows [Version 10.0.26200.7019]
(c) Microsoft Corporation. All rights reserved.

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>echo "# demo-git-command-practice" >> README.md

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git init
Initialized empty Git repository in D:/Air-Asia-POC-7-11-2025/demo-git-command-practice-projects/demo-git-command-practice/.git/

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git add README.md

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git commit -m "first commit"
[master (root-commit) 24eb090] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git branch -M main

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git remote add origin https://github.com/RamaGopal-ZapCom/demo-git-command-practice.git

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 251 bytes | 251.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/RamaGopal-ZapCom/demo-git-command-practice.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitattributes
        .gitignore
        .mvn/
        mvnw
        mvnw.cmd
        pom.xml
        src/

nothing added to commit but untracked files present (use "git add" to track)

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git add .
warning: in the working copy of '.gitattributes', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.mvn/wrapper/maven-wrapper.properties', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'mvnw.cmd', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'pom.xml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/java/com/example/demo_git_command_practice/DemoGitCommandPracticeApplication.java', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/resources/application.properties', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/test/java/com/example/demo_git_command_practice/DemoGitCommandPracticeApplicationTests.java', LF will be replaced by CRLF the next time Git touches it

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitattributes
        new file:   .gitignore
        new file:   .mvn/wrapper/maven-wrapper.properties
        new file:   mvnw
        new file:   mvnw.cmd
        new file:   pom.xml
        new file:   src/main/java/com/example/demo_git_command_practice/DemoGitCommandPracticeApplication.java
        new file:   src/main/resources/application.properties
        new file:   src/test/java/com/example/demo_git_command_practice/DemoGitCommandPracticeApplicationTests.java


D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git commit -m "second commit"
[main b0ebc0b] second commit
 9 files changed, 628 insertions(+)
 create mode 100644 .gitattributes
 create mode 100644 .gitignore
 create mode 100644 .mvn/wrapper/maven-wrapper.properties
 create mode 100644 mvnw
 create mode 100644 mvnw.cmd
 create mode 100644 pom.xml
 create mode 100644 src/main/java/com/example/demo_git_command_practice/DemoGitCommandPracticeApplication.java
 create mode 100644 src/main/resources/application.properties
 create mode 100644 src/test/java/com/example/demo_git_command_practice/DemoGitCommandPracticeApplicationTests.java

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git push
Enumerating objects: 26, done.
Counting objects: 100% (26/26), done.
Delta compression using up to 8 threads
Compressing objects: 100% (18/18), done.
Writing objects: 100% (25/25), 9.53 KiB | 1.59 MiB/s, done.
Total 25 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/RamaGopal-ZapCom/demo-git-command-practice.git
   24eb090..b0ebc0b  main -> main

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

D:\Air-Asia-POC-7-11-2025\demo-git-command-practice-projects\demo-git-command-practice>
