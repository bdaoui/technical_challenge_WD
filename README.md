# technical_challenge_WD
Soufiane Bdaoui 

Technologies used: React, NodeJs, ExpressJS

Simple React OPA requesting data from an API running in express and NodeJS environment. 
Loading the page you will automatically send the first Get request to the server, getting a list of all images that will be displayed.

Clicking on a button inside a individual div, will request data for the particular item linked to it. 
This will activate the second get request, using params to transmit the id to the server and there using a filter function to get the relevant data.

A media query is being utilized to dispaly more appropriate fonts and image size on small screens. 
A loading message is being displayed during loading times of the Axios request. 
