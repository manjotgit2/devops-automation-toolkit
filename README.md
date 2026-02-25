# devops-automation-toolkit
What is a repository?
A repository (repo) is a storage location where project files, source code, configuration files, and version history are managed using Git.
It contains:
Project files


Commit history


Branches


Contributors


Version tracking (.git directory)

What are the types of repositories?
There are two main types:
1. Local Repository
Stored on your computer


Created using:

 git init


Used for development and testing


2. Remote Repository
Hosted on platforms like GitHub


Used for collaboration


Connected using:

 git remote add origin <repository-url>

3.Difference between Public and Private repository.
1.Visibility
           Public: Anyone on the internet can view the code.
            Private: Only authorized users can view the code.
2. Access Control
           Public: Read access is open to everyone
           Private: Access is restricted to selected collaborators.
 
3. Collaboration
           Public: Anyone can fork and suggest changes (via pull requests).
           Private: Only invited members can contribute.
  
4 .Use Case
         Public: Open-source projects, portfolios, community contributions.
         Private: Company projects, confidential code, internal tools.


5. Security Level
           Public: Code is exposed; not suitable for sensitive data.
           Private: Code is protected; suitable for proprietary projects.


6. Cost (Platform Dependent)
            Public: Usually free.
            Private: May require a paid plan for advanced features (depending on platform).


7. Searchability
          Public: Searchable and discoverable by anyone.
          Private: Not searchable by the public.


8. Forking
        Public: Can be forked by anyone.
        Private: Cannot be forked publicly without permission.
   What does cloning do?
Cloning creates a complete copy of an existing Git repository.
What is origin in Git?
origin is just a default name for the remote repository you cloned from.

What is the staging area in Git?
The staging area in Git (also called the index) is an intermediate area where you prepare changes before committing them to the repository.

Developers generally avoid working directly on the main branch because it’s meant to stay stable, production-ready, and deployable at all times.
When should developers use git diff?
git diff is used to see what has changed in your files. Think of it as a preview of your edits before committing.


What information does git log show?
Git log  shows the history of commits in a repository.


