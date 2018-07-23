# Sass
#Syntactically Awesome StyleSheets


**Commands:**
1. gem install sass 
2. sass -v
3. gem update sass
4. gem install sass --pre
5. gem uninstall sass
6. cmd/ctrl + c // to stop
7. sass --watch scss:css

**Refactoring:**
01. Break related sections out into partials.
02. Extract repeating patterns into extends / Placeholder selectors
03. Nest rules where it makes sense
04. Create variables for repetitive values
05. Convert repeating declaration groups into mixins


**Process:**
01. Breaking the Style Sheet into Partials
02. Importing Partials
03. Placeholder Selectors
04. Nesting Selectors
05. Creating Variables
06. Font Stack and Asset Variables
07. Reuse code with Mixins
08. Media Queries


**When writing Sass rules:**
01. @extend placeholders first
02. @include mixins
03. Add remaining declarations


**By default Sass outputs the nested styles.**
To Change the outputs style:

1. sass --watch scss:css --style expanded
2. sass --watch scss:css --style compressed
3. sass --watch scss:css --style compact

