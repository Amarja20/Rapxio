# Rapxio UI React 

Welcome to Rapixo, where navigating the vibrant world of rap culture NFTs has never been easier or more enjoyable. Our React-based application is designed with you, the user, in mind, offering a seamless and intuitive experience from start to finish.

At Rapixo, we understand that exploring and collecting NFTs should be a breeze, which is why we've prioritized user-friendliness at every step of the way. With our clean and intuitive interface, you can effortlessly browse through our curated collection of rap culture-inspired NFTs, discover new gems, and add them to your collection with just a few clicks.

Powered by React, Rapixo offers lightning-fast performance and responsiveness, ensuring that you can explore our platform effortlessly on any device, whether you're at home or on the go. From sleek navigation menus to immersive visuals, every aspect of Rapixo is designed to enhance your experience and make your journey through the world of rap culture NFTs a memorable one.

### React Hooks support

Rapixo is built on top of Bootstrap 4 using React and Reactstrap, so it fully supports React Hooks.


### Bootstrap 4 support

Rapixo React is built on top of Bootstrap 4 using React, React Hooks, create-react-app and Reactstrap. This makes starting a new project very simple. It also provides benefits if you are already working on a Bootstrap 4, React or Reactstrap project; you can just import the Now UI Kit React style over it. Most of the elements have been redesigned; but if you are using an element we have not touched, it will fall back to the Bootstrap default.


## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Versions

| HTML | Angular | React | Vue |
| --- | --- | --- | --- |
| [![Now UI Kit HTML](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/now-ui-kit/opt_nuk_thumbnail.jpg)](https://www.creative-tim.com/product/now-ui-kit?ref=nukr-github-readme)  | [![Now UI Kit Angular](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/now-ui-kit-angular/opt_nuk_angular_thumbnail.jpg)](https://www.creative-tim.com/product/now-ui-kit-angular?ref=nukr-github-readme)  | [![Now UI Kit React](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/now-ui-kit-react/opt_nuk_react_thumbnail.jpg)](https://www.creative-tim.com/product/now-ui-kit-react?ref=nukr-github-readme)  | [![Vue Now UI Kit](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/vue-now-ui-kit/vue-now-ui-kit.jpg)](https://www.creative-tim.com/product/now-ui-kit-react?ref=nukr-github-readme)  

| Login Page | Landing Page | Profile Page  |
| --- | --- | ---  |
| [![Login Page](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/now-ui-kit-react/login.png)](https://demos.creative-tim.com/now-ui-kit-react/#/login-page?ref=nukr-github-readme)  | [![Landing Page](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/now-ui-kit-react/landing.png)](https://demos.creative-tim.com/now-ui-kit-react/#/landing-page?ref=nukr-github-readme)  | [![Profile Page](https://raw.githubusercontent.com/creativetimofficial/public-assets/master/now-ui-kit-react/profile.png)](https://demos.creative-tim.com/now-ui-kit-react/#/profile-page?ref=nukr-github-readme)  

[View More](https://demos.creative-tim.com/now-ui-kit-react/#/index?ref=nukr-github-readme)

## Quick start

1.  Download the project's zip
2.  Make sure you have node.js (<https://nodejs.org/en/?ref=creativetim>) installed
3.  Type `npm install` in terminal/console in the source folder where `package.json` is located
4.  You will find all the branding colors inside `src/assets/scss/now-ui-kit/_variables.scss`. You can change them with a `HEX` value or with other predefined variables.
5.  Run in terminal `npm start`.

## Documentation
The documentation for the Rapixo React is hosted at our [website](https://demos.creative-tim.com/now-ui-kit-react/#/documentation/introduction?ref=nukr-github-readme).


## File Structure

Within the download you'll find the following directories and files:
```
now-ui-kit-react
.
├── CHANGELOG.md
├── LICENSE.md
├── README.md
├── jsconfig.json
├── package.json
├── public
│   ├── index.html
│   └── manifest.json
└── src
    ├── assets
    │   ├── css
    │   ├── demo
    │   ├── fonts
    │   ├── img
    │   │   ├── flags
    │   │   └── nucleo-logo.svg
    │   └── scss
    │       ├── now-ui-kit
    │       │   ├── cards
    │       │   ├── mixins
    │       │   └── plugins
    │       ├── react
    │       │   ├── now-ui-kit
    │       │   ├── plugins
    │       │   └── react-differences.scss
    │       └── now-ui-kit.scss
    ├── components
    │   ├── Footers
    │   │   ├── DarkFooter.js
    │   │   ├── DefaultFooter.js
    │   │   └── TransparentFooter.js
    │   ├── Headers
    │   │   ├── IndexHeader.js
    │   │   ├── LandingPageHeader.js
    │   │   └── ProfilePageHeader.js
    │   └── Navbars
    │       ├── ExamplesNavbar.js
    │       └── IndexNavbar.js
    ├── index.js
    └── views
        ├── Index.js
        ├── NucleoIcons.js
        ├── examples
        │   ├── LandingPage.js
        │   ├── LoginPage.js
        │   └── ProfilePage.js
        └── index-sections
            ├── BasicElements.js
            ├── Carousel.js
            ├── CompleteExamples.js
            ├── Download.js
            ├── Examples.js
            ├── Images.js
            ├── Javascript.js
            ├── Navbars.js
            ├── Notifications.js
            ├── NucleoIcons.js
            ├── Pagination.js
            ├── SignUp.js
            ├── Tabs.js
            └── Typography.js
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/chrome-logo.png?raw=true" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/firefox-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/edge-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/safari-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/opera-logo.png" width="64" height="64">


## Resources
- Demo: <http://demos.creative-tim.com/now-ui-kit-react/#/index?ref=nukr-github-readme>
- Download Page: <https://www.creative-tim.com/product/now-ui-kit-react?ref=nukr-github-readme>
- Documentation: <https://demos.creative-tim.com/now-ui-kit-react/#/documentation/introduction?ref=nukr-github-readme>
- License Agreement: <https://www.creative-tim.com/license?ref=nukr-github-readme>
- Support: <https://www.creative-tim.com/contact-us?ref=nukr-github-readme>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/now-ui-kit-react/issues?ref=creativetim)


### Social Media

Twitter: <https://twitter.com/CreativeTim?ref=creativetim>

Facebook: <https://www.facebook.com/CreativeTim?ref=creativetim>

Dribbble: <https://dribbble.com/creativetim?ref=creativetim>

Instagram: <https://www.instagram.com/CreativeTimOfficial?ref=creativetim>
