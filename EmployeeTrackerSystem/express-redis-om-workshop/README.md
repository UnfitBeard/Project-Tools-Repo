# Redis OM + Express Workshop Starter Code

tutorial on [redis.io](https://redis.io/docs/stack/get-started/tutorials/stack-node/). This is just my practice version

# Simple CRUD API with Redis

This is a simple backend application that implements **CRUD (Create, Read, Update, Delete)** operations using **Redis** as the data store. The application exposes **RESTful APIs** that interact with Redis to perform various data operations.

### Features:
- **Create**: Add new records to Redis.
- **Read**: Retrieve existing records from Redis.
- **Update**: Modify existing records.
- **Delete**: Remove records from Redis.

### Technologies Used:
- **Node.js**: Backend runtime environment.
- **Express.js**: Web framework for building the RESTful API.
- **Redis**: In-memory data structure store used as the primary database.
- **Redis OM**: An Object Mapping (OM) library for Redis to facilitate data modeling and interaction.

### Setup Instructions:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```

2. **Install dependencies**:
   Navigate to the project folder and install the required dependencies.
   ```bash
   cd your-repository-name
   npm install
   ```

3. **Set up Redis**:
   - Make sure you have **Redis** installed and running. You can use **Docker** to run Redis Stack if you prefer like I do:
     ```bash
     docker-compose up -d
     ```
   - Ensure Redis is running on the default port `6379`.

4. **Start the server**:
   Once all dependencies are installed and Redis is running, you can start the application:
   ```bash
   npm start
   ```
   The server will be running on `http://localhost:8000`.

### API Endpoints:
- **POST /create**: Add a new record to Redis.
- **GET /read/:id**: Retrieve a record by its ID.
- **PUT /update/:id**: Update an existing record.
- **DELETE /delete/:id**: Remove a record from Redis.

### Contributing:
Feel free to fork this project, create a branch, and submit a pull request. Contributions are welcome!
