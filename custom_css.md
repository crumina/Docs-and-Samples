#Custom CSS codes for One Touch

##### disable the menu for certain pages.

`body.blog #topmenu {display:none;}`

-------------------------------------------------

##### Change menu font (in tiles)

`.tiled-menu>li>.menu-item-wrap>a {
color: #fff; /*Can change value*/
font-size: 12px; /*Can change value*/
}`



`.tiled-menu li ul li a {
font-size: 14px; /*Can change value*/
color: #4d4d4d; /*Can change value*/
}`

-------------------------------------------------

#####Change background color of the facebook widget

`.facebookInner iframe {background:#000 /* That value can be changed*/ }`

-------------------------------------------------

#####Change the size of the main font

`body, #content p, #content, #content div{
font-size: 16px; /*Value can be changed*/
}`

-------------------------------------------------

#####Change the font size for Paragraph Titles

`article header h2 {font-size:20px; /*Value can be changed*/}`

-------------------------------------------------

#####Increase font size of titles within post content

`#content article .entry-content h1{font-size:3.5 em} `
`#content article .entry-content h2{font-size:3 em}`
`#content article .entry-content h3{font-size:2.5 em}`
`#content article .entry-content h4{font-size:2 em}`
`#content article .entry-content h5{font-size:1.5 em}`
`#content article .entry-content h6{font-size:1.2em}`

-------------------------------------------------

#####Show all menu levels of the custom widget in sidebars

`.widget ul.menu li ul, .widget ul.pagenav li ul{
    margin: 0;
    list-style: none;
}`

`.widget ul.menu li ul li, .widget ul.pagenav li ul li{
    padding-left: 20px;
    background-position: 3px 13px;
}`

-------------------------------------------------

#####Change the background color of a section / row

`.some-extra-class{background-color:#000 /*color can be edited*/}`

-------------------------------------------------

#####remove the social section

`#top-social {display:none}`

-------------------------------------------------

#####Increase the size of logo

`#header {position:relative} #header .logo {position:absolute; width: 565px;}`

-------------------------------------------------

#####Change the default size and view of the map on the "Contact" page

`#map {height: 300  px /*some other size*/}`

-------------------------------------------------

#####Center the Home Page background

`body.home #body-wrapper {background-position:center}`

-------------------------------------------------

#####Keep the opacity/transparency of the “elements substrate color” in the “Main slider options” dialog

`.scroll-box .item.odd .description { background-color: rgba(98,100,100,.87) !important}`

`.scroll-box .item.even .description {background-color: rgba(0,168,168,.87) !important}`

-------------------------------------------------

#####“No scrolling” version

`.no-scroll .item.odd .description { background-color: rgba(98,100,100,.87) !important}`

`.no-scroll .item.even .description {background-color: rgba(0,168,168,.87) !important}`

-------------------------------------------------

#####Change the overlay colour for the postslider on the homepage

`.wrap .item.odd .description { background-color: rgba(57,85,30,.87); }`

`.wrap .item.even .description { background-color: rgba(125,154,96,.87); }`

--------------------------------------------------

#####A white line at the bottom of the page titles that goes through the back arrow

`#paget-title h1.page-title {padding-bottom:40px}`

--------------------------------------------------

#####remove the social icon bar

`#top-social{display:none;}`

--------------------------------------------------

#####Remove the “Next Slide” “Previous Slide” text from the TOUR SECTION shortcode in Visual Composer

`.wpb_tour_next_prev_nav {display:none;}`

--------------------------------------------------

#####change the size of the theme’s tiled category 

`.tile.category {
width: 145px;
height: 145px;
}`

---------------------------------------------------

#####Change post date background

`article time {backgound:# some other color in hex}`

---------------------------------------------------

#####decrease the height of the black background

`#footer {
padding-top: 60px; /*Can be changed for other value*/
}`

---------------------------------------------------

#####To make menu titles bigger

`.tiled-menu > li > .menu-item-wrap {
width: 150px;
height: 150px;
}`

--------------------------------------------------

#####to disable the date and author of the post on all posts

`time {display:none;}`

--------------------------------------------------

#####to disable breadcrumbs 

`<div class="breadcrumbs"><?php if (function_exists('dimox_breadcrumbs')) dimox_breadcrumbs(); ?></div>`

--------------------------------------------------

#####Widget icons

`.info-item-alt .inner-text{
    background: url("../icons/pencil.png") 0 0 no-repeat;
}`

`.build-block-title{
    background: url("../icons/check.png") 0 0 no-repeat;
}`

---------------------------------------------------

#####Change footer font color

`#darkf, #darkf p {
color: #b8d2e3;
}`

--------------------------------------------------

#####to change the font size, location, color of the main menu text

`.tiled-menu > li > .menu-item-wrap > a {
position: absolute;
width: 100%;
height: 100%;
left: 0;
top: 0;
padding: 8px 13px;
color: white;
}`

--------------------------------------------------

#####remove the google map at the contacts page

`#map{display:none;}`

-------------------------------------------------

#####To change background color of the exerpts

`.team-brick .bg {
background: #F0F3F4;
}`

-------------------------------------------------

#####to change the overlay color that shows when hovering over one of the post slider images

`.wrap .item  .description {
    background-color: rgba(87,186,232,.87);
}`

`.wrap .item.even .description {
    background-color: rgba(108,190,66,.87);
}`

-------------------------------------------------

#####to remove expanded panel (social icons) from template

`#show-social {display:none}`

-------------------------------------------------

#####scroll bar of post slider

`.wrap { height: 545px;}`
`.wrap { margin-bottom: **px;}`

------------------------------------------------

##### To remove promo icon

`.promo{padding-left:0}` 
`.promo .icon {display:none;}`

------------------------------------------------

##### To remove date, time on the posts at the main page

`time {display:none !important;}`

------------------------------------------------

##### To hide date on portfolio items but keep the date on blog items

`.description time {display:none}`

-------------------------------------------------

##### Bottom address to be aligned with the address icon

`.adress-icon p {position: relative;}`

-------------------------------------------------

##### To change category tile colors and/or icon

`style="background: #90a7b1" <?php } else { ?> style="background: #57bae8"`

-------------------------------------------------

##### To remove the border from the .text-block class

`.text-block {border:none !important;}`

-------------------------------------------------

##### To make more space for logo

`#header .logo {width: 30%;}`
`#topmenu { width: 68%; }`

-------------------------------------------------

##### To move the menu boxes to the right

`#topmenu .tiled-menu {float:right}`

-------------------------------------------------

##### To move social icons to the bottom

`#top-social {position: relative;
top: 60px;
z-index: 100;}`

---------------------------------------------------

##### To remove socials icons

`#top-social {display:none}`

--------------------------------------------------

##### To align text in the menu to the right

`.tiled-menu > li > .menu-item-wrap {
text-align: right;
}`

----------------------------------------------------

##### To change the background colour and font colour of the sidebar on the single posts

`#right-sidebar {
background: # 000 /*Can be changed*/
color: red /*Can be changed*/
}`

##### To hide popup information box

`.item .description {
display:none;
}`

-------------------------------------------------

##### To make the tiles text font bigger

`#content .text-big-left {font-size: 24px;}`

-------------------------------------------------

##### To decrease the padding (top & bottom) of an info row

`.aq-block-aq_info_row_block {margin:5px 0}`

--------------------------------------------------

#####To remove the icons to all widget

`.widget {background:none !important}`

---------------------------------------------------

#####To make the title of widget nearer to the text of widget

`aside .widget h3 {
padding-left: 0;
margin-bottom: 10px; /*Can be changed*/
}`

----------------------------------------------------

#####To change the icon in block "Recent works"

`.icon.recent {
background: url("../icons/recent.png") right bottom no-repeat;
}`

----------------------------------------------------

#####To change "Color of recent works hover" 

`.works-list .item .description {
background: rgba(87,186,232,.87);
}`

-----------------------------------------------------

#####To remove the menu from home page 

`body.home #topmenu {display:none}`

-------------------------------------------------------

#####To change the color and size of the submenu

`.tiled-menu.drop li.menu-portfolio ul {
max-width:250px; /*or your value*/
}`

----------------------------------------------------

##### To delete the page title and links on posts

`#page-title {
display: none;
}`

--------------------------------------------------

#####To change excerpt length

`function custom_excerpt_length( $length ) {
    return 20;
}
add_filter( 'excerpt_length', 'custom_excerpt_length', 999 );`

-----------------------------------------------------------------

##### To delete all date mentions on pages or posts

`time, article time {display:none;}
article header {margin-left:0}`

-----------------------------------------------------------------

#####To stop zooming of the featured images

`.portfolio-item:hover img, .item:hover img {
-moz-transform: none;
-webkit-transform: none;
-o-transform: none;
-ms-transform: none;
transform: none;
}`

-----------------------------------------------------------------

##### To change width of the site

`.row {
width: 1100px;
}`

-------------------------------------------------------------------

##### To change color and size of submenus

`.tiled-menu.drop li.menu-portfolio ul {
max-width:250px; /*or your value*/
}`

--------------------------------------------------------------------

##### To align your footer elements

`.adress-icon { margin-top: 20px; }`

--------------------------------------------------------------

#####To remove date on the pages with grid posts

`#grid-posts article header {margin-left: 0;}`

-----------------------------------------------------------------------

##### To change font size of Info Row

`.aq-block-aq_info_row_block h2 {
color: red;
font-size:50px;
}`

---------------------------------------------------------------

##### To change colour of a scrollbar

`#ascrail2000-hr>div {background:red !important}`

----------------------------------------------------------

##### To remove the date of the post in the slideshow

`time, article time {display:none;}
article header {margin-left:0}`

----------------------------------------------------------------------

##### To align pictures of different size in slider

`.wrap .item>img {min-height:240px;}`

-----------------------------------------------------------------

##### To reduce height of the footer

`#footer {padding-top:0}`

-------------------------------------------------------------------------

##### To change the type of hover box appearing (fade in and out on hovering)

`.item .description.disp {
top: 0;
opacity: 0;
}
 
.item:hover .description.disp {
top: 0;
opacity: 1;
}`

--------------------------------------------------------------------------

##### To change colour of submenu on hovering

`.tiled-menu.drop ul li:hover { background:red !important; }`

------------------------------------------------------------------------------------

##### To remove the icons appearing when using a widget

`.widget {background:none !important}`

------------------------------------------------------------------------------

##### To make the title of widgets a bit near to the text/content of the widgets 

`aside .widget h3 { padding-left: 0; margin-bottom: 10px; /*Can be changed*/ }`

-----------------------------------------------------------------------------

##### To remove time and date from all posts

`.entry-date, time {display:none !important;}`

---------------------------------------------------------

##### To disable date under the images on page

`.folio-info time {display:none;}`

--------------------------------------------------------

##### To decrease the height of the map

`#map {height: 300px;} `

--------------------------------------------------------------

#####to remove the automatic text from the menu tiles

`.tiled-menu>li>.menu-item-wrap>a { text-indent:-999em}`

`.tiled-menu>li>.menu-item-wrap .link-text{display:none;}`

-----------------------------------------------------------------------

##### To align images in sortable portfolio 

`.sort-panel ul {height:30px}`

------------------------------------------------------------------------------------------

##### To align "Send message" Button

`#widget_feedback  .button {
margin-right:6px;
}`

-------------------------------------------------------------------

##### To remove titles from menu items

`.menu-item-wrap .link-text {text-indent:-100em;}`

----------------------------------------------------------------

##### To adjust size of embed video

`object, embed {
height: 400px;
}`

---------------------------------------------------------------------

##### To decrease space between widgets in the sidebar

`aside .widget {
margin-bottom: 15px;
padding-bottom: 15px;
}`

---------------------------------------------------------------------

##### To align video on the page

`.wpb_video_widget .wpb_wrapper .wpb_video_wrapper {
padding-top: 0 !important;
}`

------------------------------------------------------------------

##### To remove a slim line in the drop down menus

`.tiled-menu.drop li ul li {
float: none;
}`

-----------------------------------------------------------

##### To remove gap between the columns in pricing tables

`[class*="column"]+[class*="column"]:last-child {
    float: left;
}`

---------------------------------------------------------------------------

##### To remove "Call to action" button from the page

`.call-to .button {display:none}`

-----------------------------------------------------------------------

##### To change font size in info block

`.aq-block-aq_info_row_block {min-height:80px}`

-----------------------------------------------------------

