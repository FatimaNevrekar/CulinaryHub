Steps to run the project on your local machine

Fork this repository
Open terminal or command prompt on your local machine. Run the following command to clone the repository:

```
git clone https://github.com/your-username/your-repo.git
```

Replace **your-username** with your GitHub username and **your-repo** with the name of your repository.

Open the project and rename <strong>.env.example</strong> files to <strong>.env</strong> in both client and server directory.</li>

Add your own environment variables to these both files.</li>

Add <strong>http://localhost:5173</strong> and <strong>http://localhost:5000</strong> to <strong>allowedOrigins</strong> array present in the path <strong>server/config/allowedOrigins.</strong></li>

To run the frontend, open a new terminal and run 'cd client/' to go to client directory and execute:</li>

```
npm run dev
```

To run the backend, open a new terminal and run 'cd server/' to go to server directory and execute:</li>

```
nodemon index.js
```

Open <strong>http://localhost:5173/</strong> from your browser to run the webapp.</li>

