# CampFinder
CampFinder is a website that helps users find and share information about the best campgrounds around the world.

<!-- ![camp-home](https://user-images.githubusercontent.com/100396329/183911961-c95091f6-6236-4e2c-a605-863a9c8aa5c0.png | width=50) -->
<img src="https://user-images.githubusercontent.com/100396329/183911961-c95091f6-6236-4e2c-a605-863a9c8aa5c0.png" width=600px>

## Tools Used

This project was created using JavaScript, Node.js, Express, MongoDB, and Bootstrap. <br>
Geocoding was done using Mapbox, while Passport.js was used to handle authentication. 

## Features

1. Users can register and log in their own accounts.
2. Users can create, edit, and delete campgrounds.
3. Users can create and delete rating and reviews for each campground.
4. Locate campgrounds using the interactive map

<img src="https://user-images.githubusercontent.com/100396329/183913771-adc04dcc-651c-4db9-ab3d-4e584d9983a2.png" width=600px>
<img src="https://user-images.githubusercontent.com/100396329/183913883-d6bd8a36-9403-4b5b-955e-a21129310f9b.png" width=600px>

## Run the project locally
1. Install mongodb
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/jgbattung/CampFinder.git
cd CampFinder/
npm install
```

Create a .env file in the root of the project and add the following:
```
DATABASEURL='<cloudinary-url>'
API_KEY=''<cloudinary-key>
API_SECRET='<cloudinary-secret-code>'
```

Run `mongod` and `mongo` in separate terminals. <br>
Run `node app.js` in the terminal inside the root folder of the project.

Open localhost:3000 on your browser.
<br>

###### This project was completed for the Web Developer Bootcamp 2022 Udemy Course

