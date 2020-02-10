<img src="images/c4logo.png">

### In this Tutorial we are going to learn
  * Install Git Bash/Client
  * Configure the Client 
  * Configure the Repository locally
  * Create Free GitHub Account
  * Push the local repository to GitHub 
  * Some Git Commands

## Installing GitBash
[Click Here to Download the GitBash for Windows](https://git-scm.com/download/win)

Once you download please Install with the default settings.

To Verify the installation 

<img src="images/git-version.PNG">

## To configure the client for the first time we need to specify the UserName and the UserMailID 
```
git config --global user.name "subrat" #UserName must be in doublequotes. 
git config --global user.email subrat@c4clouds.com
```

To Verify the global config
```
git config --list
```
<img src="images/git-config-list.PNG">

## Configure the Repository locally
Inorder to work with multiple repository let's create a base directory i.e. git-tutorial
In you GitBash window execute the below command

```bash
mkdir git-tutorial
cd git-tutorial
mkdir first-git-repository
```
### To Initial the Repository
```
git init 
```
<img src="images/git-init.PNG">

>Note: After initialize you can sea a hidden folder/directory i.e .git
```diff
- Warning: Don't modify any file else your repository will go for a toss 
```