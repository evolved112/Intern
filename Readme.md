goal:
- generally about git
	* Git contain
		- local workspace: Where we code
		- Staging area: Commited code + message from the local space
		- remote workspace: pushed code from staging area
- clone
    + Clone a pre-existing repo
    + git clone https://github.com/evolved112/Intern.git
- create a branch
	+ git branch sub
	+ git checkout sub
- commit
	+ currently on branch sub
	+ git add HelloV1.py
	+ git commit -m "add new branch"
- push
	+ git push origin sub
- pull
	+ git pull (haven't found any proper use)
- ignore
	+ Create a gitignore file to not have to manually stage/add 
- create a merge/pull request
	* clone main, create a new branch, push new branch, create merge/pull request, delete the new branch
	+ git pull main
	+ git checkout -b sub and add new code
	+ commit to new branch

	* on GitHub, we can process the merge/pull request
- git workflow
- produce a conflict
	* make changes to the code with a different instance (helloV1.py)

	+ Proceed to modify the helloV1.py
	+ Could not push 
- resolve a conflict

	+ Pull first to resolve changes
- fetch
	* git retrive update without modifying current local
	


step:
- any git platform 
- create an account
- create repository
- create token (platform dependent)
- document your goal
	+ goal name
	+ goal
	+ step detail
	
readme.md
push it along with git