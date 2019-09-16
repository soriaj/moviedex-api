# Moviedex-Api
Moviedex-API is a Express app to search the included movies-data-small.json movie database.

### How to use

Visit [UUID](https://www.uuidgenerator.net/) for a token to use as Bearer Authorization
Create .env file and place token in API_TOKEN='Your Token Here'

Install Dependencies and Run
```bash
npm install
npm run start

```

Valid Querys - API supports Genre, Country and Average Vote based on the following inputs

http://localhost:8000/movies?genre=Drama

http://localhost:8000/movies?country=united%20states

http://localhost:8000/movies?avg_vote=6

or

http://localhost:8000/movies?genre=action&country=united%20states&avg_vote=7

### Powered by
[Express](https://expressjs.com/) | [NPM](https://www.npmjs.com/)

[Cors](https://www.npmjs.com/package/cors)
[Helmet](https://www.npmjs.com/package/helmet)
[Morgan](https://www.npmjs.com/package/morgan)

### Contributors
Javier Soria