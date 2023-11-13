# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

created with this version
```
❯ node --version
v20.9.0
```

if using `nvm`, you can run this to set the node version

```
nvm use
```

github auth /login page added in `packages/app/src/App.tsx`

To start the app, run:

```sh
yarn install
yarn dev
```

after adding github auth, do `yarn install` again in root of backstage app. https://backstage.spotify.com/learn/standing-up-backstage/configuring-backstage/7-authentication/

to build techdocs locally not in docker; see https://backstage.io/docs/features/techdocs/getting-started#disabling-docker-in-docker-situation-optional

mkdocs stuff install locally, and update to current versions:

* pip install -U mkdocs
* pip install -U mkdocs-techdocs-core


# postgres

* `yarn add --cwd packages/backend pg`
* `yarn install` seems like you have to run this after adding packages.



