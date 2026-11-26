# Vehical Services

Monorepo structured with separate `frontend/` (React Native / Expo) and `backend/` (Node.js / Express) MVC folder layouts.

## Project Structure

```text
├── frontend/                  # Expo (React Native) client with MVC folders
│   └── src/
│       ├── app/
│       ├── components/
│       ├── constants/
│       ├── context/
│       ├── controllers/
│       ├── hooks/
│       ├── models/
│       ├── services/
│       └── views/
└── backend/                   # Node.js / Express backend with MVC folders
    ├── server.js
    └── src/
        ├── app.js
        ├── config/
        ├── controllers/
        ├── middlewares/
        ├── models/
        ├── services/
        ├── socket/
        ├── validators/
        └── views/
```
