#Custom CSS codes for One Touch

##### disable the menu for certain pages.

body.blog #topmenu {display:none;}

-------------------------------------------------

##### Change menu font (in tiles)

.tiled-menu>li>.menu-item-wrap>a {
color: #fff; /*Can change value*/
font-size: 12px; /*Can change value*/
}



.tiled-menu li ul li a {
font-size: 14px; /*Can change value*/
color: #4d4d4d; /*Can change value*/
}

-------------------------------------------------

#####Change background color of the facebook widget

.facebookInner iframe {background:#000 /* That value can be changed*/ }

-------------------------------------------------

#####Change the size of the main font

body, #content p, #content, #content div{
font-size: 16px; /*Value can be changed*/
}

-------------------------------------------------

#####Change the font size for Paragraph Titles

article header h2 {font-size:20px; /*Value can be changed*/}

-------------------------------------------------

#####Increase font size of titles within post content

content article .entry-content {
h1{font-size:3.5 em} /*Can be changed*/
h2{font-size:3 em} /*Can be changed*/
h3{font-size:2.5 em} /*Can be changed*/
h4{font-size:2 em} /*Can be changed*/
h5{font-size:1.5 em} /*Can be changed*/
h6{font-size:1.2em} /*Can be changed*/

}

-------------------------------------------------

#####Show all menu levels of the custom widget in sidebars

.widget ul.menu li ul, .widget ul.pagenav li ul{
    margin: 0;
    list-style: none;
}

.widget ul.menu li ul li, .widget ul.pagenav li ul li{
    padding-left: 20px;
    background-position: 3px 13px;
}

-------------------------------------------------

#####Change the background color of a section / row

.some-extra-class{background-color:#000 /*color can be edited*/}

-------------------------------------------------

#####remove the social section

#top-social {display:none}

-------------------------------------------------

#####Increase the size of logo

#header {position:relative} #header .logo {position:absolute; width: 565px;}

-------------------------------------------------

#####Change the default size and view of the map on the "Contact" page

#map {height: 300  px /*some other size*/}

-------------------------------------------------

#####Center the Home Page background

body.home #body-wrapper {background-position:center}

-------------------------------------------------

#####Keep the opacity/transparency of the “elements substrate color” in the “Main slider options” dialog

.scroll-box .item.odd .description { background-color: rgba(98,100,100,.87) !important}

.scroll-box .item.even .description {background-color: rgba(0,168,168,.87) !important}

-------------------------------------------------

#####“No scrolling” version

.no-scroll .item.odd .description { background-color: rgba(98,100,100,.87) !important}

.no-scroll .item.even .description {background-color: rgba(0,168,168,.87) !important}

-------------------------------------------------

#####Change the overlay colour for the postslider on the homepage

.wrap .item.odd .description { background-color: rgba(57,85,30,.87); }

.wrap .item.even .description { background-color: rgba(125,154,96,.87); }

--------------------------------------------------

#####A white line at the bottom of the page titles that goes through the back arrow

#paget-title h1.page-title {padding-bottom:40px}

--------------------------------------------------

#####remove the social icon bar

#top-social{display:none;}

--------------------------------------------------

#####Remove the “Next Slide” “Previous Slide” text from the TOUR SECTION shortcode in Visual Composer

.wpb_tour_next_prev_nav {display:none;}

--------------------------------------------------

#####change the size of the theme’s tiled category 

.tile.category {
width: 145px;
height: 145px;
}

---------------------------------------------------

#####Change post date background

article time {backgound:# some other color in hex}

---------------------------------------------------

#####decrease the height of the black background

#footer {
padding-top: 60px; /*Can be changed for other value*/
}

---------------------------------------------------

#####To make menu titles bigger

.tiled-menu > li > .menu-item-wrap {
width: 150px;
height: 150px;
}

--------------------------------------------------

#####to disable the date and author of the post on all posts

time {display:none;}

--------------------------------------------------

#####to disable breadcrumbs 

<div class="breadcrumbs"><?php if (function_exists('dimox_breadcrumbs')) dimox_breadcrumbs(); ?></div>

--------------------------------------------------

#####Widget icons

.info-item-alt .inner-text{
    background: url("../icons/pencil.png") 0 0 no-repeat;
}

.build-block-title{
    background: url("../icons/check.png") 0 0 no-repeat;
}

---------------------------------------------------

#####Change footer font color

#darkf, #darkf p {
color: #b8d2e3;
}

--------------------------------------------------

#####to change the font size, location, color of the main menu text

.tiled-menu > li > .menu-item-wrap > a {
position: absolute;
width: 100%;
height: 100%;
left: 0;
top: 0;
padding: 8px 13px;
color: white;
}

--------------------------------------------------

#####remove the google map at the contacts page

#map{display:none;}

-------------------------------------------------

#####To change background color of the exerpts

.team-brick .bg {
background: #F0F3F4;
}

-------------------------------------------------

#####to change the overlay color that shows when hovering over one of the post slider images

.wrap .item  .description {
    background-color: rgba(87,186,232,.87);
}

.wrap .item.even .description {
    background-color: rgba(108,190,66,.87);
}

-------------------------------------------------

#####to remove expanded panel (social icons) from template

#show-social {display:none}

-------------------------------------------------

#####scroll bar of post slider

.wrap { height: 545px;}
.wrap { margin-bottom: **px;}

------------------------------------------------

##### To remove promo icon

.promo{padding-left:0} 
.promo .icon {display:none;}

------------------------------------------------

##### To remove date, time on the posts at the main page

time {display:none !important;}

------------------------------------------------

#####
