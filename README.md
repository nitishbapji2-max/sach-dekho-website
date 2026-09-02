# Sach Dekho

## Run in VS Code
Install Node.js 18+, open this folder in VS Code terminal, then:

    npm install
    npm start

Open http://localhost:3000

## Included
- Responsive design matching supplied screenshots
- Working logo/home navigation and mobile menu
- Signup/login with bcrypt password hashing and JWT authentication
- Scanner requires login; unauthenticated users are sent to signup
- URL scanner, text scanner, image/video upload handling
- Logged-in web search via DuckDuckGo Instant Answer API
- LinkedIn: https://www.linkedin.com/in/umesh-yadav-0b0a40431
- Instagram: https://www.instagram.com/umesh_iitm/

## Important for public launch
A domain alone is not hosting. Deploy this Node.js app on a Node-compatible host and point the domain DNS to it. Set a strong JWT_SECRET environment variable and HTTPS.

The included scanner is a functional screening/demo engine. It does NOT magically provide real AI deepfake detection or authoritative fact checking without external AI/fact-check APIs. Those APIs require their own provider accounts/keys and should be connected before advertising the results as genuine AI verification.
