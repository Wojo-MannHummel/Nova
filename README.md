# System Documentation Repository

This repository serves as a centralized version control system for our project's documentation. It is designed to store and track changes to documentation files by leveraging GitHub's features, we aim to simplify the process of updating and maintaining these documents.

## Getting Started

To get started, you'll need a GitHub account. If you don't have one, you can create it for free at [GitHub](https://github.com/). Once you have an account, we can invite you to this repository.

### Viewing Documents

Navigate through the repository in your web browser to view files. Click on directories or files of interest. Note: Not all file types render in the browser, so we convert `.docx`, `.xlsx`, `.pptx` files to PDFs for easier viewing, located in the `pdfs` folder.

### Making Changes to Documents

To update a document, you will need to upload a new version of the file. Here's how you can do it using the GitHub web interface:

1. **Navigate to the Folder**: Go to the folder where the document you wish to update is located.

2. **Upload the New Version**: Click on the "Add file" button near the top right corner and select "Upload files" from the dropdown menu.

3. **Select Your File**: Simply drag and drop the file to be updated into the drop zone, alternativlely click "choose your files" to select the updated file from your computer. Ensure the file name matches the document you're updating else it will create a new file.

4. **Commit the Change**: After uploading the file, scroll down to the "Commit changes" section. Here, you can:
    - Provide a brief description of the changes made in the "Commit changes" textbox.
    - Choose to commit directly to the main branch or create a new branch and start a pull request. Committing directly to the main branch is straightforward, but starting a pull request allows for discussion and review before the changes go live.

5. **Submit Your Changes**: Click on "Commit changes" to finalize the update. The repository will now contain the latest version of your document, and the previous versions will be accessible through the commit history, allowing for version control and rollback if necessary.
   
## Using Branches

Branches allow you to freely work on updates or new documents without affecting the main project and maintain a single source of truth.

### Creating and Switching Branches

1. **Create a Branch**: On the repository's main page, find the branch selector dropdown. Type a name for your new branch and hit "Enter" to create it. Branch names should be descriptive (e.g., `update-installation-docs`).
2. **Switch to Your Branch**: GitHub will automatically switch you to the new branch. You're now ready to make changes without impacting the main branch.

Once on your branch, you're free to make changes:

3. **Edit or Add Files**: Use the GitHub interface to edit existing files or add new ones. Remember, changes on this branch won't affect the main branch until they're merged.
4. **Commit Changes**: Save your changes by committing them to your branch. Provide a clear commit message that explains what you've done and why.

A pull request (PR) is a way to propose changes from your branch to the main branch. It allows team members to review the changes before they're integrated, ensuring quality and collaboration.

### Initiating a Pull Request

1. **Open a Pull Request**: Once you've committed changes to your branch, navigate to the "Pull requests" tab in your repository and click "New pull request".
2. **Choose Branches**: Select your branch as the "compare" branch and the main branch as the "base" branch.
3. **Review Changes**: GitHub will show you the differences between the two branches. Review these to ensure accuracy.
4. **Create Pull Request**: Click "Create pull request". Provide a title and a detailed description of your changes. Mention any team members you wish to review your PR.

### Reviewing and Merging Pull Requests

1. **Review Process**: Team members can review the proposed changes, leave comments, and request additional modifications if necessary.
2. **Address Feedback**: If feedback is provided, you may need to make further changes to your branch. These updates will automatically be part of the existing pull request.
3. **Approve and Merge**: Once the pull request is approved, the final step is to merge it into the main branch. Click "Merge pull request" and then "Confirm merge" to integrate your changes. GitHub might offer different merge options, such as creating a merge commit, squashing commits, or rebasing. For most documentation updates, creating a merge commit is straightforward and preserves the history of your changes.

### Deleting Your Branch (Optional)

After merging, GitHub will give you the option to delete your branch since its changes have been integrated into the main branch. This keeps the repository tidy.

## Tracking Issues

Use issues to track tasks, bugs, or questions.

1. **Open an Issue**: Click "Issues" > "New Issue" and describe your concern or suggestion.
2. **Discussion**: Team members can comment on issues to provide feedback or solutions.

## Best Practices

- **Small, Frequent Updates**: It's easier to track and understand small changes than large, infrequent updates.
- **Descriptive Commit Messages**: Clearly describe what changed and why. This helps the team follow the repository's history and understand each change's purpose.
- **Review Before Committing**: Always preview your changes and proofread your work to ensure accuracy and clarity.
