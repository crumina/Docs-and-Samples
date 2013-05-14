##### Wide layout for home page while other pages are boxed

`body.home .boxed_lay {max-width: 100%;}`

-----------------------------------------------------

##### To remove the background color from the current menu item

`#top-menu>ul>li.current-menu-item>.menu-item-wrap {background: transparent;}`
`#top-menu .current-menu-item > span .link-text {color:#575757;}`

----------------------------------------------

##### To get rid of the dates on the comments section

`.comment-author time {display:none;}`

------------------------------------

##### To get rid of the dates on all posts, widgets

`#layout article .dopinfo, #layout article time, #layout .small-news time, #layout .post-info, #layout .post time, #layout .post .row .columns time, article .dopinfo, article time {display:none !important;}`

`#layout .small-news .entry-summary, article .dopinfo, article .entry-title{margin-left:0}`

--------------------------------------------

##### To align mega menu

`#primary-navigation-1983 > ul {right:0}`

-----------------------------------------------------------

##### Remove "call to action button", leave text

`.al-right .button {display: none; }`

`.al-right { text-align: center; }`

-----------------------------------------------

##### Add the logo of any size

`#logo { width: auto; } `

--------------------------------------------

##### To remove the date buttons from all posts

`.post>time, .post>.row>.columns>time, article time {
display: none;
}`

--------------------------------------
