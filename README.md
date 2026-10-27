# MET Artwork App

A web app for searching and browsing artwork from the Metropolitan Museum of Art's public API. Signed-in users can save favourites and see their search history.

- `my-app/` – Next.js and React front end.
- `user-api/` – Express and MongoDB API for registration, login (JWT) and saved favourites/history.

## Run it

API (needs a `.env` file with `MONGO_URL` and `JWT_SECRET`):

```bash
cd user-api
npm install
npm start
```

Front end:

```bash
cd my-app
npm install
npm run dev
```

Then open http://localhost:3000.
