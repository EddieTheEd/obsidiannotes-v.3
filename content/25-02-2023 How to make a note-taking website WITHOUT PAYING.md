---
layout: default
title: "25-02-2023 How to make a note-taking website WITHOUT PAYING"
---

Hello!

Perhaps you are reading this because you think my website looks cool and you want something like it.

First of all, I am a Linux user that converted from Windows (sadly) so a bunch of the things I had to do (esp. trying to get around school wifi not liking ssh) will probably not apply to you.

I should give an outline of what the final set-up will be:
- Obsidian vault where you can write your notes
- A github pages website sponsored by JZhao

All credits go to [Jacky Zhao](https://twitter.com/_jzhao?lang=en), he made literally all the code. All I am is a middleman between you and him, here to offer my guidance. (I have suffered)

## Acquire an obsidian vault
This *should* be self explanatory, I am going to assume you will use obsidian first and then use the website, hence I will outline how to import your data to fit with the website code.

1. Go to the [obsidian download](https://obsidian.md/download), and download it.
![](000_Files/000a_images/obby%20download%20page.png)

2. Open obsidian. There will probably not be a "content" vault set up already, as it is not there by default.
![](000_Files/000a_images/obby%20opened.png)

Congratulations! You have downloaded obsidian. You may consider just getting into it before you make the website, but if you do so you will have to place its content inside the "content" folder, **including the .obsidian folder**, and then use obsidian's "open another vault" and open the **content folder** within the repo. This will make sense later. However, I suggest making the website first.

## Create the website repository
First of all, you need a github account, as we will be using github pages.

1. Go to [github](https://github.com/) and make a new account.
![](000_Files/000a_images/github%20signup%20page-1.png)

2. Once you have made your account, go to [quartz](https://github.com/jackyzha0/quartz). While **logged in**, create a new repo using the template.
![](000_Files/000a_images/create%20new%20repo.png)

3. Name the repo whatever you like. It probably doesn't matter. Ensure you **include all branches**, AND you **keep it public!!!** Github Pages will **only** work for repos that are public.
![](000_Files/000a_images/create%20screen%20repo%20obby.png)

Congrats! On your account, the repository with the name you gave it should be there. Now we need to download it onto your computer. I will assume you are using **windows.** However, as a result I will not be able to assist you. I can vaguely tell you what to do, however. Feel free to email me any questions

## Downloading the repository

1. Download Github desktop
2. Add your account
3. Open the repository online
4. Press the green code section
5. Open with Github Desktop
6. Clone, and specify whatever location you want

You now have quartz on your windows computer!!! :)

## Setting Up Obby inside the repository

1. Open the file explorer to where the repository you just downloaded is. The folder should look something like this.
![](000_Files/000a_images/inital%20folder%20quartz.png)

2. Go back to your obsidian, (open a new vault if required), and **open folder as vault**. Select the **content** folder of the repository.

3. Add your notes here! This vault is now directly connected to your online repository. Not only does that mean it is safe in the chance that you lose your data (corrupt disc or something), but you can update your website via obsidian.

3a. There are many ways to update website via obsidian. However, I suggest using obsidian git(a plugin).

## Configuring the repository
First of all, we need to setup quartz so the pages will work. I suggest reading [JZhao's Guide](https://quartz.jzhao.xyz/notes/hosting/) on setting up these things. I'll essentially paraphrase and add things that may be needed.

1. Go to the actions tab. Activate workflows.
![](000_Files/000a_images/actions.png)

2. Go to the settings tab, then go to the **pages** tab.
- Make sure the branch is **master** and going to root. If you have  a custom domain set it up here, but its not necessary.
![](000_Files/000a_images/pages%20quartz.png)

## Configuring the clone
Ok, but to personalise your website we need to modify some things directly in the folder