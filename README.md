## Plant Beat 

The application aims to help the user to take better care of garden plants. 
This involves diagnosing the plant disease by capturing and analyzing an image of the affected plant. Frontend has been coded in React Native and backend using Flask and the database used is MongoDB.
<img src="/screenshots/home.jpeg" width="200" height="400">

### How to run:

#### Frontend
- Install expo on your system.
- install expo app on your android device
- open the cloned folder and navigate to frontend folder on the terminal and run `yarn add`
- Run `expo start` to start the frontend server
- Scan the QR code shown in the browser using the expo app on your device.
#### Backend
- Navigate to backend folder and run `npm install`
- Run `flask run` to start the backend server


### Features:
##### Check plant feature
- This allows us to either click a picture of the diseased plant using our phone's camera or lets us choose an image from our phone gallery. We can then save the image in the backend and analyze the image to get results
- The app also provides information about how one can cure the plant​
<img src="/screenshots/checkplant.jpeg" width="200" height="400"> <img src="/screenshots/checkplant_camera.jpeg" width="200" height="400"> <img src="/screenshots/checkplant_analyze.jpeg" width="200" height="400">


##### Gallery feature
- This feature shows us all the analyzed images and their analysis results​
<img src="/screenshots/gallery.jpeg" width="200" height="400">

##### Shops
- This feature lets us browse through what near-by nurseries have to offer.
<img src="/screenshots/shop_home.jpeg" width="200" height="400"> <img src="/screenshots/shops.jpeg" width="200" height="400">
