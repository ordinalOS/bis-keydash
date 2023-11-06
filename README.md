# API Usage Dashboard [Best in Slot]

Bisful is a React application that enables users to view and monitor Best In Slot API key usage.

## Features

- **/components/panel/ApiKeyList.tsx**: Key Name List.
- **/components/panel/ApiKeyDetails.tsx**: Displays detailed usage information.

## Notable Libraries Used

- **React**: A JavaScript library for building user interfaces.
- **React Router DOM**: For handling routing within the application.
- **Axios**: Promise based HTTP client for the browser and Node.js.
- **Chart.js and chartjs-adapter-moment**: An open-source JavaScript library for rendering charts, with time adapter.
- **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.
- **Express**: Fast, unopinionated, minimalist web framework for Node.js.
- **Dotenv**: Loads environment variables from a .env file into `process.env`.
- **Sass (devDependency)**: A preprocessor scripting language that is interpreted or compiled into CSS.


### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/bisful.git
   cd bisful
   npm i

2. **Start Proxy Server:**

    - set API_KEY={apikey} in .env

    ```bash
    cd proxy-server
    npm i
    node proxy-server.js

3. **Start the development server:**
    ```bash
    npm start
