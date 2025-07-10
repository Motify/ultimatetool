# Deploying to AWS Amplify

## Prerequisites
- AWS account ([Sign up](https://aws.amazon.com/))
- GitHub account with your project pushed to a repository
- Node.js and npm installed locally

## 1. Prepare Your Project
- Install dependencies and build your project:
  ```bash
  npm install
  npm run build
  ```
- Commit and push all changes to your GitHub repository.

## 2. Set Up AWS Amplify
1. Go to the [AWS Amplify Console](https://console.aws.amazon.com/amplify/home).
2. Click **Get Started** under 'Deploy' or 'Host web app'.
3. Choose **GitHub** as your repository service and connect your GitHub account.
4. Select your repository and branch.
5. Amplify will auto-detect your build settings (for React, it usually uses `npm run build`).
6. Review and confirm the settings, then click **Save and Deploy**.

## 3. Wait for Deployment
- Amplify will build and deploy your app. This may take a few minutes.
- Once complete, you’ll get a live URL (e.g., `https://your-app-id.amplifyapp.com`).

## 4. Continuous Deployment
- Any push to your connected GitHub branch will automatically trigger a new build and deployment.

## 5. (Optional) Add Backend Features
- In the Amplify Console, you can add authentication, storage, APIs, etc., using the Amplify Studio or CLI.

## References
- [Official AWS Amplify React Guide](https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/module-one/)
- [Full-Stack React on AWS](https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/)