# Install Helper for Patchwork App

Requirements:
* python3

## Install
To start the installation process run this command:

```sh
bash -l -c "$(curl -sfL https://raw.githubusercontent.com/patchworkhealth/AppDepInstaller/main/main.sh)"
```

It will ask you after the first setup for your user password.
So please keep an eye on your command line and provide your password.

## Included dependencies
Dependencies are specified in the `default.config.yml`.
At the moment these dependencies are specified:
- applesimutils
- bitrise
- idb-companion
- node
- ruby
- watchman
- zsh
- altair-graphql-client
- android-studio
- flipper
- react-native-debugger
- Xcode
- cocoapods
- detox-cli
- fb-idb

It also installs a default android emulator

