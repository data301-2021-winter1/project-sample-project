# Milestone 2 - Load Dataset

In this milestone you will be expected to setup the project on your local machine and load in your approved dataset.

## Overall Expectations

- Every time you resume working on a project, you should run `git pull` to pull down any changes that may have occurred since the last time you worked on the project.
- You should be committing to git every time you work on this project, and 
- On average, all team members should be contributing to the project equally!
- Each team member is responsible for their own research question(s), but the data processing, wrangling, and cleaning steps can be shared.
- Commit messages should be meaningful. We will look at them. It's OK if one or two are less meaningful, but most should provide a short phrase to remind yourself (and others looking at your repository) what the changes were.
- Use GitHub issues to communicate and document major decisions 
- Your question, analysis and visualizations should make sense, be well-formed, and it does not have to be complicated.
- You should use proper grammar and full sentences in your READMEs. Point form may occur, but should be less than 30% of your written documents.
- You must use proper English, spelling, and grammar and you should write concisely.
- There should be a plan in place to to deal with any teamwork conflicts and issues.

## Task 1: Project Setup

- The first step is to create/join a GitHub repository. 
    - Discuss with your partner(s) to determine which of you will accept the initial repository link (only one person in a group should accept the link).
    - If you are the first person in the group, click this link to accept the [Template Project GitHub Classroom](https://classroom.github.com/g/kAD2P_UM).
    - Make sure you set the name of your repository to be exactly this: `groupXX-project` and then let your team member(s) know the name of your group.
    - Other team member(s) should search for their group name and join it.

- Once you accept the project template, I have created all the directories below, but you should know what they are. Here is description of the file and folder structure of this project: 
  - `data` - your data files should be split up into "raw" and "processed":
    - `data/raw` - raw data should go in this directory; you should add the original source file here. Always keep the original data file without editing.
    - `data/processed` - You can add cleaned up, and processed data files in this directory.
  - `images` - any external images you use should be in this directory so things are organized.
  - `notebooks` - all Jupyter Notebook files should be kept in this parent directory. Keep this folder organized and have as few notebooks in here as possible.
    - `notebooks/analysis1.ipynb` : Teammate 1 should have Jupyter Notebook work stored here. Remember to change the header in this file to your names or an alias. Don't change the name of this file.
    - `notebooks/analysis2.ipynb` : Teammate 2 should have Jupyter Notebook work stored here. Remember to change the header in this file to your names or an alias. Don't change the name of this file.
    - `notebooks/analysis3.ipynb` : Teammate 3 should have Jupyter Notebook work stored here. Remember to change the header in this file to your names or an alias. Don't change the name of this file.
    - `notebooks/ungraded/` : Anything you don't want to be marked or looked at can be placed in this folder.   
    - You may add additional subdirectories within the current structure, but try to avoid creating any directories in the project root. If you have questions about this, you can ask the project TA.
  - `dashboard` - this folder won't be used until Milestone 04 where you will be working with tableau to turn your dataset into a dashboard.
- In your GitHub repository, you should have the following files:
  - README files describing what is happening (or going to happen) in each directory:
    - `data/README.md` : One sentence explaining what will be in this directory
    - `data/raw/README.md`: One sentence explaining what will be in this directory
    - `data/processed/README.md`: One sentence explaining what will be in this directory
    - `images/README.md`: One sentence explaining what will be in this directory
    - `notebooks/README.md`: One sentence explaining what will be in this directory
    - `README.md`: This file should contain all the important information someone needs to know about your project
  - `CODE_OF_CONDUCT.md`: This file allows you to set standards for how people should interact with your repository, and signals to others that this is a welcoming and inclusive project; it should also outline procedures for handling abuse.
    - [Follow the steps here to use a Code of Conduct template](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/adding-a-code-of-conduct-to-your-project)
    - `LICENSE`: Your repository currently has a default license called the [MIT license](https://choosealicense.com/licenses/mit/). I suggest choosing the **MIT** license unless you have a strong preference otherwise.

```{warning}
 **Note: GitHub currently does not allow you to upload empty directories, so each directory has a README file that you should populate with relevant information**
```
  <!-- - `LICENSE`: As you create a new repository, [you will be asked to choose a license](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/licensing-a-repository#applying-a-license-to-a-repository-with-an-existing-license). I suggest choosing the **MIT** license unless you have a strong preference otherwise -->


## Task 2: Load your dataset from a file or URL

- For this task, you should create a Jupyter notebook and load your data into a dataframe using Pandas.
- If you are working in a group, each person in the team **must** include a separate Jupyter Notebook (`.ipynb` file) demonstrating proficiency with the things we ask you to do for each milestone.
- Remember that others will be running your analysis notebook so it's important that the data is accessible to them. 
- If your dataset isn't accessible as a URL, make sure to commit it directly into your repo.
- If your dataset is only accessible as a URL, add it to this README: `data/README.md`
  - You should name your files as follows to keep things organized: `notebooks/analysis1.ipynb`
  - If your jyputer notebook gets very long you may consider breaking it up. Just make sure you keep a simple naming convention like `analysis1a.ipynb`.


## Task 3: Conduct an Exploratory Data Analysis (EDA) on your dataset

If you are working in groups, each person should do their EDA separately and independently. 
You have chosen rich datasets and there should be plenty of different features for each of you to explore.

**Note: The EDA task (Task 4) is different from the Analysis task (Task 5). The EDA is "exploratory" in nature, and is done at a superficial level to get counts of columns, limits, ranges, understand the data distribution, and a cursory look at the relationships between the columns. Think of it as a 'quick and dirty' analysis of your data in preparation for a more thorough analysis.**

You should use the `project_functions` to store any functions (including method chains) rather than defining them in your notebook. 

- As a rough guideline, **each** EDA should:

  - Involve at least two columns/features of your dataset
  - At least three **useful** visualizations created by you (the more the merrier (within reason)!)
  - Some notes and commentary to help others see observations you find interesting.

Remember that the goal of the EDA is to understand and explore your datasets.
Here are three examples or guides:

  - [Guide 1](https://towardsdatascience.com/an-extensive-guide-to-exploratory-data-analysis-ddd99a03199e)
  - [Guide 2](https://towardsdatascience.com/exploratory-data-analysis-eda-a-practical-guide-and-template-for-structured-data-abfbf3ee3bd9)
  - [Guide 3](https://aiden-dataminer.medium.com/the-data-science-method-dsm-exploratory-data-analysis-bc84d4d8d3f9)
  - Lab 4 had some elements of a rudimentary EDA (but we expect much more from you now!)

## Working collaboratively in GitHub

As we progress through the course, you will be learning more and more about GitHub and how to work collaboratively on code.
Since this is the first time many of you are using Git, I recommend that if you are working in a group, you avoid editing each others' files until you are more familiar with git.
Below are a few things you may find useful as you continue your git journey.

### How to pull the most recent changes to your computer

If you edit your code on the GitHub web interface, or if another use commits to your repository, to update the repository with the most recent changes, you should **always start a working session by running this command** in your git repository (using either Terminal or GitBash): 

> `git pull`

This will make sure your local computer is updated with any changes.
Commit and push your changes often while you work to stay in sync.
