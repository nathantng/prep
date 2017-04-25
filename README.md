#Code

Code for the week

##Whenever asked to open a mingw terminal, complete the following:

1. Open up mingw by double clicking on the bat file at this location: C:\utils\mingw\msys\1.0\msys.bat

2. Navigate to the repo folder by typing the following command:

```
cd /c/course/prep
```

##Setting Up

1. Open up a mingw terminal
2. Run the following commands:
```
./x.bootstrap
```
3. Make changes to the file that was just created for you in "settings/[your_user_name].settings
  * You will definitely need to change the git:user setting
  * Only change the value for the git:user key. Don't copy my settings file (settings/jp.settings) as the extra key that I am using (provider) will mess up your configuration

4. Repeat steps 1 and 2

##Verifying Setup

1. Open up a mingw terminal
2. Run the following commands:
```
source aliases
sr
```
3. It should complete with output like the following (only showing the bottom line):
```
3 passed, 15 failed
```
