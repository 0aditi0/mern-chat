
# Talk-A-Tive

Talk-a-tive is a Full Stack Chatting App.
Uses Socket.io for real time communication and stores user details in encrypted format in Mongo DB Database.
## Tech Stack

**Client:** React JS

**Server:** Node JS, Express JS

**Database:** Mongo DB
  

## Run Locally

Clone the project

```bash
  [git clone https://github.com/0aditi0/mern-chat.git]
```

Go to the project directory

```bash
  cd mern-chat
```

Install dependencies

```bash
  cd backend/
  npm install --legacy-peer-deps
  npm install dotenv
```
Set environment variables
```bash
  set MONGO_URI="mongodb+srv://aditianand1112:aditianand1112@cluster1.2bixzbm.mongodb.net/?retryWrites=true&w=majority&appName=Cluster1"
  set JWT_SECRET="aditi"
  set PORT=5000
  set NODE_ENV=development
```

```bash
  cd frontend/
  npm install --legacy-peer-deps
```

Start the server

```bash
  cd ..
  cd backend/
  npm run start
```
Start the Client

```bash
  //open now terminal
  cd frontend
  npm start
```

  

  
