# Assignment Answers to CE 3.12

## Create GitHub Repository
01. Create new public git repository with README.md and gitignore.
	gh repo create build_repo --public --description 'description here' --add-readme
02. Git clone repository into local.
	git clone git@github.com:username/build_repo
03. Change path into repository locally.

## Deploy Serverless application
04. Run "npm init".
05. Run "code ." to open the repository directory in VSCode.
06. Create a index.js file and input and save the relevant code.
07. Exit and go back to terminal to run "npm install serverless".
08. Run "npm install serverless-offline --save-dev".
09. Create a serverless.js file and input and save the relevant code.
10. Run "serverless deploy" to deploy serverless application to AWS.
11. Run "serverless remove" after deployment finish to remove items in AWS.

## Create CI/CD pipeline
12. Add "node_modules" and ".serverless" into .gitignore file.
13. Create "main.yml" file and input and save the relevant code in ".github/workflows".
14. Run "npm install jest --save-dev".
15. Create a index.test.js file and input and save the relevant code.
16. Run "npm run test" to test the CI/CD pipeline.

## Deploy CI/CD pipeline into GitHub Actions
17. Add "AWS_ACCESS_KEY_ID" and "AWS_SECRET_ACCESS_KEY" to GitHub secrets.
18. Add, commit and push the local repository to remote repository GitHub.
19. Go to GitHub Actions to observe the deployment status.
20. Remove/delete/terminate all AWS service/resources that were created.

https://github.com/apkiys/github-3.12-chris

![image](https://github.com/apkiys/6m-cloud-3.12-continuous-deployment-serverless/assets/20112494/1168e46b-5ee2-46be-92fb-508f73fded88)
