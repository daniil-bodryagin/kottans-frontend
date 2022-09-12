# Kottans course repository

Hello, eweryone, who desided to checkout what is going on here in my github account. My name is Daniil Bodryagin. I am an astronomer and programming "is out there" permanently during my study or work. So at last I've desided to drown in it. Here I'm going to describe my forwarding trough the course topics and mark milestones passed. In short - some routine info.

Repository without a link on itself would be not elegant enough, so here it is - [**Recursion, aka Circulus vitiosus**](https://github.com/daniil-bodryagin/kottans-frontend)

### General

- [x] Git Basics
- [x] Linux CLI and Networking
- [x] VCS (hello gitty), GitHub and Collaboration

### Front-End Basics

- [x] Intro to HTML & CS S
- [x] Responsive Web Design
- [ ] HTML & CSS Practice - *...pending approval*
- [x] JavaScript Basics
- [ ] Document Object Model - *...pending approval*

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

![Coursera's Introduction to Git and GitHub - First week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git/coursera_git_first_week.jpg)

![Coursera's Introduction to Git and GitHub - Second week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git/coursera_git_second_week.jpg)

![Learn git branching app - Main tasks](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git/git_branching_app_main_first_part.jpg)

![Learn git branching app - Remote tasks](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git/git_branching_app_remote_first_part.jpg)

</details>

## Linux CLI, and HTTP

Linux survival seems a bit easy, but at the same moment a bit frustrating. It's not good when you type `cd ~/jokes` and it answers `**wrong**, you should type 'cd jokes' because you're already in home dir. But nevermind, you pass all the same`.

The wholy new thing I found is ability to use printer through the comand line. "Not even a Maybach has this!©". Very surprising. Other commands like `cd`, `cp`, `mkdir`, `rm`, etc are useful in combine with git in terminal not only in Linux but in Windows too so I'm sure I will use them permenently.

In the first part of article about HTTP I found that protocol vesion 2.0 uses parallel requests. Also I didn't see most of response codes before. For sure the information about REST API will be nessessary when I will have deal with client-server interactions, use fetch or probably node.js + ExpressJS (in case of working in back-end).

The topic of multiple resourse caching (on user's machine, on the proxy) and checks is wholy new for me. The article tells about basic things but they are inevitable for proseeding to more special themes such as security policies implementation.

<details>
<summary>Screenshots of progress</summary>

![Linux Survival - First module](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_linux_cli/linux_survival_module_1.jpg)

![Linux Survival - Second module](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_linux_cli/linux_survival_module_2.jpg)

![Linux Survival - Third module](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_linux_cli/linux_survival_module_3.jpg)

![Linux Survival - Fourth module](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_linux_cli/linux_survival_module_4.jpg)

</details>

## Git Collaboration

This part was interesting and sometimes challenging. The very surprising moment was that branches are only some kind on pointers which can be moved, switched between each other, etc. Also commits can be copied and disposed at any will. But I have a feeling that unlike the ordinary git flow with cycle of branching, pulling and pushing, these crazy commits-history deconstruction can bring chaos and misunderstanding. If some conditions will force me to use `cherry-pick` and things, I would do it with extremely caution.

Another new thing is that remote branches in fact are local too. They only show the state of data in remote repository. Working alone I would prefer to use `merge` than `rebase`. And pushing in style `push origin main:feature` also looks dangerous.

<details>
<summary>Screenshots of progress</summary>

![Coursera's Introduction to Git and GitHub - Third week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git_collaboration/coursera_git_third_week.jpg)

![Coursera's Introduction to Git and GitHub - Fourth week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git_collaboration/coursera_git_fourth_week.jpg)

![Learn git branching app - Main tasks](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git_collaboration/git_branching_app_main_second_part.jpg)

![Learn git branching app - Remote tasks](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_git_collaboration/git_branching_app_remote_second_part.jpg)

</details>

## Intro to HTML and CSS

Both video-course, or Code academy excersises present basic information about html tags and css selectors. This facts for sure I will use in future work, but I must say francly, they are not new for me except a couple of trifles. 

I'm pretty confused that nobody even remember about css table layout (do not mix up with html table tag!) as if it have never exist. I've read about this layout in the Head First series book and since have never meet it again. Nevertheless we have now flexbox and grid, so there no need in that old layout already - even floats now are almost useless, as I guess.

The interesting method of layout is using 12-columns grid. I haven't used it before, but want to, because it look like be able to solve problems of making page adaptive without tons of media-queries.

Also I've found some new html attributes and tags in html forms. This topic is immense and i still haven't mastered it despite that it's one of the most important things in html.

<details>
<summary>Screenshots of progress</summary>

![Coursera's HTML, CSS, and Javascript for Web Developers - First week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_html_css_intro/coursera_html_scc_js_first_week.jpg)

![Coursera's HTML, CSS, and Javascript for Web Developers - Second week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_html_css_intro/coursera_html_scc_js_second_week.jpg)

![Code Academy - Learn HTML & Learn CSS](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_html_css_intro/codeacademy_html_and_scc.jpg)

</details>

## Responsive Web Design

Flexbox was already known for me but css grid, on the conrary, was completly new. The fresh useful feature I found among flexbox properties is `align-content` which is good if you don't want to have excess space between the rows.

Grid is looks like the history completed the full turn and came back to the beginning but on the higher level. After the domination of fluid designs we again trying to use best practices of paper typography. I don't think that css grid is universal tool, but i'm going to use it very often. Also it's interesting for me to make some experiments and try in action such properties as `auto`, `fit-content()` and `grid-auto-flow: dense` in combination. I was surprised that css grid can automatically change tracks' sizes, but not only to render them from predefined proportion.

<details>
<summary>Screenshots of progress</summary>

![Flexbox Froggy](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_responsive_web_design/flexbox_froggy.jpg)

![Grid Garden](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_responsive_web_design/grid_garden.jpg)

</details>

## HTML-CSS-Popup

[Demo](https://daniil-bodryagin.github.io/html-css-popup/)

[Code base](https://github.com/daniil-bodryagin/html-css-popup)

## JS Basics

While I'm taking Kottans course I read learn.javascript at the same time. That's why I met on freecodecamp and in coursera's videos familiar things. But I wish to list the things, I've learned in general and didn't know before.

Earlier I usually used very fundamental things from classical structural programming: if...else, switch...case, cycles, arrays, functions, objects - stuff which is presented in every programming language. Now I've got to my toolkit a lot of built-in methods: for the first for the arrays, strings and objects. Also destructuring assignment and rest arguments are very handy and allow to write code more quickly. Arrow functions are funny, functions, which return functions, look very powerful. I'm trying to use these instruments everytime it seems to me that they will make code shorter and clearer.

But sometimes I see examples of code that in tutorials are described as more readable, but I wouldn't describe them so too. Furthermore I wouldn't even guess that this way of coding is more readable. For instance recursion is not for me more clear than a loop.

The most intrigue object type I've met is a hashmap. O(1) for search is awesome. Looking for examples of use now :-)

<details>
<summary>Screenshots of progress</summary>

![Coursera's HTML, CSS, and Javascript for Web Developers - Fourth week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_js_basics/coursera_html_scc_js_fourth_week.jpg)

![Freecodecamp - JS Basics, ES6](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_js_basics/freecodecamp_js_basics_es6_first_part.jpg)

![Freecodecamp - Basic Data Structures, Basic Algorithm Scripting](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_js_basics/freecodecamp_basic_data_structures_basic_algorithm_scripting.jpg)

![Freecodecamp - Functional Programming, Intermediate Algorithm Scripting](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_js_basics/freecodecamp_functional_programming_intermediate_algorithm_scripting_first_part.jpg)

</details>

## DOM

The last part of algorithm tasks on freecodecamp was very tricky. I've met again with regular expressions - very interesting and useful topic. When I will have a free time, I definitelly will dedicate it to their studing. 
DOM maipulations were familiar for me. As I saw this operations are usually separated from core logic of applications. It's interesting, how is it implemented in frameworks - does they practice manipulate DOM objects directly?

[Demo](https://daniil-bodryagin.github.io/js-dom/)

[Code base](https://github.com/daniil-bodryagin/js-dom)

<details>
<summary>Screenshots of progress</summary>

![Coursera's HTML, CSS, and Javascript for Web Developers - Fifth week](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_js_dom/coursera_html_scc_js_fifth_week_first_part.jpg)

![Freecodecamp - Intermediate Algorithm Scripting](https://github.com/daniil-bodryagin/kottans-frontend/blob/main/task_js_dom/freecodecamp_intermediate_algorithm_scripting_second_part.jpg)

</details>
