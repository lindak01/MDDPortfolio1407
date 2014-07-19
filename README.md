Portfolio Deployment Plan

In order to deploy the Portfolio to the server please follow the deployment plan below.

1. Merge the portfolioTest branch into the Master branch on your local machine and then ensure that you sync Git remotely.

    a.) $ git checkout master
        This will switch you to the local master branch
    b.)$ git pull MDDPortfolio1407 master
        Resolve any conflicts.
        After conflicts are resolved and saved:
        $ git add -A
        $ git commit -am 'Commit message'
        $ git pull MDDPortfolio1407 master
    c.)$ git merge portfolioTest
        Resolve any conflicts(see above)
    d.)Test
        
    e.)$ git push MDDPortfolio1407 master