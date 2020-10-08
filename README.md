# 📜 haikunator-cli

Generate Heroku-like random names from the terminal

## About

CLI for [haikunatorjs](https://github.com/Atrox/haikunatorjs).

## Install

```sh
npm install --global @scoop/haikunator-cli

# OR

npx @scoop/haikunator-cli
```

## Usage

```sh
$ haikunator
# yellow-sky-8300
$ haikunator --delimiter=*
# shy*snow*7086
$ haikunator --length=10
# tiny-cake-5392564104
$ haikunator --hex
# rough-sun-d4ae
```

Read the [haikunatorjs](https://github.com/Atrox/haikunatorjs) docs for more info about the different flags available.

## Deploying a New Version

Bump the version to trigger a publish.

```sh
git checkout -b bump-version
npm version # to get current version
npm version x.y.z # to increase the version
git push --set-upstream origin bump-version
```

## License

Licensed under the MIT License.
