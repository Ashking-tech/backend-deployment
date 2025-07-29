

---

# Backend Deployment – EthPe (Web3SSH Hackathon)

This repository contains the **backend deployment code** for the project submitted to the **Web3SSH Hackathon** conducted by **IIIT Sri City**.

🔗 **Main project repository:** [EthPe](https://github.com/KadamKaustubh147/EthPe)

## 🔧 Tech Stack

 **Backend:** Node.js + Express.js
 **Database:** MongoDB (with Mongoose)

##  Features Implemented

*  Passwords securely hashed using **bcrypt**
*  **JWT** tokens for authentication and session management
*  **ReentrancyGuard** used in smart contracts for added security
*  Backend validations and middleware checks for robust API handling

---

##  API Endpoints

| Method | Route                          | Description                    |
|--------|--------------------------------|--------------------------------|
| POST   | `/auth/register`               | Register a new user            |
| POST   | `/auth/login`                  | Login existing user            |
| GET    | `/transaction/balance/:address`| Get ETH wallet balance         |
| POST   | `/transaction/send`            | Send ETH securely              |

