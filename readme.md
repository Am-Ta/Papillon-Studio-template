# Papillon Studio Template
* I used the BEM as a naming convention standard for CSS class names.
    * BEM  —  Block Element Modifier is a methodology that helps you to create reusable components and code sharing in front-end development.
    * [Read More about BEM](http://getbem.com/)
___
* I used the Font Awesome(4.7.0) as the iconic font.
    * [complete set of icons](https://fontawesome.com/v4.7.0/icons/)
    * [CDN](https://www.bootstrapcdn.com/fontawesome/)
___
* [CSS Reset](https://meyerweb.com/eric/tools/css/reset/)
    * The goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, margins and font sizes of headings, and so on.
___
* I used the Dosis font for document webpage.
    * [Dosis](https://fonts.google.com/specimen/Dosis)
___
* Fix
    * margin-top and clear
        * ```css
            .clearfix:before,
            .clearfix:after {
                content: " ";
                display: table;
            }
            .clearfix:after {clear:both;}
          ```
    * box-sizing
        * ```css
            html {
                -webkit-box-sizing: border-box;
                -moz-box-sizing: border-box;
                box-sizing: border-box;
            }

            *,
            *:before,
            *:after {
                -webkit-box-sizing: border-box;
                -moz-box-sizing: border-box;
                box-sizing: border-box;
            }
          ```
___
* Color Schemes
    * base color : 150, 86, 2
    * accent color : 140, 2, 22
    * dark gray : 68, 62, 53
    * light gray : 250, 250, 249
    * white: 255, 255, 255
___
* Responsive and Mobile First design
    * Medium and up
        * ```css
            @media screen and (min-width: 40em) {}
          ```
    * Large and up
        * ```css
            @media screen and (min-width: 64em) {}
          ```
