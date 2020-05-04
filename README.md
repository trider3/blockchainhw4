# CSC 4980 HW4
## Step 1
Clone the repository and cd into it
## Step 2
Open Ganache
## Step 3
Run the following commands in terminal:
```
truffle init
truffle compile
truffle migrate --reset --all
truffle develop
```
## Step 4
Run the following commands in the develop console:
```
Courses.deployed().then(function(instance){return instance.setInstructor("INSERT YOUR ACCOUNT ADDRESS HERE",19,"Thomas","Rider");})
Courses.deployed().then(function(instance){return instance.getInstructor("INSERT THE SAME ADDRESS YOU PUT IN THE ABOVE COMMAND");})
Courses.deployed().then(function(instance){return instance.getInstructors();})
Courses.deployed().then(function(instance){return instance.countInstructors();})
```
