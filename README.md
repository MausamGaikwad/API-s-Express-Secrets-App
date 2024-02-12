# Express Secrets App
This is a simple web application built with Express.js that allows users to interact with a secrets API. Users can perform CRUD operations (Create, Read, Update, Delete) on secrets stored in the API by sending HTTP requests through the provided form.

## Features
* GET Secret: Retrieves a secret from the API based on the provided ID.
* POST Secret: Creates a new secret in the API.
* PUT Secret: Updates an existing secret in the API.
* PATCH Secret: Partially updates an existing secret in the API.
* DELETE Secret: Deletes a secret from the API based on the provided ID.
## Setup
1. Clone the repository: `git clone https://github.com/MausamGaikwad/API-s-Express-Secrets-App.git`
2. Install dependencies: `npm install`
3. Set your bearer token: Replace `yourBearerToken` in `index.js` with your actual bearer token obtained from the API provider.
4. Run the server: `npm start`
## Usage
1. Access the application through a web browser at `http://localhost:3000`.   
2. Fill in the form with the required details:
   * Id: The ID of the secret (required for all operations except POST).
   * Secret: The content of the secret (required for POST and PUT operations).
   * Score: The score associated with the secret (optional).
3. Click on the appropriate button to perform the desired operation:
   * GET: Retrieves the secret associated with the provided ID.
   * POST: Creates a new secret with the provided details.
   * PUT: Updates the secret associated with the provided ID with the new details.
   * PATCH: Partially updates the secret associated with the provided ID.
   * DELETE: Deletes the secret associated with the provided ID.
4. View the response in the response area below the form.
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
MAUSAM GAIKWAD
