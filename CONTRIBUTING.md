## Rules for appending papers:

1. You should thoroughly read the research paper and make proper notes using [HackMD](https://hackmd.io/).
2. HackMD notes must mention those members who were part of reading group.
3. If notes and paper reading are completed, then update the details in the appropriate table below.
4. You can then create a pull request to merge the changes. For help on creating pull requests, [refer to this page](https://github.com/IvLabs/resources/tree/master/software).
5. If anyone feels that there are changes required in HackMD notes, please add comments in the notes itself ([How to add comments](https://hackmd.io/s/how-to-use-comments)).
6. These comments will be reviewed and proper actions will be taken by the authors.

____

## Steps to put up an issue:

1. Click on the [Issue button](https://github.com/IvLabs/ResearchPaperNotes/issues) at top of the page.
2. Click new issue and fill up the details!

**Note: Issues must clearly mention what they are addressing.**

____

## Steps to create a pull request:

**All pull requests should be made for `devel` branch only.**

In order to contribute, you have to create a Pull Request from your forked repository which is a remote clone of this upstream repository. 

1. Click the button at the top right hand corner of the screen to fork this repository, don't forget to star the repository!

2. Now head over to the forked repository and copy the clone HTTPS URL.

3. Next up, clone the forked repository on to the local machine using: `git clone <copied-fork-link>`

4. It is critical to keep your [forked repository in sync with the upstream](https://www.freecodecamp.org/news/how-to-sync-your-fork-with-the-original-git-repository/) repository so merge conflicts can be avoided: 

   ```sh
   git remote add upstream https://github.com/IvLabs/ResearchPaperNotes.git
   git fetch upstream
   git pull upstream master
   git push
   ```

5. Create a separate branch to work on and the branch name must be according to the issue: `git checkout -b <branch-name>`

6. Contributers must follow these guidelines:

   1. You are encouraged to add paper notes on various topics related to AI and Robotics
   2. All of these should be segregated by sub-topic.
   3. Refer to existing sections before contributing a new one.
   4. Follow the Fork-Commit-Pull Request cycle for contributing, more on this [here](http://github.com/ivlabs/resources/tree/master/software/github#open-source-contributions-with-git). All pull requests should be made for `devel` branch only.
   5. If you create a new topic folder make sure to **link that folder in landing page `README.md`**
   6. The **name of folder should be consistent with exact format of `word1-word2`**. Some NOT allowed forms are `word1 word2`, `word1word2`, `Word1-word2`, etc. This maintains consistency and proper ordering of folder.
   7. The topic names in [List of Various Fields](https://github.com/comrade-om/ResearchPaperNotes/tree/contributing-guide#list-of-topics) should be in increasing alphabetical order.

7. After the contribution work is ready go ahead and add it to staging area: `git add .`

8. Now it is time to commit your changes and sync these changes to forked repository: 

   ```sh
   git commit -m <your_message>
   git push origin <branch-name>
   ```

9. Issue a [pull request](https://www.freecodecamp.org/news/how-to-make-your-first-pull-request-on-github/) from forked repo to this repo:

   1. Head over to `Pull Request` tab in the forked repo and click on `New Pull Request`
   2. Verify base and head repository name and branch names.
   3. Fill in the title and provide a concise description.

10. Wait for response on the PR. Congratulations you just contributed to open source!

____

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment include:

- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

- The use of sexualized language or imagery and unwelcome sexual attention or advances
- Trolling, insulting/derogatory comments, and personal or political attacks
- Public or private harassment
- Publishing others' private information, such as a physical or electronic address, without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this Code of Conduct, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

____

## Maintainers

- [Rohit Lal](http://take2rohit.github.io/)
- [Raj Ghugare](https://www.linkedin.com/in/raj-ghugare-917137169)
- [Aditya Shirwatkar](https://in.linkedin.com/in/aditya-shirwatkar-40a956188)
- [Akshay Kulkarni](https://github.com/akshaykvnit) 

____
