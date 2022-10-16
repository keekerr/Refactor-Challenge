# Refactor-Challenge
## Table of Contents

* [Description](#description)
* [Code Examples](#code-examples)
* [Important links](#important-links)
* [Languages Used](#languages-used)
* [Questions](#questions)

## Description

The purpose of this project was to analyze index.html and style.css files to identify areas where the code either needed correction or consolidation. The intention of this projecct was to ensure that all code was inline with best practice standards without causeing any changes to the appearance of the deployed website. 

## Code Examples

These Code Examples show the type of changes made to the source code in order to remain in compliance with best practices.

Origional Code (HTML)
```js
<body>
    <div class="header">
        <h1>Hori<span class="seo">
```
Updates Made (HTML)
```js
<body>
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
```
Origional Code (CSS)
```js
.benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```
Updates Made (CSS)
```JS
.benefits {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

.benefits {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefits h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefits img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```
## Important Links
[GitHub Repository](https://github.com/keekerr/Refactor-Challenge)

[Deployed Application](https://keekerr.github.io/Refactor-Challenge/)
## Languages Used

![HTML Badge](https://th.bing.com/th/id/OIP._Ik4_2kbAUkc8WfirxFSLwHaHa?w=100&h=120&c=7&r=0&o=5&pid=1.7)
![CSS Badge](https://th.bing.com/th/id/OIP.bVCzXbidOak-TcOhmW0QTAHaHa?pid=ImgDet&w=100&h=120&c=7)
## Questions

If you have any questions regarding this project, please feel free to contact me at this email: keeley.s.sprouse@gmail.com

Other examples of projects I have worked on can be viewed on Github via this link: [keekerr](https://github.com/keekerr)