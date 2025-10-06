# 🚀 Firebase Extension for Gemini CLI

The Gemini CLI gives you the power of Gemini directly in your terminal, and you can **install the Firebase extension to give the Gemini CLI more Firebase-specific capabilities and expertise**.

## ✨ Features

###  **Set up backend services**
- Add data-backed features with Cloud Firestore database.
- Add user sign up/login to enable users to access their own data with Firebase Authentication.
- Deploy your app to a Firebase hosting service.

### **Add gen AI features**
- Add text, chat, and image generation features to your app with Firebase AI Logic.

### **Access to the Firebase MCP server**
- Access all the tools available in the Firebase MCP server, like project setup and management as well as tools to work with our database products, Remote Config, Crashlytics, and more.

## 🚀 Quickstart

1. [Install the Gemini CLI.](https://github.com/google-gemini/gemini-cli)

   The Gemini CLI offers a no-cost tier of usage and easy authentication with a Google Account.

2. Install the Firebase extension for Gemini CLI:

   ```bash
   gemini extensions install https://github.com/gemini-cli-extensions/firebase
   ```

## 🛠️ Use features of the extension

The Gemini CLI can access all the tools of the Firebase MCP server as well as commands that access pre-written prompts that help streamline common app development journeys:

### `/firebase:init`
This command provides you options like setting up backend services for your app and implementing genAI features that access the Gemini API.

- **Backend services:** Sets up and writes the code for Cloud Firestore database as well as Firebase Authentication to secure your app and user data. It can even deploy your app to an appropriate Firebase hosting service.
- **Gen AI features:** Sets up Firebase AI Logic and writes the code to easily and securely access the Gemini API directly from your mobile and web apps.

### `/firebase:deploy`
This command deploys your application to a Firebase hosting service by analyzing your code and determining if you need static app hosting or a full-stack hosting solution.

### `/firebase:consult`
This command accesses detailed up-to-date documentation for the Firebase platform. Just ask a question and the model will find an answer grounded in the latest Firebase documentation.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request (PR)

## 📄 License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

**Made with ❤️ from Firebase for the AI community**
