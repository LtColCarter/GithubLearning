# GithubLearning
Repository to help learn and teach Github

*The majority of this repository will contain markdown files and will also be used to practise working with markdown syntax.*


# Setting up Github Repository through Github website:
1 - So I'm going to assume you've first got a Github account sorted and set up. The first thing you want to do is head to [Github](https://github.com) and log into your account and create a new respository.

![Create new repo](https://user-images.githubusercontent.com/44203462/51057073-70be0300-15dc-11e9-92a0-446fd0cc5861.png)



2 - (a) Name your repository something short and memorable.

![Repo name image](https://user-images.githubusercontent.com/44203462/51057444-85e76180-15dd-11e9-9673-54319092d9a8.png)

(b) I'd recommend writing a little description for setting up your repository, so just write a little description to describe this repository.

![Repo description name](https://user-images.githubusercontent.com/44203462/51057565-e8d8f880-15dd-11e9-8ecc-465e68f51d2c.png)

(c) Decide if you want the repository to be public or private. 

![Public/Private image](https://user-images.githubusercontent.com/44203462/51057637-19b92d80-15de-11e9-9d6b-a193ad967457.png)

A public repository is just like this one and anyone can access it, but only the people you choose can commit changes to it. Public also means people can also clone the repository or fork it. Forking a repository allows you to take a copy of the repository and then experiment on it freely without making any changes to the original project. Cloning I will get onto soon. If you want to read more about the different types of repositories, you can find it in [Github Help](https://help.github.com/articles/setting-repository-visibility/).

A private repository can only be viewed and edited by you, unless you add certain people as collaborators. For example if you were working on a project, with a team of software engineers, and you didn't want your code open to the public you can all either work on the same branch (master) or work on specific branches of the repository and then at the end merge all of each other's into the master branch. Again if you want to read more about the different types of repositories, you can find it in [Github Help](https://help.github.com/articles/setting-repository-visibility/).

For this option of creating a Github repository, you'll need to tick the "Initialize this repository with a README" because we're going to clone this repository onto your computer. If you don't want to use this option of creating a Github repository, please click here (Add link whenever I get down to the other way).

![Readme tickbox](https://user-images.githubusercontent.com/44203462/51058487-d3b19900-15e0-11e9-8e7c-ed7b9324a235.png)

Leave the .gitignore tickbox unticked as I'll set this up once we clone your repository. A .gitignore file contains a list of file extensions that git will ignore when tracking any changes you make to files inside the repository. If you want to read more about using a .gitignore file [click here](https://help.github.com/articles/ignoring-files/). You can of course setup the .gitignore file now, if you know which files you don't want to be tracked now, Octocat has a good [Gist](https://gist.github.com/octocat/9257657) of common .gitignore configurations.

Lastly you have to choose on a licence for your repository, both public and private repositories should have a licence. As you can use Github for a variety of different reasons the licence is down to your choice. Github created [this](https://choosealicense.com/) to help you decide which licence to use. If you need additional information and guidance for choosing a licence [click here](https://opensource.guide/legal/#which-open-source-license-is-appropriate-for-my-project).

![.gitignore and licence](https://user-images.githubusercontent.com/44203462/51059002-9a7a2880-15e2-11e9-839b-d81399761145.png)

(d) Once you've created your repository you can go ahead and open up your Windows Command Prompt, Linux Terminal or Mac Terminal. I'll assume you have a decent grasp of using the command line interface (e.g. navigating through folders). So you're going navigate to wherever you want your Github repository in your cmd/terminal window. Once you reach the folder, head back to your Github repository in your browser and click on "Clone or download"

![clone](https://user-images.githubusercontent.com/44203462/51059238-6e12dc00-15e3-11e9-8c75-a24abaa958b8.png)

and copy the HTTPS url. Back in your cmd/terminal window type:

`git clone [your link from Github]`
This will clone your repository from Github to your local file system. For me my code would look like:

`git clone https://github.com/LtColCarter/GithubLearning.git`

## Let's try that out now.
*Please note that for this example I will be using a public repository so a few things might be different for a private repository, but nothing major.*

This is what you should see once you've run the code:

![Cloning Example](https://user-images.githubusercontent.com/44203462/51059566-90592980-15e4-11e9-8286-0290bf6fcf1f.png)
