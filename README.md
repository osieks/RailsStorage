# README
# RailsStorage

Welcome to StorageAPP! This is a Ruby on Rails application that allows users to manage posts using Active Storage for file attachments and Tailwind CSS for styling.

## Getting Started

1. **Prerequisites:**
   - Make sure you have Ruby and Rails installed on your system.
   - Install Node.js and Yarn for managing JavaScript dependencies.

2. **Clone the Repository:**
   ```bash
   git clone RailsStorage
   cd RailsStorage

3. **Install Dependencies:**
bundle install
yarn install

3. **Database Setup:**
rails db:create
rails db:migrate

3. **Run the Application:**
rails server

3. **Access the App: Open your browser and navigate to http://localhost:3000.**

# Features
User authentication (login and logout)
File uploads using Active Storage
Posts management (CRUD operations)
Tailwind CSS Integration
The project uses Tailwind CSS for styling. You can find the styles in the app/assets/stylesheets/application.scss file. Customize the styles according to your design requirements.

# Active Storage
Active Storage is integrated for file attachments. You can attach files to posts using the has_one_attached :file association in the Post model.

# Contributing
Feel free to contribute to this project by opening issues or submitting pull requests. Let’s make StorageAPP even better!

# License
This project is open-source and available under the MIT License.



