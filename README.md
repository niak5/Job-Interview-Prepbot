# jobprepbot
**Job PrepBot**
Job PrepBot is a chatbot designed to assist users in preparing for job interviews and career advancement. By integrating common interview questions, resume tips, and company insights into a large language model (LLM), this bot provides personalized guidance to help users succeed in job applications and interviews.

**Features**
Interactive chatbot for job interview preparation.
Extensive database of common interview questions and resume tips.
Personalized mock interviews based on user-selected job roles.
Company-specific insights and tips.
Tailored feedback to improve answers and resume writing.

**Installation**
To get started with Job PrepBot, follow these steps:

**Clone the repository:**
git clone https://github.com/niak5/job-prepbot.git
cd JobPrepBot

Install the Gaia Node by running the following command:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Run the following command to update your config.json to run with a small language model:
gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

**Start the node:**
gaianet start

**How to Use**
Open your web browser and navigate to the generated link.
Start interacting with the bot by selecting job roles, practicing interview questions, or getting resume advice.
The bot will provide feedback and tailored suggestions based on your performance.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.
