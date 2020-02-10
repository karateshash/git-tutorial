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

#solution
For Windows you can find the keys here:

control panel > user accounts > credential manager > Windows credentials > Generic credentials

Next remove the Github keys.
```

<img src="images/github-login.PNG">

<img src="images/git-push-origin-master-status.PNG">

### To connect the local to remote repository over  SSH
Inorder to connect over SSH we need to genereate the public and private keys


### To Generate SSH Key Pairs
```
ssh-keygen
```

Once you generate the Public and Private keys open the Public key and copy the contents. Navigate to the github account --> settings --> SSH and GPG keys.

<img src="images/ssh-and-gpg-keys.PNG">

Click on New SSH Keys --> Add SSH Key

<img src="images/add-ssh-public-key.PNG">

To Check SSH Keys are working or not?
```code
#ssh -i /path/to/privatekey-file -T git@github.com
ssh -i ~/.ssh/demo-c4clouds -T git@github.com
```

<img src="images/ssh-connection-check.PNG">

[Click Here to go to git.md](https://github.com/submah/git-tutorial/blob/master/git.md)

