1:Introduction to GitHub:Github is a web based hosting service for version control using Git.
   Primary functions
   -Facilitates collabortaion among developers through features such as tracking.
   -Provides hosting services for users to host their repositories
   -Provides a platform for verion control for users to track their changes.
   -Integrate with various CI/CD services enabling automated testing and deployment.
        Support
    -Developers can create branches to work on and merge with the main branch once reday.
    -Provides cloning and forking services and developers can collaborate on various projects and improve on projects.
    -Teams use issues features to track bugs and tasks and projects.
    -  Offers realtime collaboration features like live chat and real-time communication among developers.

2: Github Repository.
  A GitHub repository is a storage space where developers save their code and  documentation.
       Creating a New Repository
    Log In: First, log in to your GitHub account. If you don't have one, you'll need to sign up for free.
    Click on the + Icon: On the upper-right corner of the GitHub homepage, click on the + icon and select 'New repository'.
    Name Your Repository: Enter a name for your repository. It's common practice to use lowercase letters and hyphens for readability and to avoid spaces.
    Choose Visibility: Decide whether your repository will be public (visible to everyone) or private (only visible to you and people you choose).
    Initialize the Repository with a README (Optional): You can choose to initialize your repository with a README file, which is a text document that introduces your project.
    Click 'Create Repository': After filling out the form, click Create Repository. Your new repository will now be created.
        Essential Elements of a GitHub Repository
        -Readme File: A README file typically contains an overview of the project and instructions.
        -Contributing Guide: A contributing guide outlines how others can contribute to your project.
        -.gitignore File: This file specifies intentionally untracked files that Git should ignore

3:Version Control with Git:
    -Version control is a system that records changes to a file or set of files over time so that you can recall specific versions at a later date.
    -In the context of Git, which is a distributed version control system, every developer works with a full copy of the entire project history, allowing them to switch between different versions of the project as needed.
    -Git tracks changes made to files over time. 
    -Each change is recorded in a snapshot, which includes the modifications made since the last commit. 
    -These snapshots are stored in a local repository on your computer. When you want to share your work with others or collaborate on a project, you push your commits to a remote repository, eg; GitHub.
         How GitHub Enhances Version Control to Developers
    -Provides a friendly web interface for managing repositories, viweing commit histories and reviewing pull requests.
    -Github simplifies the proccess  of submitting pull reequest and conducting code reviews thus improving code quality.
    Github makes it easier to fork or clone a repository and work on it to improve or create a better version of the project.
    -Provides tools for issue tracking ,project management and continuous integration and delployment through 
    Github actions.

4:Branching and Merging in GitHub:
   -In GitHub, a branch is a parallel version of your project.
   -Branches allow developers to work on separate tasks concurrently without interfering with each other's work.
     Importance of branches
     -Provide an isolated environment for fixing code without interfering with the main code.
     -Enable developers to collaborate on a similar project simultaneously easily.
     -Developers can test new features/ideas without the risk of destabilizing the main project.

     Process of creating a branch
     -Navigate to the main page of the repository in the github website.
    -Click on the "Branch: master" dropdown menu at the top of the file list.
    -Type the name of your new branch into the text box and press Enter

    Using the command line in Git
    -git checkout -b branch-name(creates a new branch)
    -After making changes run git add . then git commit -m "add a descriptive message"
    -Run git checkout main to return to the main branch.
    -Run git merge feature-branch-name to merge your feature branch with the main branch.

5:Pull Requests and Code Reviews:
   -A pull request in GitHub is a mechanism that allows developers to notify team members that they have completed a feature or fixed a bug in a branch. It serves as a proposal to merge the changes from one branch (usually a feature or bugfix branch) into another branch ( main or master branch)
           How Pull Requests Facilitate Code Reviews and Collaboration
    -Before code changes are merged in the main code , they are subjected to review by team members to check whether its right.
    -Pull requst facilitate discussions in the team in the context of code changes thus leading to better communication.
    -Developers collaborate by proposing necessary code changes and work together to refine the code before it is merged into the main project.
    -Pull requst document the history of changes performed in  the code and who performed the changes leading to better maintenance of the project.
       Steps involved in creating and reviweing a pull request
       1:Creating a pull request.
       push your changes to github( git add . , git commit -m"message", git push origin feature-branch-name )
       -switch to your feature branch in your repository.
       -Click on "New pull request" 
       -Give your pull request a title and a description
       -click on  "Create pull request"

       2:Reviewing a pull request
       -Team members will receive a notification once you create  pull request.
       -You can go to the pull request in your repository and check out the changes.
       -Review the changes to the code 
       -Discuss the changes and whether they are needed in the code 
       -Approve or request further changes  to the code .
       After approval the bugfix branch is merged with the main branch.

6:GitHub Actions:GitHub Actions is a feature within GitHub that allows you to automate, customize, and execute your software development workflows right in your repository.
 --With GitHub Actions, you can build, test, package, release, and deploy your projects directly from GitHub.
      Features of Github Actions
      -You can define custom workflows of your project.
      -Workflows can be triggered by events such a pull requests and pushing code.
      -Actions run in a vrtual environment with no access to your private data unless you grant it thus enhancing privacy and security.
         Basic example of a CI/CD pipeline using GitHub Actions;
         -AN example of a CI/CD pipeliine involves automaticaly building and testing code whenever changes are pushed to the repository and then the application if the test passes

7:Introduction to Visual Studio:Visual Studio is an Integrated Development Environment (IDE) developed by Microsoft that provides comprehensive tools for developers to write, debug, and deploy applications across different platforms.
   Key features:
   -Integrated Development Environment (IDE) that offers a rich set of coding, testing and debugging tools.
   -Offers direct integration with cloud services thus ensuring easy deployment of applications by developers.
   -Deep integration with the .NET framework offering advanced features for building windows desktop applicatons and services.
   -Testing tools that help with ensuring good code quality and reliability.
 Visual Studio Code (VS Code) is a lightweight, open-source code editor developed by Microsoft.VS Code is designed to be lightweight and extensible, supporting a wide range of programming languages and frameworks.
   Key features:
   -Lightweight and fast thus uses less memory than traditional IDEs
   -Supports extensions written in many populat programming languages eg python jvavscript, C, C++.
   -Has built in Git integration facilitating robust version control operations.
   -Extensive support for test and debugging functionalities.
    Differences Between Visual Studio and Visual Studio Code;
    - Visual Studio is a full-fledged IDE aimed at professional developers working on large-scale applications, while VS Code is a lightweight code editor focused on simplicity and flexibility
    - VS Code starts faster and uses fewer resources than Visual Studio, making it ideal for smaller projects or for developers who value speed and efficiency.
    - VS Code starts faster and uses fewer resources than Visual Studio, making it ideal for smaller projects or for developers who value speed and efficiency.
    - Both support Windows, but VS Code also supports macOS and Linux, whereas Visual Studio primarily targets Windows development
 
Integrating GitHub with Visual Studio enhances the development workflow by allowing developers to manage their source code directly from the IDE.
This helps developers to;
   -clone repositories easily
   -Perform code reviews
   -Automate deploymenys and workflows
   -Manage branches and commits 

8:Debugging in Visual Studio:Visual Studio comes equipped with a comprehensive suite of debugging tools designed to help developers identify and fix issues in their code efficiently.
   -Breakpoints: Breakpoints are markers placed in the code where execution will pause, allowing developers to inspect the program state at that moment. 
   -Watch Window: allows developers to monitor the values of specific variables or expressions during debugging.
   Variables can be added to the watch list either manually or by dragging them from the Autos or Locals windows.
   -Debugging Tools Window:The Debugging Tools window provides advanced debugging features, such as setting conditional breakpoints, controlling thread execution, and manipulating memory.

9:Collaborative Development using GitHub and Visual Studio:GitHub provides a platform for version control and collaboration, allowing teams to work together on projects, manage code, and track issues and enhancements.
Visual studio offers extensive tools for coding, debugging, and testing.
-The combination of GitHub's collaborative features with Visual Studio's development capabilities streamlines the development workflow, making it easier for teams to produce high-quality software efficiently.
    Real world example;
    A startup that aims to create a food delivery app and wants to create a mobile appplication to facilitate the seamless food rdering and distribution process. The development team is spread across different locations and rely on Github to version control and collaboration while using VS Code and Visual Studio for development, testing and debugging.





