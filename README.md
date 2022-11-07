# Express-Quests

### Initialisation

1. Clone the repo
2. `cd Express-Quests-04`
3. `npm i`
4. `cp .env.sample .env`
5. `npm run dev`

---

### To validate the quest

_In Postman_

1. Do a GET request `localhost:5005/api/users/`
2. Copy a user
3. Paste it in the body of your request
4. Modify the name
5. Do a PUT request `localhost:5005/api/users/*id of the user*`
6. Do a GET request with the same URL to check that the modification has been done !
