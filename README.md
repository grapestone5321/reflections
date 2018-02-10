# How to Use Git and GitHub

# reflections

### Reflect: Using diff to Find Bugs

### Make sure you can access the command line

If you are on Windows, you’ll need to install some software in order to use a unix-like command line

(different from the Windows built-in Command Prompt), as we mentioned previously. For more info, check out this page.

### Choose a text editor

As noted in the previous video, you should make sure to use a simple text editor like Notepad++, Sublime, Atom, emacs, vim, etc. and not a rich-text editor like Microsoft Word or OpenOffice, so that you can easily look at your files' content on the command line.

If you don’t have one that you like yet, Sublime is a good option that will work on Windows, Mac, and Linux. We have provided more detailed instructions for setting up Sublime than for other editors, and we use Sublime for all the examples in the course. You can download Sublime here.

### Make sure you can launch your editor from the command line

It will be helpful to be able to launch your text editor from the command line. See here for instructions on how to do this for Sublime. If you have trouble getting this working, videos at the end of the lesson called "Setting up Your Workspace on Windows" and "Setting Up Your Workspace on Mac" will demonstrate this process, so you can wait until then.

### Set up your course workspace

Right now, you should create a version-control directory (a more computer-science-y term for “folder”) to hold all your files for this course in an easy to remember location, then create a reflections sub-directory, and within that, create a plain text file called lesson_1_reflections.txt for the questions from this lesson.

You can do this by running the following commands in either Git Bash or the terminal (the bits after the # signs are comments, anything after those are not interpreted):

```
cd ~                          # change directories to your home directory
mkdir version-control         # make version-control directory
cd version-control            # go to version-control directory
mkdir reflections             # create reflections directory
cd reflections                # go to reflections directory
subl lesson_1_reflections.txt # launch sublime with file called lesson_1_reflections.txt (you can replace subl with another editor here if you prefer a different one)
```

If you prefer, rather than creating the file from scratch, you could download the lesson_1_reflections_prompts.txt file from the Downloadables section, place it in the reflections directory and rename it, then add your response after the first prompt.

Once you’ve saved your file, if you want to double-check that everything has gone as planned, try these commands:

```
pwd # print working directory - shows what directory you are in
ls  # list the files in this directory
```

If you're having trouble getting this working, videos at the end of the lesson called "Setting up Your Workspace on Windows" and "Setting Up Your Workspace on Mac" will demonstrate parts of this process, so you might want to wait until then. In the mean time, you can create the directories and file using your OS’s Graphical Interface for working with files (Finder, Windows Explorer, etc). It's good to get some practice using the command line, though, since we'll be using it a lot in this course, so once you've watched the workspace instructions, make sure you can complete actions like this on the command line.

You are also welcome to use a different naming scheme, but later in the course we will refer to this file structure and it will be up to you to translate to whatever naming scheme you chose instead!

### Use short lines
Many command line tools, including Git, are less useful if your files contain very long lines. For example, if you use diff to compare two files that have all their content on the same line, diff will only show you that the two files are different. It will not be able to pinpoint the location of the difference for you.

For this reason, it is a good idea to make sure you keep your lines reasonably short when writing your reflections (or other plain-text files). The exact limit is a matter of personal preference. Many developers use a max line length of 80 to 120 characters. Some editors can automatically insert line breaks for you, but for others, like Sublime, you will need to remember to press enter when you want to create a new line.


### Do the first reflection exercise
Populate lesson_1_reflections.txt with the following question and your thoughts on it:

How did viewing a diff between two versions of a file help you see the bug that was introduced?

When you've created your document, written down your thoughts, and saved the file, click "Next" to learn about some systems that can help you create these versions of your files.
Like Sarah said, there is a lot of research out there on reflection. If you want a quick intro with some neat graphics, check out this site.

For a more in-depth look, check out this seminal 20-page paper on the topic.

## Reflect: Using History for Efficiency
Now that you've learned about some version control systems, and how they can help you save the history of a file, go add the following question and your thoughts on it to your reflections file: 

How could having easy access to the entire history of a file make you a more efficient programmer in the long term?

When you've updated your document, click "Next" to learn about some differences between these version control systems.

## Reflect: Manual Commits
Now you've learned about Git commits and thought about good times to create commits, go add the following question and your thoughts on it to your reflections file: 

What do you think are the pros and cons of manually choosing when to create a commit, like you do in Git, vs having versions automatically saved, like Google Docs does?

When you've updated your document, click "Next" and Sarah will go over another difference between version control systems.

## Reflect: Multi-File Commits
Go add the following question and your thoughts on it to your reflections file: 

Why do you think some version control systems, like Git, allow saving multiple files in one commit, while others, like Google Docs, treat each file separately?

When you've updated your document, click "Next", and an experienced Git user will share why version control is useful to him.

## Reflect: Using Git to View History
Now that you've had some experience using Git yourself, go add the following question and your thoughts on it to your reflections file: 

How can you use the commands git log and git diff to view the history of files?

When you've updated your document, click "Next" to add more concepts to your map with Sarah. Then you'll learn how to use Git to return to previous versions of your files.

## Reflect: Confidence from Version Control
Now that you know how to return to a previous version of your files using Git, go add the following question and your thoughts on it to your reflections file: 

How might using version control make you more confident to make changes that could break something?

When you've updated your document, click "Next" to start configuring a workspace that will make you more efficient at using Git.

## Reflect: How Do You Want to Use Git?
Go add the following question and your thoughts on it to your reflections file: 

Now that you have your workspace set up, what do you want to try using Git for?

When you've updated your document, click "Next" and we'll wrap up the lesson.


## Reflect: Initializing a Repository
Now that you’ve initialized your first repository, go to your reflections directory, create a new file called lesson_2_reflections.txt, and add the following question and your thoughts on it:

What happens when you initialize a repository? Why do you need to do it?

You may also wish to run git status after you have created the file. You should see that now both files are listed as untracked files.

## Reflect: Staging Area
Now that you’ve added a file to the staging area (or maybe multiple files!), go add the following question and your thoughts on it to your lesson_2_reflections file: 

How is the staging area different from the working directory and the repository? What value do you think it offers?

When you've updated your document, click "Next" and Caroline will go over how to commit the changes you’ve added to the staging area.

## Reflect: Commit Size
Now that you’ve committed changes using the staging area, go add the following question and your thoughts on it to your lesson_2_reflections file: 

How can you use the staging area to make sure you have one commit per logical change?

You may also want to commit your changes to the file. When you're ready to move on, click "Next" and Sarah will go over a concept called branching.

