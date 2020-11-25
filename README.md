# Colonia

Progressive Webapp about colonialism and its history around you.

## Description

Vue3 Typescript PWA with Leaflet Map

## Info

## Useful Links

## ToDo


## Changelog

Steps done on Elementary OS 5:
### Steps:

1. Install Yarn:

    1.1 Open terminal:

    ```bash
    $ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
    ```
    Add Repository for Yarn by using this Command.

    Confirm with password.

    1.2 Ensure to add the GPG Key of the source as well:

    ```bash
    $ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
    ```
    1.3 Update your repositories:

    ```bash

    $ sudo apt update

    ```

    1.4 install yarn

    ```bash
    $ sudo apt-get install yarn
    ```
    1.5 update yarn to the latest version

    ```bash
    $ curl --compressed -o- -L https://yarnpkg.com/install.sh | bash

    ```
    1.6 To make yarn available restart your terminal window/session.

2. Install NodeJS

    2.2 Add Repository for NodeJS:
    ```bash
    $ curl -sL https://deb.nodesource.com/setup_15.x | sudo -E bash -
    ```

    2.3 Install NodeJS
    ```bash
    $ sudo apt-get install -y nodejs
    ```
    
    2.4 Install development tools in order to install native addons:

    ```bash
    $ sudo apt-get install gcc g++ make
    ```




3. Install VueCLI

    Useful Link:
    
    https://medium.com/vue-typescript/vue-3-with-typescript-setup-a-new-project-with-the-vue-cli-4ea806be7a91

    ```bash
    $ yarn global add @vue/cli
    ```
4. Add needed packages:


