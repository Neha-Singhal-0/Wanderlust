# Wanterlust

Wanterlust is a web application that serves as a basic version of Airbnb. This platform allows registered users to create, edit, and delete listings, as well as post reviews. The project is built using HTML, CSS, JavaScript, Node.js, Express, and MongoDB, with Cloudinary used for image uploads. The application is deployed on Render, with MongoDB Atlas used for cloud storage.

## Features

- **User Authentication**: 
  - Signup and login functionality.
  - Only registered users can create or interact with listings.

- **Listings Management**:
  - Create, edit, and delete listings.
  - Listings include details such as name, price, location, and pictures.
  - Only the user who created the listing can edit or delete it.

- **Reviews**:
  - Registered users can post reviews for listings.

- **Image Uploads**:
  - Cloudinary is used to manage image uploads and storage.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: MongoDB Atlas
- **Image Storage**: Cloudinary
- **Architecture**: MVC (Model-View-Controller)
- **Deployment**: Render

## Project Structure

- **Model**: Defines the data structure for listings and users.
- **View**: Handles the user interface and user experience.
- **Controller**: Manages the application logic and user requests.

## Getting Started

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/wanterlust.git
   ```
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Set up environment variables**:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     CLOUDINARY_CLOUD_NAME=your_cloud_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
     MONGODB_URI=your_mongodb_uri
     ```
4. **Run the application**:
   ```bash
   npm start
   ```
5. **Visit the application**:
   - Open your browser and go to `http://localhost:3000`.

## Deployment

The live version of the application is available at [Wanterlust on Render](https://wanderlust-292e.onrender.com).

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
