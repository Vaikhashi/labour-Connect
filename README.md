# Labour Connect

A job board for local work. Employers post jobs, workers in the area apply, and once the employer accepts someone they can chat and leave a review when the job's done.

Built with Node.js, Express and EJS, with MongoDB for data and Firebase for the chat.

## What's in it

- Sign up as a worker or an employer (passwords hashed with bcrypt, sessions with express-session).
- Employers post jobs, see who applied, and accept the people they want.
- Workers browse jobs, apply, and track pending and accepted applications.
- One-to-one chat between employer and worker (Firebase).
- Reviews after a job is finished.

## Running it

You need Node.js and MongoDB running locally.

```bash
npm install
node index.js
```

Open http://localhost:3000. The app connects to `mongodb://127.0.0.1:27017/LabConnect`.

## Next steps

- Move the database URL and Firebase config into a `.env` file.
- Host it so people can try it without setting it up.
