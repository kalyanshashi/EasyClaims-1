# EasyClaims



   0. Clone the project from GitHub - run the command “git clone https://github.com/kalyanshashi/EasyClaims”
     and run command "cd EasyClaims/"
1. Run the command “git branch” to validate the branches as mentioned in the below sample output
          (venv) 19:08 ~/EasyClaims (staging)$ git branch
              develop
              master
             * staging

2. Checkout to development branch - run command “git checkout develop”
3. Create python3 environment - run command “python3 -m venv venv”
4. Activate created virtual environment - run command “source venv/bin/activate”
5. Install required packages to the project - run command “pip install -r requirements.txt”
  6. “cd easyclaims”
  7. run “./manage.py makemigrations”
  8. run command “./manage.py migrate”
  

Git commands:
———————

Git life cycle

Staging —> Committing —> Pushing


Configure git your userid and email (GitHub registered email id):

git config —global user.name “kalyanshashi”
git config —global user.email “shashikalyan421@gmail.com”

Verify where your local branch pointing to right now:

	git branch

	Note: Observe * over there — where it is pointing to that branch

Switch to another branch:

	git checkout <branch_name>

Pull the latest changes from the remote repository:

	git pull


Check the status of git (Run below command every time during git related information to know the status of your current repository):

	git status

Staging/adding modified files:

	To add all modified files:

		git add -A

	To add specific file:

		git add <file_name>

To remove the modified changes (in case required):

	git stash

	Note: Above command is dangerous as it will remove all your changes. Be careful before executing it.

Commit the files to your local branch:

	git commit -a -m “<Appropriate message>”
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	Scenario 1:
how can you help  me?
Scenario 2:
i want to create claim?
Scenario 3:
what are the documents needed for car insurance claim?
Scenario 4:
Claim Status

Today I am going to present mobile application which we developed for reducing customer calls queries related to purchasing policies and raising claims as part of hackathon.

This application has two roles admin and customer.
Admin has the authority to create new policies introduced by company and can approve claims raised by customers.
Whereas customer can sign up, login and purchase or subscribe (if paid) any policies added by admin. Customer can raise claims for policies subscribed or bought.
Customer can also check the Information about claims process or documents , check claim status via artificial intelligence chat bot.
This chatbot has different capabilities .we have added few important scenarios as part of implementation.

We have implemented this implementation with latest technologies which results best productivity in less time.
The technologies we have used are python which Improved Programmer’s Productivity and it has extensive support libraries and clean object-oriented designs that increase two to tenfold of programmer’s productivity while using the languages like Java, VB, Perl, C, C++ and C#.
Django rest framework we have used as it has rich amount of libraries for commonly used requirements without reinventing wheel from scratch. This improves productivity.

Postgresql we have used as it supports object orieneted database and django supports objects relational management. Django orm makes easy of process for db transactions and also in future if we want change db we can change db in with in one minute.
Semaphore CI/CD is to make the deployment automated. The important feature of this tool is it will build and deploy the application in less than 10 minutes. So less worry about manual support of deployment as it is automated. It has the capability to host application in any one of the cloud  as of now we have used heroku for hosting.
Dialog flow API is used to make chatbot work with intelligence and it also supports various local languages. So if customer is from other than english language this application can integrate that language and we provide customer support across the world


Push the changes to your remote branch:

	git push -u origin <branch_name>






 



