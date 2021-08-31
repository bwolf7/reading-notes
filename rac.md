commit important for the long term. 
Git commit messages are public
Git is different for Github

Github uses git as its engine
Share and Store code online. 
Review Changes 

Sync: 
Add 
- `git clone (link)`
-  `git add (file name)`
- `git status` 

Commit
- `git commit -m "message goes here" `
- `git status`

Push
- `git push origin main`
- **refresh github**


# Revision and Cloud 
Git is a way for developers to collaborate with each other using a server as the main service. A series of server's setup in a failover cluster is recommended to prevent a single point of failure. Uptime in the IT world is necessary for maximum effectiveness. The rule of 9's is a great reading point to understand how important a 99.99999% uptime is compared to a 99% uptime. Utilizing Git allows developers to clone and work on projects from their local machines. The industry standard of A-C-P is used at most major companies to produce a streamline and effective way to edit projects between multiple developers. A is for Add. This is the first step when a developer will Add the project from GitHub to their local machine.  

`git clone (link to repo)` 

Once they have it, they can start working and making changes. C is for Commit. Commit is the changes made to the project. Changes can be annotated with remarks on what was changed and how it betters the project.  

`git commit -m "message goes here" ` 

Lastly, when the changes are made, the developer can push them back to the servers using `git push origin main` 

Itis important that all the developers use the ACP method rather than editing directly on GitHub. Tampering with the original file while it is loaned out to others will create more rework and headaches for all. `git status` Should be used in-between all steps of ACP to ensure their is no Merging conflicts. Another system that is used to prevent conflicts is the Tagging. Tagging is used to show the version of the project being used. If a developer is working on project `v1.2.9` but the most recent version on GitHub is `v1.3.0`, the developer should stop, get the latest version, and continue from there. 

 