# Sass
My works related to Syntactically awesome style sheets (Sass) style sheet language.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [Live Sass Compiler in Visual Studio Code.](#livesass)
4. [GitHub notes.](#github)

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

**_Sass Text Editor_** <br />
Visual Studio Code by Microsoft : https://code.visualstudio.com <br />

**_Sass Documentation_** <br />
sass:map by Sass : https://sass-lang.com/documentation/modules/map <br />
Interpolation by Sass : https://sass-lang.com/documentation/interpolation <br />

**_Sass Articles_** <br />
Difference between .sass and .scss : https://responsivedesign.is/articles/difference-between-sass-and-scss <br />
The Sass Ampersand by CSS-TRICKS : https://css-tricks.com/the-sass-ampersand <br />

**_Sass Developers_** <br />
Sass was designed by Hampton Catlin : https://github.com/hcatlin, https://twitter.com/hcatlin, http://hamptoncatlin.com <br />
Sass was developed by Natalie Weizenbaum : https://github.com/nex3 <br />

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

<a name="github"></a>
## 4. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/Sass.git
$ cd Sass/
$ git remote -v
$ git status
```
