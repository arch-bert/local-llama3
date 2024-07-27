Build an offline web application that allows users to interact with Llama3, a conversational AI, using a React-based frontend and a Node.js/Express backend, which communicates with Ollama’s local API. The application also includes functionality to save and retrieve chat logs using a MongoDB database.

## Project Components

1.	Frontend (React):
- UI Components: Create a user-friendly interface for entering prompts and displaying AI responses.
- API Requests: Send user prompts to the backend and display responses.
2.	Backend (Node.js/Express):
- API Endpoints: Handle incoming requests from the frontend, interact with Ollama’s local API, and manage chat logs.
- Ollama API Interaction: Send requests to Ollama’s local API to generate responses from the Llama3 model.
3.	Database (MongoDB):
- Schema and Models: Define the structure for storing chat logs.
- CRUD Operations: Save and retrieve chat logs from the database.

## Implementation Steps

1.	Backend Server:
- Create an Express server.
- Define routes for interacting with the Ollama API and managing chat logs.
- Connect to MongoDB for storing chat logs.
2.	Frontend Application:
- Set up a React project.
- Build components for the chat interface.
- Implement API calls to the backend.
3.	Integration:
- Ensure the frontend can communicate with the backend.
- Verify that the backend properly interacts with Ollama’s local API and the MongoDB database.
4.	Deployment (Optional for CV):
- Host the backend server and database (if showcasing online).
- Deploy the React application using services like Netlify or Vercel.