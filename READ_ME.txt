# Real Estate APP




# APP Features

- Create a real estate listing
- Retrieve all listings
- Delete a listing

---

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Docker](https://www.docker.com/)

---

## Installation

1. Clone the repository:

  
2. Install dependencies:

	Run npm install

3.Build the Docker image:

	docker-compose up --build.

4.Run the application in a Docker container:

	ports:
  - "8081:80"  # Frontend
  - "3001:3000"  # Backend

5.Alternatively if you want to run the apps without docker you can run every app on its own

-http://localhost:5000 ----->Front End
-http://localhost:3000 -----> Backend



# For Api Endpoints please follow this link for swagger documentation: http://localhost:3000/api-docs
