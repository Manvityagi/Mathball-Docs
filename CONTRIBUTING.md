# Contribution is fun! :green_heart:

With your contribution, we can create a comprehensive documentation site that may potentially aid people who are using `mathball`. In order to make a hassle-free environment, I implore you all (_while contributing_) to follow the instructions mentioned below!

Happy Contributing :slightly_smiling_face:

## :mag: Project Architecture

![](https://github.com/pbiswas101/Mathball-Docs/blob/master/assets/project-architecture.png)

> NOTE: Do not make a PR on `gh-pages` directly:heavy_exclamation_mark:

## :arrow_down: Installation

- First, fork this repository :fork_and_knife: and follow the given instructions:

```bash
# clone the repository to your local machine
$ git clone https://github.com/<YOUR-GITHUB-USERNAME>/Mathball-Docs.git

# navigate to the project's directory and install all the relevant dependencies
$ cd Mathball-Docs && npm i

# include all the latest changes from the remote repository
$ git remote add upstream https://github.com/pbiswas101/Mathball-Docs.git
$ git fetch upstream
$ git merge upstream/master
```

Next, create a new branch for the particular issue - `$ git checkout -b <NEW-BRANCH-NAME>` and make PR from that branch while leaving **master** branch unchanged :white_check_mark:

## :construction: Development

- In **master** branch you can run the following command:
```bash
# setting up development server
$ npm run start

# building locally
$ npm run build
```

- While working on the [documentation site][1], you should not use `$ npm run eject` :x:
- Once you have made your changes, run the following command:

```bash
# add your changes
$ git add .

# make your commit
$ git commit -m "<YOUR-COMMIT-MESSAGE>"
```

> Think you're ready :grey_question: Make the PR :tropical_drink:


## :page_with_curl: Guidelines

Being an open-source contributor is awesome :bowtie: but with great awesomeness comes great responsibility; and the responsibility of what you might ask! Well, you certainly don't wanna make a PR that would break the codebase :x:, or instead of fixing bugs, creates more :beetle:. So, here are some curated guidelines one should follow while contributing :trophy:

- Raise an issue regarding bug fixes or feature enhancements, before making a PR.

- While raising an issue, please follow the **ISSUE_TEMPLATE.md** guidelines.

- First, claim an issue and make a PR only when you're assigned to it.

- To claim an issue, just leave a comment and you'll be assigned on `first come, first serve` basis.

- Organize your code adhered to [Airbnb style guide][2] as much as possible.

- Configure your editor to support the preferences from the **.editorconfig** file.

- Squash your commits for cleaner commit history.

- While making a PR, please follow the **PULL_REQUEST_TEMPLATE.md** guidelines and mention the issue you are solving, like so - `Fixed #2`.

- Your PR must pass the [Travis CI][3], [Codacy][4], [Snyk][5] checks for it to be considered getting merged.

- Use ES6+ syntax precisely and do not review others' PR!

- Maintain a healthy environment and don't indulge in any kind of activities that's against the **CODE_OF_CONDUCT.md**.

##### Additional Instructions for GirlScript Summer of Code 2019 Participants:

- If a participant resolves any issue which includes the label `gssoc19`, he/she would earn a score!

- Scores are rewarded according to the difficulty level of the corresponding issue which can be identified by the labels like `beginner`, `easy`, `medium` and `hard`.

- When a participant is assigned an issue, he/she would've to make a PR within a particular duration according to the difficulty level:
	- 1 day for `beginner`
	- 1 day for `easy`
	- 3 days for `medium`
	- 5 days for `hard`

- Failing to make a PR within the given time would result in its corresponding issue being assigned to someone else or labeled as `up-for-grabs`.

- One cannot claim more than one issue at a time!

- Biweekly evaluation will be conducted based on each participants' score and the result will be declared on the Slack Workspace.

---

<p align="center">Made with :hearts: for the Community!</p>

[1]: https://pbiswas101.github.io/Mathball/
[2]: https://github.com/airbnb/javascript
[3]: https://travis-ci.org/
[4]: https://www.codacy.com/
[5]: https://snyk.io/
