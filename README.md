# Micro Frontend example
This repository contains an example implementation for a microfrontend. It takes use of [single-spa](https://single-spa.js.org/docs/getting-started-overview) and uses angular as submodules.

## Structure
The folder `micro-root` contains the base of the page, basicly the root of all.
The other folders contains a base implemenation of angular. Those haven't to be strucuted in the same repo!

## Start
First you have to run `npm i` in every subfolder.

To start the angular applications you have to run the npm task `npm run serve:single-spa:frontendX`. After you started every application, start the micro-root part by using `npm run serve`. 

Afterwards you will be able to open the base page on [localhost:4200](localhost:4200).