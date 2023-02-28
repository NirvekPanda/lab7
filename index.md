__**Lab Report 4**__

For the lab report this week, reproduce the task from the competition on your own. For each numbered step starting right after the timer (so steps 4-9), take a screenshot, and write down exactly which keys you pressed to get to that step. For special characters like <enter> or <tab>, write them in angle brackets with code formatting. Then, summarize the commands you ran and what the effect of those keypresses were.

__Clone Repository__
```
git clone git@github.com:NirvekPanda/lab7.git 
<enter>
ls
cd lab7
ls
```
[!clone repo](https://github.com/NirvekPanda/lab7/blob/main/images/image1.png)

    
__Test Code__
```
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```

__Debug Code__    
```
nano ListExample.java 
    CTRL + _
    type 42 
    change 1 to 2 to update correct variables
Ctrl + O
Ctrl + X
```
    
__Test Code Again__
```
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```
    
__Commit and Push to Github__
```
git add ListExamples.java
git commit -m “lab report 4”
git push origin main
```
