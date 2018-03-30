---
layout: single
title:  "How to Set-up a Vagrant box for Jekyll"
date:   2018-03-21 07:24:01 +0100
categories: [vagrant, jekyll]
---

# Prerequisites

First I had to install the most up-to-date versions of [Virtual Box](https://www.virtualbox.org/) and
[Vagrant](https://www.vagrantup.com/) on my Laptop. Virtual Box is used by Vagrant for the Virtual Machines. In addition
also a version of PowerShell > 2 is needed. If you are using Windows 10, you should already have it installed. As my
Laptop still runs on Windows 7, I had to install the [Windows Management Framework v5.1](https://docs.microsoft.com/en-us/powershell/wmf/5.1/install-configure). After some reboots

vagrant init jadesystems/rails5
vagrant up
vagrant ssh

vagrant suspend
vagrant halt
vagrant destroy

sudo apt-get update
sudo apt-get upgrade

Select /dev/sda1 /boot for grub?!

sudo gem install bundler
sudo apt-get install libffi-dev
sudo apt-get install libcurl4-openssl-dev
https://kvz.io/blog/2013/01/16/vagrant-tip-keep-virtualbox-guest-additions-in-sync/
