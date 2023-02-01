Please follow these instructions [to access Github](https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/#what-you-need-to-do-today):

#### Option 1: Personal access token to authenticate over HTTPS

* First, log into Github.com and set up a [personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- Log on to aurora using the command: ``ssh yourusername@aurora.cs.uaf.edu`` and the password that you set for that account on Friday
-  Then [use that access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#using-a-token-on-the-command-line) when authenticating with Github at the terminal.
- You can also [configure git to remember your credentials](https://stackoverflow.com/questions/5343068/is-there-a-way-to-cache-https-credentials-for-pushing-commits) so that you don't have to provide them every time. 



#### Option 2: Authenticate using ssh instead of HTTPS

- Log on to aurora using the command: ``ssh yourusername@aurora.cs.uaf.edu`` and the password that you set for that account on Friday
- [Generate an ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key) on aurora
- Log on to Github.com and [add the newly generated ssh key to your Github account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account#adding-a-new-ssh-key-to-your-account)
- Change your HW00 remote to [use ssh instead of HTTPS](https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories#changing-a-remote-repositorys-url)