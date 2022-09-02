## How to setup the project in your local system and start contributing?



### 1. Fork the repo

​	Go to the repo and click on the fork button available at the top right corner of the repo page.
![](./images/setup-guide/1.jpeg)

### 2. Clone the repo

​	After forking the main repo, go to the forked repo available under your Github repos. Clone this repo into your local system. Click the button shown in the image and then go to the desired repository where you want to locally setup this project. Use the given command to clone the repo.
![](./images/setup-guide/2.jpeg)
```
git clone <repo-link>
```

### 3. Install all the required dependency

​	In order to install all the required dependency, you will need nodejs installed on your system. If you already have nodejs installed in your system, you can move ahead else you can install nodejs for your respective system (follow any youtube tutorial). To install all the required dependencies, you simply have to install the given command.

```
npm install
```

### 4. Create your feature branch

​	Create a brand new branch with the name of the respective feature you are going to work on. This can be simply done by executing the following command.

```
git checkout -b <branch-name>
```

### 5. Committing changes and pushing them to the forked repo

​	After you are done making the changes in your branch, you should commit the changes. First you need to add all the changes for the commit. Use the following command for that.

```
git add *
```

To check the status of the git repository, use the following command.

```
git status
```

After adding the changes and reviewing them, you can commit the changes by using the following command. 

```
git commit -m <write commit message inside quotes>
```

To push all the changes to your forked remote repository, use the following command.

```
git push -u origin <branch-name>
```

### 6. Open a Pull Request

After the feature development is completed, you can open a pull request to the main remote repository. You can open a pull request by clicking on this button. 
![](./images/setup-guide/4.jpeg)

### IMPORTANT

Before making changes to your local code always make sure that the code available to you locally is the latest code. To update your repo, you need to first update your forked repo which can be done by clicking the following button. 
![](./images/setup-guide/3.jpeg)
After updating your forked repo, you need to run the following command in order to update your local repo with your forked remote repo.
```
git pull origin main
```

Happy Hacking!!
