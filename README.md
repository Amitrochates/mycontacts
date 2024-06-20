# MyContacts App

The MyContacts App is a simple contact management application that allows users to organize and manage their contacts. It provides a user-friendly interface for adding, editing, and deleting contacts.

## Deployment

- The app’s frontend is deployed using Vercel.
- The backend is running on Render.
- You can access the live version of the MyContacts App [here](https://blog-app-psi-tawny.vercel.app/signin).

## Features

### Frontend

#### Technologies Used
- **JavaScript**: The primary language for building the frontend.
- **React**: Utilizes functional components along with hooks like `useState`, `useEffect`, and `useNavigate` for state management and navigation.
- **Tailwind CSS**: Facilitates efficient styling with a utility-first approach.

#### Key Features
- Custom hooks are implemented to fetch data from the backend, streamlining data retrieval and state management.
- Auxiliary functionalities like network requests and routing are handled by libraries such as `axios` and `react-router-dom`, respectively.
- Toasts for improved user experience.

### Backend

#### Technologies Used
- **Express**: A minimal and flexible Node.js web application framework for building the backend.
- **Node.js**: The runtime environment for executing JavaScript on the server.
- **MongoDB**: A NoSQL database for storing contact information.
- **CRUD Operations**: Implemented to manage user contacts.

#### Key Features
- Implements CRUD routes for managing user contacts, ensuring a robust API structure.
- `bcrypt` library is used to securely hash passwords before storing.
- CORS is configured to enable secure cross-origin requests.
- JWT (JSON Web Tokens) is used for secure authentication.

## Getting Started

1. Clone this repository.
2. Install dependencies using `npm install` in both frontend and backend.
3. Set up your MongoDB database and configure the connection in the backend.
4. Start the frontend using `npm run dev`.
5. Start the backend using `node server.js`.
