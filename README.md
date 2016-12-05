![Wordpress from scratch](https://guides.nanobox.io/assets/quickstart-icons/wordpress.png)

# WordPress from scratch

Run a WordPress app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>

## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-wordpress.git

# cd into the wordpress app
cd nanobox-wordpress
```

## Run the app

```bash
nanobox run php-server
```

## Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local wordpress.dev
```

Visit your app at <a href="http://wordpress.dev" target="\_blank">wordpress.dev</a>

## Explore
With Nanobox, you have everything you need develop and run your WordPress app:

```bash
# drop into a Nanobox console
nanobox run

# check the php version
php -v

# and your code is mounted
ls

# exit the console
exit
```

## Now What?
For more details about running WordPress apps with nanobox, visit [guides.nanobox.io/php/wordpress/](https://guides.nanobox.io/php/wordpress/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
