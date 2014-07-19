MDD1405
Portfolio Deployment Plan

In order to deploy the Portfolio to the server please follow the deployment plan below.

Merge the project-ideas branch into the Master branch on your local machine and then ensure that you sync Git remotely.

$ git checkout master This will switch you to the local master branch
$ git pull MDDPortfolio1407 master Resolve any conflicts. After conflicts are resolved and saved: $ git add -A $ git commit -am 'Commit message' $ git pull github master
$ git merge portfolioTest Resolve any conflicts(see above)
Test
$ git push MDDPortfolio1407 master