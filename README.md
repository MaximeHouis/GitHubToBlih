# GitHubToBlih
Synchronize your GitHub repository to blih. (Epitech)

## Install

Clone the repository or download the script directly by using the following command:
```sh
wget https://raw.githubusercontent.com/MaximeHouis/GitHubToBlih/master/github_to_blih
```

* GitHub and blih usernames  
You can define the `USER_GHUB` and `USER_BLIH` environment variables containing your corresponding usernames. If you don't want your usernames stored in the environment, you can [edit the script](github_to_blih#L16) in order to provide them directly:
```sh
USER_GHUB="$USER_GHUB"
USER_BLIH="$USER_BLIH"
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

You can install the script to run on a server (VPS, Raspberry Pi, ...).  
You could, for example, setup a cron job or a service to run the script every x minutes.

## Contribute

Feel free to submit pull requests or suggestions! :)
