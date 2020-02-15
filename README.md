## What

Basic template for react app + rails API + JWT token login.

## How

First:

```
git clone --recurse-submodules git@github.com:GregPK/boat-app.git && cd boat-app
```

Then you will need two terminals:
```
cd boat-app-api && rake db:setup && rails s -p 3004
cd boat-app-react && yarn install && PORT=3005 yarn start
```

(substitute yarn to npm if needed)

This will start the app on localhost and redirect to the login page. You can
then login as `adminboat@example.org:password`.





