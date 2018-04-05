# Scrum-Kaizen
solution - improvement


## Generate the SSH Key:
```ssh-keygen -t rsa -C "your-email-address"```

### https://code.tutsplus.com/tutorials/quick-tip-how-to-work-with-github-and-multiple-accounts--net-22574

## Multiple GIT account:
```
cd ~/.ssh
vim config

#Default GitHub
Host github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_rsa
```

remove origin if already existed
Add git remote add origin git@HOST NAME:Company/testing.git