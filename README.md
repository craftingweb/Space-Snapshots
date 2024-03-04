# SpaceSnapshots

The [SpaceSnapshot](https://spacesnapshots.vercel.app/) is a web application that allows users to view and save images from NASA's Astronomy Picture of the Day (APOD) API. The application is built using HTML, CSS, and JavaScript, and it leverages the Fetch API to communicate with the NASA API.

## Key Features

- **View NASA Images:** Users can view images from NASA's APOD API. The application fetches the latest 10 images from the API and displays them in a grid format.

- **Save Favorites:** Users can save their favorite images by clicking the "Add to Favorites" button. The application stores the favorites in the browser's local storage, allowing users to access their saved images even after closing the browser.

- **Remove Favorites:** Users can remove images from their favorites by clicking the "Remove Favorites" button. The application updates the local storage and removes the image from the favorites list.

- **Responsive Design:** The application is designed to be responsive and works well on both desktop and mobile devices.

## How It Works

1. **Fetch NASA Images:** When the application loads, it fetches the latest 10 images from the NASA APOD API using the Fetch API. The images are stored in the `resultsArray` variable.

2. **Display Images:** The `createDOMNodes` function creates HTML elements for each image in the `resultsArray` and appends them to the `imagesContainer` element. Each image is displayed as a card with a title, image, and description.

3. **Save Favorites:** When a user clicks the "Add to Favorites" button, the `saveFavorite` function is called. This function checks if the image is already in the `favorites` object and adds it if it's not. It then updates the local storage and displays a confirmation message.

4. **Remove Favorites:** When a user clicks the "Remove Favorites" button, the `removeFavorite` function is called. This function removes the image from the `favorites` object, updates the local storage, and updates the DOM to reflect the change.

## Conclusion

The NASA Picture Viewer is a simple yet powerful web application that allows users to view and save images from NASA's APOD API. It demonstrates how to use the Fetch API to communicate with an external API, how to store data in the browser's local storage, and how to create a responsive user interface. The application is a great starting point for anyone interested in building web applications that interact with external APIs.

[cosmicCaptures.webm](https://github.com/VitaliPri/Space-Snapshots/assets/101225909/fe481dc4-6232-48eb-ac38-7e9b481ccc95)

