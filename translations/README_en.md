# Github-101

Short course to learn how to use Github.

<details id=0>
<summary><h2>Welcome to everyone!</h2></summary>

We're happy to have you here, welcome to this excited course, where you'll learn the fundamentals of Github, and how to get advantage of all the features that Github offers to you. Github become the tool of choice for millions devolvers around the world. this course will give all the skills that you need yo use it in a professional way.

Through this course, we'll take a dive in the concepts basics of Github, even how to configure your account, how yo create a repository, clone, make changes, colaborate with other devolvers, and more. As well as, we'll provide you tricks and good practices to make sure you're using a efficient workflow.

Our goal is help everyone to getting familiar with Github concepts, improve your productivity, make easier the collaboration with your team, and bring your software to the next level. Doesn't matter if you're begginer in the world of programming, or if you're a senior developer, this course is for you.

We're so excite to follow along with you in this new joruney, and we hope get advantage of this great course.

Good luck and happy coding!

- The team of Github-101

</details>

<details id=1>
    <summary><h2>Introduction</h2></summary>
<br>
Github is a cloud-based service which host a control sistem version called [Git](https://docs.github.com/en/get-started/using-git/about-git), in other word, is a plataform of collaboration which use Git to manage the changes, this mean, Github is used for sharing and contributing [open source](https://github.com/topics/open-source) code. 

📺 Video: [What's Github](https://www.youtube.com/watch?v=pBy1zgt0XPc)
<br>

**What's a repository**
A [repository]((https://docs.github.com/en/get-started/quickstart/github-glossary#repository)) is  a proyect which contains all of the fill by itself, like images, folders, and other types of files along with the history of all the changes that have been made to those files.

📺 Video: [What's a repository](https://www.youtube.com/watch?v=T6o3Ci8Ieag)

**What's a branch**
<br>
In github a [branch](https://docs.github.com/en/get-started/quickstart/github-glossary#branch) is a version of the repository, this mean, you can have a repository with multiple versions of the same project, and each version is called a branch. The default branch is called `main`, but you can create new branches from the default branch and create pull requests to propose changes to the default branch.

The branches are helpful to solve problems, like devolvp new chracateristics, fix bugs, or experiment with new ideas. Each branch can chave its own commits history, and it's independent from the other branches. This allows a workflow collaborative where multiple people can work in the same project at the same time, in parrellel.

📺 Video: [What's a branch](https://www.youtube.com/shorts/YyFrdoD-Wjk)

**What's a commit**
<br>
A [commit](https://docs.github.com/en/get-started/quickstart/github-glossary#commit) is a change to a file or set of files. When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes commited along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.

📺 Video: [What's a commit](https://www.youtube.com/watch?v=XfDbGgSwa5I)

**What's a pull request**
<br>
A [pull request](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request) is a request to the owner to merge changes from a branch in a repository into another branch. Pull requests start and facilitate code review and conversation about changes before merging them into the project.
This show tha changes that have been pushed to a repository, and you can compare the changes, add comments, and review the code before merging the changes into the repository.

📺 Video: [What's a pull request](https://www.youtube.com/watch?v=8lGpZkjnkt4)

**What's a merge**
<br>
A [merge](https://docs.github.com/en/get-started/quickstart/github-glossary#merge) is the process of integrating changes from a pull request into the main branch. Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. GitHub also offers a merge button that automatically merges the changes locally and creates a merge commit.

📺 Video: [How to make a merge](https://www.youtube.com/watch?v=XX-Kct0PfFc)

**What's  README file**
<br>
A [README](https://docs.github.com/en/get-started/quickstart/github-glossary#readme) is a text file that introduces and explains a project. It contains information that is commonly required to understand what the project is about.

The README is used to give basic information about the hosted proyect on Github, the main goal is give to the users a quick overview of the project, and how to use it. The README is the first file that the users will see when they visit your repository, and it's a great way to show the users how your project works and what it does.

The content in a README file is different from one project to another, but some of the most common sections are:

**Title and description**: A title and description of the project.
**Requirements**: A list of the requirements that the user need to use the project.
**Installation**: A list of the steps that the user need to follow to install the project.
**Usage**: A list of the steps that the user need to follow to use the project.
**Contributing**: A list of the steps that the user need to follow to contribute to the project.
**Adittional information**: A list of the adittional information that the user need to know about the project.
**License**: A list of the license that the project use.

**Whats a profile README**
<br>
A profile READMe is a introduction to who you're, in others words, we can call it like a biography where you can show your skills, interests, and projects. This is a great way to introduce yourself to the community, and show your work to the world.
If you wanna know more  go to [Manage your README profile](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-your-profile-readme)

📺 Video: [How to create a profile README](https://www.youtube.com/watch?v=G-EGDH50hGE)

<br>

![vgglProfileREADME](/images/vgglProfileREADME.jpeg)

</details>

<details id=2>
<summary><h2>Start of the course</h2></summary>

1. Click on **Start course** button. (I suggest open it in a new tab)

<br>

[![Start course](https://user-images.githubusercontent.com/1221423/218596841-0645fe1a-4aaf-4f51-9ab3-8aa2d3fdd487.svg)](https://github.com/new?template_owner=)

2. Once we're are in the tab, go to the next instructions to make a new repository.
    - The owner of the account should indicate if will use their personal account or a organization to host the repository.
    - We suggest you create a repository public; the private repository [will use minutes from Github Actions](https://docs.github.com/en/github/setting-up-and-managing-billing-and-payments-on-github/about-billing-for-github-actions#about-billing-for-private-repositories).

    ! [Create a new repository](/images/creando-nuevo-repositorio.jpg)

3. After of making the repository, we need to wait around 20 seconds to update the page and see tje new repository.

</details>

<details id=3>
<summary><h2>Step 1: Sending a file/change</h2></summary>

Once inside the repository, we can see that we don't have any files yet, but the platform provides us with some recommendations, such as adding (uploading) a file or creating one. It also suggests that we can create/include a README, LICENSE, or .gitignore file.
<br>

 ![Incluidng a README file](/images/incluyendo-archivo-README.jpg)

For this exercise, we will click on the README option, which will redirect us to the view that shows the created file with the same name in .md format on our `main` branch.
<br>

![Creating our README file](/images/creando-nuestro-archivo-README.jpg)

Here, we can add the desired information, as mentioned earlier. It's worth noting that if we don't want to edit it at the moment, we can do it later. For now, let's click on the blue "Commit changes" button located in the upper right corner. Upon doing so, a window will appear asking us to add a title and an optional description. Once we have written them, we can click on the corresponding button.

![Commit changes](/images/commit-changes.jpg)

Great! With this, we have made our first commit, which can be interpreted as if we have created a new file and stored it in our repository.

![README file completed](/images/README-completo.jpg)

Go to the next step.
<br>

**Notes**: if you made a repository selecting the checkbox "Add README file", the last step won't be necessary.**

<br>

[Add a README](/images/addA-README.jpeg)

</details>

<details id=4>
<summary><h2>Step 2: Creating a branch</h2></summary>

Creating a branch allows us to edit the project without changing the `main` (default) branch.

1. On the page where we previously left off, we will see on the left side and below the name of our repository, the **< > Code** tab, along with other header menu options.

2. When clicked, this tab will display a dropdown menu that initially only contains the `main` branch.

<br>

[Branch Dropdown Menu](/images/menu-desplegable-rama-principal.jpg)

In the text field, it indicates that we can search or create a branch. Here, let's enter a name for the second option, and let's call our branch: dev. By doing this, the content will automatically change, and the option to create the branch with the name dev from main will appear.

[dev branch](/images/rama-dev.jpg)
Click on the option Create branch: dev from main to create the branch.

The branch will automatically change to the newly created one. The branch dropdown menu will reflect the new branch option and display its name, which in our case is dev.

[Branch created](/images/rama-creada.jpg)

Done! - You have created a branch :tada:

</details>

<details id=5>
<summary><h2>Step 3: Create a pull request</h2></summary>
To proceed with this step, the first thing we need to do is to create/add a new file since we are currently in the newly generated branch. Let's follow these steps:

1. In the **< > Code** tab, located in the repository's header menu, make sure that we are on the branch we named dev in this example.

2. Next, click on the "Add file" dropdown menu and select the option "Create new file".
<br>

![Create a new file](/images/crear-nuevo-archivo.jpg)
3. In the new view, you will see an empty field with a placeholder text saying "Name your file...". This indicates that we should provide a name for the file. Let's name it `LICENSE.md`.


**Note**: `.md` is a file extension that creates a [Markdown](https://docs.github.com/en/get-started/quickstart/github-glossary#markdown) file. For more information about Markdown, visit [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) in the GitHub documentation or take the [Communicate using Markdown]

<br>

[Licence-template](/images/licencia-platilla.jpg)

``` 
Copyright Notice.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to operate with the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
<br>

![licence-text](/images/licencia-texto.jpg)

5. Next, click on the **Commit changes** button. Similar to the previous step where we created the `README` file, a popup window will appear asking for a brief commit message that describes the changes we made. Remember that this message helps others understand what we are adding in our commit. While GitHub provides a default simple message, let's customize it a bit for practice.

<br>
First, in the title, let's write: "Add LICENSE.md file". In the extended description, let's enter: "Create a License file in markdown format that expresses the copyright notice."

6. Last, now we confirm the changes by clicking on the **Commit changes** button.

![licencia commit](/images/licencia-commit.jpg)

Great! You're already mastering the process of making commits. Isn't it straightforward?

Now that a change has been made in the project and added, it's time to share the proposed change through a pull request (PR), as defined in the Introduction.
</details>

<details id=6>
<summary><h2>Step 4: Merge a pull request</h2></summary>
Once you have completed the previous steps, you may have noticed a small message showing the recent submission to the branch, along with a button that says **Contribute**. When you click on it, you will see two options: **Compare** and **Open pull request**.

### Activity: Creating our first pull request :keyboard:

In the actual screen, lets make a click on the button **Merge pull request**

![Merge pull request](/images/merge-pull-request.jpg)

2. Next, in the mini dropdown that appears, click on **Confirm merge** (note that you can edit both the title and the description, but for this example, let's leave it as it is).

![Confirm merge](/images/confirm-merge.jpg)

3. Once the branch has been merged, we will no longer need it. To delete it, click on **Delete branch**.

![Delete branch](/images/delete-branch.jpg)


**Note**: If we delete the branch, we can restore it using the option that will appear to us.

![recover the branch](/images/restaurar-rama.jpg)

Great! Has successfully merged your changes from the `dev` branch to `main` :tada:

</details>

<details id=7>
<summary><h2>End of the course<h2></summary>

Congratulations! You have completed this mini-course and have acquired the fundamental knowledge that every developer should know.

Throughout the course, you have gained a solid understanding of the fundamental concepts of GitHub and learned how to effectively use this version control platform. Here is a summary of your achievements:

- You learned about GitHub, repositories, branches, commits, and pull requests.
- You created a branch, made a commit, and generated a pull request.
- The pull request was successfully merged.
- You made your first contribution! 🎉

Congratulations on your accomplishments, and keep up the great work on your journey as a developer!

## Next steps
If you wanna create your README profile, i suggest you read the next article
[How to configure a README profile](https://www.sitepoint.com/github-profile-readme/)

Check out the next resources:

- are you students? [GitHub Student Developer Pack](https://education.github.com/pack)
- Live on Mexico or Colombia? Apply to [GitHub Octerships](https://education.github.com/students/octernships) which offers pay mentoryship opportunities to students who are passionate about open source.
- Join to the meetup oficial for GitHub in your country [GitHub Community](https://community.github.com/)

We appreciate your feedback! We strive to provide valuable courses and content to our learners. If you have any comments, suggestions, or feedback about this course, we would love to hear from you. Your input helps us improve and deliver better learning experiences.

If you feel that this course met your expectations and you found it helpful, we would greatly appreciate it if you could leave a star rating or recommend it to your friends. Thank you for your support and we hope to continue providing you with valuable learning resources in the future!

</details>


[Github support](https://support.github.com/)
[Github Community](https://community.github.com/)
