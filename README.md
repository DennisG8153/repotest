# To Make A New Repository
## Adding Files into the Directory
1) cd (*Change Directories*) into your home directory with _cd ~_
2) cd into github-learning/ with _cd github-learning/_ (If you *DO NOT* have the directory github-learning, please do _mkdir github-learning_ *FIRST* before anything else.)
3) Make a new directory called repotest. To do so you need the command _mkdir repotest_.
4) Use _touch README.md_ to make a new md file (A new text file.)
5) Use the command _c9 README.md_ to open the file.
6) Type what you want into the file.
7) Use _Control (Windows & Linux) or Command (iOS) + S_ to save the file and it's changes.
8) Initiaze git with _git init_ (This should say Initialized empty Git repository in /home/ubuntu/github-learning/repotest/.git/ and put the word *master* in parenthesis if it worked.)
9) Use _git add README.md_ to add the file README.md onto the staging area.
10) Check that the file was added to the staging area with _git status_.(This is completely optional, but it will help with double checking.)
11) Use the command _git commit -m_ to commit the changes to the staging area. (Make sure you type something like "Added text to README.md." to help explain what you did. *Note that any other message text MUST be in quotation marks ("")*)
12) You are done adding files into the directory!YAY!

## To Add Files into a Repository
1) Go to [www.github.com](www.github.com) (You can click on the link!)
2) Sign into GitHub.
3) In the top right corner *click* on the plus sign (+).
4) In the dropdown tab, click on *New Repository* to add a new repository.
5) Name the repository *EXACTLY* how the directory is. (If you directory is repotest, name the repository repotest)
6) Click on the green button or press _Enter_.
7) Make sure you put the repo on _SSH_. (If is isn't on SSH, you will have to input your account info *every single time* you want to make changes.)
8) Scroll down to the *2nd* block of text.
9) Click on the clipboard icon or highlight the text and copy it.
10) Go _back_ to your IDE.
11) _Paste_ the code into the terminal.
12) Press _Enter_ and you're done!