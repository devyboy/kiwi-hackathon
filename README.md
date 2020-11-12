# Plantae 🌱
**Plantae** is a web application that allows you to identify and learn about almost any plant you find.

# Gallery
<details>
  <summary>Click here to view the image gallery</summary>
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/title.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/landing-start.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/landing-middle.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/landing-end.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/id-start.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/id-end.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/search.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/plant-page.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/more-fields.png" />
  <img src="https://raw.githubusercontent.com/devyboy/plantae/master/screens/images.png" />
</details>

## Project Members
- Gideon : Backend & Data transformation
- Alexandra : Backend & Data transformation
- Devon : Frontend

## Quickstart
Head over to our [beta web deployment](https://plantae-1.web.app/) to check it the latest changes, or our [main website](https://mygreenery.space/) if we are fully live by the time you're reading this README.

## Overview
__Plantae__ is inspired by apps on the iOS App Store that claim to identify a plant based on taking a picture of it, but we wanted a tool for people who were into cultivating plants and already knew some limited information and simply wanted quick facts rather than rely on the accuracy of an automatic image matcher.

We also wanted to create a simple, consistent, and aesthetically pleasing application to compile and allow users quickly find basic information about certain plants. Generally a person would be relegated to reading the Wikipedia article or a bunch of dated plant journals from 2005 to get certain information but Plantae makes it much simpler.

Use cases for this application can range from a curious hiker who stumbled across some unknown flora to a seasoned gardener ready to take on a new challenge. Unfortunately, the data can sometimes be missing certain fields or be inconsistent, it is quite a large amount of information after all. If something doesn't make sense or seems incorrect, feel free to let us know.

## Challenges
Although all of our teammates had different working hours, we did our best and made do with what we had. There was a lot of data to manage and deal with, especially in terms of filtering and searching through it. All in all it was an amazing experience!

# Built With
Plantae is built with a Node.js, React, and Gatsby client-side tech stack, and the server is built with Python and Flask. We deployed continuous integration and continuous deployment to our servers with GitHub Actions and utilized automated testing using Pytest.

# Open Source Dependencies
- Trefle API
- antd
- rc-scroll-anim
- react-helmet
- react-tooltip
- react-simple-maps
- prettier

## Getting Started
You'll need the latest production deployment of Node.js and Python 3.7+ on installed and on your PATH. Then, to install the client:

```
npm install -g gatsby # Install Gatsby
cd client && npm install # Install Package Dependencies
gatsby develop # Run Local Client
```

Once you've done this, you'll be able to open your browser to port 8000 on localhost, or click this link to go there immediately.

For setting up the server:
```
cd server && pip install -r requirements.txt # Install Dependencies
flask run # Run Server
```

After the server is active (or before!) you'll want to set up a file called secrets.json in your server/config directory with the API key to Trefle.io.

## Legal
We are not professional botanists or toxicologists. Take any information displayed in this application with a grain of salt. The authors, any contributors, and any images or infographics used are not responsible if you hurt yourself or others. **Plantae** is primarily an educational resource and not a survival guide to edible plants. Just because this application states a plant is not toxic to eat does not mean you should eat it. Stay safe and use common sense.
