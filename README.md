# LinkedIn & Resume Optimizer

A simple tool that helps users improve their LinkedIn profiles and resumes for a new role.

## Features

- Upload LinkedIn screenshots
- Upload resume (PDF or Word)
- Enter details about the new role
- Get personalized recommendations using Claude AI

## Deployment Instructions

This application uses Netlify Functions to handle the Anthropic API requests. Follow these steps to deploy:

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```
3. Deploy to Netlify:
   ```
   npx netlify-cli deploy
   ```

Or simply use the Netlify Deploy button below:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourusername/linkedin-resume-optimizer)

## Local Development

1. Install dependencies:
   ```
   npm install
   ```

2. Start the Netlify dev server:
   ```
   npm run dev
   ```

3. Open your browser to the URL shown in the terminal (typically http://localhost:8888)

## Note

This application requires an Anthropic API key to function. Users must provide their own API key when using the application.
