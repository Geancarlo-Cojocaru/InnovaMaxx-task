# InnovaMaxx task

The template page is fully responsive (mobile, tablets, laptop, desktop) and it will be displayed identically in all modern browsers. The distribution files are located in the 'dist' folder and the development files can be found in the 'app' folder.

## Features

The page was built using Bootstrap 4.5.2 & Pug.js. The task runner used is Gulp/NPM. For lazy loading I used yall.js.

All images are placed in containers that makes sure that they will keep a proper aspect ratio. This means that we can use images with different aspect ratios (16:9, 21:9, 4:3, etc) and they will auto-adjust to cover the container. This is great when clients are using a CMS and dont have the time or expertise to adjust the images.

The font required for the test did not display correctly on my screen, so I built a second page for the test called "task_page_webfonts" in which I used a webfont hosted by Google (Roboto).

## Install

Clone the repository or just download the Zip archive. If you're only interested in the distribution files, just ignore the following steps as they require Node.js installed on your machine.

Open a terminal window in the folder in which you cloned/unzipped the repository and type 'npm install'. When finished you can launch the local server by typing in the terminal 'gulp watch'. Once started, you will be able to view the pages on mobile or other devices by typing the External access URL in mobile/device browser address bar. You will find the exact URL in the terminal window.