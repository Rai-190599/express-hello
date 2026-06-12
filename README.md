```markdown
# Express Hello JSON API

A simple and lightweight Node.js application built with Express.js. This application serves as a basic health check endpoint returning a JSON response. 

## Prerequisites

Before you begin, ensure you have [Node.js](https://nodejs.org/) installed on your local machine.

## Installation

1. Clone the repository to your local machine:

```bash

   git clone [https://github.com/Rai-190599/express-hello.git](https://github.com/Rai-190599/express-hello.git)

```

2. Navigate into the project directory:

```bash
   cd express-hello

```

3. Install the required dependencies (Express.js):

```bash
   npm install

```

## Running the Application

To start the server, run the following command in your terminal:

```bash
node index.js

```

You should see the following output in your terminal:
`App listening at http://localhost:3000`

## Testing the Endpoint

Open your browser or use an API testing tool like Postman or cURL, and navigate to:

```text
http://localhost:3000

```

**Expected JSON Response:**

```json
{
  "message": "This server is healthy"
}
