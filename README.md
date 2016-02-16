# GitHub-web-plus-app-workflow
My GitHub workflow for working on other people's repos.  These instructions help when you want to contribute Pull Requests to a GitHub repository that you do not have write access to.  It goes thru the step-by-step process for using the [http://github.com][] website and the [GitHub Desktop app] to make a local __Fork__ of the repository and then make code or documentation changes and then __Commit__ those changes and send a __Pull Request_ to the repo's owner.  Tha approach here is just to use the web pages and the app and not use the git commandline commands which I find difficult to use.

I will assume that you have a GitHub ID, working webbrowser and the GetHub Desktop app installed and configured with your GitHub ID.

In your web browser:
* Navigate to the GitHub webpage of a repo that you want to contribute to
* Click the "__Fork__" button at the upper right corner of the page
* Click the "__Save local__" icon (a computer with down arrow) below “Star" and “Fork" buttons and just to the left of the “Download ZIP” button

In the GitHub desktop app:
* In the Open Dialog:
  * Make a user folder to match the GitHub username -- This is _optional_ but does make things easier to find
  * "__Save__" fork into user folder
* Click the "__Sync__" button (this is super important!!)
* Click the "__Add a branch__" button (this is super important!!) with a name appropriate to the kind of changes you intend to make
* Click the "__Update from master__" button (this is super important!!)
 
Ok...  You are now free to make and test changes to the files in the local directory with your favorate Editor or IDE.

Once your changes are complete and all your tests have passed...  In the GitHub desktop app:
* Add a comment to the Commit
* Click the "__Commit to <new branch>__" button (NOT to Master!”)
* Click the "__Pull Request__" button
* Add a comment to the Pull Request
* Click the “Send Pull Request” button

In your web browser:
* Navigate to the GitHub webpage of the repo and verify that the Pull Request is there and review all of the changes that you have made





[http://github.com](http://github.com/)
[GitHub Desktop app](https://desktop.github.com/)