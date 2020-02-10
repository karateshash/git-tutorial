## Create Free GitHub Account

[Click Here to Create a Free GitHub Account](https://github.com/join)

Provide necessary information to create an Account

<img src="images/create-github-account.png">

<img src="images/github-choose-free-plan.PNG">

<img src="images/github-complete-setup.PNG">

<img src="images/verify-github-account.png>

<img src="images/create-a-repository.PNG">

<img src="images/create-a-new-repository.PNG">

### To connect the local to remote repository over  HTTPS 

```bash
git remote add origin https://github.com/demo-c4clouds/first-git-repository.git
```

<img src="images/conntct-local-to-remote-https.PNG">

To verify the Remote Repository
```bash
git remote -v
```
Push to remote
```bash
git push -u origin master
```
```code
Note: If you are getting error
$ git push -u origin master
remote: Permission to demo-c4clouds/first-git-repository.git denied to some-username.
fatal: unable to access 'https://github.com/demo-c4clouds/first-git-repository.git/': The requested URL returned error: 403
# Execute the below command
git remote set-url origin https://github.com/demo-c4clouds/first-git-repository.git
```

