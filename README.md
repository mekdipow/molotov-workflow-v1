# Ghost Mirror Single Job Workflow
Join [@ghost_mirror](https://t.me/ghost_mirror)

You can use [this repos](https://github.com/ghostmirrorlab/mirror-bot-repos) as a template
First setup everything then push to your private Repository

## Prerequisite
Then Fork this Repo
Setup secrets in settings --> Secrets
```text
GH_TOKEN :- Your github personal access token, from https://github.com/settings/tokens
MIRROR_REPOSLUG :- Your Secret Repository, as in "<username>/<reponame>"
```
![image](https://user-images.githubusercontent.com/77688759/120898707-a2224800-c649-11eb-8b5c-4f184736e717.png)


Then edit .github/workflows/*.yml

![](https://telegra.ph/file/d26f96a651978decf749f.png)

Change `GitHubMail`, `GitHubName` and `Branch` environment variable as your own

And That's it.

©ElytrA8
