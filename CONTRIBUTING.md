# Contributing to this project

We would love your contributions to the `cc_gen` project. Please review the following guidelines before contributing
in order to make the contribution process easy and uniform for all the contributors. You can also propose changes to
these guidelines by updating this file and submitting a pull request.

-   [I have a question...](https://github.com/zuri-training/Proj-CC_gen-Team-124/blob/main/CONTRIBUTING.md#have-a-question)
-   [I found a bug...](https://github.com/zuri-training/Proj-CC_gen-Team-124/blob/main/CONTRIBUTING.md#found-a-bug)
-   [I have a feature request...](https://github.com/zuri-training/Proj-CC_gen-Team-124/blob/main/CONTRIBUTING.md#have-a-feature-request)
-   [I have a contribution to share...](https://github.com/zuri-training/Proj-CC_gen-Team-124/blob/main/CONTRIBUTING.md#have-a-contribution)

<div id="have-a-question">
<h2>Have a question?</h2>

Ask your question in the team's Slack channel.

</div>

<div id="found-a-bug">
<h2>Found a bug or style-related issue?</h2>

1. Check if the [issues tab](https://github.com/zuri-training/Proj-CC_gen-Team-124/issues) to see if it has already been reported, or fixed.

2. If the issue has not been created or fixed, [create](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue#creating-an-issue-from-a-repository) a [new issue](https://github.com/zuri-training/Proj-CC_gen-Team-124/issues/new).

    When creating a new issue, please **provide as much information as possible** so the problem
    can be easily found, and then fixed. The issue should also **contain a descriptive title and a
    brief summary**. If you have a potential solution to the problem already, feel free
    to [submit a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) with your proposed solution to the problem, or you can also explain your solution in the issue description.

</div>

<div id="have-a-feature-request">
<h2>Have a feature request?</h2>

All feature requests should be started by adding the feature, with all necessary information - including your name, to the document containing all proposed features in the team's Slack channel description. After doing this,
[an issue can be submitted](https://github.com/zuri-training/Proj-CC_gen-Team-124/issues/new) documenting the proposed feature.

</div>

<div id="have-a-contribution">
<h2> Have a contribution to make?</h2>

1. [Fork](https://help.github.com/articles/fork-a-repo) the [cc_gen repository](https://github.com/zuri-training/Proj-CC_gen-Team-124).

2. Clone your forked copy of the repository.

    ```
    git clone https://github.com/<your-github-username>/Proj-CC_gen-Team-124.git
    ```

3. Check the current remote repository for your fork.

    ```
    git remote -v

    <!--- What you should see -->
    > origin  https://github.com/<your-github-username>/Proj-CC_gen-Team-124.git (fetch)
    > origin  https://github.com/<your-github-username>/Proj-CC_gen-Team-124.git (push)
    ```

4. Add a new remote _upstream_ repository.

    ```
    git remote add upstream https://github.com/zuri-training/Proj-CC_gen-Team-124.git
    ```

5. Verify the new upstream repository has been added.

    ```
    git remote -v

    <!--- What you should see -->
    > origin  https://github.com/<your-github-username>/Proj-CC_gen-Team-124.git (fetch)
    > origin  https://github.com/<your-github-username>/Proj-CC_gen-Team-124.git (push)
    > upstream        https://github.com/zuri-training/Proj-CC_gen-Team-124.git (fetch)
    > upstream        https://github.com/zuri-training/Proj-CC_gen-Team-124.git (push)
    ```

6. Sync your fork with the upstream repository.

    ```
    git fetch upstream
    ...

    git merge upstream/main
    ...
    ```

7. Create a new branch and switch to the newly created branch.

    ```
    git checkout -b <name_of_your_new_branch>
    ```

8. Make your desired changes to the code in the repository.

9. Add all new and updated files to the staging area.

    ```
    git add .
    ```

10. Commit the new changes.

    ```
    git commit -m "<descriptive_commit_message>"
    ```

11. Switch back to the `main` branch.

    ```
    git checkout main
    ```

    After running the `git checkout` command, **repeat step 6** to ensure your fork and the upstream repository are still in sync.

12. Push the committed changes in your current branch to the remote repository.

    ```
    git push -u origin <your_branch_name>
    ```

13. [Create a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).
