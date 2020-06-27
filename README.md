# StoryBooks App

A place to share your public and private stories.<br>
Check demo at [DEMO](https://abs-storybook.herokuapp.com/)
## Dependencies

- [connect-mongo](https://npmjs.com/package/connect-mongo)
- [dotenv](https://npmjs.com/package/dotenv)
- [express](https://npmjs.com/package/express)
- [express-handlebars](https://npmjs.com/package/express-handlebars)
- [express-session](https://npmjs.com/package/express-session)
- [method-override](https://npmjs.com/package/method-override)
- [moment](https://npmjs.com/package/moment)
- [mongoose](https://npmjs.com/package/mongoose)
- [morgan](https://npmjs.com/package/morgan)
- [passport](https://npmjs.com/package/passport)
- [passport-google-oauth20](https://npmjs.com/package/passport-google-oauth20)
- [cross-env](https://npmjs.com/package/cross-env)
- [nodemon](https://npmjs.com/package/nodemon)

## Running the project
- Clone the repository
- Add your environment variables in `config/config.env`
  - `PORT`
  - `MONGO_URI`
  - `GOOGLE_CLIENT_ID`
  - `GOOGLE_CLIENT_SECRET`
- Run `npm install`
- Run in development mode: `npm run dev`
- Run in production mode: `npm run start`

## Sources and Links
- [Google OAuth2 API](https://developers.google.com/identity/protocols/oauth2) - Google's Blog
- [PassportJS Oauth2 Strategy](http://www.passportjs.org/docs/oauth2-api/) - Passport JS Strategies
- [Materialize CSS](https://materializecss.com/getting-started.html) - CSS Library used
- [Traversy Media Video](https://www.youtube.com/watch?v=SBvmnHTQIPY) - YouTube video about the project