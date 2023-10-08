## Continuous Integration

In a large-scale project hosted on GitHub, numerous branches are created. We utilize CircleCI to automatically initiate builds and deployments for one of these branches. CircleCI is integrated with GitHub and automatically builds and deploys the latest code version to AWS S3 and triggers an automatic commit to AWS ElasticBeanstalk whenever code changes are pushed to the repository.


## API Build
Runs the `api:build` script to build BE.
## Front-End Build
Runs the `frontend:build` script to build FE.
## On hold
Waiting the build progress successfully, then confirm to deploy.
## Deploy
Runs the `deploy` script to deploy.