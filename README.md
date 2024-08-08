
# BERTaurant

BERTaurant is a web application that allows users to view and add reviews for restaurants. It also includes administrative functionalities for managing reviews and restaurant details. The unique aspect of this project is the use of a pre-trained BERT model to classify and score restaurant reviews.

## About BERT

BERT (Bidirectional Encoder Representations from Transformers) is a state-of-the-art natural language processing model developed by Google. It is designed to understand the context of a word in search queries and other text inputs, making it highly effective for tasks like sentiment analysis, question answering, and language inference. In this project, BERT is utilized to analyze and classify restaurant reviews into positive or negative sentiments and to predict a rating score out of five.

## BERTaurant Demo

<p align="center">
  <a href="https://drive.google.com/file/d/1FZVIRUNCX80aOwmFZSKUT3uYDe6Ap0Hf/preview">
    <img src="https://drive.google.com/uc?export=download&id=18GaH5kfEXGiK0HbnUE_m7Tz3Fw5GYPql" alt="BERTaurant Demo">
  </a>
</p>

<p align="center">
  <iframe src="https://drive.google.com/file/d/1FZVIRUNCX80aOwmFZSKUT3uYDe6Ap0Hf/preview" width="640" height="480" allow="autoplay"></iframe>
</p>

Click on the image above to watch the video demonstration of BERTaurant in action.

## Features

- **User Functionality**: 
  - View reviews for a particular restaurant.
  - Add reviews to a restaurant.
  
- **Admin Functionality**: 
  - Access and manage all restaurant reviews.
  - Modify restaurant details as needed.
  - Add or remove restaurants and reviews.

- **Rating System**: 
  - Reviews are analyzed and classified using a pre-trained BERT model.
  - Scores are predicted based on the sentiment analysis.

## Installation

1. **Clone the repository**:
   ```
   git clone https://github.com/SakethAraveti/BERTProject.git
   cd BERTProject
   ```

2. **Install dependencies**:
   ```
   npm install
   ```

3. **Run the application**:
   ```
   npm run dev
   ```

## Project Structure

- **/model**: Contains the BERT model and related scripts for processing reviews.
- **/client**: Contains the frontend code for the website.
- **/server**: Contains the backend code and API routes.
- **/config**: Configuration files for environment variables and database connections.

## Scripts

- **\`npm run server\`**: Runs the backend server with Nodemon for hot reloading.
- **\`npm run client\`**: Runs the React frontend.
- **\`npm run app\`**: Starts the Flask server hosting the BERT model.
- **\`npm run dev\`**: Runs both the backend, frontend, and BERT model concurrently for development.

## Dependencies

- **Backend**:
  - \`express\`
  - \`cors\`
  - \`dotenv\`
  - \`mongoose\`
  - \`jsonwebtoken\`
  - \`bcryptjs\`
  - \`body-parser\`
  - \`morgan\`
  - \`colors\`
  - \`slugify\`
  - \`concurrently\`
  - \`nodemon\`

- **Frontend**:
  - \`axios\`
  - \`@tensorflow/tfjs\`

- **BERT Model**:
  - \`torch\`
  - \`transformers\`
  - \`bert-tokenizer\`
  - \`request\`

## Usage

Once the application is running, users can:
- Browse restaurants and view existing reviews.
- Submit new reviews, which will be automatically analyzed and rated using the BERT model.
- Admins can log in to access additional functionalities like modifying reviews and restaurant details.

## License

This project is licensed under the ISC License.
