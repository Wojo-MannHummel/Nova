# System Documentation Repository

This repository serves as a centralized version control system for our project's documentation. It is designed to store and track changes to documentation files by leveraging GitHub's features, we aim to simplify the process of updating and maintaining these documents. 

## Viewing Documents

Navigate through the repository in your web browser to view files. Click on directories or files of interest. Note: Not all file types render in the browser, so we convert `.docx`, `.xlsx`, `.pptx` files to PDFs for easier viewing.

## Making Changes to Documents

To update a document, you will need to upload a new version of the file. Here's how you can do it using the GitHub web interface:

1. **Navigate to the Folder**: Go to the folder where the document you wish to update is located.
2. **Upload the New Version**: Click on the "Add file" button near the top right corner and select "Upload files" from the dropdown menu.
3. **Select Your File**: Simply drag and drop the file to be updated into the drop zone, alternativlely click "choose your files" to select the updated file from your computer. Ensure the file name matches the document you're updating else it will create a new file.
4. **Commit the Change**: After uploading the file, scroll down to the "Commit changes" section. Here, you can:
    - Provide a brief description of the changes made in the "Commit changes" textbox.
    - Choose to commit directly to the main branch or create a new branch and start a pull request. Committing directly to the main branch is straightforward, but starting a pull request allows for discussion and review before the changes go live.

5. **Submit Your Changes**: Click on "Commit changes" to finalize the update. The repository will now contain the latest version of your document, and the previous versions will be accessible through the commit history, allowing for version control and rollback if necessary.

## Viewing Previous Versions

1. Navigate to the main page of the repository and click `Commits`.

    ![image](https://github.com/Wojo-MannHummel/nova-docs/assets/122921481/4aa8cdc7-5953-4eaa-9e89-bd2f52727031)

2. This shows what changed, who changed it, and state of repository at the time.

    ![image](https://github.com/Wojo-MannHummel/nova-docs/assets/122921481/fea9c078-628c-431e-be57-685bee0108f8)

4. Clicking the SHA-1 hash (the sequence of letters and numbers to the far right) reveals the commit details
5. Clicking the `<>` shows the repository at that time

# Using the Wiki

The wiki is a powerful tool which can track changes line by line because of its text based nature of markdown (`.md`) files, and is quick to write and modify.

### Viewing Wiki History

Wiki history includes:
- The user who made the change.
- The commit message they provided.
- When the change was made.

1. Navigate to the main page of the repository.
2. Under your repository name, click `Wiki`.

    ![image](https://github.com/Wojo-MannHummel/nova-docs/assets/122921481/76af4805-7592-410b-863d-29a043ad6eb5)

4. Using the wiki sidebar, navigate to the page whose history you want to view.
5. At the top of the wiki, click the revision link.

    ![image](https://github.com/Wojo-MannHummel/nova-docs/assets/122921481/c291622f-6f73-4834-97be-e47630c53d13)


## Viewing Previous Content

On the wiki history table, you can click a SHA-1 hash to see a wiki page as it existed at a particular point in time.

![image](https://github.com/Wojo-MannHummel/nova-docs/assets/122921481/024a375a-59d8-48e4-b1ee-9d0af41fcf94)

## Comparing Two Revisions

1. Select two rows that you want to compare.
2. At the top of the history table, on the right side, click `Compare Revisions`.
3. You'll see a diff of the changes showing which lines were added, removed, and modified.

## Reverting Previous Changes

You can only revert changes if you have permission to edit the wiki.

1. Select a row that you want to revert.
2. At the top of the history table, on the right side, click `Compare Revisions`.
3. You'll see a diff of the changes showing which lines were added, removed, and modified.
4. To revert the newer changes, click `Revert Changes`.

   
## Best Practices

- **Small, Frequent Updates**: It's easier to track and understand small changes than large, infrequent updates.
- **Descriptive Commit Messages**: Clearly describe what changed and why. This helps the team follow the repository's history and understand each change's purpose.
- **Review Before Committing**: Always preview your changes and proofread your work to ensure accuracy and clarity.
