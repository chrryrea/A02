# A02
IS117
Part 1: Setup
  Install Git:
    Download Git from Git Downloads.
    Follow the installation instructions for your operating system.
    After installation, configure your Git username and email:
      git config --global user.name "Your Name"
      git config --global user.email "you@example.com"
  Install WebStorm:
    Download WebStorm from JetBrains.
    Follow the installation instructions.
Step 2: Create a New Project in WebStorm
  Open WebStorm and select Create New Project.
  Choose a project type (e.g., JavaScript) and set the project location.
  Click Create.
Step 3: Initialize a Git Repository
  In WebStorm, go to VCS > Enable Version Control Integration.
  Select Git from the dropdown menu and click OK. This initializes a local Git repository.
Step 4: Create a Remote Repository on GitHub
  Log in to your GitHub account at GitHub.
  Click the "+" icon and select New repository.
  Name your repository and click Create repository.
Step 5: Link Local Repository to GitHub
  Open the terminal in WebStorm
  Run the following command to add your remote repository:
    git remote add origin https://github.com/username/repository.git
Step 6: Make Changes and Commit
  Edit your project files.
  Go to VCS > Commit to stage your changes
  Write a descriptive commit message and click Commit.
Step 7: Push Changes to GitHub
  In the terminal, run:
      git push -u origin main
Step 8: Pull Changes from GitHub
  To fetch and merge changes from the remote repository, run:
      git pull origin main
Step 9: Branching/Merging
  Create a New Branch:
      git checkout -b new-branch
  Switch Back to the Main Branch:
      git checkout main
  Merge the New Branch:
      git merge new-branch
Step 10: Handling Merge Conflicts
    If a merge conflict occurs, WebStorm will highlight conflicting files.
    Edit the files to resolve conflicts, then stage and commit the changes.

    
Part 2: Glossary
    Branch: A parallel version of the repository that allows you to work on features independently.
    Clone: A copy of a repository that you can work on locally.
    Commit: A snapshot of your changes in the repository, normally saved with a summarizing message.
    Fetch: A command to retrieve changes from the remote repository without merging them.
    GIT: A distributed version control system for tracking changes in source code.
    GitHub: A platform for hosting Git repositories and facilitating collaboration.
    Merge: Combining changes from one branch into another.
    Merge Conflict: A situation where changes from different branches conflict and cannot be automatically merged.
    Push: Uploading your local changes to the remote repository on GitHub.
    Pull: Fetching changes from the remote repository and merging them into your local branch.
    Remote: A version of your project that is hosted on a network.
    Repository: A storage location for your project files.

    
  References
  Git documentation: https://git-scm.com/doc
  GitHub documentation: https://docs.github.com/en
  WebStorm documentation: https://www.jetbrains.com/help/webstorm/
