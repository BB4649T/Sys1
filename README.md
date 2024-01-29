#Introduction
First, I signed up on warchall.net, entered my email address with a password, and confirmed them. After that, I went to the challenge, stole the flag, and entered in. Then, the website provided SSH access to my terminal so I could begin the challenge. 
 #Command:
- cd : change directory;
- cat: show the content;
- ls: list files in the current folder;
- ls -al: list all files even who are hide;

For every level that I passed, here are the steps:

1. **Level 0**:
    - Commands:
        ```
        ls
        cd 00_welcome
        ls
        cat README.md
        ```
    - Solution: `bitwarrior`

2. **Level 4**:
    - Commands:
        ```
        cd 04_kwisatz
        ls
        cat README.nfo
        ls ~
        cd ~/level
        ls
        cd 04_kwisatz
        ls
        cat README.txt
        cat README2.md
        chmod +rwx README2.md
        ```
    - Solution: `AndOfCourseIDoKnowChown`

3. **Level 3**:
    - Commands:
        ```
        cd 03
        ls -al
        cat ./.bash_history
        ```
    - Solution: `RepeatingHistory`

4. **Level 2**:
    - Commands:
        ```
        cd 02
        ls -al
        cd ./.porb
        ls -al
        cat ./.solution
        ```
    - Solution: `HiddenIsConfig`

5. **Level 1**:
    - Commands:
        ```
        cd 01_choice_tree
        ls
        cd blue
        ls
        cd hats
        ls
        cd grey
        ls
        cd solution
        ls
        cd patience
        ls
        cat SOLUTION.txt
        ```
    - Solution: `patience`

6. **Level 5**:
    - Commands:
        ```
        cd 05_privacy
        ls
        cat README.md
        ```
    - Solution: `OKPRIVATE`

7. **Level 10**:
    - Commands:
        ```
        cd /home/level/10_choose_path
        ls
        ./charp "solution.txt | cp solution.txt /tmp/solutionVraie.txt"
        ```
    - Solution: `EpidermalGlance`

