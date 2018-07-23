# Sass
Sass (Syntactically Awesome StyleSheets)


Commands:
=>  gem install sass 
=>  sass -v
=>  gem update sass
=>  gem install sass --pre
=>  gem uninstall sass
=>  cmd/ctrl + c // to stop
=>  sass --watch scss:css

Refactoring:
01: Break related sections out into partials.
02: Extract repeating patterns into extends / Placeholder selectors
03: Nest rules where it makes sense
04: Create variables for repetitive values
05: Convert repeating declaration groups into mixins


Process:
01. Breaking the Style Sheet into Partials
02. Importing Partials
03 Placeholder Selectors
04.Nesting Selectors
05. Creating Variables
06. Font Stack and Asset Variables
07. Reuse code with Mixins
08. Media Queries


When writing Sass rules:
01. @extend placeholders first
02. @include mixins
03. Add remaining declarations

To Change the outputs style:
=> By default Sass outputs the nested styles.

sass --watch scss:css --style expanded
sass --watch scss:css --style compressed
sass --watch scss:css --style compact

