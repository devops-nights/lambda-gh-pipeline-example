# Github actions demo for lambda
Quick example on creating a simple lamdba CD pipeline

This leverages github actions and sam to do a very simple pipeline.  

https://github.com/j-devops/demo-cloud/blob/main/.github/workflows/deploy.yml

Every push to master will trigger the pipeline to run.

### Steps:
1. Create s3 bucket called gha-lambda-jtest
2. Check regions in code
3. Add your AWS secretes to github secrets (variables in code)
3. deploy

### Issues:
no simple way to destroy / undeploy

### Test:
https://(lambda-url)/Prod/hello
