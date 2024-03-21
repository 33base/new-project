# New Repository creation instruction

## Create a New Repository on GitHub:
 - Log in to your GitHub account.
- Click on the "+" icon in the top-right corner of the page and select "New repository".
- Enter "new-project" as the Repository name.
- Optionally, you can add a description, choose if you want it to be Public or Private, and select any other options you need.
- Click on "Create repository".
## Set Up a New Git Repository Locally:
- Open your terminal or command prompt.
- Navigate to the directory where you want to create your new project: ```
```
cd /path/to/your/directory
```

- Initialize a new Git repository by running the following command:
```
git init new-project
```
- This will create a new directory named `new-project` and initialize a Git repository inside it.
## Link Your Local Repository to the Remote Repository on GitHub:
- Go back to your terminal.
- Navigate into the `new-project` directory:
```
cd new-project
```
- Link your local repository to the remote repository on GitHub using the following command:
```
git remote add origin https://github.com/your-username/new-project.git
```
- Replace `your-username` with your GitHub username.
## Create a Development Branch:
- To create a new branch named `development`, use the following command:
```
git checkout -b development
```
- This command creates a new branch named `development` and switches to it. Now you're on the `development` branch.
## Make Changes, Commit, and Push:
- Add your project files to the repository and make any initial changes.
- Stage your changes using the following command:
```
git add .
```
- Commit your changes with a meaningful message:
```
git commit -m "Initial commit"
```
- Push the changes to the remote repository on GitHub:
```
git push -u origin development
```
- This command pushes your local `development` branch to the remote repository on GitHub.

Now you have set up a new Git repository on GitHub, created a development branch, and pushed your local changes to the remote repository. You can continue working on your project, making changes, committing, and pushing them to the `development` branch as needed.