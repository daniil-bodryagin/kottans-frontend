# Kottans course repository

Hello, eweryone, who desided to checkout what is going on here in my github account. My name is Daniil Bodryagin. I am an astronomer and programming "is out there" permanently during my study or work. So at last I've desided to drown in it. Here I'm going to describe my forwarding trough the course topics and mark milestones passed. In short - some routine info.

Repository without a link on itself would be not elegant enough, so here it is - [**Recursion, aka Circulus vitiosus**](https://github.com/daniil-bodryagin/kottans-frontend)

### General

- [x] Git Basics
- [x] Linux CLI and Networking
- [x] VCS (hello gitty), GitHub and Collaboration

### Front-End Basics

- [ ] Intro to HTML & CS S
- [ ] Responsive Web Design
- [ ] HTML & CSS Practice
- [ ] JavaScript Basics
- [ ] Document Object Model

### Advanced Topics

- [ ] Building a Tiny JS World (pre-OOP)
- [ ] Object oriented JS
- [ ] OOP exercise
- [ ] Offline Web Applications
- [ ] Memory pair game
- [ ] Website Performance Optimization
- [ ] Friends App

## Git Basics

I was really wondered when understood, that *.md* extension means *markdown* :-)

When I faced the Gihub first time I stucked with problem I didn't understand. That appeared because I listened to recomendation of Github when created repository and added readme.md automatically. Then trying to push commits from my local repository was unsuccessful (a-ha, for sure...) - there already were two repositories with different commit history.
But this case forsed me to understand what's goin on step by step and further learning of git moved easy.

The main new features of git I found in coursera videos were in the ending: `checkout HEAD`, `commit --ammend`, `reset`, `revert`. In the "Git PRO" book the topic about restoring data from history is far from the beginning, despite it's one of the most important thing in the whole version control.

Also in the git training app I've notised the pover of `branch -f` command. Really mightly.

<details>
<summary>Screenshots of progress</summary>

![Coursera's Introduction to Git and GitHub - First week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git/1.jpg)

![Coursera's Introduction to Git and GitHub - Second week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git/2.jpg)

![Learn git branching app - Main tasks](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git/3.jpg)

![Learn git branching app - Remote tasks](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git/4.jpg)

</details>

## Linux CLI, and HTTP

Linux survival seems a bit easy, but at the same moment a bit frustrating. It's not good when you type `cd ~/jokes` and it answers `**wrong**, you should type 'cd jokes' because you're already in home dir. But nevermind, you pass all the same`.

The wholy new thing I found is ability to use printer through the comand line. "Not even a Maybach has this!©". Very surprising. Other commands like `cd`, `cp`, `mkdir`, `rm`, etc are useful in combine with git in terminal not only in Linux but in Windows too so I'm sure I will use them permenently.

In the first part of article about HTTP I found that protocol vesion 2.0 uses parallel requests. Also I didn't see most of response codes before. For sure the information about REST API will be nessessary when I will have deal with client-server interactions, use fetch or probably node.js + ExpressJS (in case of working in back-end).

The topic of multiple resourse caching (on user's machine, on the proxy) and checks is wholy new for me. The article tells about basic things but they are inevitable for proseeding to more special themes such as security policies implementation.

<details>
<summary>Screenshots of progress</summary>

![Linux Survival - First module](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_linux_cli/1.jpg)

![Linux Survival - Second module](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_linux_cli/2.jpg)

![Linux Survival - Third module](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_linux_cli/3.jpg)

![Linux Survival - Fourth module](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_linux_cli/4.jpg)

</details>

## Git Collaboration

This part was interesting and sometimes challenging. The very surprising moment was that branches are only some kind on pointers which can be moved, switched between each other, etc. Also commits can be copied and disposed at any will. But I have a feeling that unlike the ordinary git flow with cycle of branching, pulling and pushing, these crazy commits-history deconstruction can bring chaos and misunderstanding. If some conditions will force me to use `cherry-pick` and things, I would do it with extremely caution.

Another new thing is that remote branches in fact are local too. They only show the state of data in remote repository. Working alone I would prefer to use `merge` than `rebase`. And pushing in style `push origin main:feature` also looks dangerous.

<details>
<summary>Screenshots of progress</summary>

![Coursera's Introduction to Git and GitHub - Third week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git_collaboration/1.jpg)

![Coursera's Introduction to Git and GitHub - Fourth week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git_collaboration/2.jpg)

![Learn git branching app - Main tasks](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git_collaboration/3.jpg)

![Learn git branching app - Remote tasks](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git_collaboration/4.jpg)

</details>
