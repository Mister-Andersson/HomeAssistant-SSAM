# HomeAssistant-SSAM

## About SSAM
[SSAM](https://ssam.se/om-ssam/learn-more-about-waste-collection.html) (Southern Småland´s Waste and Environmental Services) is a regional company responsible for waste collection in the region of Kronoberg - established in 2019. The municipalities of Lessebo, Markaryd, Tingsryd, Växjö and Älmhult own the company in partnership. The partnership is built on cooperation which is necessary to reach our common goal to recycle more to decrease waste. For homeowners, someone who owns their own property (e.g. a house, not an apartment or a company building), this means a new system in form of two bins with four compartments for recycling materials at home. The thought behind this system is to make it easier for people to do the right thing for our resources and for our planet.

## Project goals
The main goal with this project is to get a notification the day before my waste bins are scheduled for emptying. It started with a python script made by a friend, originally made for the Homey IoT platform. I rewrote it to work with Home Assistant and used it for a couple of years. Then one day I decided to learn how to use the built in [RESTful Integration ](https://www.home-assistant.io/integrations/rest/) in Home Assistant and this is the result.

## Using the scripts
Before you can use the scripts you need to know your customer ID. You can retrieve this from [SSAMs](https://ssam.se/mitt-ssam/hamtdagar.html) website, just search for your adress. Replace YOUR_CUSTOMER_NO in configuration.yaml with your customer ID and you are good to go.
