## Dang-thats-delicious

A website where people can view and review stores. Store owners have the ability to add and edit info about their store.

See live deployment [here](https://restaurant-navigator.herokuapp.com/).

## Directions to Run Locally
1. Make sure you have node (version 7.6.0 or above) and npm installed on your computer.
2. Clone the repo.
3. `cd` into the cloned directory and `npm i`
4. Install [MonogoDB](https://www.mongodb.com) locally or set one up on [mLab](https://mlab.com/).
5. Get an email provider. I like to use [mailtrap.io](https://mailtrap.io/) for testing and [Postmark](https://postmarkapp.com/) for production, however other things like Sendgrid, Mandrill, etc will also work.
6. Create a `dev.env` file. It should look similiar to `variables.env.sample` with the dummy data filled in with your actual data.
7. `npm run dev` or `npm start` will run the app locally on whatever `PORT` you specify in your `dev.env` file.

## Sample Data

To load sample data, run the following command in your terminal:

```bash
npm run sample
```

If you have previously loaded in this data, you can wipe your database 100% clean with:

```bash
npm run blowitallaway
```

That will populate 16 stores with 3 authors and 41 reviews. The logins for the authors are as follows:

|Name|Email (login)|Password|
|---|---|---|
|Wes Bos|wes@example.com|wes|
|Debbie Downer|debbie@example.com|debbie|
|Beau|beau@example.com|beau|
