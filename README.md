# Lab 16 - Cloud Server

## Author: Chris Gantt

---

### Setup

`.env` requirements

- PORT - Port Number

---

### Running the app

`npm run start`

Endpoints: /

---

### Tests

n/a

---

### Deployments

- [GUI Deploy](http://testserver-env.eba-tsmytyjb.us-west-1.elasticbeanstalk.com/)
- [CLI Deploy]()

---

### Process

- GUI Deploy:
  - Setup repo and simple express server
  - npm init, install express, add npm start
  - check the server is functional locally
  - remove node_modules directory and package-lock.json
  - `zip -rp server.zip *`
  - Create IAM user with admin all access
  - Create app in EB
    - Set to Node environment
    - Upload zip file
- CLI Deploy:
  -