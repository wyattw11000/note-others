# Config

-   CLI

    -   `git config --global user.name`
    -   `git config --global user.email`
    -   `git config --global init.defaultBranch main`
    -   `ssh-keygen -t rsa -b 4096 -C "" -f ~/.ssh/%rsa%`

-   ~/.ssh/config

    -   Host %host%
    -   HostName github.com
    -   User git
    -   IdentityFile ~/.ssh/%rsa%

-   CLI
    -   `ssh -T %host%`
    -   `git remote add origin git@%host%:repos`
    -   `git push -u origin main`
