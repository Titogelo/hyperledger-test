# Hyperledger + Rest + Angular 

## To install

[Link to tutorial] (https://medium.com/@Niharika3297/ultimate-end-to-end-tutorial-to-create-an-application-on-blockchain-using-hyperledger-3a83a80cbc71)

## Before starting up

cd ~/fabric-tools
    ./startFabric.sh
    ./createPeerAdminCard.sh

## Spin up the rest server

cd test-bank/
composer-rest-server -c admin@test-bank -n always -w true

## Start the Angular app

cd bank-app/
npm start

## How to use it

The Composer Rest Server

http://localhost:3000/explorer/

The Angular App

http://localhost:4200/