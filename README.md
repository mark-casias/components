# Component Based Development Using UI_Patterns
A training workshop for people who develop websites using the component based approach.

## Local Environment Setup (Do this first)
Before anything else, follow these steps to get your local envrionment setup.

1. Install Lando

For Mac OS, download the latest version on [GitHub](https://github.com/lando/lando/releases).
[More info and other platforms](https://docs.devwithlando.io/installation/installing.html)


2. Install Composer

[Follow these instructions](https://www.hostinger.com/tutorials/how-to-install-composer) for your specific Operating System


3. Clone or download this repo anywhere on your local machine

```
git clone https://github.com/mariohernandez/components
```


4. Start Lando

Change into the directory of the repo to run all commands below:

```
lando start
```

5. Install all PHP Dependencies with Composer

```
composer install
```


6. Install Drupal

`lando drush site-install config_installer --account-name=admin --account-pass=admin --db-url='mysql://drupal8:drupal8@database/drupal8' --site-name=Components`

7. Train your dragon.

## Training Documentation

[Training material](https://mariohernandez.gitbooks.io/components/content/), including step-by-step exercises, are available as a gitbook.  Proceed to the documentation after following the Environment setup instructions above.
