# WordPress on Nanobox
This is the companion application for the [WordPress: Getting Started](https://guides.nanobox.io/wordpress/) guide on [guides.nanobox.io](https://guides.nanobox.io) and is pre-configured and ready to run on [nanobox](https://nanobox.io/)!

## Up and Running

``` bash

# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-wordpress.git

# cd into the wordpress app
cd nanobox-wordpress

# build the code
nanobox build

# add a convenient way to access your app from the browser
nanobox dev dns add wordpress.nanobox.dev

# start the dev environment and run the app server (Apache & PHP-FPM)
nanobox dev run
```

Visit the app from your favorite browser at: `wordpress.nanobox.dev:8080`

### Now What?
For more details about how this works or for more advanced topics related to running WordPress applications on nanobox, visit [guides.nanobox.io/wordpress/](https://guides.nanobox.io/wordpress/)
