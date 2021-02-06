# StoryBooks

> Create public and private stories from your life

This app uses Node.js/Express/MongoDB with Google OAuth for authentication

It uses Docker + docker-compose for local execution, Terraform to provision cloud resources, and Github actions for CI/CD.

For full tutorial, see the video I created for the Traversy Media YouTube channel.

## Usage

Add your mongoDB URI and Google OAuth credentials to the config.env file

```
# Install dependencies
npm install

# Run in development
npm run dev

# Run in production
npm start
```
