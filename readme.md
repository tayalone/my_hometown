# Project

## Setup Step
// setup in package.json
1. npm init , npm install
2. npm install node-sass
3. เพิ่ม script ใน package.js ' "watch:sass": "node-sass sass/main.scss css/style.css -w" '

// setup index.html
1. link font จาก google
    <link href="https://fonts.googleapis.com/css?family=Kanit:100,300,400,700" rel="stylesheet">

// setup sass folder
    1.main.scss ทำหน้าที่ import อย่างเดียว @import "folder/filename.scss";
    2. abstracts folder 
        - _functions.scss
        - _mixins.scss
        - _variable.scss
    3. base folder
        - _animations.scss
        - _base.scss
        - _typograhy.scss
        - _utilities.scss
    4. components 
    5. layouts พวก header footer หรือ nav
        - _footer.scss
        - _header.scss
        _ _nav.scss 
        _ ...
    6. pages พวก section
        - _home.scss 
        - ...