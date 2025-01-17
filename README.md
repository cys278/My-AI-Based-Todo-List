# MyTodoList - AI-Based Todo List

## Overview
**MyTodoList** is an AI-powered todo list application designed to simplify task management and improve productivity. Built using Next.js, TailwindCSS, and CopilotKit, this project integrates AI to assist users in managing their tasks more effectively.

## Features
- Add and delete todo items dynamically.
- Responsive user interface using TailwindCSS.
- AI-powered assistance through CopilotKit.
- Intuitive design with accessible navigation and user-friendly interactions.
- Easily deployable Node.js server.

## Technologies Used
- **Next.js**: Framework for server-side rendering and building scalable React applications.
- **TailwindCSS**: Utility-first CSS framework for styling.
- **CopilotKit**: Provides AI capabilities for task management.
- **OpenAI**: Powering the AI functionalities through GPT models.
- **Node.js**: Backend server for handling API requests and interactions.

## File Structure
### Key Files and Directories

1. **`route.js`**
   - Defines the API endpoint for CopilotKit integration.
   - Handles incoming requests and routes them to the appropriate AI services.

2. **`global.css`**
   - Defines the global styles for the application.
   - Customizes TailwindCSS utilities and sets the application's color scheme and font styles.

3. **`layout.js`**
   - Sets up the root layout for the application.
   - Integrates fonts and the navigation bar.
   - Configures CopilotKit runtime for AI functionalities.

4. **`page.js`**
   - Implements the main page logic and UI for managing todo items.
   - Contains React state management for todos and integration of CopilotKit actions.

5. **`Navbar.js`**
   - Implements the navigation bar with links to Home, About, and Contact pages.
   - Provides a consistent header for the application.

6. **`server.js`** (or `app.js` if applicable)
   - Handles the backend logic of the application.
   - Includes server setup using Node.js.

## How to Run
### Prerequisites
- Node.js installed on your system.
- An OpenAI API key.

### Installation Steps
1. Clone the repository
   
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add your OpenAI API key:
     ```env
     OPENAI_API_KEY=your_openai_api_key
     ```
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open the application in your browser:
   ```
   http://localhost:3000
   ```
6. (Optional) To run the Node.js backend server:
   ```bash
   node server.js
   ```

## Usage
1. Enter a task in the textarea and click the **Add Todo** button to add a new item.
2. Use the **Delete** button next to a task to remove it from the list.
3. Use the AI-powered popup assistant for help with managing tasks.

## Deployment
### Deploying to GitHub
1. Initialize a Git repository:
   ```bash
   git init
   ```
2. Add your files:
   ```bash
   git add .
   ```
3. Commit the changes:
   ```bash
   git commit -m "Initial commit"
   ```
4. Link the repository to GitHub
   
5. Push your code to GitHub:
   ```bash
   git branch -M main
   git push -u origin main
   ```

### Deployment to Hosting Platforms
- For hosting the Node.js server, use platforms like Heroku, Vercel, or AWS.
- Configure environment variables and deployment settings according to the platform's documentation.

## AI Integration
- **CopilotKit Actions**: 
  - `addTodoItem`: Adds a new task to the todo list.
  - `deleteTodoItem`: Deletes a specific task based on its index.
- **CopilotPopup**: Provides an AI assistant for user guidance.

## Design and UI
- **TailwindCSS**: Ensures a responsive and modern design.
- **Color Scheme**: Red tones for buttons and headers, with balanced text and background colors.

## Future Enhancements
- Add task categories and priorities.
- Implement a task completion tracker.
- Integrate user authentication.
- Add AI suggestions for task scheduling and prioritization.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Acknowledgments
- OpenAI for the GPT models.
- Next.js and TailwindCSS communities for their robust frameworks and tools.
- CopilotKit for simplifying AI integration.

