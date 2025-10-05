John Krebian TeeDoc
=====

**[README](./README.md)**

[jkrebian.github.io](https://jkrebian.github.io)

![Static Badge](https://img.shields.io/badge/Jkrebian-TeeDoc-black?style=flat-square&logo=github&logoColor=white&labelColor=black&link=https%3A%2F%2Fjkrebian.github.io)

### Create a repository based on a template

* Visit [https://github.com/teedoc/template](https://github.com/teedoc/template) or [https://github.com/teedoc/teedoc.github.io](https://github.com/teedoc/teedoc.github.io), click `Use this template`

![github use template](./assets/github_use_template.jpg)


* Set the name of the new repository to `username or organization name.github.io`, select the public repository, and then confirm the submission
![create repo](assets/create_repo.jpg)

> Then use `git clone your repository address` to clone to the local

### Set up pages service

* Wait for the automatic build to generate a new branch `gh-pages`, you can click on the `Actions` column to view the progress of the automatic build, if a green tick appears, it means it is OK, if a red cross appears, the build fails Yes, where is the problem, you can click in to view the log according to the screenshot method below (you must submit a screenshot of the log) and submit [issue](https://github.com/teedoc/teedoc.github.io/issues/ new) feedback

![action status](./assets/action_status.jpg)

If there is an error, you can click to view the error log according to the following figure:
![error0](./assets/action_error.jpg)
![error](.//assets/action_error_log.jpg)

* Set the `pages` service of the repository and select the `gh-pages` branch. If there is no such branch, the previous step has not been completed or an error occurred. You can view the issue submission [issue](https://github.com/ teedoc/teedoc.github.io/issues/new) feedback
![pages](./assets/pages_settings.jpg)

* Then visit `username or organization name.github.io`, you will find a webpage, the content is exactly the same as `teedoc.github.io`!


