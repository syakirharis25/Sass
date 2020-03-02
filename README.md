# Sass
My works related to Syntactically awesome style sheets (Sass) language.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Live Sass Compiler in Visual Studio Code.](#livesass)
4. [Hosting and view the Sass files live in GitHub.](#livegithub)
5. [Sass developers.](#developers)
6. [GitHub notes.](#github)
7. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="sass.svg" height="150"> 
Sass (short for syntactically awesome style sheets) is a style sheet language initially designed by Hampton Catlin and developed by Natalie Weizenbaum. After its initial versions, Weizenbaum and Chris Eppstein have continued to extend Sass with SassScript, a simple scripting language used in Sass files. <br /> <br />

Sass is a stylesheet language that’s compiled to CSS. It allows you to use variables, nested rules, mixins, functions, and more, all with a fully CSS-compatible syntax. Sass helps keep large stylesheets well-organized and makes it easy to share design within and across projects.  <br />

Sass is a preprocessor scripting language that is interpreted or compiled into Cascading Style Sheets (CSS). SassScript is the scripting language itself. Sass consists of two syntaxes. The original syntax, called "the indented syntax," uses a syntax similar to Haml. It uses indentation to separate code blocks and newline characters to separate rules. The newer syntax, "SCSS" (Sassy CSS), uses block formatting like that of CSS. It uses braces to denote code blocks and semicolons to separate lines within a block. The indented syntax and SCSS files are traditionally given the extensions .sass and .scss, respectively. <br />

CSS3 consists of a series of selectors and pseudo-selectors that group rules that apply to them. Sass (in the larger context of both syntaxes) extends CSS by providing several mechanisms available in more traditional programming languages, particularly object-oriented languages, but that are not available to CSS3 itself. When SassScript is interpreted, it creates blocks of CSS rules for various selectors as defined by the Sass file. The Sass interpreter translates SassScript into CSS. Alternatively, Sass can monitor the .sass or .scss file and translate it to an output .css file whenever the .sass or .scss file is saved. <br />

The indented syntax is a metalanguage. SCSS is a nested metalanguage, as valid CSS is valid SCSS with the same semantics. <br />

SassScript provides the following mechanisms: variables, nesting, mixins, and selector inheritance. <br />

<a name="references"></a>
## 2. Official references websites.
Official Sass website : https://sass-lang.com <br />
Official Sass documentation : https://sass-lang.com/documentation <br />

Font Awesome : https://fontawesome.com <br />
Stack Overflow question and answer official website : https://stackoverflow.com <br />

**_Sass Text Editor_** <br />
Visual Studio Code by Microsoft : https://code.visualstudio.com <br />

**_Sass Documentation_** <br />
sass:map by Sass : https://sass-lang.com/documentation/modules/map <br />
Interpolation by Sass : https://sass-lang.com/documentation/interpolation <br />
@import by Sass : https://sass-lang.com/documentation/at-rules/import <br />
Functions by Sass : https://sass-lang.com/documentation/values/functions <br />
@mixin and @include by Sass : https://sass-lang.com/documentation/at-rules/mixin <br />
@extend by Sass : https://sass-lang.com/documentation/at-rules/extend <br />
Special Functions by Sass : https://sass-lang.com/documentation/syntax/special-functions#calc-element-progid-and-expression <br />

**_Sass Articles_** <br />
Difference between .sass and .scss : https://responsivedesign.is/articles/difference-between-sass-and-scss <br />
The Sass Ampersand by CSS-TRICKS : https://css-tricks.com/the-sass-ampersand <br />
rem() is a Sass mixin that converts pixel values to rem values for whatever property is passed to it. : https://gist.github.com/bitmanic/1134548 <br />
EASY-PEASY REM CONVERSION WITH SASS by Stubbornella : http://www.stubbornella.org/content/2013/07/01/easy-peasy-rem-conversion-with-sass <br />
How to use & (Ampersand) to simplify your Sass by Sparkbox : https://seesparkbox.com/foundry/how_to_use_ampersands_to_simplifiy_your_sass <br />
Fun with Viewport Units by Miriam Suzanne : https://css-tricks.com/fun-viewport-units <br />
Using lighten() and darken() in SASS by https://falkus.co : https://falkus.co/2017/05/using-lighten-and-darken-in-sass/ <br />
SASS: @content directive is a wonderful thing by Krasimir Tsonev : https://krasimirtsonev.com/blog/article/SASS-content-directive-is-a-wonderful-thing <br />

**_Sass questions and answers by Stack Overflow_** <br />
:after and :before pseudo-element selectors in Sass [duplicate] by Stack Overflow : https://stackoverflow.com/questions/10750563/after-and-before-pseudo-element-selectors-in-sass <br />

<a name="livesass"></a>
## 3. Live Sass Compiler in Visual Studio Code.
To use Live Sass Compiler in Visual Studio Code, press **[ Ctrl ]** + **[ Shift ]** + **[ X ]** on your keyboard, then type `Live Sass Compiler` on the appeared text box under the EXTENSIONS: MARKETPLACE text on the left of the Visual Studio Code interface, then hit **[ Enter ]** on your key board and then hit the `Install` green box on the right side of the appeared `Live Sass Compiler` below it. Hit **[ Ctrl ]** + **[ , ]** on your keyboard to enter the Settings menu, type `sass` on the `Search settings` text box, under `Extensions`, click `Live Sass Compiler Configuration`, under `Live Sass Compile > Settings: Formats`, click on the `Edit in settings.json`, add the following codes into `settings.json` file.

```
"liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/dist/css"
        }
    ],
```

<a name="livegithub"></a>
## 4. Hosting and view the Sass files live in GitHub.
[ STEP 1 ]
From the GitHub menu, click on the `Settings` with gear icon on its left.

[ STEP 2 ]
Scroll down until you can see `GitHub Pages`, under the `Sources` section, from the drop down menu, click on it and select `master branch`. Then wait for GitHub to refresh the page until you can see the word `GitHub Pages source saved.`

[ STEP 3 ]
Scroll down until you see `GitHub Pages`, then you can see it is updated with the message

```
Your site is ready to be published at [address link of the website]
```

Then go the working Sass directory to see the result of the working Sass files.

The shown website link will show the contents of README.md file : https://syakirharis25.github.io/Sass/

The dist link will show the content of the working Sass files on GitHub : https://syakirharis25.github.io/Sass/code/dist/

<a name="developers"></a>
## 5. Sass developers.
Sass was designed by Hampton Catlin : https://github.com/hcatlin, https://twitter.com/hcatlin, http://hamptoncatlin.com <br />
Sass was developed by Natalie Weizenbaum : https://github.com/nex3 <br />
Krasimir Tsonev : https://github.com/krasimir <br />
Miriam Suzanne : https://github.com/mirisuzanne, https://twitter.com/MiriSuzanne <br />

<a name="github"></a>
## 6. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Sass.git
$ cd Sass/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 7. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
CSS                              2             66              2            497
Sass                             8             66              0            440
HTML                             4             34              0            373
Markdown                         2             24              0             86
JavaScript                       1              5              0             22
SVG                              1              0              0              1
-------------------------------------------------------------------------------
SUM:                            18            195              2           1419
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
