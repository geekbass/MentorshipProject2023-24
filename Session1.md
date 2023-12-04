# Session 1
Create a setup for the Project. In this working session we will go through how to setup a Python Environment. We will also go through setting up a code review process and work through a "real" code review process using GitHub.

## Set up Python Environment
- Install `git` and `Python`
```
brew install git python
```
- Setup SSH keys for Github.
- Set `gitconfig`
- Clone the repo using SSH
```
cd $DIRECTORY
git clone git@github.com:geekbass/MentorshipProject2023-24.git
```
- Create `virtualenv`
```
python -m venv venv
```
- Activate the virtual environment
```
source venv/bin/activate
```
- Install Python packages using pip 
```
pip install jupyterlab pandas numpy scikit-learn xgboost ipython beautifulsoup4
```
- Start a Jupyterlab 
```
jupyter lab
```

## Working through a code review
- Discussion: What is a Pull Request?
- Assign user to review
- Discussion: Walk through how to review.

### Getting familiar with `git`
- Create a new branch for feature: `git checkout -b BRANCH_NAME`
- Adding new files: `git add FILE_OR_DIRECTORY`
- Committing changes: `git commit -m 'Message containing changes that you just made' -i file file2 dir/`
- Push changes to repo: `git push origin BRANCH_NAME`
- Open a "Pull Request" (via UI)

#### Some additional commands
- Check file status: `git status`
- Switch branches: `git checkout BRANCH`
- Pull changes from a branch into yours: `git pull origin BRANCH`


## Try on your own
1) Create a Notebook and write some code in it. 
2) Create a new branch, add the Notebook as a new file, commit changes and then push the changes to the new branch. See above "Getting familiar with `git`". *(HINT: The notebook will have a file extension of `.ipynb` and live in the same directory as where you started jupyterlab)*
3) Create a new "Pull Request" with your changes.
4) Assign me as the reviewer.
5) Once we agree and we have "Approval", merge changes!

[Video](https://www.youtube.com/watch?v=jRLGobWwA3Y) showing git flow.


## Some Research (if interested)
- Setting up your own IDE. My favorites. 
    - [VSCode](https://code.visualstudio.com/)
    - [PyCharm](https://www.jetbrains.com/pycharm/)
- [Hitchhikers Guide to Python](https://docs.python-guide.org/) - Opinionated way of doing things in Python. 
