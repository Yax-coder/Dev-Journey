Guidelines on how this Project works :)

Read below to see how you can join an existing project or create your own.

## One rule of this community:

We don't care if you break things. This is a playground, and we encourage failing often. Use this as a practice ground, and enjoy contributing to projects you create with your fellow mates.
## A Guide to Get Started (used to be the 4 step guide)

**Contributors**: Everyone who has contributed something back to the project.

**Community Members**: People who use the project. They might be active in conversations or express their opinion on the project’s direction.

**README**: The README is the instruction manual that welcomes new community members to the project. It explains why the project is useful and how to get started.

 **CONTRIBUTING**: Whereas READMEs help people use the project, contributing docs help people contribute to the project. It explains what types of contributions are needed and how the process works. While not every project has a CONTRIBUTING file, its presence signals that this is a welcoming project to contribute to.

1. **CODE_OF_CONDUCT**: The code of conduct sets ground rules for participants’ behavior and helps to facilitate a friendly, welcoming environment. While not every project has a CODE_OF_CONDUCT file, its presence signals that this is a welcoming project to contribute to.

2. **Issue tracker**: Where people discuss issues related to the project.

3. **Pull requests**: Where people discuss and review changes that are in progress.

4. Shift to project directory:

    ```bash
    cd Dev-journey.projects   ```

5. Before you make any changes, [keep your fork in sync](https://www.freecodecamp.org/news/how-to-sync-your-fork-with-the-original-git-repository/) to avoid merge conflicts:

    ```bash
    git remote add upstream https://github.com/Yax-coder/Dev-Journey.git
    git pull upstream master
    ```

    If you run into a **merge conflict**, you have to resolve the conflict. There are a lot of guides online, or you can try this one by [opensource.com](https://opensource.com/article/20/4/git-merge-conflict).

6. After adding the upstream and checking that all files are up to date, we now will create new branch before editing any files. There are two ways to do so:

    ```bash
    git checkout -b <branch-name>
    ```

    ```bash
    git branch <branch-name>
    git switch <branch-name>
    ```


7. On your computer, open your text editor, and add your name to the `CONTRIBUTORS.md` file.

8. Add the changes with `git add`, `git commit` ([write a good commit message](https://chris.beams.io/posts/git-commit/), if possible):

    ```bash
    git add CONTRIBUTORS.md
    git commit -m "Add <your-github-username>"
    ```

    **Replace \<your-github-username\>!**

9. Push your changes _to your repository_:

    ```bash
    git push origin <branch-name>
    ```

10. Go to the GitHub page of _your fork_, and make a pull request:

    ![pull request image](https://help.github.com/assets/images/help/pull_requests/choose-base-and-compare-branches.png)

    Read more about pull requests on the [GitHub help pages](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

11. Wait until Zerobot or one of the maintainers merges your pull request. If there are any conflicts, you will get a notification.

