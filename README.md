# Roxiler System Project

### This web application enables users to submit ratings for stores registered on the platform. The application supports three types of user personas: System Admin, Normal User, and Store Owner. Each type of user has unique functionalities based on their role. 

# Technologies Used
### Backend: Node.js with Express 
### Frontend: React.js
### Database: MongoDB 

# 1. User
  Users can register on the platform by providing their name, email, address, and a password during the signup process. Once registered, they can log in to the platform using their email and password. After successfully logging in, users also have the option to reset their password from their account settings, allowing them to update their credentials if needed. The platform ensures a secure and straightforward authentication process for all users.
# 2. Store Owner
  Store owners can view a list of all users who have submitted ratings for their store, along with detailed information about each rating. Additionally, they can see the overall average rating for their store, giving them a clear understanding of customer feedback. For security and account management, store owners also have the ability to change their password after logging in, ensuring their account remains secure and up to date
# 3. Validations
  User input validation ensures that the name must be between 20 to 60 characters, while the address can be up to 400 characters. The password must be between 8 to 16 characters and include at least one uppercase letter and one special character for security. Additionally, the email field requires a valid email format to ensure proper user registration and communication.
# 4.Store Listing
  Users can view all registered stores on the platform, along with key details such as the store name, address, and the store's overall rating. If a user has previously submitted a rating for a store, their submitted rating will also be displayed. Additionally, users can search and filter stores by name or address to easily find specific locations. They also have the option to submit a new rating or modify an existing rating, with ratings being between 1 and 5
  
