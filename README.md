# Quantum CMS

A powerful Content Management System built with Node.js, Express, and MongoDB.

## Features

- User registration with password hashing
- Extendable for custom CMS routes

## Installation

1. Clone the repository: `git clone https://github.com/your-username/QuantumCMS.git`
2. Install dependencies: `npm install`
3. Run the server: `npm start`

## Usage

1. Register a new user by sending a POST request to `/register` with a JSON body containing `username` and `password`.
   Example:
   ```bash
   curl -X POST -H "Content-Type: application/json" -d '{"username":"your_username", "password":"your_password"}' http://localhost:3000/register
