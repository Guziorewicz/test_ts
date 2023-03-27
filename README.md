# Map 
// This application was created ONLY for educational reasons :] //

///// Setup

Need to have `npm`, `node`, `npx` and `ts` installed

Run `npm install @faker-js/faker` to get the random values for classes

Run `npm install @types/google.maps` for add a @types/googlemaps library

///// An app Overview

This app generates random user and company with bunch of values then show it on map. The structure is based on the UDEMY course by Stephen Grider.

To handle the data I used 3 files for user, company and map whith provides classes for that objects and connected them with one index.ts file.
I used Parcel to compile .ts file and run in on localhost.
To generate random data for this project I used `faker` package.

In this app I used API key from Google Developer.
Creating an API key requires a Google Developer account with billing enabled. I don't wanted to use that in my app so I used API provided from course master. The API key is `AIzaSyBNLrJhOMz6idD05pzfn5lhA-TAw-mAZCU`

To open the main file index.html run command `npx parcel index.html`
that runs script localy, there will be two pointers that presents random values for User and Company

