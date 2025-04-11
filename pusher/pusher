#!/usr/bin/python3

import os
import subprocess
import sys

cmd1 = []
cmd2 = []
cmd3 = []

if (len(sys.argv) != 2):
    print("FR: Veuillez mettre un commentaire en argument\nMerci")
    print("EN: Please put on comment in argument\nThank you")
    sys.exit(1)
if (len(sys.argv) == 2 and sys.argv[1] == '-h'):
    print("USAGE")
    print("Fr : Ce script a été fait dans le but de faciliter vos push en transformant trois commandes en une seule !")
    print("EN : This scipt has been made in order to make push easier by transforming three command in just one !")
    sys.exit(0)

#For executing git add .
cmd1.append("git")
cmd1.append("add")
cmd1.append(".")

#git commit -m "message"
cmd2.append("git")
cmd2.append("commit")
cmd2.append("-m")
cmd2.append(sys.argv[1])

#for pushing
cmd3.append("git")
cmd3.append("push")

subprocess.run(cmd1)
subprocess.run(cmd2)
subprocess.run(cmd3)




