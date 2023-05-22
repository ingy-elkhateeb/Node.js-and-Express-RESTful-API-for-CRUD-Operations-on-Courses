# 🌐 Node.js and Express RESTful API for CRUD Operations on Courses

This repository contains a RESTful API developed using Node.js and Express for performing CRUD (Create, Read, Update, Delete) operations on courses. The API provides endpoints to manage courses and allows testing these operations using Postman. 


## ✨ Features

- Create new courses by providing relevant information such as title, description, and duration.
- Retrieve a list of all courses or fetch a specific course by its ID.
- Update existing courses by modifying their attributes.
- Delete courses based on their unique ID.
- Comprehensive error handling and appropriate status codes for different scenarios.
- Integration with Postman to easily test the API endpoints.

## 🚀 Installation

1. Clone the repository to your local machine.
2. Install the required dependencies using npm or yarn.
3. Configure the database connection in the `.env` file.
4. Run the API using the command `npm start` or `yarn start`.
5. you should see the App is listening on port ...
6. Start testing the API endpoints using Postman.


## ✅ Testing with Postman

To test the API endpoints, you can import the provided Postman collection from the `postman` directory. The collection includes pre-configured requests for all the CRUD operations on courses.
<br>
- **Deleting a Course**
<br>
<img src="docs/Deleting Course.jpeg"></img><br>

- **Add course using Put**
<br>
<img src="docs/Add course using Put.jpeg"></img><br>

- **Error if course name is not specified**
<br>
<img src="docs/Error if course name is not specified.jpeg"></img><br>

- **Get list of courses**
<br>
<img src="docs/Get list of courses.jpeg"></img><br>

- **Posting New Course**
<br>
<img src="docs/Posting New Course.jpeg"></img><br>

## 🤝 Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to create an issue or submit a pull request. Please follow the established coding conventions and provide clear descriptions of your changes.


Enjoy managing courses effortlessly with the Node.js and Express RESTful API for CRUD operations! 🎉
