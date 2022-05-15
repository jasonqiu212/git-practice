# Git and GitHub Practice using Command Line

Follow along the set up guide and tasks to hone your Git skills!

## Set up

1. Install Git on your machine. (Git should already be installed on Mac and Linux. For Windows users, check out this [guide](https://www.atlassian.com/git/tutorials/install-git#windows).)
2. Verify your Git installation: Open Terminal and type `git --version`.
3. Check if your machine has a SSH key using this [guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys) and set up new SSH key if needed.
4. Add your SSH key to GitHub using this [guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

## Tasks

Background: Congrats, you made a start up! Your product is an amazing text file that contains some humorous jokes. Follow along to expand your start up.

1. To continue working on what you have started, clone this repository onto your machine.
2. Edit `Change.txt` by adding a joke and commit it to your local repository. Push your changes to the remote repository on GitHub.

```
Hello world!

Add your jokes below:
1. Why do all the numbers avoid talking to pi at a party? Cos he goes on forever!!
```

You now recruit a team of jokesters to expand your text file and you all agree to deploy the `main` branch online to the world! You wish to add another joke now.

> Be careful when adding new changes now! You should **not** directly push and commit to the `main` branch, since the changes may break your deployment.

3. To add another joke, create a new feature branch in your local repository and commit your new joke.
4. Push the new branch onto the remote repository.
5. Create a pull request to merge the your feature branch into the `main` branch.

Life happens and you stop coding for 100 years. The `main` branch in the remote repository has been edited many times by others.

6. Update your local repository.

## Walkthrough

1. Clone this repository onto your machine.
