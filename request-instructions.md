# Request to join

I'm happy that you are interested in joining the program. I'm looking forward to working with you.
Please follow the instructions below to join the program. I'll show you step by step how to do it.

## Final Goal

The final goal is to have a directory with your name under the `/participants/1-introduction` directory.

```
|--- participants
|    |--- 1-introduction
|         |--- your-git-username
|              |--- README.md
|              |--- mentorship.md
|              |--- progress.md
|              |--- resources.md
|              |--- timeline.md
|              |--- worklog.md
```

## Instructions

1. Fork this repository.
2. Clone the forked repository to your local machine.
3. Create a new branch. `git checkout -b add-your-name`
4. Copy the `/participants/0-copy-me` directory into `/participants/1-introduction` directory.
5. Rename the `/participants/1-introduction/0-copy-me` directory to your github username.
6. Edit the `README.md` file and add your information.
7. Commit your changes. `git commit -m "Add <your-name>"`
8. Push to the branch. `git push origin add-your-name`
9. Create a pull request.
10. Wait for the pull request to be merged.

## Commands to use

After forking the repository, you can use the following commands in order to complete the steps above.

```bash
# Replace <your-github-username> with your github username.
git clone https://github.com/<your-github-username>/d-mentor.git
cd d-mentor

# Replace <your-name> with your name.
git checkout -b add-your-name

# Again, replace <your-github-username> with your github username.
cp -r participants/0-copy-me participants/1-introduction/<your-github-username>
# You should edit the README.md file and add your information. Use your favorite editor.

git add participants/1-introduction/<your-github-username>
git commit -m "Add <your-name>"
git push origin add-your-name
```

Finally, you should create a pull request. I'll review your pull request and merge it if everything is ok.
