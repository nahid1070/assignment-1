1st Prompt:

I have a website called - "Developer conference 2026". On homepage, this website has these sections: Hero( Code. Connect. Create ), Meet the Speakers, Secure Your Spot. In the website UI, there should be a relevant section on homepage after the "Secure Your Spot" section, but this section is missing on the UI. This website has these menu items "[Speakers, Schedule, Tracks, Venue, Blog](http://127.0.0.1:5500/index.html#). Generate a section using html and css(no framwork or css library) that is relevant to the website content. The section design should be minimal and elegant. Don't use dumy text to generate the design and code.
Primary Color:  
#1D4ED8


2nd Prompt
I have these global codes and also use the existing flexbox layout to build the columns and the design. Keep the design same that you generated a few minutes ago but use the website global code. Here is the global code:

/* Global CSS */
:root{
    --primary: #1D4ED8;
    --text: #333333;
    --bg: #fff;
    --gray: #f9f9f9;
    --white: #fff;
    --black: #1a1a1a;
    --menu: #575757;
    --border: #e5e7ebFF;
    --gray-text: #575757;
    --footer-bg: #0D1B2A;
    --gray-text-2: #888888;
    --Dark-blue: #0D1B2A;
    --light-blue: #60A5FA;
    --btn-hover: #0d1b2a;
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    color: var(--text);
    font-size: 1rem;
    line-height: 1.5;
    font-family: "Inter", sans-serif;
}
img{
    max-width: 100%;
    display: block;
}
a{
    font-family: "Inter", sans-serif;
    text-decoration: none;
}
p{
    color: var(--text);
    font-size: 1rem;
    line-height: 1.5;
    font-family: "Inter", sans-serif;
}
h1,h2,h3,h4,h5,h6{
    color: #0D1B2A;
    font-family: "Inter", sans-serif;
}
h2{
    font-size: 2.5rem;
    line-height: 1.3;
}

/* Flexbox Grid System */
.container{
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
}
.row{
    display: flex;
    flex-wrap: wrap;
    margin-left: -15px;
    margin-right: -15px;
}
[class*="col-"]{
    padding-left: 15px;
    padding-right: 15px;
}
.col-1{
    width: 8.333%;
}
.col-2{
    width: 16.666%;
}
.col-3{
    width: 25%;
}
.col-4{
    width: 33.333%;
}
.col-5{
    width: 41.666%;
}
.col-6{
    width: 50%;
}
.col-7{
    width: 58.333%;
}
.col-8{
    width: 66.666%;
}
.col-9{
    width: 75%;
}
.col-10{
    width: 83.333%;
}
.col-11{
    width: 91.666%;
}
.col-12{
    width: 100%;
}

/* Global Button */
.btn{
    font-family: "Inter", sans-serif;
    font-size: 1rem;
    font-weight: 500;
    color: var(--white);
    background: var(--primary);
    padding: 12px 30px;
    border: 1px solid var(--primary);
    border-radius: 8px;
    cursor: pointer;
    display: inline-block;
    text-align: center;
    transition: 0.3s ease-in-out;
}
.btn:hover{
    color: var(--white);
    background: var(--btn-hover);
    border-color: var(--btn-hover);
}
.btn-outline{
    color: var(--primary);
    background: transparent;
}

/* Global Card */
.card{
    border: 1px solid var(--border);
    border-radius: 10px;
}
.card .card-content{
    padding: 20px;
}
.card .image-box{
    overflow: hidden;
    border-radius: 10px 10px 0px 0px;
}
.card .image-box img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.card .card-content .card-top-title{
    color: var(--primary);
    font-size: 0.75rem;
    font-weight: 500;
    margin-bottom: 8px;
}
.card .card-content .card-title{
    font-size: 1.25rem;
    margin-bottom: 5px;
}
.card .card-subtitle{
    font-size: 0.875rem;
    color: var(--gray-text);
}
```
