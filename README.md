# learn-github-from-zero
# availeble languages
english and persian
## Complete GitHub Tutorial (For Everyone)
In this tutorial, we're going to learn how to work with GitHub, from zero to one hundred. This tutorial is for those who are just starting out and want to learn everything step by step. Here's what we're going to learn:
---
### Table of Contents
1: Creating a GitHub Account
2: Installing GitHub Desktop
3: Creating a New Repository and Getting to Know Its Options
4: Recording Changes and Uploading Code
5: Publishing the Repository on the Site
6: Making the Repository Public or Private
7: Deleting a Repository
8: Complete Guide to Licenses
9: GitHub Telegram Bot
10: Forking a Project (Fork)
11: Cloning a Project (Clone)
12: Creating a New Branch
13: Submitting a Pull Request
14: Reviewing and Approving a Pull Request (Pull Request Review)
15: Creating a Release for the Project
---
### Creating a GitHub Account
To create an account, first we go to github.com. On the main page, we select the Sign up option. A form opens where we need to enter our email, username, and password. We also need to select our country from a dropdown menu. Sometimes this menu doesn't open, in which case it's better to turn on a VPN and try again. After filling out the form, GitHub sends us a verification email that we need to open and click on the link to activate the account. It's better to save the password we chose in a secure place, because we might need it later for some administrative tasks.
---
### Installing GitHub Desktop
To avoid having to work with the command line, we use GitHub Desktop software. We can download and install this software from soft98 or from the official GitHub website.
```
https://soft98.ir/internet/webmaster-tools/698-github-9c.html
```
After installation, we run the program. The first time we open it, it asks us to log in to our GitHub account. We click on Sign in to GitHub.com, the browser opens, and after logging in to our account, it shows us a verification link that we click on to establish the connection. From this point on, we can do most of our work through this software and go to the site less often.
**Accessing the File Menu:** The File menu is at the top left of the screen. If you're in Full Screen mode and can't see the menu, just press the Alt key to make it appear.
**Keyboard Shortcuts for Managing Repositories:**
- `Ctrl+N` (Windows) or `Command+N` (Mac): Create a new repository
- `Ctrl+O` or `Command+O`: Add a repository that's already on your system
- `Ctrl+Shift+O` or `Shift+Command+O`: Clone a repository from GitHub
- `Ctrl+T` or `Command+T`: View the list of all repositories
- `Ctrl+Shift+G` or `Shift+Command+G`: View the repository on the GitHub site
---
### Creating a New Repository in GitHub Desktop
To create a new repository, in GitHub Desktop we select New repository from the File menu. For faster access, we can use the `Ctrl+N` (Windows) or `Command+N` (Mac) keys.
A window opens with several fields that we need to fill in:
- **Name**: We write our project name here. It's better if the name has no spaces, but if we write it with spaces, it will automatically replace spaces with underscores.
- **Description**: We give a brief description of what the project does.
- **Local path**: We specify the storage path. By default it's in Documents/GitHub, but we can change it.
- **Initialize this repository with a README**: If we check this option, a README file will be automatically created for us, where we can later write the project description. This file is very important for introducing the project to others.
- **Git ignore**: In this section, we specify which files should not be sent to GitHub. For example, if the project is in Python, we select the Python option so that GitHub creates a suitable gitignore file for us that ignores extra files like temporary files and cache.
- **License**: In this section, we can specify the project license, which we'll explain in more detail later.
- After filling in these items, we click on Create repository. This creates the repository on our computer, but it hasn't been published on the site yet.
---
### Recording Changes and Uploading Code
Whenever we add a file to the project folder or make changes to it, GitHub Desktop shows it in the Changes section. To record these changes, we write a brief title in the Summary section about what we did. We can also write more details in the Description section, which is optional.
To quickly go to the commit description writing section, we can use the `Ctrl+G` (Windows) or `Command+G` (Mac) keys.
After writing the description, to commit, we press `Ctrl+Enter` (Windows) or `Command+Enter` (Mac).
To see all the changes we made before committing, we press `Ctrl+1` (Windows) or `Command+1` (Mac), and to see the commit history, we press `Ctrl+2` or `Command+2`.
After committing, to send the changes to the GitHub site, we click the Push origin button or press `Ctrl+P` (Windows) or `Command+P` (Mac).
If we want to get the latest changes from GitHub, we press `Ctrl+Shift+P` (Windows) or `Shift+Command+P` (Mac).
---
### Publishing the Repository on the Site
For our project to be visible on the GitHub site, we need to publish it. In GitHub Desktop, we click the Publish repository button. A window opens showing the project name and description. In this window, there's an option called Keep this code private. If we uncheck it, the project becomes public and everyone can see it. If we keep it checked, it remains private. After making our choice, we click on Publish repository to upload the project to the site.
To view the project on the site, we can press `Ctrl+Shift+G` (Windows) or `Shift+Command+G` (Mac) to open the browser and show the project.
---
### Making the Repository Public or Private
If we later want to change the project's status, we need to go to the GitHub site. We log in to our account and click on the repository name to open its page. Then we go to the Settings tab. The first time we want to change settings, it might ask for our password, which we need to enter. After that, we scroll down to the Danger Zone section. In this section, we click on Change visibility. If the project is private, we select Change to public, and if it's public, we select Change to private. GitHub shows us some explanations about the consequences of this action, such as the code becoming visible to everyone or anyone being able to fork it. After reading these explanations, we click on I have read and understand these effects and confirm the change.
---
### Deleting a Repository
If we no longer need a project and want to delete it completely, we again go to the Settings section and the Danger Zone. This time we select Delete this repository. GitHub gives us a serious warning that everything will be deleted. To confirm, it asks us to type the exact full name of the repository in a box. After typing, we click on Delete this repository and it might ask for the password again.
To delete a repository from GitHub Desktop, we can click on the desired repository and press `Ctrl+Delete` (Windows) or `Command+Delete` (Mac).
---
### Complete Guide to Licenses
A license tells others what they can do with our code. If we don't choose a license for our project, default copyright laws apply and no one has the right to copy or modify the code. Licenses are divided into several main categories:
#### Permissive Licenses
These licenses allow users to do almost anything with the code, including commercial use and closing the code:
**MIT License** - The simplest and most popular license. It allows everyone to see the code, modify it, and use it in commercial projects. The only condition is that they must keep the original copyright. React and Node.js use this license.
**Apache License 2.0** - Similar to MIT but with specific rules for patents. Users must declare their changes. Kubernetes and Android use this license.
**BSD Licenses** - Very similar to MIT. The 2-Clause version is almost identical to MIT, and the 3-Clause version has an additional condition that the creator's name cannot be used for promotion.
#### Copyleft / Reciprocal Licenses
These licenses allow use, but if you modify and distribute the code, you must distribute the modified code under the same license:
**GNU GPLv3** - The most famous copyleft license. Anyone who modifies and distributes the code must distribute the modified code under GPL. It doesn't allow commercial and closed use. The Linux Kernel uses this license.
**GNU LGPLv3** - A milder version of GPL. It allows libraries to be used in closed projects, but the library itself must remain open source.
**Mozilla Public License 2.0** - Between MIT and GPL. It allows combining code with other code, but files that have been changed must remain open source. Firefox uses this license.
#### Special Licenses
**Eclipse Public License 2.0** - Similar to MPL. Suitable for organizational and commercial projects. Eclipse IDE uses this license.
**Unlicense** - Releases the code into the Public Domain. This means anyone can do whatever they want with the code, without any conditions.
**Creative Commons** - These licenses are mostly for content (text, images, music) rather than code. They have different versions such as CC BY (with attribution) and CC BY-SA (with attribution and share-alike).
**How to Add a License**
There are two ways to add a license on GitHub:
1: **When creating the repository**: In the New repository window, in the License section, we can select one of the licenses from the dropdown menu. GitHub automatically creates a LICENSE file in the project.
2: **After creating the project**: We go to the GitHub site and on the repository page, click on Add file and then Create new file. We name the file LICENSE and from the Choose a license template button on the right side of the page, we select a license. GitHub writes the full license text for us and we just need to change the name and year.
---
### GitHub Telegram Bot
There's a bot on Telegram called GitHubBot that we can use. First we start the bot, then we give it the /connect command to send us a link. By clicking on the link, we allow the bot to connect to our GitHub account. Then with the /add command and selecting the desired repository, we add it to the bot. From then on, whenever a commit or Pull Request happens, the bot notifies us on Telegram.
```
https://t.me/GitHubBot
```
We can choose to receive messages within the group, or within a private message, we can remove the repository only from the list of messages, when we reply to the bot's message, our comment will be sent to GitHub through the bot.
---
### Forking a Project (Fork)
Fork means creating a complete copy of a public project that belongs to someone else in our own account. To do this, on the GitHub site and on the desired project page, we click the Fork button. The project is created as a new repository in our own account.
---
### Cloning a Project (Clone)
When we've forked a project or want to bring any other project to our computer, we need to clone it. In GitHub Desktop, from the File menu, we select Clone repository. For faster access, we can use `Ctrl+Shift+O` (Windows) or `Shift+Command+O` (Mac).
In the opened window, we select the URL option. We copy the project address from the site and paste it into the URL field. We select the storage path and click on Clone.
**Very Important Note About Cloning a Forked Project**
When we clone a project that we've forked, GitHub Desktop asks us what our purpose is for this project. There are two options:
- **For my own purposes**: We choose this option if we want to use the project independently for ourselves and save our changes in our own fork. This means we don't intend to send changes to the original project and just want to have a copy of the project.
- **To contribute to the parent repository**: We choose this option if we want to make changes to the project and later suggest to the original project owner to merge these changes into their project (the Pull Request we'll explain later). With this option, GitHub knows that we intend to help the original project.
This question is only asked for forked projects and we don't see this option for regular projects.
---
### Creating a New Branch
When we want to make changes to a project, it's better to do this on a separate branch so that we don't damage the main branch, which is usually called main. In GitHub Desktop, we click on the Current branch button, which usually has main written on it. Then we select New branch or press `Ctrl+Shift+N` (Windows) or `Shift+Command+N` (Mac).
We write a name for our new branch. The branch is created and automatically switches to it. We make any changes we want on this branch and commit and push them.
To see the list of all branches, we press `Ctrl+B` (Windows) or `Command+B` (Mac).
To rename the current branch, we press `Ctrl+Shift+R` (Windows) or `Shift+Command+R` (Mac).
To delete the current branch, we press `Ctrl+Shift+D` (Windows) or `Shift+Command+D` (Mac).
---
### Submitting a Pull Request
Now if we want to suggest our changes to the original project owner, we need to send a Pull Request (abbreviated as PR). In GitHub Desktop, we click the Create Pull Request button, which is at the top of the page. For faster access, we can press `Ctrl+R` (Windows) or `Command+R` (Mac) to open the current PR on the site.
The browser opens and the Pull Request page is displayed on the site. On that page, we write the title and description of our request and then click on Create Pull Request.
To compare branches on the site, we press `Ctrl+Shift+C` (Windows) or `Shift+Command+C` (Mac).
---
### Reviewing and Approving a Pull Request (Pull Request Review)
When someone sends us a Pull Request, we need to review it to see if the changes are correct. On the GitHub site, we go to the Pull Requests tab and click on it to open it. Then we go to the Files changed tab to see all the changes. On this page, we can review the code line by line. On any line we want to comment on, we hover the mouse over it and click on the + sign that appears to leave a comment.
When we've reviewed all the changes, we click the Review changes button at the top of the page. There are three options:
**Comment**: We just give our opinion and can ask questions or mention a point, without approving or rejecting. This option doesn't change the status.
**Approve**: This means we accept the changes and think they can be merged. With this, the PR gets an approved status and can be merged.
**Request changes**: This means we don't accept the submitted changes and they need to be fixed. In our comments, we write exactly what needs to be changed.
After selecting one of these three options, we write a summary comment and click on Submit review.
**Important Points About Pull Request Review:**
- The person who submitted the PR cannot approve their own PR. Someone else must review it.
- If we have branch protection settings enabled, the PR cannot be merged until someone approves it.
- After the PR is approved, the project owner can click the Merge pull request button to merge the changes with the main branch.
To merge branches in GitHub Desktop, we can press `Ctrl+Shift+M` (Windows) or `Shift+Command+M` (Mac).
---
### Sync Fork
If we've forked a project and the original owner has made new changes to it, to update our fork, on the GitHub site and on the page of the forked project, we click the Sync fork button to receive the new changes.
To get the latest changes from the main branch in GitHub Desktop, we press `Ctrl+Shift+U` (Windows) or `Shift+Command+U` (Mac).
To hide current changes (Stash) and restore them later, we press `Ctrl+Shift+S` (Windows) or `Shift+Command+S` (Mac), and to show or hide stashed changes, we press `Ctrl+H` (Windows) or `Control+H` (Mac).
---
### Creating a Release for the Project
When the project reaches a stable version, we can create a release for it so that users can download the executable file or the code for that specific version. On the GitHub site and on the repository page, we go to the Releases tab and then click on New release.
On the opened page, first we need to choose a name for the version in the Tag section. Usually the pattern v1.0.0 is used. If the version is not stable yet, we can write v0.2.0-alpha. We must choose a valid tag, otherwise the release won't be published.
In the Target section, we select the branch we want to build the release from, which is usually main.
In Release title, we write a title for this version.
In Release description, we can write complete explanations about the changes in this version, such as what bugs were fixed or what new features were added.
In the Attach files section, we can upload the project's executable file so that users can download it.
If we check the Set as a pre-release option, it warns users that this version is not stable yet. If we're sure that the version is complete and stable, we don't check it.
Finally, we click on Publish release to publish the release. If it's not complete yet, we can click on Save draft to keep it as a draft and edit it later.
---
### Complete Explanation of the gitignore File
The gitignore file is one of GitHub's important tools that helps us not send some files to GitHub. This file tells Git to ignore certain files and not record their changes in the project history. This is especially useful for system files, temporary files, binary files, and log files.
**What files should we ignore?**
- Files containing sensitive information such as passwords and security keys (e.g., *.pem, *.key)
- Binary files such as *.docx
- Log files such as *.log
- Files created by the operating system such as Thumbs.db and .DS_Store
- Folders related to installed libraries such as node_modules
**How to create a gitignore file?**
**Method 1: Creating a gitignore file for a specific repository**
When we create a new repository in GitHub Desktop, in the Git ignore section, we can choose from a series of ready-made templates. For example, if the project is in Python, we select the Python option so that GitHub creates a suitable gitignore file for us that ignores extra files such as the __pycache__ folder and *.pyc files.
**Method 2: Manually creating a gitignore file**
We can create a file called .gitignore in the project root ourselves and write our desired rules in it. To do this, in the terminal or command line, we go to the project folder and run this command:
```
touch .gitignore
```
Then with a text editor, we write the rules in it.
**Method 3: Using ready-made GitHub templates**
GitHub has a complete collection of gitignore templates for various languages and environments in the github/gitignore repository. We can go there and find a template that suits our project and copy it into our gitignore file.
**Method 4: Using special tools**
There are several tools that make creating a gitignore file easier:
- **gitignore.io**: A website that generates a suitable gitignore file for you by selecting different languages and tools.
- **create-gi**: A command-line tool that with the command `npx create-gi` we can quickly create a standard gitignore file for our project.
- **GIG (GitIgnore Generator)**: Another tool with an attractive user interface that with the command `gig generate --template node` we can create a gitignore file suitable for our desired language.
**Important Note**: If we've already sent a file to GitHub and now want it to be ignored, we first need to remove it from tracking with the command `git rm --cached FILENAME`, then add it to gitignore.
---
### Interesting GitHub Features You Might Not Have Heard About
GitHub is not just a simple place to store code. It has very interesting and advanced features that can make our work much easier. Let's take a look at a few of them:
#### GitHub Copilot and AI Features
GitHub has recently released a new software specifically for Copilot that's very advanced. This software allows us to manage multiple AI agents simultaneously. With the "My Work" dashboard, we can control all active sessions, Issues, and Pull Requests from one place. Each AI session runs in an isolated environment called Git Worktree so it doesn't interfere with other tasks.
**Interesting Copilot Features:**
- **Canvases**: An interactive environment that shows the AI program's outputs and status in real-time, and we can edit directly on it.
- **Sandbox**: Isolated environments for testing code without affecting the main system. We can run these environments on our own system or on GitHub's cloud servers.
- **Agent Merge**: An automated tool that monitors CI/CD Pipelines, tracks human reviews, and after all conditions are met, automatically merges the code.
In GitHub Desktop version 3.6, interesting features have also been added:
- **AI commit generation**: Copilot can generate commit messages according to the project's guidelines.
- **Conflict resolution with Copilot**: When we encounter problems merging code, Copilot can explain the conflict and suggest a solution.
- **Git Worktrees support**: We can work on multiple branches simultaneously without having to constantly save changes and switch between branches or have multiple separate clones.
#### GitHub Codespaces
GitHub Codespaces is a complete cloud development environment that runs directly in the browser. We no longer need to install various software on our system. We just go to GitHub and open a Codespace for our project and everything is already set up.
Main advantages:
- No more "it works on my system" problems.
- Newcomers can start working very quickly.
- We can create isolated test environments.
- Great for remote teams.
#### GitHub Actions
GitHub Actions is a powerful automation tool with which we can automate various workflows. For example, we can set it up so that every time new code is pushed to the main branch, tests run automatically, and if everything is okay, the code gets deployed to GitHub Pages or anywhere else. Currently, over 2 billion minutes of GitHub Actions are used per month, which shows how popular it is.
#### GitHub Secrets
GitHub has a feature called Secrets where we can store sensitive information such as passwords and API keys. This information is stored encrypted and is only provided to programs when necessary.
There are different types of Secrets:
- **Dependabot Secrets**: For automatically updating libraries and dependencies.
- **Codespaces Secrets**: For use in cloud development environments.
This feature greatly helps with project security because we no longer have to write sensitive information directly in the code.
---
### Frequently Used GitHub Desktop Keyboard Shortcuts
**Repository Management:**
| Shortcut Key (Windows) | Shortcut Key (Mac) | Function |
|---|---|---|
| `Ctrl+N` | `Command+N` | Create a new repository |
| `Ctrl+O` | `Command+O` | Add a local repository |
| `Ctrl+Shift+O` | `Shift+Command+O` | Clone a repository |
| `Ctrl+T` | `Command+T` | View the list of repositories |
| `Ctrl+P` | `Command+P` | Send commits to GitHub |
| `Ctrl+Shift+P` | `Shift+Command+P` | Get changes from GitHub |
| `Ctrl+Shift+G` | `Shift+Command+G` | View repository on the site |
| `Ctrl+Delete` | `Command+Delete` | Delete repository |
**Branch Management:**
| Shortcut Key (Windows) | Shortcut Key (Mac) | Function |
|---|---|---|
| `Ctrl+Shift+N` | `Shift+Command+N` | Create a new branch |
| `Ctrl+Shift+R` | `Shift+Command+R` | Rename the current branch |
| `Ctrl+Shift+D` | `Shift+Command+D` | Delete the current branch |
| `Ctrl+Shift+U` | `Shift+Command+U` | Get changes from the main branch |
| `Ctrl+Shift+M` | `Shift+Command+M` | Merge with the current branch |
| `Ctrl+Shift+S` | `Shift+Command+S` | Hide current changes (Stash) |
| `Ctrl+B` | `Command+B` | View the list of branches |
**Working with Commits:**
| Shortcut Key (Windows) | Shortcut Key (Mac) | Function |
|---|---|---|
| `Ctrl+1` | `Command+1` | View changes before commit |
| `Ctrl+2` | `Command+2` | View commit history |
| `Ctrl+G` | `Command+G` | Go to the commit description writing section |
| `Ctrl+Enter` | `Command+Enter` | Commit |
**Working with Pull Requests:**
| Shortcut Key (Windows) | Shortcut Key (Mac) | Function |
|---|---|---|
| `Ctrl+R` | `Command+R` | View the current PR on the site |
| `Ctrl+Shift+C` | `Shift+Command+C` | Compare branches on the site |
---
***made by***
***invincible627***
***github profile link***
***https://github.com/invincible627***

# learn-github-from-zero
# زبانهای در دسترس
انگلیسی و فارسی
## آموزش کامل کار با گیتهاب (برای همه)
توی این آموزش قراره یاد بگیریم که چطور با گیتهاب کار کنیم، از صفر تا صد. این آموزش مخصوص کسایی هست که تازه میخوان شروع کنن و میخوان همه چیز رو قدم به قدم یاد بگیرن. قراره این چیزها رو یاد بگیریم:
---
### فهرست محتوای آموزش
1: ساخت اکانت در گیتهاب
2: نصب و راهاندازی گیتهاب دسکتاپ (GitHub Desktop)
3: ساختن ریپازیتوری جدید و آشنایی با گزینههاش
4: ثبت تغییرات و آپلود کد
5: انتشار ریپازیتوری در سایت
6: عمومی یا خصوصی کردن ریپازیتوری
7: حذف ریپازیتوری
8: آشنایی کامل با لایسنسها
9: ربات تلگرام گیتهاب
10: فورک کردن پروژه (Fork)
11: کلون کردن پروژه (Clone)
12: ساختن شاخه جدید (Branch)
13: درخواست پول ریکوست (Pull Request)
14: بررسی و تأیید پول ریکوست (Pull Request Review)
15: ساختن ریلیس برای پروژه (Release)
---
### ساخت اکانت در گیتهاب
برای ساخت اکانت، اول میریم توی سایت github.com. توی صفحه اصلی، گزینه Sign up رو انتخاب میکنیم. یه فرم باز میشه که باید ایمیل، نام کاربری و رمز عبور رو توش وارد کنیم. کشور رو هم از یه منوی کشویی باید انتخاب کنیم. گاهی پیش میاد که این منو باز نمیشه، که توی این شرایط بهتره فیلترشکن رو روشن کنیم و دوباره امتحان کنیم. بعد از پر کردن فرم، گیتهاب یه ایمیل تأیید به ما میفرسته که باید بریم توی ایمیل و روی لینکش کلیک کنیم تا اکانت فعال بشه. رمز عبوری که انتخاب کردیم رو بهتره یه جای امن یادداشت کنیم، چون ممکنه برای بعضی کارهای مدیریتی بعداً بهش نیاز پیدا کنیم.
---
### نصب گیتهاب دسکتاپ (GitHub Desktop)
برای اینکه مجبور نباشیم با خط فرمان کار کنیم، از نرمافزار گیتهاب دسکتاپ استفاده میکنیم. این نرمافزار رو میتونیم از سایت soft98 یا از خود وبسایت رسمی گیتهاب دانلود و نصب کنیم.
```
https://soft98.ir/internet/webmaster-tools/698-github-9c.html
```
بعد از نصب، برنامه رو اجرا میکنیم. اولین بار که بازش میکنیم، از ما میخواد که وارد اکانت گیتهابمون بشیم. گزینه Sign in to GitHub.com رو میزنیم، مرورگر باز میشه و بعد از وارد شدن به اکانت، یه لینک تأیید بهمون نشون میده که روش کلیک میکنیم تا اتصال برقرار بشه. از این مرحله به بعد، دیگه میتونیم بیشتر کارهامون رو از طریق همین نرمافزار انجام بدیم و کمتر سراغ سایت بریم.
**دسترسی به منوی File:** منوی File توی بالای صفحه و سمت چپ قرار داره. اگه صفحه کامل (Full Screen) هستید و منو رو نمیبینید، کافیه کلید Alt رو فشار بدید تا منو نمایان بشه .
**کلیدهای میانبر برای مدیریت ریپازیتوریها:** 
- `Ctrl+N` (ویندوز) یا `Command+N` (مک): ساختن ریپازیتوری جدید
- `Ctrl+O` یا `Command+O`: اضافه کردن یه ریپازیتوری که از قبل روی سیستمتون هست
- `Ctrl+Shift+O` یا `Shift+Command+O`: کلون کردن یه ریپازیتوری از گیتهاب
- `Ctrl+T` یا `Command+T`: دیدن لیست همه ریپازیتوریها
- `Ctrl+Shift+G` یا `Shift+Command+G`: دیدن ریپازیتوری توی سایت گیتهاب
---
### ساختن ریپازیتوری جدید توی گیتهاب دسکتاپ
برای ساختن یه ریپازیتوری جدید، توی گیتهاب دسکتاپ از منوی File گزینه New repository رو انتخاب میکنیم. برای دسترسی سریعتر میتونیم کلیدهای `Ctrl+N` (ویندوز) یا `Command+N` (مک) رو بزنیم .
یه پنجره باز میشه که چند تا فیلد داره و باید پر کنیم:
- **Name**: اسم پروژه‌مون رو توش مینویسیم. بهتره اسم بدون فاصله باشه، ولی اگه با فاصله بنویسیم خودش به جای فاصله زیرخط میذاره.
- **Description**: یه توضیح مختصر درباره پروژه میدیم که چه کاری انجام میده.
- **Local path**: مسیر ذخیره‌سازی رو مشخص میکنیم. به‌طور پیش‌فرض توی Documents/GitHub هست، ولی میتونیم تغییرش بدیم.
- **Initialize this repository with a README**: اگه این گزینه رو تیک بزنیم، یه فایل README به‌طور خودکار برامون ساخته میشه که بعداً میتونیم توضیحات پروژه رو توش بنویسیم. این فایل برای معرفی پروژه به دیگران خیلی مهمه.
- **Git ignore**: توی این بخش مشخص میکنیم چه فایل‌هایی نباید به گیتهاب فرستاده بشن. مثلاً اگه پروژه پایتونه، گزینه Python رو انتخاب میکنیم تا فایل‌های اضافی مثل فایل‌های موقت و کش به گیتهاب نرن.
- **License**: توی این بخش میتونیم مجوز پروژه رو مشخص کنیم که بعداً مفصلتر دربارهاش توضیح میدیم.
- بعد از پر کردن این موارد، روی Create repository کلیک میکنیم. این کار ریپازیتوری رو روی کامپیوتر خودمون میسازه، ولی هنوز توی سایت منتشر نشده.
---
### ثبت تغییرات و آپلود کد
هر وقت فایلی رو به پوشه پروژه اضافه میکنیم یا تغییرش میدیم، گیتهاب دسکتاپ اون رو توی قسمت Changes نشون میده. برای ثبت این تغییرات، توی قسمت Summary یه عنوان مختصر مینویسیم که چه کاری انجام دادیم. توی قسمت Description هم میتونیم توضیحات بیشتری بدیم که اختیاری هست.
برای رفتن سریع به قسمت نوشتن توضیحات کامیت، میتونیم کلیدهای `Ctrl+G` (ویندوز) یا `Command+G` (مک) رو بزنیم.
بعد از نوشتن توضیحات، برای ثبت کامیت، کلیدهای `Ctrl+Enter` (ویندوز) یا `Command+Enter` (مک) رو میزنیم.
برای دیدن همه تغییراتی که قبل از کامیت انجام دادیم، کلیدهای `Ctrl+1` (ویندوز) یا `Command+1` (مک) رو میزنیم و برای دیدن تاریخچه کامیتها، `Ctrl+2` یا `Command+2` رو میزنیم.
بعد از کامیت، برای اینکه تغییرات به سایت گیتهاب برن، دکمه Push origin رو میزنیم یا کلیدهای `Ctrl+P` (ویندوز) یا `Command+P` (مک) رو میزنیم .
اگه بخوایم جدیدترین تغییرات رو از گیتهاب بگیریم، کلیدهای `Ctrl+Shift+P` (ویندوز) یا `Shift+Command+P` (مک) رو میزنیم.
---
### انتشار ریپازیتوری در سایت
برای اینکه پروژه‌مون توی سایت گیتهاب قابل مشاهده باشه، باید منتشرش کنیم. توی گیتهاب دسکتاپ، دکمه Publish repository رو میزنیم. یه پنجره باز میشه که اسم و توضیحات پروژه رو نشون میده. توی این پنجره یه گزینه داریم به اسم Keep this code private. اگه تیکش رو برداریم، پروژه عمومی میشه و همه میتونن ببیننش. اگه تیکش رو نگه داریم، خصوصی میمونه. بعد از انتخاب، روی Publish repository کلیک میکنیم تا پروژه توی سایت آپلود بشه.
برای دیدن پروژه توی سایت، میتونیم کلیدهای `Ctrl+Shift+G` (ویندوز) یا `Shift+Command+G` (مک) رو بزنیم تا مرورگر باز بشه و پروژه رو نشون بده .
---
### عمومی یا خصوصی کردن ریپازیتوری
اگه بعداً بخوایم وضعیت پروژه رو عوض کنیم، باید بریم توی سایت گیتهاب. وارد اکانت میشیم و روی اسم ریپازیتوری کلیک میکنیم تا صفحه‌اش باز بشه. بعدش میرویم توی تب Settings. ممکنه اولین بار که میخوایم تنظیمات رو تغییر بدیم، ازمون رمز عبور بخواد که باید واردش کنیم. بعد از اون، میریم به پایین صفحه تا به بخش Danger Zone برسیم. توی این بخش، گزینه Change visibility رو میزنیم. اگه پروژه خصوصیه، Change to public رو انتخاب میکنیم و اگه عمومی‌ست، Change to private رو. گیتهاب یه سری توضیحات درباره عواقب این کار بهمون میده، مثلاً اینکه کد برای همه قابل مشاهده میشه یا هرکسی میتونه فورکش کنه. بعد از خوندن این توضیحات، روی I have read and understand these effects کلیک میکنیم و تغییر رو تأیید میکنیم.
---
### حذف ریپازیتوری
اگه دیگه به پروژه‌ای نیاز نداشته باشیم و بخوایم کامل پاکش کنیم، بازم میریم توی بخش Settings و توی Danger Zone. این بار گزینه Delete this repository رو انتخاب میکنیم. گیتهاب یه هشدار جدی بهمون میده که با این کار همه چیز پاک میشه. برای تأیید، ازمون میخواد که دقیقاً اسم کامل ریپازیتوری رو توی یه کادر تایپ کنیم. بعد از تایپ، روی Delete this repository کلیک میکنیم و ممکنه دوباره رمز عبور بخواد.
برای حذف ریپازیتوری از گیتهاب دسکتاپ، میتونیم روی ریپازیتوری مورد نظر کلیک کنیم و کلیدهای `Ctrl+Delete` (ویندوز) یا `Command+Delete` (مک) رو بزنیم .
---
### آشنایی کامل با لایسنسها
لایسنس یا مجوز، به دیگران میگه که چه کارهایی میتونن با کد ما انجام بدن. اگه برای پروژه‌مون لایسنس انتخاب نکنیم، قوانین کپی‌رایت پیش‌فرض اعمال میشه و هیچکس حق نداره کد رو کپی یا تغییر بده. لایسنسها به چند دسته اصلی تقسیم میشن:
#### لایسنسهای کاملاً آزاد (Permissive)
این لایسنسها به کاربرا اجازه میدن تقریباً هر کاری با کد بکنن، حتی استفاده تجاری و بستن کد:
**MIT License** - ساده‌ترین و محبوب‌ترین لایسنس. به همه اجازه میده کد رو ببینن، تغییر بدن، توی پروژه‌های تجاری استفاده کنن. تنها شرطش اینه که کپی‌رایت اصلی رو نگه دارن. React و Node.js از این استفاده میکنن.
**Apache License 2.0** - شبیه MIT با این تفاوت که قوانین خاصی برای حق ثبت اختراع (پتنت) داره. کاربرا باید تغییراتشون رو اعلام کنن. Kubernetes و Android از این استفاده میکنن.
**BSD Licenses** - خیلی شبیه MIT هستن. نسخه ۲-Clause تقریباً عین MIT و نسخه ۳-Clause یه شرط اضافی داره که نمی‌شه از اسم سازنده برای تبلیغ استفاده کرد.
#### لایسنسهای کپی‌لفت (Copyleft / Reciprocal)
این لایسنسها اجازه استفاده میدن ولی اگه کد رو تغییر بدید و منتشر کنید، باید کد تغییر داده شده رو هم با همون لایسنس منتشر کنید:
**GNU GPLv3** - معروف‌ترین لایسنس کپی‌لفت. هرکسی که کد رو تغییر بده و منتشر کنه، باید کد تغییر داده شده رو با GPL منتشر کنه. اجازه استفاده تجاری و بسته رو نمیده. Linux Kernel از این استفاده میکنه.
**GNU LGPLv3** - نسخه ملایم‌تر GPL. اجازه میده کتابخونه‌ها توی پروژه‌های بسته استفاده بشن، ولی خود کتابخونه باید متن‌باز بمونه.
**Mozilla Public License 2.0** - بین MIT و GPL هست. اجازه میده کد رو با کدهای دیگه ترکیب کنن، ولی فایل‌هایی که تغییر کردن باید متن‌باز بمونن. Firefox از این استفاده میکنه.
#### لایسنسهای خاص
**Eclipse Public License 2.0** - شبیه MPL. برای پروژه‌های سازمانی و تجاری مناسبه. Eclipse IDE از این استفاده میکنه.
**Unlicense** - کد رو به مالکیت عمومی (Public Domain) تبدیل میکنه. یعنی هرکی هر کاری دوست داره با کد بکنه، بدون هیچ شرطی.
**Creative Commons** - این لایسنسها بیشتر برای محتوا (متن، تصویر، موسیقی) هستن تا کد. نسخه‌های مختلفی دارن مثل CC BY (با ذکر منبع) و CC BY-SA (با ذکر منبع و اشتراک مشابه).
**نحوه اضافه کردن لایسنس**
توی گیتهاب دو راه برای اضافه کردن لایسنس وجود داره:
1: **هنگام ساختن ریپازیتوری**: توی پنجره New repository، توی بخش License میتونیم از منوی کشویی یکی از لایسنس‌ها رو انتخاب کنیم. گیتهاب به طور خودکار یه فایل LICENSE توی پروژه میسازه.
2: **بعد از ساختن پروژه**: میریم توی سایت گیتهاب و توی صفحه ریپازیتوری، روی Add file کلیک میکنیم و بعد Create new file. اسم فایل رو LICENSE میذاریم و از دکمه Choose a license template که سمت راست صفحه هست، یه لایسنس انتخاب میکنیم. گیتهاب متن کامل لایسنس رو برامون مینویسه و فقط باید اسم و سال رو تغییر بدیم.
---
### ربات تلگرام گیتهاب
یه ربات توی تلگرام هست به اسم GitHubBot که میتونیم ازش استفاده کنیم. اول ربات رو استارت میکنیم، بعد دستور /connect رو بهش میدیم تا یه لینک برامون بفرسته. با کلیک روی لینک، اجازه میدیم که ربات به اکانت گیتهابمون وصل بشه. بعد با دستور /add و انتخاب ریپازیتوری مورد نظر، اون رو به ربات اضافه میکنیم. از این به بعد، هر کامیت یا Pull Requestی که اتفاق بیفته، ربات توی تلگرام بهمون خبر میده.
```
https://t.me/GitHubBot
```
ما میتونیم انتخاب کنیم که پیامها رو داخل گروه دریافت کنیم، یا داخل پیام شخصی، میتونیم ریپازیتوری رو فقط از لیست پیامها حذف کنیم، وقتی ما روی پیام ربات پاسخ بزنیم دیدگاهمون از طریق ربات به گیتهاب ارسال میشه
---
### فورک کردن پروژه (Fork)
فورک یعنی از یه پروژه عمومی که مال شخص دیگه‌ای هست، یه کپی کامل توی اکانت خودمون بسازیم. برای این کار، توی سایت گیتهاب و توی صفحه پروژه مورد نظر، دکمه Fork رو میزنیم. پروژه به‌عنوان یه ریپازیتوری جدید توی اکانت خودمون ساخته میشه.
---
### کلون کردن پروژه (Clone)
وقتی پروژه‌ای رو فورک کردیم یا میخوایم هر پروژه دیگه‌ای رو روی کامپیوتر خودمون بیاریم، باید کلونش کنیم. توی گیتهاب دسکتاپ از منوی File گزینه Clone repository رو انتخاب میکنیم. برای دسترسی سریعتر میتونیم کلیدهای `Ctrl+Shift+O` (ویندوز) یا `Shift+Command+O` (مک) رو بزنیم.
توی پنجره باز شده، گزینه URL رو انتخاب میکنیم. آدرس پروژه رو از سایت کپی میکنیم و توی قسمت URL میچسبونیم. مسیر ذخیره‌سازی رو انتخاب میکنیم و روی Clone کلیک میکنیم.
**نکته خیلی مهم درباره کلون کردن پروژه فورک شده**
وقتی پروژه‌ای رو که فورک کردیم کلون میکنیم، گیتهاب دسکتاپ ازمون میپرسه که این پروژه رو برای چه هدفی میخوایم؟ دو تا گزینه داریم:
- **For my own purposes**: این گزینه رو انتخاب میکنیم اگه میخوایم پروژه رو به‌طور مستقل برای خودمون استفاده کنیم و تغییراتمون رو توی همون فورک خودمون ذخیره کنیم. یعنی قصد نداریم تغییرات رو به پروژه اصلی بفرستیم و صرفاً میخوایم یه کپی از پروژه داشته باشیم.
- **To contribute to the parent repository**: این گزینه رو انتخاب میکنیم اگه میخوایم روی پروژه تغییراتی بدیم و بعداً به صاحب پروژه اصلی پیشنهاد بدیم که این تغییرات رو توی پروژه خودش ادغام کنه (همون Pull Request که بعداً توضیح میدیم). با این گزینه، گیتهاب میدونه که ما قصد کمک به پروژه اصلی رو داریم.
این سوال فقط برای پروژه‌هایی که فورک شدن مطرح میشه و برای پروژه‌های معمولی این گزینه رو نمیبینیم.
---
### ساختن شاخه جدید (Branch)
وقتی میخوایم روی یه پروژه تغییراتی بدیم، بهتره این کار رو روی یه شاخه جداگانه انجام بدیم تا به شاخه اصلی که معمولاً main هست، آسیب نرسه. توی گیتهاب دسکتاپ، روی دکمه Current branch کلیک میکنیم که معمولاً روش نوشته main. بعد گزینه New branch رو انتخاب میکنیم یا کلیدهای `Ctrl+Shift+N` (ویندوز) یا `Shift+Command+N` (مک) رو میزنیم .
یه اسم برای شاخه جدیدمون مینویسیم. شاخه ساخته میشه و خودش به‌طور خودکار به اون سوئیچ میکنه. هر تغییری که میخوایم بدیم، روی همین شاخه انجام میدیم و کامیت و پوشش میکنیم.
برای دیدن لیست همه شاخه‌ها، کلیدهای `Ctrl+B` (ویندوز) یا `Command+B` (مک) رو میزنیم .
برای تغییر اسم شاخه فعلی، کلیدهای `Ctrl+Shift+R` (ویندوز) یا `Shift+Command+R` (مک) رو میزنیم .
برای حذف شاخه فعلی، کلیدهای `Ctrl+Shift+D` (ویندوز) یا `Shift+Command+D` (مک) رو میزنیم .
---
### درخواست پول ریکوست (Pull Request)
حالا اگه بخوایم تغییراتمون رو به صاحب پروژه اصلی پیشنهاد بدیم، باید یه Pull Request (به اختصار PR) بفرستیم. توی گیتهاب دسکتاپ، دکمه Create Pull Request رو میزنیم که توی بالای صفحه قرار داره. برای دسترسی سریعتر، میتونیم کلیدهای `Ctrl+R` (ویندوز) یا `Command+R` (مک) رو بزنیم تا PR فعلی توی سایت باز بشه .
مرورگر باز میشه و صفحه Pull Request توی سایت نمایش داده میشه. توی اون صفحه، عنوان و توضیحات درخواستمون رو مینویسیم و بعد روی Create Pull Request کلیک میکنیم.
برای مقایسه شاخه‌ها با هم توی سایت، کلیدهای `Ctrl+Shift+C` (ویندوز) یا `Shift+Command+C` (مک) رو میزنیم .
---
### بررسی و تأیید پول ریکوست (Pull Request Review)
وقتی یه Pull Request برای ما میفرستن، باید اون رو بررسی کنیم تا ببینیم تغییرات درسته یا نه. توی سایت گیتهاب، میریم توی تب Pull Requests و روی اون یکی کلیک میکنیم تا باز بشه. بعد میریم توی تب Files changed تا همه تغییرات رو ببینیم. توی این صفحه میتونیم خط به خط کد رو بررسی کنیم. روی هر خطی که میخوایم نظر بدیم، موس رو میبریم روش و علامت + که ظاهر میشه رو کلیک میکنیم تا یه کامنت بذاریم.
وقتی همه تغییرات رو بررسی کردیم، بالای صفحه دکمه Review changes رو میزنیم. سه تا گزینه داریم:
**Comment** (نظر دادن): فقط نظر میدیم و میتونیم سوال بپرسیم یا یه نکتهای رو بگیم، بدون اینکه تأیید یا رد کنیم. این گزینه وضعیت رو تغییر نمیده.
**Approve** (تأیید): یعنی تغییرات رو قبول داریم و فکر میکنیم که میشه ادغامشون کرد. با این کار، PR وضعیت تأیید شده میگیره و میتونن ادغامش کنن.
**Request changes** (درخواست تغییرات): یعنی تغییراتی که فرستادن رو قبول نداریم و باید اصلاح بشن. توی کامنت‌هامون دقیقاً مینویسیم که چه چیزی باید عوض بشه.
بعد از اینکه یکی از این سه گزینه رو انتخاب کردیم، یه کامنت خلاصه مینویسیم و روی Submit review کلیک میکنیم.
**نکات مهم درباره بررسی پول ریکوست:**
- کسی که خودش PR رو فرستاده، نمیتونه PR خودش رو تأیید کنه. حتماً باید یه نفر دیگه بررسی کنه.
- اگه تنظیمات محافظت از شاخه رو فعال کرده باشیم، PR تا وقتی که یه نفر تأییدش نکنه، قابل ادغام نیست.
- بعد از اینکه PR تأیید شد، صاحب پروژه میتونه روی دکمه Merge pull request کلیک کنه تا تغییرات با شاخه اصلی ادغام بشه.
برای ادغام شاخه‌ها توی گیتهاب دسکتاپ، میتونیم کلیدهای `Ctrl+Shift+M` (ویندوز) یا `Shift+Command+M` (مک) رو بزنیم .
---
### همگام‌سازی فورک (Sync Fork)
اگه پروژه‌ای رو فورک کردیم و صاحب اصلی تغییرات جدیدی روش اعمال کرد، برای به‌روز کردن فورک خودمون، توی سایت گیتهاب و توی صفحه همون پروژه فورک شده، دکمه Sync fork رو میزنیم تا تغییرات جدید رو دریافت کنیم.
برای گرفتن آخرین تغییرات از شاخه اصلی توی گیتهاب دسکتاپ، کلیدهای `Ctrl+Shift+U` (ویندوز) یا `Shift+Command+U` (مک) رو میزنیم .
برای مخفی کردن تغییرات فعلی (Stash) و بعداً برگردوندنشون، کلیدهای `Ctrl+Shift+S` (ویندوز) یا `Shift+Command+S` (مک) رو میزنیم و برای نمایش یا مخفی کردن تغییرات ذخیره شده، `Ctrl+H` (ویندوز) یا `Control+H` (مک) رو میزنیم .
---
### ساختن ریلیس برای پروژه (Release)
وقتی پروژه به نسخه پایدار رسید، میتونیم براش ریلیس بسازیم تا کاربرا بتونن فایل اجرایی یا کد همون نسخه خاص رو دانلود کنن. توی سایت گیتهاب و توی صفحه ریپازیتوری، میریم توی تب Releases و بعد روی New release کلیک میکنیم.
توی صفحه باز شده، اول از همه باید توی بخش Tag یه اسم برای نسخه انتخاب کنیم. معمولاً از قاعده v1.0.0 استفاده میشه. اگه نسخه هنوز پایدار نیست، میتونیم v0.2.0-alpha بنویسیم. حتماً باید یه تگ معتبر انتخاب کنیم وگرنه ریلیس منتشر نمیشه.
توی بخش Target، شاخه‌ای که میخوایم از روش ریلیس بسازیم رو انتخاب میکنیم که معمولاً main هست.
توی Release title یه عنوان برای این نسخه مینویسیم.
توی Release description میتونیم توضیحات کاملی درباره تغییرات این نسخه بدیم، مثلاً چه باگ‌هایی رفع شده یا چه قابلیت‌های جدیدی اضافه شده.
توی بخش Attach files میتونیم فایل اجرایی پروژه رو آپلود کنیم تا کاربرا بتونن دانلودش کنن.
گزینه Set as a pre-release رو اگه تیک بزنیم، به کاربرا هشدار میده که این نسخه هنوز پایدار نیست. اگه مطمئن هستیم که نسخه کامل و پایدار هست، تیکش رو نمیزنیم.
در نهایت، روی Publish release کلیک میکنیم تا ریلیس منتشر بشه. اگه هنوز کامل نیست، میتونیم روی Save draft کلیک کنیم تا به صورت پیش‌نویس بمونه و بعداً ویرایشش کنیم.
---
### توضیح کامل فایل gitignore
فایل gitignore یکی از ابزارهای مهم گیتهاب هست که بهمون کمک میکنه بعضی فایل‌ها رو به گیتهاب نفرستیم. این فایل به گیت میگه که بعضی فایل‌ها رو نادیده بگیره و تغییراتشون رو توی تاریخچه پروژه ثبت نکنه. این کار مخصوصاً برای فایل‌های سیستمی، فایل‌های موقت، فایل‌های باینری و فایل‌های لاگ خیلی مفیده.
**چه فایل‌هایی رو باید نادیده بگیریم؟**
- فایل‌های حاوی اطلاعات حساس مثل رمزها و کلیدهای امنیتی (مثلاً *.pem, *.key)
- فایل‌های باینری مثل *.docx
- فایل‌های لاگ مثل *.log
- فایل‌های ساخته شده توسط سیستم عامل مثل Thumbs.db و .DS_Store
- پوشه‌های مربوط به کتابخونه‌های نصب شده مثل node_modules
**چطور فایل gitignore بسازیم؟**
**روش اول: ساخت فایل gitignore برای یه ریپازیتوری خاص**
وقتی توی گیتهاب دسکتاپ یه ریپازیتوری جدید میسازیم، توی بخش Git ignore میتونیم از بین یه سری الگوهای آماده انتخاب کنیم. مثلاً اگه پروژه پایتونه، گزینه Python رو انتخاب میکنیم تا گیتهاب یه فایل gitignore مناسب برامون بسازه که فایل‌های اضافی مثل پوشه __pycache__ و فایل‌های *.pyc رو نادیده بگیره.
**روش دوم: ساخت دستی فایل gitignore**
میتونیم خودمون توی ریشه پروژه یه فایل به اسم .gitignore بسازیم و توش قوانین مورد نظرمون رو بنویسیم. برای این کار، توی ترمینال یا خط فرمان میریم توی پوشه پروژه و این دستور رو میزنیم:
```
touch .gitignore
```
بعد با یه ویرایشگر متن، قوانین رو توش مینویسیم.
**روش سوم: استفاده از قالب‌های آماده گیتهاب**
گیتهاب یه مجموعه کامل از قالب‌های gitignore برای زبان‌ها و محیط‌های مختلف داره توی مخزن github/gitignore. میتونیم بریم اونجا و قالبی که به درد پروژمون میخوره رو پیدا کنیم و توی فایل gitignore خودمون کپی کنیم.
**روش چهارم: استفاده از ابزارهای مخصوص**
چندتا ابزار هست که کار ساخت فایل gitignore رو راحت‌تر میکنن:
- **gitignore.io**: یه وبسایت هست که با انتخاب زبان‌ها و ابزارهای مختلف، یه فایل gitignore مناسب براتون تولید میکنه.
- **create-gi**: یه ابزار خط فرمان هست که با دستور npx create-gi میتونیم سریع یه فایل gitignore استاندارد برای پروژه‌مون بسازیم.
- **GIG (GitIgnore Generator)**: یه ابزار دیگه با رابط کاربری جذاب که با دستور gig generate --template node میتونیم فایل gitignore مناسب زبان مورد نظرمون رو بسازیم.
**نکته مهم**: اگه فایلی رو قبلاً به گیتهاب فرستادیم و حالا میخوایم نادیده گرفته بشه، اول باید با دستور `git rm --cached FILENAME` اون رو از Track خارج کنیم، بعد به gitignore اضافهش کنیم.
---
### قابلیت‌های جالب گیتهاب که شاید نشنیده باشید
گیتهاب فقط یه جای ساده برای نگهداری کد نیست. قابلیت‌های خیلی جالب و پیشرفته‌ای داره که میتونن کارمون رو خیلی راحت‌تر کنن. بیایید چندتاش رو باهم ببینیم:
#### GitHub Copilot و قابلیت‌های هوش مصنوعی
گیتهاب اخیراً یه نرمافزار جدید مخصوص Copilot منتشر کرده که خیلی پیشرفته‌ست. این نرمافزار به ما اجازه میده چندین عامل هوش مصنوعی رو همزمان مدیریت کنیم. با داشبورد "My Work" میتونیم همه جلسات فعال، Issueها و Pull Requestها رو از یه جا کنترل کنیم. هر جلسه هوش مصنوعی توی یه محیط ایزوله به اسم Git Worktree اجرا میشه تا با کارهای دیگه تداخل نکنه.
**ویژگی‌های جالب Copilot:**
- **Canvases**: یه محیط تعاملی که برنامه هوش مصنوعی، خروجی‌ها و وضعیت کار رو به صورت لحظه‌ای نشون میده و میتونیم مستقیم روش ویرایش کنیم.
- **Sandbox**: محیط‌های ایزوله برای تست کد بدون اینکه به سیستم اصلی آسیبی برسه. میتونیم این محیط‌ها رو روی سیستم خودمون یا روی سرورهای ابری گیتهاب اجرا کنیم.
- **Agent Merge**: یه ابزار خودکار که Pipelineهای CI/CD رو مانیتور میکنه، بررسی‌های انسانی رو پیگیری میکنه و بعد از تأیید همه شرایط، کد رو به‌طور خودکار ادغام میکنه.
توی گیتهاب دسکتاپ نسخه ۳.۶ هم قابلیت‌های جالبی اضافه شده:
- **تولید کامیت با هوش مصنوعی**: Copilot میتونه پیام‌های کامیت رو با توجه به دستورالعمل‌های پروژه تولید کنه.
- **حل تعارض با Copilot**: وقتی توی ادغام کد به مشکل میخوریم، Copilot میتونه تعارض رو توضیح بده و راه حل پیشنهاد بده.
- **پشتیبانی از Git Worktrees**: میتونیم همزمان روی چندین شاخه کار کنیم بدون اینکه مجبور باشیم مدام تغییرات رو ذخیره و بین شاخه‌ها جابه‌جا بشیم یا چندین کلون جداگانه داشته باشیم.
#### GitHub Codespaces
GitHub Codespaces یه محیط توسعه کامل در ابر هست که مستقیم توی مرورگر اجرا میشه. دیگه لازم نیست نرمافزارهای مختلف رو روی سیستم خودمون نصب کنیم. کافیه بریم توی گیتهاب و یه Codespace برای پروژمون باز کنیم تا همه چیز از قبل تنظیم شده باشه.
مزایای اصلی:
- دیگه مشکل "روی سیستم من کار میکنه" رو نداریم.
- تازه‌واردها میتونن خیلی سریع شروع به کار کنن.
- میتونیم محیط‌های تست ایزوله بسازیم.
- برای تیم‌های دورکار عالیه.
#### GitHub Actions
GitHub Actions یه ابزار اتوماسیون قدرتمنده که میتونیم باهاش workflowهای مختلف رو خودکار کنیم. مثلاً میتونیم تنظیم کنیم که هر بار که کد جدیدی به شاخه main میفرستیم، به‌طور خودکار تست‌ها اجرا بشن و اگه همه چی اوکی بود، کد به GitHub Pages یا هر جای دیگه‌ای دیپلوی بشه. الان ماهی بیش از ۲ میلیارد دقیقه از GitHub Actions استفاده میشه که نشون میده چقدر محبوبه.
#### GitHub Secrets (رمزهای امن)
گیتهاب قابلیتی داره به اسم Secrets که میتونیم اطلاعات حساس مثل رمزها و کلیدهای API رو توش ذخیره کنیم. این اطلاعات به‌صورت رمزنگاری شده ذخیره میشن و فقط در مواقع لازم در اختیار برنامه‌ها قرار میگیرن.
انواع مختلفی از Secrets وجود داره:
- **Dependabot Secrets**: برای به‌روزرسانی خودکار کتابخونه‌ها و وابستگی‌ها.
- **Codespaces Secrets**: برای استفاده توی محیط‌های توسعه ابری.
این قابلیت خیلی به امنیت پروژه کمک میکنه چون دیگه مجبور نیستیم اطلاعات حساس رو مستقیم توی کد بنویسیم.
---
### کلیدهای میانبر پرکاربرد گیتهاب دسکتاپ 
**مدیریت ریپازیتوری:**
| کلید میانبر (ویندوز) | کلید میانبر (مک) | کاربرد |
|---|---|---|
| `Ctrl+N` | `Command+N` | ساختن ریپازیتوری جدید |
| `Ctrl+O` | `Command+O` | اضافه کردن ریپازیتوری محلی |
| `Ctrl+Shift+O` | `Shift+Command+O` | کلون کردن ریپازیتوری |
| `Ctrl+T` | `Command+T` | دیدن لیست ریپازیتوریها |
| `Ctrl+P` | `Command+P` | ارسال کامیتها به گیتهاب |
| `Ctrl+Shift+P` | `Shift+Command+P` | گرفتن تغییرات از گیتهاب |
| `Ctrl+Shift+G` | `Shift+Command+G` | دیدن ریپازیتوری در سایت |
| `Ctrl+Delete` | `Command+Delete` | حذف ریپازیتوری |
**مدیریت شاخه (Branch):**
| کلید میانبر (ویندوز) | کلید میانبر (مک) | کاربرد |
|---|---|---|
| `Ctrl+Shift+N` | `Shift+Command+N` | ساختن شاخه جدید |
| `Ctrl+Shift+R` | `Shift+Command+R` | تغییر اسم شاخه فعلی |
| `Ctrl+Shift+D` | `Shift+Command+D` | حذف شاخه فعلی |
| `Ctrl+Shift+U` | `Shift+Command+U` | گرفتن تغییرات از شاخه اصلی |
| `Ctrl+Shift+M` | `Shift+Command+M` | ادغام با شاخه فعلی |
| `Ctrl+Shift+S` | `Shift+Command+S` | مخفی کردن تغییرات فعلی (Stash) |
| `Ctrl+B` | `Command+B` | دیدن لیست شاخه ها |
**کار با کامیت:**
| کلید میانبر (ویندوز) | کلید میانبر (مک) | کاربرد |
|---|---|---|
| `Ctrl+1` | `Command+1` | دیدن تغییرات قبل از کامیت |
| `Ctrl+2` | `Command+2` | دیدن تاریخچه کامیتها |
| `Ctrl+G` | `Command+G` | رفتن به قسمت نوشتن توضیحات کامیت |
| `Ctrl+Enter` | `Command+Enter` | ثبت کامیت |
**کار با Pull Request:**
| کلید میانبر (ویندوز) | کلید میانبر (مک) | کاربرد |
|---|---|---|
| `Ctrl+R` | `Command+R` | دیدن PR فعلی در سایت |
| `Ctrl+Shift+C` | `Shift+Command+C` | مقایسه شاخه ها در سایت |
---
***ساخته شده توسط***
***invincible627***
***لینک پروفایل گیتهاب***
***https://github.com/invincible627***