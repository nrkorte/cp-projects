fa.ps1

    Purpose: Automates the process of adding user to folder access groups

    How to use:
    1. Run this command -> ./fa.ps1 "username" "path" "rwm"

    Program arguments:
    username-> this is the username of the user (their ICIG username)
    path-> this is the path to the folder they want access to (you can use drive names like "W:\..." or full path like "cp4boufs101\...")
    rwm-> put any of the three characters 'r' 'w' or 'm' for what the user's level of access is. Examples: "r" "rw" "wm" "rwm"

    Known Bugs:
    I think I worked out all of the bugs so far but if there is any problems let me (Nick) know!

ra.ps1

    Purpose: Automates removing users from all groups associated with a folder

    How to use:
    1. Run this command -> ./ra.ps1 "username" "path"

    Program arguments:
    username-> this is the username of the user (their ICIG username)
    path-> this is the path to the folder they want access to (you can use drive names like "W:\..." or full path like "cp4boufs101\...")

    Known bugs:
    n/a

cha.ps1

    Purpose: Changes what permissions a user has on a folder

    How to use:
    1. Run this command -> ./cha.ps1 "username" "path" "permissions"

    Program arguments:
    username-> this is the username of the user (their ICIG username)
    path-> this is the path to the folder they want access to (you can use drive names like "W:\..." or full path like "cp4boufs101\...")
    permissions-> put any of the three characters 'r' 'w' or 'm' for what the user's level of access is. Examples: "r" "rw" "wm" "rwm"

    Known bugs:
    n/a


aol.ps1

    Purpose: Adds the appropraite office to each user (either COL or BOU depending on their job site)

    How to use:
    1. Run this command -> ./aol.ps1

    Program Arguments:
    n/a

    Known Bugs:
    n/a

du.ps1

    Purpose: To automate disabling a user and adding them to the correct disables users OU

    How to use:
    1. Run this command -> ./du.ps1 "username"

    Program Arguments:
    username-> The username of the user you are trying to disable

    Known Bugs:
    n/a

eu.ps1

    Purpose: To automate enabling a user and removing them from the disables users OU and adding them to the correct users OU

    How to use:
    1. Run this command -> ./eu.ps1 "username"

    Program Arguments:
    username-> The username of the user you are trying to enable

    Known Bugs:
    n/a

jobs.ps1

    Purpose: To return what jobs are associated with what group

    How to use:
    1. Run this command -> ./jobs.ps1 "group"

    Program Arguments:
    group-> The group name of the group you are trying to find the associated jobs from

    Known Bugs:
    n/a

rp.ps1

    Purpose: To automate the action of resetting a users password

    How to use:
    1. Run this command -> ./rp.ps1 "username"

    Program Arguments:
    username-> The username of the user you are trying to reset the password of

    Known Bugs:
    n/a

rfg.ps1

    Purpose: To automate the action of removing a user from a group

    How to use:
    1. Run this command -> ./rfg.ps1 "username" "group"

    Program Arguments:
    username-> The username of the user you are trying to remove
    group-> The name of the group you are removing the user from

    Known Bugs:
    n/a

atg.ps1

    Purpose: To automate the action of adding a user to a group

    How to use:
    1. Run this command -> ./atg.ps1 "username" "group"

    Program Arguments:
    username-> The username of the user you are trying to add
    group-> The name of the group you are adding the user to

    Known Bugs:
    n/a

access.ps1

    Purpose: To see what groups have access to a folder

    How to use:
    1. Run this command -> ./access.ps1 "path"

    Program Arguments:
    path-> The path to the folder you are trying to see the access rights of

    Known Bugs:
    n/a

when.ps1

    Purpose: To see when a user was created

    How to use:
    1. Run this command -> ./when.ps1 "username"

    Program Arguments:
    username-> The username of the user you want to see the date their account was made

    Known Bugs:
    n/a