#####Remove fixed navigation bar

`.droped-navi.active {
display: none;
}`

----------------------------------------

#####Increase sidebar size, decrease content size

`aside#right-sidebar {padding:0;}`
`#main-content{padding-right:20px;}`

`aside#left-sidebar {padding:0;}`
`#main-content{padding-left:20px;}`

----------------------------------------

#####Bring the menu items closer together to allow more navigation (mor menu items)

`#header .menu>li {
width: auto;
margin-right: 30px;
}`

-----------------------------------------

#####Hide icon on posts page

`.icon-format {display: none;}`

------------------------------------------

#####Change color of the call to action button

`.to-action-block .action-button {
background-color: black;
}`

--------------------------------------------

#####Change the size of the menu icons

`.menu-item-wrap:before {
font-size: 34px;
}`

-------------------------------------------

#####Reduce the height of header navigation

`#header .menu>li {min-height: 45px;}
.menu>li>.menu-item-wrap {min-height: 30px;}`

----------------------------------------

#####Hide slider on mobile screen

`@media (max-width: 480px) { body.home .widget_crum_shortcode_widget {display:none} }`

-----------------------------------

#####Reduce height of footer

`#footer {
padding-top: 0;
}`

-----------------------------------

#####Make search bar displayed on one line with social icons on the top right corner

`#header .soc-head-icons {margin: 36px 70px 0 0; }`
`#searchsubmit {
top: 0;
}`

--------------------------------------

#####Change font size of phone information in header

`#header .phone { font-size: 20px; }`

----------------------------------------

#####Make stunning header background larger

`#stuning-header { height: 200px; } #page-title { margin: 40px 0 20px; }`

-----------------------------------------

#####Align menu to the right

`header .menu { width: 90%; float: right; }`

---------------------------------

#####Make the plus sign of the toggle not cut off

`h4.wpb_toggle {
padding-bottom: 10px;
}`

--------------------------------------

#####Turn off the portfolio date that it was posted

`time {
display: none;
}`

-----------------------------------------

#####Hide the "Previous Slide" and "Next Slide" in the tab/accordion

`.wpb_tour_next_prev_nav a {
display: none;
}`

-------------------------------------

#####Change icon color in "Box: Features Block"

`.feature-box.al-center .icon, .feature-box.al-left .icon, .feature-box.al-right .icon {color:green !important;}`

--------------------------------------

#####Change icon color in "Box: Features Block" on hover

`.feature-box.al-center:hover .icon, .feature-box.al-left:hover .icon, .feature-box.al-right:hover .icon {color:red !important;}`

-------------------------------

#####Change the color of the social icons

`.soc-head-icons a {color: red;
}`
`.soc-head-icons a:hover {color: green;
}`

-----------------------------------------

#####Center the logo and menu

`#logo {
float: none;
text-align: center;
}`

`#header .menu>li {
float: none;
text-align: center;
display: inline-block;
}`

----------------------------------------

#####Change the position of the Arrow Open Top Panel to the middel

`#open-top-panel {
left: 50%;
margin-left: -52px;
}`

-----------------------------------

#####Remove page title from all pages

`#page-title {display: none; }`

-----------------------------------

#####Remove title from a particular page

`.page-id-961 #page-title {display: none; }` /*Instead of the sample id, put id of your page*/

--------------------------------------

#####Make buttons "older" "newer" more visible

`.page-nav .older, .page-nav .newer {
color: #000000;
}`

-----------------------------------

#####Make catalogue/shop image to be in centre

`.prod-image-wrap {
width: 100%;
text-align: center;
min-width: 280px;}`

-------------------------------------

#####Hide social icons from the modal box

`.pp_social {display:none;}`

---------------------------------------

#####Part of the top panel becomes hidden behind the toolbar (also called the admin bar) and this cuts off the logo. This only happens on the BuddyPress pages.

`body.logged-in {
  padding-top: 30px;
}`

-------------------------------------

#####Change the hover color on language selector box

`.lang-sel ul>li:hover a {
    color: #fff;
    background-color: yellow;
}`

--------------------------------------

#####Make menu items clickable

`#header.horizontal #top-menu>ul>li>.menu-item-wrap>a {position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
padding-left: 54px;}`

--------------------------------

#####Change color of submenus

`#header .menu>li>ul {background-color: #E1E188;}`
`#header .menu>li>ul {border: none; box-shadow: none; -webkit-box-shadow: none; -moz-box-shadow: none; }`

----------------------------------------

##### Fixed menu fix (when you are logged in, your navigation panel hides half of the fixed menu)

`.logged-in .droped-navi.active {top: 27px !important;}`

--------------------------------------------------------------------
