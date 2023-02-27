
# My First Fork (and clone)


## How to Download

### Part 1 - Forking the Project
* To _fork_ the project, click the `Fork` button located at the top right of the project.


### Part 2 - Navigating to _forked_ Repository
* Navigate to **your github account** to find the _newly forked repository_.
* Copy the URL of the project to the clipboard.

### Part 3 - Cloning _forked_ repository
* Clone the repository from **your account** into the `~/Projects` directory.
    * if you do not have a `~/Projects` directory, make one by executing the following command:
        * `mkdir ~/Projects`
    * navigate to the `~/Projects` directory by executing the following command:
        * `cd ~/Projects`
    * clone the project by executing the following command:
        * `git clone https://github.com/ZipCodeCore/MyFirstFork`


## Make Changes
* edit the `my-name` file, by adding your name to the file.


## How to Submit

### Part 1 -  _Pushing_ local changes to remote repository
* from a _terminal_ navigate to the root directory of the _cloned_ project.
* from the root directory of the project, execute the following commands:
    * add all changes
        * `git add .`
    * commit changes to be pushed
        * `git commit -m 'I have added changes'`
    * push changes to your repository
        * `git push -u origin main`

### Part 2 - Submitting assignment
* from the browser, navigate to the _forked_ project from **your** github account.
* click the `Pull Requests` tab.
* select `New Pull Request`
