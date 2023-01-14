 # Pipeline Process
 
 1. Push Hosting a Full-Stack Application to GitHub
 2. Circleci setup the Hosting a Full-Stack Application on GitHub
 3. steps of the CI/CD:


## install node and checkout code and build

- Use root level package.json to install dependencies in the frontend app
- Install dependencies in the the backend API 
- Lint the frontend
- Build the frontend app
- Build the backend API      
 
## deploy step will run only after manual approval

###  setup aws, node, elastic beanstalk

- node/install:node-version: '14.15' 
- eb/setup
- aws-cli/setup
- checkout

### deploy

