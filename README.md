# WordPress on Nanobox

This WordPress repo is preconfigured to quickly get WordPress up and running on [Nanobox](https://nanobox.io). Clone this repo to your local machine and do the following:

## Install Nanobox
If you haven't already, you'll need to [install Nanobox](https://docs.nanobox.io/getting-started/install-nanobox/).

## Generate Auth Keys & Salts
WordPress needs authentication keys and salts to create secure sessions. These are configured in your wp-config.php (lines 49-56). WordPress will generate auth keys and salts for you when you go [here](https://api.wordpress.org/secret-key/1.1/salt/).

Add the generated auth keys and salts to your wp-config.php.

## Start Your Dev Environment
Navigate into your WordPress directory and run:

```bash
$ nanobox dev run
```

This will generate a new build package, start your local dev environment, deploy the build into your dev environment, then start Apache and PHP-FPM.

## Add a DNS Alias to Your Dev App
In a separate console, run the following command to add a DNS alias to your dev app. This will add an entry to your local hosts file and allow you to access your dev app at the specified domain.

```bash
$ nanobox dev dns add your-custom-domain.dev
```

## Visit Your Running Dev Site
With your DNS alias in place, you can view your running dev WordPress site at:

`your-custom-domain.dev:8080`

#### Guides for WordPress on Nanobox
More information about running WordPress on Nanobox is available in the [WordPress on Nanobox guides](https://guides.nanobox.io/wordpress/).
