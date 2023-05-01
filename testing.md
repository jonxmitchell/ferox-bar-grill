# Testing

In this file, you will see the documentation that I have put together throughout the time of creating this website. This will go over any errors that were encourted if any and also checking to ensure that the code valid by running it through code validators.

## Code Validation

This section will show how well the code has performed within code validators.

### HTML

I have decided to use the [W3C HTML Validator](https://validator.w3.org/) to check if my HTML code is valid. Please see the below table with the results.

| Page   | Screenshot | Notes |
| ------ |  ---------- | ----- |
| Home Page (index.html) | ![Home Page Test Screenshot](./assets/img/home-page-test.png) |  Passed |
| Menu Page (menu.html) | ![Menu Page Test Screenshot](./assets/img/menu-page-test.png) |  Passed |
| Gallery Page (gallery.html) | ![Gallery Page Test Screenshot](./assets/img/gallery-page-test.png) |  Passed |
| Book A Table Page (tablebooking.html) | ![Book A Table Page Test Screenshot](./assets/img/tablebooking-page-testing.png) |  Passed |
| Contact Page (contact.html) | ![Contact Page Test Screenshot](./assets/img/contact-page-testing.png) |  Passed |
| Response Page (response.html) | ![Response Page Test Screenshot](./assets/img/response-page-testing.png) |  Passed |

### CSS

I have decided to use the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator) to check if my CSS code is valid. Please see the below table with the results.

| File   | Screenshot | Notes |
| ------ |  ---------- | ----- |
| CSS File (style.css) | ![CSS File Test Screenshot](./assets/img/CSS-validatator.png) |  Passed |

## Browser Compatibility

Here I have chosen to test how the site works across 4 of the biggest browsers available. As I do not have access to a MacBook or a device that can run the latest version of Apple's Safari browser, I am unable to test the site on that browser. The site has been tested on Microsoft Edge, Google Chrome, Opera and Firefox.

![Browser Market Share](./assets/img/browser-market-share.png)

| Browser   | Screenshot | Notes |
| ------ |  ---------- | ----- |
| Microsoft Edge | ![Microsoft Edge Screenshot](./assets/img/microsoft-edge-test.png) |  Passed, no issues were found |
| FireFox | ![FireFox Screenshot](./assets/img/firefox-test.png) |  Passed, no issues were found |
| Chrome | ![Chrome Screenshot](./assets/img/chrome-test.png) |  Passed, no issues were found |
| Opera | ![Opera Screenshot](./assets/img/Opera-test.png) |  Passed, no issues were found |

## Accessibility Accessibility

Accessibility on the web is important to make sure we accommodate for everyone who tries to access our site to ensure they can have a smooth experience and get the information or action they need. To test the accessibility of the website, I have used [Web Accessibility Evaluation Tool (WAVE)](https://wave.webaim.org/).

| Page   | Screenshot | Notes |
| ------ |  ---------- | ----- |
| Home Page (index.html) | ![Home Pag Screenshot](./assets/img/homepage-access-test.png) |  Errors found, corrected the alt text on images, however, I contrast errors are not needed to be corrected, alerts can be ignored. |
| Menu (menu.html) | ![Menu Screenshot](./assets/img/menu-access-test.png) |  Errors found, fixed linking to same page in navbar links, blank links in footer can be ignored, alerts can be ignored. |
| Book A Table (tablebooking.html) | ![Book A Table Screenshot](./assets/img/tablebooking-access-test.png) |  Errors found, fixed linking to same page in navbar links, blank links in footer can be ignored as the text are icons with links to external sites, alerts can be ignored. |
| Gallery (gallery.html) | ![Gallery Screenshot](./assets/img/gallery-access-test.png) |  Errors found, fixed linking to same page in navbar links, blank links in footer can be ignored as the text are icons with links to external sites, alerts can be ignored. |
| Contact (contact.html) | ![Gallery Screenshot](./assets/img/contact-access-test.png) |  Errors found, fixed linking to same page in navbar links, blank links in footer can be ignored as the text are icons with links to external sites, alerts can be ignored. |
| Response (contact.html) | ![Response Screenshot](./assets/img/contact-access-test.png) |  Errors found, blank links in footer can be ignored as the text are icons with links to external sites, error with the redirect can be ignored as this is the purpose of the page is to redirect you after 5 seconds as soon as you join it, alerts can be ignored. |

## Lighthouse Analyzing  

I have used the Lighthouse feature within the Microsoft Edge browser to help get a good idea on the scoring of how the site performs on each page on mobile and desktop versions of the site.

| Page   | Screenshot | Format | Notes |
| ------ |  ---------- | ----- |----- |
| Home Page (index.html) | ![Home Page Screenshot](./assets/img/home-desktop-lighthouse-test.png) |  Desktop  |   Passed with an overall score of 95%  |
| Home Page (index.html) | ![Home Page Screenshot](./assets/img/home-mobile-lighthouse-test.png) |  Mobile  |   Scored an 82% due to the issue being with image sizes, this can be fixed by compressing images to be smaller in size to.  |
| Menu Page (menu.html) | ![Menu Page Screenshot](./assets/img/menu-desktop-lighthouse-test.png) |  Desktop  |   Passed  |
| Menu Page (menu.html) | ![Menu Page Screenshot](./assets/img/menu-mobile-lighthouse-test.png) |  Mobile  |   Passed  |
| Gallery Page (gallery.html) | ![Gallery Page Screenshot](./assets/img/gallery-desktop-lighthouse-test.png) |  Desktop  |   Passed  |
| Gallery Page (gallery.html) | ![Gallery Page Screenshot](./assets/img/gallery-mobile-lighthouse-test.png) |  Mobile  |   Scored 85% on performance due to the size in the image, these can be better optimized by compressing the images down to a smaller size.  |
| Book A Table Page (tablebooking.html) | ![Book A Table Page Screenshot](./assets/img/tablebooking-desktop-lighthouse-test.png) |  Desktop  | Passed  |
| Book A Table Page (tablebooking.html) | ![Book A Table Page Screenshot](./assets/img/tablebooking-mobile-lighthouse-test.png) |  Mobile  | Passed  |
| Contact Page (contact.html) | ![Contact Page Screenshot](./assets/img/contact-desktop-lighthouse-test.png) |  Desktop  | Passed, however best practices with scored 83% due to the google maps console logging errors from the embed. |
| Contact Page (contact.html) | ![Contact Page Screenshot](./assets/img/contact-mobile-lighthouse-test.png) |  Mobile  | Passed |

## Responsiveness

Below you will see the examples of how well the site performance on different device resolutions.

<details>
<summary> iPhone 12 Pro (Microsoft Edge Dev Tools)</summary>

![iPhone 12 Pro](./assets/img/homepage-responsive-test.png)

| Page | Result |
| --- | --- |
| Home | ✅ Passed |
| Menu | ✅ Passed |
| Gallery | ✅ Passed |
| Book A Table | ✅ Passed |
| Contact | ✅ Passed |
| Response | ✅ Passed|
</details>

<details>
<summary> Samsung Galaxy 8+ (Microsoft Edge Dev Tools)</summary>

![Samsung Galaxy 8+](./assets/img/homepage-responsive-samsunggalaxy-test.png)

| Page | Result |
| --- | --- |
| Home | ✅ Passed |
| Menu | ✅ Passed |
| Gallery | ✅ Passed |
| Book A Table | ✅ Passed |
| Contact | ✅ Passed |
| Response | ✅ Passed|
</details>

<details>
<summary> Samsung Galaxy 20 Ultra (Microsoft Edge Dev Tools)</summary>

![Samsung Galaxy 20 Ultra](./assets/img/homepage-responsive-samsunggalaxy20-test.png)

| Page | Result |
| --- | --- |
| Home | ✅ Passed |
| Menu | ✅ Passed |
| Gallery | ✅ Passed |
| Book A Table | ✅ Passed |
| Contact | ✅ Passed |
| Response | ✅ Passed|
</details>

<details>
<summary> iPad Air (Microsoft Edge Dev Tools)</summary>

![iPad Air](./assets/img/homepage-responsive-ipadair-test.png)

| Page | Result |
| --- | --- |
| Home | ✅ Passed |
| Menu | ✅ Passed |
| Gallery | ✅ Passed |
| Book A Table | ✅ Passed |
| Contact | ✅ Passed |
| Response | ✅ Passed|
</details>

<details>
<summary> Surface Pro 7 (Microsoft Edge Dev Tools)</summary>

![Surface Pro 7](./assets/img/homepage-responsive-surfacepro7-test.png)

| Page | Result |
| --- | --- |
| Home | ✅ Passed |
| Menu | ✅ Passed |
| Gallery | ✅ Passed |
| Book A Table | ✅ Passed |
| Contact | ✅ Passed |
| Response | ✅ Passed|
</details>

<details>
<summary> Surface Duo (Microsoft Edge Dev Tools)</summary>

![Surface Duo](./assets/img/homepage-responsive-surfaceduo-test.png)

| Page | Result |
| --- | --- |
| Home | ✅ Passed |
| Menu | ✅ Passed |
| Gallery | ✅ Passed |
| Book A Table | ✅ Passed |
| Contact | ✅ Passed |
| Response | ✅ Passed|
</details>

<details>
<summary> Samsung Galaxy A51/71 (Microsoft Edge Dev Tools)</summary>

![Samsung Galaxy A51/71](./assets/img/homepage-responsive-samsunggalaxya5171-test.png)

| Page | Result |
| --- | --- |
| Home | ✅ Passed |
| Menu | ✅ Passed |
| Gallery | ✅ Passed |
| Book A Table | ✅ Passed |
| Contact | ✅ Passed |
| Response | ✅ Passed|
</details>

<details>
<summary> Nest Hub Max (Microsoft Edge Dev Tools)</summary>

![Nest Hub Max](./assets/img/homepage-responsive-nesthubmax-test.png)

| Page | Result |
| --- | --- |
| Home | ✅ Passed |
| Menu | ✅ Passed |
| Gallery | ✅ Passed |
| Book A Table | ✅ Passed |
| Contact | ✅ Passed |
| Response | ✅ Passed|
</details>