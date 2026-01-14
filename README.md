# MindMapAI  ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue) ![License](https://img.shields.io/badge/license-MIT-yellowgreen)

## Project Description
MindMapAI is an innovative web application that leverages AI to assist users in creating and organizing their thoughts visually through mind maps. By integrating real-time collaboration and AI-generated suggestions, it enhances brainstorming sessions for teams and individuals alike.

## Features
- 🧠 **AI-assisted mind mapping**: Users can input topics and the AI generates a structured mind map with related concepts.
- 🤝 **Collaborative brainstorming**: Multiple users can work on the same mind map in real-time, with chat functionality powered by LangChain.
- 📤 **Export options**: Users can export their mind maps in various formats (PDF, image, text) for presentations or sharing.

## Tech Stack
### Frontend
- 🌐 **Next.js**: A React framework for server-side rendering and static site generation.

### Backend
- ⚡ **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python 3.6+ based on standard Python type hints.
- 🔗 **LangChain**: A framework for developing applications powered by language models.

### Database
- 🗄️ **PostgreSQL**: A powerful, open-source object-relational database system.

### AI Integration
- 🤖 **OpenAI**: API for integrating advanced AI capabilities.

## Installation
To set up MindMapAI locally, follow these steps:

- Clone the repository
bash
git clone https://github.com/vikasexcel/mindmapai.git
- Navigate to the project directory
bash
cd mindmapai
- Create a virtual environment
bash
python -m venv venv
- Activate the virtual environment
bash
# On Windows
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
- Install the required dependencies
bash
pip install -r requirements.txt
- Set up the database (ensure PostgreSQL is running)
bash
# Create a new database
createdb mindmapai
- Run the application
bash
uvicorn main:app --reload
## Usage
1. Open your web browser and navigate to `http://localhost:8000`.
2. Create a new mind map by entering a topic.
3. Collaborate with others by sharing the link and brainstorming together.
4. Export your mind map in your desired format using the export options.

## API Documentation
For detailed API documentation, please refer to the [API Docs](https://github.com/vikasexcel/mindmapai/wiki/API-Documentation).

## Testing
To run the tests for MindMapAI, follow these steps:

- Ensure your virtual environment is activated.
- Run the test suite
bash
pytest
## Deployment
To deploy MindMapAI, follow these steps:

- Build the application for production
bash
npm run build
- Deploy to your preferred cloud service (e.g., AWS, Heroku).
- Ensure environment variables are set for production.

## Contributing
We welcome contributions! Please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them.
- Push your branch and create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Special thanks to the contributors and the open-source community for their support and resources.