# Docker Install on Parrot OS

Simple script to install main docker plugins on your parrotOS machine. It works with the latest 5.1 version on parrot. It should also work for Kali linux machines.

## Why ?

I've been trying to install docker on Parrot with the documentation on the official docker website. Unfortunately there is no tutorial for the installation on Parrot OS. ParrotOS being a debian like distribution I tried to use the debian documentation but it was failing due to the use of the command ``lsb_release -cs``. This command returns the name of the debian distribution and hence is used to extract the right docker release.

## Solution

I just made the script to download the latest docker release from the newest debian distribution (bullseye).
