# StoryBooks

> Create public and private stories from your life

This app uses Node.js/Express/MongoDB with Google OAuth for authentication

It uses Docker + docker-compose for local execution, Terraform to provision cloud resources, and Github actions for CI/CD.

For full tutorial, see the video I created for the [Traversy Media YouTube channel](https://www.youtube.com/c/TraversyMedia/videos).

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

## Github Action

`.github/workflows/build-push-deploy.yaml` contains a workflow which deploys to a staging environment on pushes to the `main` branch and to a production environment on pushes of tags of the form `v#.#.#`.
