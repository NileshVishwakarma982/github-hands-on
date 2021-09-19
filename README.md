# github-hands-on
Companion repository for the session Git and Github Hands-On on Sept. 19th, 2021.

## Initial Setup

To get started, fork this repo to create your own version of this repo. Once done, visit your fork and clone the repository to your local machine using this command:
```
git clone https://github.com/<your-username>/github-hands-on.git
```
Please be sure to replace `<your-username>` with your GitHub username while running the command.

## Adding your name

Open the foked repo with Visual Studio Code (or other text editor of your choice) and explore the file structure and code to get an idea of how everything works. Once done, it's time to add your information to `data/participants.json`.

Got to `participants.json` file inside the `data` folder and append a new object to the end of `participants` array in this manner:
```json
{
  "participants": [
    /* Old data above */
    {
      "name": "Your Name",
      "imageURL": "link-to-your-image.png",
      "about": "A cool description of yourself"
    }
  ]
}
```

After saving the changes, check if the website still works. If not, be sure to check for common JSON errors inside the console. If it does work, congratulations! Move ahead to the next section.

## Pushing your changes

Before you push the changes, we encourage you pull all the changes that we made since you cloned the repo. You can do this with this command:
```
git pull
```

Be sure to fix the merge conflicts (if any). Now, run the following commands to commit your changes:
```
git add .
git commit -m "Added name: your-name"
git push
```

## Opening a pull request

After pushing changes to your remote GitHub repository, you will have an option to open a pull request. Describe your pull request properly and we'll take care of the rest.

Congrats on your initial step towards becoming an open-source ninja!
