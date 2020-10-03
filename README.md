# Let Get Started
  As a user of your mobile or web app, I want to personalize my experience by including profile picture 😎 but the picture I want to use is too large and does not focus the part I wanted or I want to remove some part of the image. 
It will be nice to use the app to crop the image to my taste! Right?

  Apart from the editting part, for better image experience, we might need images of a particular width and height ratio (📝 we call this **aspect ratio**) in our apps. 
In this article, we are going to implement a simple image cropping system in a React Application we will create. Great! Let's get started! 🚀.
  
# Project Structure
  Let's create our React projects with our command line.
```bash
npm init react-app reactimagecrop
```
After our **reactimagecrop** project is loaded, we are left with this nice structure.
* public
* src
  * app.js
  * app.css
  * index.js
  * index.css

We will also use a react image cropping component, **ReactCrop**. You could check out it's documentation here.
```bash
npm install ReactCrop
```
So this is how my package.json is
```
{
  name: reactimagecrop
}
```
