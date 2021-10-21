# Envman

`.env` files manager.

## How to install

`npm i -g envman`

## How to use

Create the config file by running:

```
$ envman init
```

This command will create a `.envmanrc` file at your home directory.

Now you can `cd` inside any git repo that has an `.env` file and run 
`envman store` to store a copy of your `.env` into your vault.
