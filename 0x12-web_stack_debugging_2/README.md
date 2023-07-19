0x12. Web stack debugging #2
DevOpsSysAdminScriptingDebugging

    By: Sylvain Kalache, co-founder at Holberton School
    Weight: 1
    Ongoing second chance project - started Jul 17, 2023 6:00 AM, must end by Jul 22, 2023 6:00 AM
    An auto review will be launched at the deadline

In a nutshell…

    Auto QA review: 0.0/6 mandatory & 0.0/3 optional
    Altogether:  0.0%
        Mandatory: 0.0%
        Optional: 0.0%
        Calculation:  0.0% + (0.0% * 0.0%)  == 0.0%

Concepts

For this project, we expect you to look at this concept:

    Web stack debugging

Requirements
General

    All your files will be interpreted on Ubuntu 20.04 LTS
    All your files should end with a new line
    A README.md file at the root of the folder of the project is mandatory
    All your Bash script files must be executable
    Your Bash scripts must pass Shellcheck without any error
    Your Bash scripts must run without error
    The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
    The second line of all your Bash scripts should be a comment explaining what is the script doing

Tasks
0. Run software as another user
mandatory
Score: 0.0% (Checks completed: 0.0%)

The user root is, on Linux, the “superuser”. It can do anything it wants, that’s a good and bad thing. A good practice is that one should never be logged in the root user, as if you fat finger a command and for example run rm -rf /, there is no comeback. That’s why it is preferable to run as a privileged user, meaning that the user also has the ability to perform tasks that the root user can do, just need to use a specific command that you need to discover.

For the containers that you are given in this project as well as the checker, everything is run under the root user, which has the ability to run anything as another user.

Requirements:

    write a Bash script that accepts one argument
    the script should run the whoami command under the user passed as an argument
    make sure to try your script by passing different users
