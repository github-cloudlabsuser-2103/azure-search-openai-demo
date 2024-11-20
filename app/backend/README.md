# Backend Application Documentation

## Overview
This document provides an overview of the backend application for the Azure Search OpenAI Demo.

## Prerequisites
- Node.js (version 14 or higher)
- npm (version 6 or higher)
- Azure account

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/azure-search-openai-demo.git
    ```
2. Navigate to the backend directory:
    ```sh
    cd azure-search-openai-demo/app/backend
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Configuration
1. Create a `.env` file in the backend directory.
2. Add the following environment variables to the `.env` file:
    ```env
    AZURE_SEARCH_API_KEY=your_azure_search_api_key
    AZURE_OPENAI_API_KEY=your_azure_openai_api_key
    ```

## Running the Application
To start the backend server, run:
```sh
npm start
```
The server will start on `http://localhost:3000`.

## API Endpoints
- `GET /api/search`: Perform a search query.
- `POST /api/generate`: Generate text using OpenAI.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss changes.

## License
This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for details.

## Contact
For any questions or support, please contact [your-email@example.com](mailto:your-email@example.com).
