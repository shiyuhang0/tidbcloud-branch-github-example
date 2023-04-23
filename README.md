# tidbcloud-branch-github-example


This repo has been connected to a TiDB Cloud cluster using the TiDB Cloud GitHub integration. This brings database branches to your GitHub workflows, the TiDB Cloud App will automatically manage database branches for you when PR, commits are created.

You can open a PR in this repo to have a try. You can also use this step-by-step tutorial to build your own example.

## Before you start

Before you start, make sure you have:

- A TiDB Cloud account
- A GitHub account
- Create a TiDB Cloud cluster
- Create A GitHub repository


## Connect TiDB Cloud to your GitHub repository

1. Go to the integrations page under the admin, then you can find the GitHub integration

<img width="1417" alt="image" src="https://user-images.githubusercontent.com/52435083/233818397-96e2c8d6-5971-4f2b-b9a6-e278293cf9f4.png">

2. Go to the GitHub integration and click `connect` button. 
    - If you have not login the GitHub, you will be asked to login the GitHub account in a pop-ups. 
    - If it is the frist time you use the integration, you will be asked authorize the GitHub app in a pop-ups.
    
<img width="793" alt="image" src="https://user-images.githubusercontent.com/52435083/233824789-37c55dfb-939f-48bd-8773-9e47aa3bdd7a.png">


3. Select A TiDB Cloud 

You will enter the connect page after click the connect button. Select the cluster under the project first.

<img width="1063" alt="image" src="https://user-images.githubusercontent.com/52435083/233825019-a85b306a-52c8-415b-bbb1-907cc5792ad4.png">

4. Install and select a account

If it is the first time you use the integration. you need to install the GitHub app for your account. Click the `GitHub account` and choose the `install other account`, you will be redirected to a install page.

<img width="780" alt="image" src="https://user-images.githubusercontent.com/52435083/233826052-cc63d74b-c12d-4c44-ac5a-5173633737c5.png">

After you have installed your account, it will be shown under the `GitHub account` drop down. Select the account you need.

5. Select a repository under the account

Choose a repository under the account you selected.

<img width="1107" alt="image" src="https://user-images.githubusercontent.com/52435083/233826252-1469f6d5-a6e2-4a6c-8d77-1dc1dc30f4ee.png">


6. Connect

Click the `Connect` button to connect between the TiDB Cloud cluster and GitHub repository. 

<img width="1117" alt="image" src="https://user-images.githubusercontent.com/52435083/233826403-b9480b8d-9c95-47b6-a4b3-6c76885c1341.png">


## Open a PR in the connected repository


