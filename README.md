AYTHON HOUTTEKIER


*Install git

        sudo apt-get install git

*Install putty

        sudo apt-get install putty

*Install build-essential

        sudo apt-get install build-essential

*Create a directory in home called "hello_world"

        mkdir hello_world



*Change to the directory

        cd /home/aython/hello_world

*Do a git init

        git init

*Create a README.md file with this content and the actual commands executed


   nano README.md

*Add, commit and place on github

        git status
        git add file
        git commit -m "commentaar"
        git remote add origin https://github.com/aythonhouttekier/exerciselinux$
        git push origin master

*Add main.cpp to the dir and place the code for a hello world application into $

        nano main.cpp   (code erin zetten)

*Compile the application

        g++ main.cpp


*Add a gitignore for the binary file that was generated

        nano .gitignore

*Make sure to add, commit and push the latest updates

*Send the teacher a mail with the link of your repository
