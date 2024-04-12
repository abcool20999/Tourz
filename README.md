
<img width="545" alt="Screenshot 2024-04-13 at 00 50 31" src="https://github.com/abcool20999/Tourz/assets/126710132/393dd84e-ddc8-4aae-901c-b1e857c9f495">

The image above displays the command to start the project, which is `npm start`. The Node modules are not attached in this repo, but they can be installed through `npm install`. When you run `npm start`, it directs you to the homepage where you'll find a list of countries. Clicking on a country reveals a grid view of several tourist destinations. Further clicking on a particular destination redirects you to a page showing a picture of the place along with news about it.

I integrated two functioning APIs into this project:

1. [Google Places API](https://places.googleapis.com/v1/places:searchText): This API provides a list of countries to visit as tourist destinations.
2. [Rest Countries API](https://restcountries.com/v3.1/all): This API offers details and news about the place you choose to visit.

I attempted to integrate a third API to convert the cost of vacation into your local currency, but I couldn't implement it due to time constraints.

