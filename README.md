[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support%20my%20work-FFDD00?style=flat&labelColor=101010&logo=buy-me-a-coffee&logoColor=white)](https://www.buymeacoffee.com/r0mymendez)

---

# My Preparation Journey for GitHub Fundamentals Certification

This month, I achieved the **"GitHub Fundamentals"** certification, and in this article, I want to share how I did it, what new things I learned, and what I didn’t know before but wish I had known earlier so I could have implemented it sooner.

# What is the GitHub Platform?
The **GitHub** platform is a cloud-based solution built on **Git**, a version control system. It facilitates collaboration and project management through a range of features and AI-powered tools, enabling efficient software development, while ensuring quality and secure deployment.

![github-features](img/github-0.png)


**Some features we can highlight are as follows:**

* **🤖 AI**: GitHub uses products like Copilot, which will be described later, to help develop and solve problems and perform automated security reviews. This enhances collaboration, productivity, and security.
* **🤝 Collaboration**: GitHub facilitates efficient collaboration with tools such as Repositories, Issues, and Pull Requests. These features allow multidisciplinary teams to work together quickly, reduce approval times, and accelerate project delivery.
* **⚙️ Productivity**: Automation through GitHub Actions enables developers to focus on creating solutions and avoid repetitive manual tasks.
* **🔒 Security**: GitHub includes features like Dependabot and automated security reviews, ensuring that code remains private and protected within the organization.
* **🌍 Scalability**: GitHub boasts the largest developer community in the world, with over 100 million developers and more than 330 million repositories.
* **🔗 Integration**: Additionally, GitHub offers an API that allows for integrations and customization of workflows, as well as automation of tasks.

---


# 🟠 GitHub Functionalities & Products
As mentioned initially, this post is intended to discuss what you need to know in order to pass the certification exam. Below, we have an image that represents each of the described entities and the topics you should study to successfully pass the certification exam, which consists of **✏️ 75 multiple-choice questions**.

This mental map represents how I organized the key concepts needed to prepare for the certification, following the GitHub Foundation Learning Path, which I will explain next.

![github-mental-map](img/github-1.png)

---

# 🟠 GitHub Foundations Learning Path
In order to effectively study and understand all the essential content for the certification, I completed the **['GitHub Foundations Learning Path'](https://learn.microsoft.com/en-us/collections/o1njfe825p602p)** provided by **Microsoft Learn**. This path consists of 15 modules, totaling approximately ⌛ 10 hours, with each module averaging about ⌛ 35 minutes. 
The journey combines 📚 theoretical knowledge with ✏️hands-on exercises, enabling me to effectively learn and apply the concepts.

## Practices with GitHub Actions
The modules include ✏️ hands-on exercises solved in stages, using **GitHub Actions** to validate each step of the process. This inspired me to develop similar tutorials for future posts.

## Interactive Console
Some modules, such as the first one, offer an interactive console that facilitates executing typical Git commands, further enhancing the learning experience.

## Knowledge Check
Each unit includes a set of ✏️questions to validate what has been learned, similar to those found on the exam. 
> 🙌 I recommend completing and reviewing these questions to consolidate the knowledge acquired.


------------------------

# 🟠 Overview of Units
With the foundational concepts established, I will now delve into a detailed description of each unit. Below, you will find explanations of the key elements and tools I studied, and how I organized them to effectively prepare for the certification.

---

## 🟠 Code Management
**Code management on GitHub** is essential for productivity and effective collaboration within development teams. Below are the key tools that facilitate this management:


![github-code-management](img/github-11.png)


---

### 📁 Repository
The **repository** is the core component of a project on GitHub, which is where the source code, along with its version history, documentation, and other relevant resources for the project, is stored.

---

### 🔄 Pull Requests
**Pull Requests (PRs)** are a fundamental tool for collaboration on GitHub. They allow developers to propose changes to the source code, which can then be reviewed and discussed by other team members before being merged into the base code.


**Pull Request States**
It is important to understand the possible states of a Pull Request (PR) on GitHub, which can be:
* **Draft**: PRs in draft status are still in development and not yet ready for formal review. This state allows collaborators to work on a proposal before requesting official feedback.
* **Open**: Open PRs are ready and available for review and discussion by project collaborators. This is where proposed changes are evaluated before deciding whether to integrate them into the base code.
* **Closed**: Closed PRs have not been accepted and therefore will not be merged into the project's base code. This state may indicate that the proposal was rejected or that the author decided not to proceed with it.
* **Merged**: Merged PRs have been accepted, and the proposed changes have been successfully integrated with the main branch of the project. This is the final state of a successful PR.

---
### 🔧 Issues
**Issues** are tracking tickets used to report bugs, suggest improvements, or discuss new features. They are essential for planning and organizing work within a project, allowing teams to prioritize tasks and track progress.

---

### 💬 Discussions

**Discussions on GitHub** provide a space where collaborators can engage in broader conversations about the project. These discussions can be organized into several categories:

* **📢 Announcements:** For communicating important updates about the project.
* **💬 General:** For general conversations that don't fit into any other category.
* **💡 Ideas:** For proposing and debating new ideas or improvements.
* **🗳️ Polls:** For conducting surveys and gathering community opinions.
* **🙏 Q&A:** For questions and answers about the project.
* **🙌 Show and Tell:** For sharing achievements, demos, or use cases of the project.

---

## 📁 Gists
**Gists** are a simple way to share snippets of code or text. They can be public, accessible to anyone, or private, visible only to the creator or those with whom the link is shared. Gists are useful for quickly sharing code examples, notes, or scripts among collaborators or with the broader community.

----

## 🟠 Accounts
This is one of the topics where you may encounter questions, and within the recommended learning path, you can find three types of accounts:

* **👥Personal Account**: This is the basic account for individual users, allowing them to own and manage repositories, packages, and projects.
* **🏢 Organization Account**: Allows multiple users to collaborate on shared projects.
* **💼 Enterprise Account**: Designed for large companies, it enables centralized management of policies and billing for multiple organizations.

![github-accounts.](img/github-3.png)


Additionally, the existing plans are:

* **GitHub Free:** Provides the essentials for individuals and organizations, with limited storage and GitHub Actions minutes.
* **GitHub Pro:** Extends the features of GitHub Free with more GitHub Actions minutes, storage, and advanced tools for private repositories, ideal for individual developers.
* **GitHub Team:** Similar to GitHub Pro but optimized for organizations, adding advanced team collaboration capabilities.
* **GitHub Enterprise:** Offers premium support, enhanced security, compliance, and advanced authentication options, along with significantly increased resources and storage. There are two versions of this account type:
  - **Cloud** (hosted by GitHub)
  - **Server** (self-managed)


----

## 🟠 Methodologies

I’ve titled this section "Methodologies" because throughout different chapters of the learning path, I encountered several methodologies that you need to learn. Therefore, I decided to group them all under the same concept.

> ⚠️ Remember that this is my approach to studying for the certification, and you might find that the learning path or other resources refer to these methodologies differently.

![methodologies](img/github-4.png)


* **🔀 GitHub Flow:** A workflow that utilizes specific components (branches, commits, and pull requests) to collaborate and experiment with new features or fixes in a software project.

* **🔄 InnerSource:** Involves adopting open-source practices and principles, such as transparency and collaboration, within an organization. This means projects are shared internally, allowing any team member to access, modify, and contribute to the code, similar to an open-source project but within the organization.

* **🛠️ Contributing to Projects:** I consider this a methodology because GitHub enables active participation in open-source projects through its platform. This practice is not only fundamental for collaborative software development but also promotes learning, innovation, and community building among developers. Key considerations include:
  - **📢 Identification and Communication:** Before making changes, it's important to communicate your intentions with the project's maintainers, whether you are addressing an existing issue or proposing a new feature.
  - **🔄 Creating a Pull Request:** Once changes are made, a pull request is created on GitHub, allowing others to review, discuss, and eventually merge it with the main codebase.
  - **🔎Review and Adjustments:** The pull request is reviewed by the project maintainers, who may request adjustments. It's essential to be open to feedback and willing to make necessary changes for your contribution to be accepted.
  - **👥 Iteration and Ongoing Collaboration:** The review and discussion process around a pull request is iterative and collaborative, allowing for improved software quality and ensuring each contribution aligns with the project's standards and goals.
* **❤️ Supporting Projects Financially**: In addition to contributing code and feedback, you can also support open-source projects financially. For this reason, GitHub Sponsors allows you to fund projects and individuals to help them continue their open-source work, while giving them the recognition they deserve. To support a project:
  - **Identify Projects**: Explore and select projects you are passionate about.
  - **Choose a Sponsorship Level**: Pick a tier that fits your budget and desired level of support, with varying benefits such as exclusive content or early access to new features.
  - **Support and Recognition**: Find the Sponsor button on a project’s main page if it’s eligible for sponsorship. You can select the sponsorship tier and decide if you want your contribution to be public.

![github-sponsor](img/github-sponsor.png)
> source: [Identify where you can help](https://learn.microsoft.com/en-us/training/modules/contribute-open-source/2-identify)

![github-tier](img/github-tier.png)
> source: [Identify where you can help](https://learn.microsoft.com/en-us/training/modules/contribute-open-source/2-identify)

----


## 🟠 Communication

Communication within a repository is essential and encompasses the detailed documentation of objectives, changes, methodologies, and rules to be applied. Below are the main tools and practices that facilitate this communication:

* **📄 README File:** The README file is the first line of communication in a project. It should contain essential information about the project's purpose, how to use it, how to set it up, and any other relevant details that users and collaborators need to know.

* **📚 Wiki:** This section is designed to host more extensive and detailed documentation. Unlike the README, which is brief and direct, the Wiki is ideal for sharing content such as use cases, examples, design principles, technical details, and any other aspects that require a more in-depth explanation.

![communication](img/github-5.png)


### 📝 Markdown
**Markdown is a markup language** that provides a simple and efficient way to format and style content in issues, README files, wikis, and any other textual documentation within a repository.

If you're not familiar with Markdown, I recommend checking out the [DataCamp CheatSheet](https://www.datacamp.com/cheat-sheet/markdown-cheat-sheet-23), which summarizes everything you need to get started. Additionally, within the chapter, there's an exercise titled ["Exercise - Communicate using Markdown"](https://learn.microsoft.com/en-us/training/modules/communicate-using-markdown/3-communicating-using-markdown) that will allow you to apply and reinforce your practice using markdown.


![github-project-table](img/github-project-table.png)
> source: [DataCamp CheatSheet](https://www.datacamp.com/cheat-sheet/markdown-cheat-sheet-23)


-----

## 🟠 Products
I have titled this section **"Products"** as it includes two chapters dedicated to two key products. One of these products leverages AI, while the other focuses on enhancing productivity.

![products](img/github-6.png)


### 🚀 GitHub Copilot
**GitHub Copilot** is an AI-powered assistance tool for developers. Its main features include:

* **💬 GitHub Copilot Chat**: Provides a chat within the editor for code analysis, generating unit tests, and fixing bugs.
* **🔄 Copilot for Pull Requests**: Automatically adds labels to pull request descriptions using AI to facilitate review.
* **📄 AI-Generated Documentation Answers**: Delivers AI-generated responses to questions about documentation and technologies.
* **⚙️ Copilot for CLI**: Assists in creating complex commands and loops in the command line.
 

### 🚀 GitHub Codespaces

**GitHub Codespaces** provides configurable development environments in the cloud, built on Docker container. Therefore  every each Codespace operates within a 🐋 Docker container hosted on GitHub. Also, this container includes all the necessary tools and settings for your project, ensuring a consistent and reproducible environment for all project contributors.

Here’s an overview of the key functionalities and states of a Codespace:

* **🛠️ Creating Codespaces:** You can create a Codespace from templates, repository branches, open pull requests, or historical commits. By default, each Codespace is based on an Ubuntu Linux image, but you can customize it with any Linux distribution to meet your specific needs. This provides a complete development environment running inside a Docker container on a virtual machine. You can create multiple Codespaces per repository or branch, though there is a limit on the number of simultaneous Codespaces.
* **📥 Saving Changes:** Changes made within a Codespace are automatically saved when connected through the web. To avoid losing work if the Codespace is deleted, it is crucial to commit and push changes to a remote repository.
* **🔄 Reopening and Using Codespaces:** You can reopen active or stopped Codespaces from GitHub.com, Visual Studio Code, JetBrains IDE, or GitHub CLI. When connected, you access the Docker container of the Codespace, ensuring a consistent development environment accessible from anywhere.
* **⏱️ Timeout and Internet Connection:** Codespaces automatically stop after 30 minutes of inactivity. They require an internet connection, and any uncommitted changes are saved to prevent data loss.
* **🔧 Closing, Stopping, or Rebuilding a Codespace:** You can stop or restart a Codespace to apply configuration changes or troubleshoot issues. You can also rebuild the Codespace to update the Docker container configuration.
* **🗑️ Deleting a Codespace:** You can delete a Codespace after committing your changes. Inactive Codespaces are automatically deleted after 30 days, though this period can be adjusted.
Using Docker containers ensures that your development environment is consistent and reproducible, making it easier to collaborate and maintain projects.

---


## 🟠 Projects

GitHub has introduced new types of projects that significantly enhance productivity and project management. While previously existing projects focused primarily on code management, the new GitHub Projects integrate key elements that allow you to manage not only the code but also the broader aspects of project management within a single tool.

This new approach aims to streamline workflows, provide more comprehensive tracking, and improve collaboration. It’s important to note that there may be questions about the differences between the previous project types and these new ones. In the following sections, I'll highlight the functionalities and benefits of the new project types, helping you understand how they differ from the old ones and how they can be utilized to optimize project management.

![projects](img/github-7.png)

### 📋 View
In GitHub Projects, tasks are represented as issues and can include key details such as title, description, assignee, start date, and complexity. These issues can be customized with various field types like text, number, date, single selection (for dropdown lists), or iteration to better suit your needs.

The types of views that can be generated are:

* **📄 Table**: A `tabular view` that organizes issues in a table format. This view is primarily used to view and manage detailed information on multiple issues simultaneously, facilitating comparison and bulk editing of data.
![github-project-table](img/github-project-table.png)

* **📋 Board**: A `card-based view` where issues are organized into columns, typically by status or category. This view is primarily used to visualize the workflow of issues through different stages, aiding task management and progress tracking.
![github-project-board](img/github-project-board.png)

* **⌛ Roadmap**: A graphical view that shows a timeline of issues and the associated milestones. This view is primarily used for planning and visualizing the long-term evolution of projects, helping to identify dependencies and delivery schedules.
![github-project-roadmap](img/github-project-roadmap.png)



### 📊 Insights 
**Insights in Projects** allows you to `visualize`, `create`, and `customize` `charts` using the elements added to your Project as data sources. When creating a chart, you can define filters, the type of chart, and the information to be displayed. The generated charts are available to anyone with access to the Project.

These charts enable you to analyze and manage the project, enhancing your ability to plan, control, and assess the project's progress.

![github-insights](img/github-insights.png)


---

### 🤖 Task Automation

Task automation on GitHub is important for improving efficiency and consistency in project management. The following are the key tools that facilitate this automation:

* **Workflows:** Workflows are the simplest way to automate project management on GitHub. These workflows allow you to automate repetitive processes such as `updating task statuses`, `running tests`, `deployments`, and `other actions` defined in YAML files. Integrated workflows in GitHub Projects streamline automation without the need for complex configurations.
* **GraphQL API:** The GraphQL API offers more granular control over project automation. With GraphQL, you can customize how you interact with your project data, enabling advanced automations tailored to your team's specific needs.
* **GitHub Actions:** GitHub Actions provides a powerful platform for further customizing automation in your projects. With GitHub Actions, you can create pipelines that respond to specific events, such as the creation of issues or changes in task statuses, ensuring that all activities in your project are executed consistently and automatically.

----

## 🟠 Security
Security is a fundamental aspect within GitHub, which provides a range of tools and best practices to enhance security in software development.

![security](img/github-8.png)

### 🔐 Authentication & Access Controls
Access to your GitHub account can be enhanced with advanced authentication methods that validate user identity more securely.
* **SAML SSO Authentication**: Allows user authentication through a centralized Identity Provider (IdP), enhancing security and access control.
* **Multifactor Authentication (2FA)**: Adds an extra layer of security through two-step authentication, which may include physical security keys and time-based one-time password (TOTP) applications.

---

### ⚠️ Vulnerability Alerts

GitHub offers vulnerability alerts to help you identify and address security issues in your repositories.

* **Dependabot Alerts**: Detects and notifies you about vulnerable dependencies in your project, helping you keep your libraries and packages up to date.

![github-dependabot-alerts](img/github-dependabot-alerts.png)
> source:[Automated security](https://learn.microsoft.com/en-us/training/modules/maintain-secure-repository-github/3-security-automation)


* **Code Scanning**: Analyzes your code for vulnerabilities and errors. It can be customized using CodeQL, allowing you to detect and fix security issues before they become risks. Integration with other tools like SonarQube or Policy Validator for Terraform by Amazon Web Services is also possible.
* **Secret Scanning**: Automatically scans the repository for exposed credentials or secrets, helping to prevent misuse of sensitive information.


### 📊 Reporting
* **Security Policy**: The security policy for your project should be documented in a `SECURITY.md` file, detailing how to responsibly report vulnerabilities.

### 🚀 Best Practices

* **Keep Sensitive Information Secure**: It's crucial to protect sensitive information by ensuring it is not included in commits. Use `.gitignore` to exclude critical files and carefully review changes before committing them.
* **Branch Protection Rules**: Set up protection rules for key branches like `master` or `develop`, requiring approved reviews before allowing merges. This ensures that only secure and reviewed code is integrated into the main branches.


----


## 🟠 Types of Search on GitHub
On GitHub, you can use advanced search to efficiently navigate repositories, find issues, review pull requests, and join discussions. Here are some practical examples to enhance your search capabilities and collaboration on projects:


![type-of-search](img/github-9.png)


### Search Examples

#### 🔎 Repositories

- **Description**: Finds repositories related to "machine learning" with more than 1000 stars.
- **Use**: Ideal for locating popular projects in a specific area of interest.

```
topic:machine-learning stars:>1000
```


#### 🔎 Issues in a Specific Repository
 - **Description**: Searches for closed issues within the `r0mymendez/datapp` repository.
 - **Use**: Useful for reviewing the history of resolved issues in a particular repository.

```
repo:r0mymendez/datapp is:issue is:closed
```


#### 🔎 Issues with Labels and Status
- **Description**: Finds open issues tagged with "help-wanted" in projects using Python.
- **Use**: Perfect for finding opportunities to contribute to Python projects where maintainers are seeking help.

```
is:issue language:python is:open label:help-wanted
```

#### 🔎 Pull Requests
- **Description**: Shows all pull requests where a review has been requested from you.
 - **Use**: Ideal for managing your code review responsibilities.

```
is:pr review-requested:@m
```


#### 🔎 Discussions
- **Description**: Finds open discussions in repositories related to the Python language.
- **Use**: Useful for participating in relevant conversations or searching for open topics in a specific programming language.

```
in:discussions is:open language:python
```


#### Issues with Specific Combinations
- **Description**: Searches for open issues in repositories related to "machine learning" with more than 1000 stars, tagged with "help-wanted," and using Python.
- **Use**: Ideal for finding open issues in popular machine learning projects that are seeking help in Python.

```
topic:machine-learning stars:>1000 is:issue label:help-wanted language:python is:open
```

---

## 🟠 Summary

![complete](img/github-10.png)


---


## 📚 References
The following references were used to create this article, with the first being the primary resource. The other materials were utilized to practice and simulate the exam.

1. **GitHub Foundations Learning Path**: [GitHub Foundations Learning Path](https://learn.microsoft.com/en-us/collections/o1njfe825p602p)
2. **GitHub Foundations Practice Test**: Contains a series of multiple-choice questions for exam simulation. [GitHub Foundations Practice Test](https://ghcertified.com/practice_tests/foundations/)
3. **Study Guide GitHub Foundations**: A PDF guide for studying and preparing for the exam. [Study Guide GitHub Foundations](https://assets.ctfassets.net/wfutmusr1t3h/1kmMx7AwI4qH8yIZgOmQlP/79e6ff1dfdee589d84a24dd763b1eef7/github-foundations-exam-study-guide__1_.pdf)
4. **GitHub Foundations Certification – Exam Prep Guide**: This is a post in FreeCodeCamp blog and it is content very helpful, and this post provides a good summary of everything you should know for exam preparation. [GitHub Foundations Certification – Exam Prep Guide](https://www.freecodecamp.org/news/github-foundations-certified-exam-prep-guide/)
