# GitHubToBlih
Synchronize your GitHub repository to blih. (Epitech)

## Install

* You can download the script using the following command:
```sh
wget https://raw.githubusercontent.com/MaximeHouis/GitHubToBlih/master/github_to_blih
```

* Edit the script to provide your blih and GitHub logins:
```sh
USER_GHUB="GITHUB_USERNAME_HERE"
USER_BLIH="BLIH_LOGIN_HERE"
```

* If you want to access the script from anywhere, add it to your PATH.

## Usage

```sh
./github_to_blih REPO_NAME
# or
sh github_to_blih REPO_NAME
```

If your GitHub repository name is different from the blih one, edit the script and figure it out.  
*Using the same name for both repositories is much easier :wink:*

## Synchronize periodically

You can setup the script to run on a server (VPS, Raspberry Pi, ...).  
You could for example setup a cron job or a service to run the script every x minutes.
