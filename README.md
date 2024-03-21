# JobAd: React-Firebase Platform for Finding Jobs

[JobAD](https://job-ad-qdzj.vercel.app/) is a web application built on React.js and Firebase, designed to help users find job opportunities by allowing them to browse, post, edit, and delete job ads. 
With a simple and intuitive interface, JobAd facilitates job seekers and employers in connecting efficiently.

## Deployment

JobAd is deployed and accessible online at [JobAD](https://job-ad-qdzj.vercel.app/). 
You can visit the live version of the application to explore its features and functionality.


## Features

- **User Authentication**: Users can sign up or log in securely using email and password authentication provided by Firebase.
  
- **Job Advertisement Management**: Authenticated users can post job advertisements, edit their own ads, and delete them when necessary.

- **Admin Panel**: An admin panel allows administrators to manage job ads by deleting any ad from the platform.

- **Responsive Design**: The application is built with responsiveness in mind, ensuring a seamless experience across various devices and screen sizes.

## Technologies Used

- **React.js**: A popular JavaScript library for building user interfaces.
  
- **Tailwind CSS**: A utility-first CSS framework for quickly styling the application with minimal custom CSS.

- **Firebase**: A comprehensive platform provided by Google for building web and mobile applications, including authentication, real-time database, hosting, and more.

## Getting Started

To run the JobAd application locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/Filip-git/JobAd.git
   ```

2. Navigate to the project directory:

   ```
   cd JobAd
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Set up Firebase:
   
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Obtain your Firebase configuration keys.
   - Replace the Firebase configuration in `src/firebase-config.js` with your own configuration.
   - Enable email and password authentication in the Firebase Authentication section.

5. Run the application:

   ```
   npm start
   ```

6. Open your browser and visit [http://localhost:3000](http://localhost:3000) to view the application.

## Usage

- **Sign Up/Login**: Create an account or log in using your email and password.
  
- **Browse Job Ads**: Explore all job ads posted by users.

- **Post a Job Ad**: Logged-in users can post new job advertisements by providing relevant details.

- **Edit/Delete Job Ads**: Users can edit or delete their own job ads as needed.

- **Admin Actions**: Admins have the ability to delete any job ad from the platform.

## Contributing

Contributions to JobAd are welcome! If you have any ideas for improvements, features, or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or support, please contact at filip.oroz1@gmail.com 
