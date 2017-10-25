# Contributing

For any changes, please create a feature branch and open a PR for it when you
feel it's ready to merge. Even if there's no real disagreement about a PR, at
least one other person on the team needs to look over a PR before merging. The
purpose of this review requirement is to ensure shared knowledge of the app and
its changes and to take advantage of the benefits of working together changes
without any single person being a bottleneck to making progress.  

## Steps  

1. Fork this repository.  
2. Clone the repository by running this command:  
    ```shell
    $ git clone https://github.com/YOUR-GITHUB-USERNAME/playtime.git
    ```  
3. Add a remote upstream in order for git to know the original Playtime repository is:  
    ```shell
    $ git remote add upstream https://github.com/rubyforgood/playtime.git
    ```  
4. To make changes, create a new branch and try to name it with the change you want to make as follows:  
    ```shell
    $ git checkout -b BRANCH-NAME
    ```  
    - For example `git checkout -b update/ReadmeFile`  
5. Make your modification and commit the changes locally:  
    ```shell
    $ git commit -m MESSAGE
    ```  
6. Push your new branch to GitHub:  
    ```shell
    $ git push origin BRANCH-NAME
    ```  
7. Open a pull request on GitHub.  
