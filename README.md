# GithubLearning
Repository to help learn and teach Github

*The majority of this repository will contain markdown files and will also be used to practise working with markdown syntax.*


# Setting up Github Repository through Github website:
1 - So I'm going to assume you've first got a Github account sorted and set up. The first thing you want to do is head to [Github](https://github.com) and log into your account and create a new respository.
![Image of how to create new repo](https://github.com/LtColCarter/GithubLearning/issues/1#issue-398434486)

2 - (Make sure all of these are in the correct order once I get back up online)
(a) Name your repository something short and memorable. (Add image)

(b) Setup a README.md document when you initialise your repository, just put a little description of that the repository will be used for. (Add image)

(c) Decide if you want the repository to be public or private. 

A public repository is just like this one and anyone can access it, but only the people you choose can commit changes to it. Public also means people can also clone the repository or fork it. Cloning I will get on to soon and forking means [Add proper definition here] and then make changes to their own fork. 

A private repository can only be viewed and edited by you, unless you add certain people to contribute to it. For example if you were working on a project, with a team of software engineers, and you didn't want your code open to the public you can all either work on the same branch (master) or work on specific branches of the repository and then at the end merge all of each other's into the master branch.

You can also add a .gitignore file when initialising the repository so that you ignore certain types of files (check on this as well to get proper definition). Lastly you have to choose on a licence for your repository, this is more if you are looking to develop and then publish your code or a fully functioning program and so you can add a licence to protect you from people using any of your code (Check on this properly as I don't fully understand it as of yet). Both a public and private repository should have a licence. (Add image)

(d) Once you've created your repository you can go ahead and open up your Windows Command Prompt, Linux Terminal or Mac Terminal. I'll assume you have a decent grasp of using the command line interface (e.g. navigating through folders). So you're going navigate to wherever you want your Github repository in your cmd/terminal window. Once you reach the folder, head back to your Github repository in your browser and click on "Clone or download" (image) and copy the HTTPS url. Back in your cmd/terminal window type "git clone https://github.com/your_username/your_repo_name.git" (paste the link from Github). This will clone your repository from Github to your local file system.

## Let's try that out now.
Example git clone.
