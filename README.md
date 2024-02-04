# ChatGPT Clone

## Introduction
This project is a clone of ChatGPT, built using the OpenAI API. It's designed to provide users with a conversational AI experience, allowing them to ask questions, get information, or simply chat with an AI. The application is built with a modern web technology stack and is hosted live for easy access and use.

Live Site: [https://chatgpt-clone-five-peach.vercel.app/](https://chatgpt-clone-five-peach.vercel.app/)

## Features
- **Conversational AI Interface**: Engage in dialogues with the AI on a wide range of topics.
- **Responsive Design**: Access the chat interface from any device, with a design that adapts to fit screens of all sizes.
- **Real-time Interaction**: Messages are processed and replied to in real-time, providing an interactive experience.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **APIs**: OpenAI API for generating AI-based responses
- **Hosting**: Deployed on Vercel for seamless scalability and performance.

## Local Development
To run this project locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd chatgpt-clone
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add your OpenAI API key:
   ```
   OPENAI_API_KEY=<your_openai_api_key_here>
   ```

4. **Start the Server**
   ```bash
   npm start
   ```
   This will run the server on `http://localhost:5000`, so please replace the current `https://chatgpt-clone-g69k.onrender.com/` found on client -> script.js and replace it with `http://localhost:5000` to run locally.

5. **Accessing the Frontend**
   Open `http://localhost:3000` (or may open automatically with its own port) in your browser to view the app.

## Usage
To interact with the AI, simply type your message into the chat input and press enter or click the send button. The AI will process your message and respond in real-time.

## Contributing
Contributions to the project are welcome! Please refer to the contributing guidelines for more information.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- OpenAI for providing the GPT-3 API.
- Vercel for hosting the live site.

---

Remember to replace `<repository-url>` with the actual URL of your GitHub repository and `<your_openai_api_key_here>` with a placeholder instruction if you're sharing this README in a public repository. Adjust any sections as necessary to match your project's specific setup, features, or requirements.
