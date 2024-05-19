   <h2> Explain version control.</h2>

    <h3>Version control is a system that helps manage changes to documents, computer programs, large websites, or other collections of information over time. It enables multiple people to work on a project simultaneously, tracks changes, and maintains a complete history of modifications.</h3>

    <h2>Explain difference between git and github</h2>
    <h3>Git is the underlying version control system that manages the history and versions of your project.</h3>
    <h3>GitHub is a platform built on top of Git that provides additional features to facilitate collaboration and project management.</h3>
<h3>In essence, you can use Git without GitHub, but GitHub relies on Git to function. GitHub makes it easier to use Git, especially for team collaboration and open-source development.</h3>

    <h2>List 3 other github alternatives</h2>
     <h3>1. GitLab</h3>
     <h3>2. Bitbucket</h3>
     <h3>3. SourceForge</h3>


    <h2>Explain the difference between git fetch and git pull,</h2>

    <h3>git fetch: Fetches changes from the remote repository without modifying your working directory. Use it when you want to see changes before merging.
    git pull: Fetches and merges changes from the remote repository into your current branch in one step. Use it when you are ready to update your branch with remote changes and handle any merge conflicts immediately.

Choosing between git fetch and git pull depends on your workflow and how much control you want over the integration process of remote changes into your local repository.</h3>

   <h2> Explain in simple terms git rebase and the command for it</h2>
<h3>Git rebase is a command that allows you to integrate changes from one branch into another. Unlike git merge, which creates a new commit for the merge, git rebase moves or combines a sequence of commits to a new base commit. This can make the project history cleaner and more linear. git rebase main </h3>


   <h2> Explain in simple terms git cherry-pick and the command for it </h2>

<h3>Git cherry-pick is a command that allows you to select specific commits from one branch and apply them to another branch. It’s like copying a single commit (or a few commits) from one branch and adding it to another branch, without merging the entire branch.
git cherry-pick <commit-hash> </h3>
