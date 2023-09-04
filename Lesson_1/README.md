# GIT Basics Workshop
Resources used for a BearingPoint workshop

## Prerequisits 

1. Open an account in http://github.com/

2. Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for your operating system.

3. Verify the installation.

```
git --version
```
The system output should display the inslled version. (ex. git version 2.41.0).

## Commands

CLone the repository locally. 
```
git clone https://github.com/IgorStojanov-BE/workshop.git
```

Navigate to the local workshop folder
```
cd workshop
```
Create a new file and name it with your name.

```
touch Lesson_1/<YourName>.txt
```

Add your name inside the file.
```
echo "Hello, I am <YourName>" > Lesson_1/<YourName>.txt
```
Check the status of the file.
```
git status
```
Something similar to the following output will appear.
```
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   Lesson_1/YourName.txt
```

Commit the file to the repository. 
```
$ git commit -m "Added IgorStojanov.txt"
$ git push origin master
```
