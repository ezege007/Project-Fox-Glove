## Lesson 1.1 — Git, Repositories and Saving Your Work

| **Estimated time**   | 25–30 minutes                                                                 |
|----------------------|-------------------------------------------------------------------------------|
| **Learning purpose** | Understand the basic version-control ideas you will use throughout the trial. |

### What you should be able to do

- Explain in simple language what Git, a repository and a commit are.

- Recognise the difference between Git and Gitea.

- Understand the basic save cycle: edit → check → stage → commit → push.

- Know why meaningful commit messages make project history easier to understand.

### Why software engineers use version control

When you write code, your project changes constantly. You add a function, repair a bug, rename something, or try an idea that later turns out to be wrong. If the only copy of your project is the latest folder on your computer, it can be difficult to remember what changed or return to an earlier working version. Git is a version-control system: it records the history of changes to a project so that you can see what changed and save useful snapshots as you work.

A repository, often shortened to repo, is the project together with its tracked history. You can think of the project folder as the work itself and Git as the history that remembers important versions of that work. Gitea is the Git hosting and collaboration platform used during this trial. It hosts Git repositories so your work can be stored remotely, reviewed and shared with the people who have access. Git and Gitea are related, but they are not the same thing: Git tracks the history of your code, while Gitea provides the server and web interface where the repository is hosted.

### The basic Git workflow

A beginner does not need every Git command on Day 1. You only need a mental model of a few actions. First, you edit files. Second, you check what Git sees as changed. Third, you choose the changes you want in the next snapshot. Fourth, you create the snapshot with a short message. Finally, when a remote repository is being used, you send your commits to it.

git status  
git add solution.py  
git commit -m "Complete travel cost drill"  
git push

\`git status\` tells you what has changed. \`git add\` stages a file for the next commit. \`git commit\` creates a snapshot in the repository history. \`git push\` sends your local commits to the remote repository hosted on Gitea. During the trial, use the Gitea repository assigned to you and follow the repository workflow provided by the platform. Do not create extra branches or change repository configuration unless instructed.

### What makes a useful commit

A commit should represent a meaningful piece of progress. Messages such as “stuff”, “work” or “final final” tell your future self very little. Prefer messages that describe the change: “Complete budget message”, “Fix exact-fit comparison”, or “Add zero-attendee test”. Small, understandable commits make it easier to review how your work developed.

### Quick self-check

In your own words, explain the difference between a repository and a commit. Then explain why a developer may want a history of working versions instead of one final folder.

### Optional resources if you want another explanation

**Watch:** [<u>Git Explained in 100 Seconds (Fireship)</u>](https://www.youtube.com/watch?v=hwP7WQkmECE)

**Read:** [<u>Gitea Docs: What is Gitea?</u>](https://docs.gitea.com/)

**Try later:** [<u>Gitea repository guide</u>](https://docs.gitea.com/usage/repository/)

### Drill

No coding drill is attached to this lesson. The goal is to understand the workflow and use the trial repository correctly. Repository activity can still be observed as part of your work evidence.
