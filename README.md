# Revea CDN

All static assets go here. As of 14th of December, 2021 this is a public repo. We are not storing any sensitive information here.

This repo uses GitLFS extension. Git LFS handles large files by storing references to the file in the repository, but not the actual file itself.

Read more about [Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-git-large-file-storage)

If you are adding a new file type, you will need to tell Git LFS to track it. For example: `git lfs track "*.tar"`
