Step 1: Set up a GitHub repository
1. Create a new repository on GitHub by clicking on the "New" button on the main page.
2. Give your repository a name and choose whether it should be public or private.
3. Optionally, you can add a README file or a .gitignore file during the repository creation.

Step 2: Prepare your website files
1. Make sure you have your website files ready. This can include HTML, CSS, JavaScript, images, and any other necessary assets.
2. Place all your website files in a single directory on your local machine.

Step 3: Initialize Git and connect it to your repository
1. Open a terminal or command prompt on your local machine.
2. Navigate to the directory where you have your website files using the `cd` command.
3. Run the following command to initialize a Git repository: `git init`.
4. Link your local repository to the remote GitHub repository using the command: `git remote add origin <repository_url>`. Replace `<repository_url>` with the URL of your GitHub repository.

Step 4: Commit and push your website files to GitHub
1. Add all your files to the Git repository using the command: `git add .`.
2. Commit the changes with a meaningful message using the command: `git commit -m "Initial commit"`.
3. Push the files to your GitHub repository using the command: `git push -u origin master`. If you're using a different branch, replace `master` with the appropriate branch name.

Step 5: Enable GitHub Pages
1. Open your GitHub repository in a web browser.
2. Click on the "Settings" tab.
3. Scroll down to the "GitHub Pages" section.
4. Under "Source," select the branch that contains your website files (e.g., "master" or "main").
5. Choose the root folder where your website files are located.
6. Click on "Save" or "Save Changes."

Step 6: Access your published website
1. After saving the settings, GitHub will provide you with the URL to access your published website. It might take a few minutes for the changes to take effect.
2. Visit the provided URL, and you should see your website live on GitHub Pages.
