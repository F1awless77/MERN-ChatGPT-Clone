# Installing Node packages

1. Navigate to the server directory and run:
   ```bash
   npm install
   
1. Navigate to the client directory and run:
   ```bash
   npm install -f

#Setting up environment variables
###server directory
IMAGE_KIT_ENDPOINT: 'Your Imagekit endpoint'

IMAGE_KIT_PUBLIC_KEY: 'Your Imagekit public key'

IMAGE_KIT_PRIVATE_KEY: 'Your Imagekit private key'

CLIENT_URL: 'Your client URL'

MONGO: 'Your URL path to your MongoDB database'

CLERK_PUBLISHABLE_KEY: 'Your Clerk publishable key'

CLERK_SECRET_KEY: 'Your Clerk secret key'

###client directory

VITE_CLERK_PUBLISHABLE_KEY: 'Your Clerk publishable key'

VITE_IMAGE_KIT_ENDPOINT: 'Your Imagekit endpoint'

VITE_IMAGE_KIT_PUBLIC_KEY: 'Your Imagekit public key'

VITE_GEMINI_PUBLIC_KEY: 'Your Gemini language model'

VITE_API_URL: 'Your URL to server'

## Important Notes

- **.gitignore**: Make sure to add your `.env` file to your `.gitignore` to prevent it from being tracked by version control.
  
- **Keep Keys Secure**: Remember to keep your API keys and sensitive information private. Do not expose them in public repositories.
