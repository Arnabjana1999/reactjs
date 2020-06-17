# reactjs
front-end development using react

## Getting dependencies for yarn

curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

## Installing yarn

sudo apt update && sudo apt install yarn

export PATH="$PATH:/opt/yarn-1.22.4/bin"

## Creating react-app and starting yarn server

sudo yarn create react-app confusion

yarn start
