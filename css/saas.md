# SASS - Syntacticly Awesome Style Sheets
## SCSS - Sassy CSS

* & - apply to parent
```
.notecard{
  &:hover{ };
```
* @mixin ---> @include
  * arguments (value) i.e. ($vivibility)
  ```
  @mixin backface-visibility($visibility: hidden) {
   backface-visibility: $visibility;
  -webkit-backface-visibility: $visibility;
  -moz-backface-visibility: $visibility;
  -ms-backface-visibility: $visibility;
  -o-backface-visibility: $visibility;}
  ```
1. Mixins can take multiple arguments.
2. Sass allows you to explicitly define each argument in your @include statement.
3. When values are explicitly specified you can send them out of order.
4. If a mixin definition has a combination of arguments with and without a default value, you should define the ones with no default value first.
5. Mixins can be nested.

* list arguments / map - allows you to pass in multiple arguments in a list or a map format.
```
$college-ruled-style: ( 
    direction: to bottom,
    width-percent: 15%,
    stripe-color: blue,
    stripe-background: white
);

.definition {
      width: 100%;
      height: 100%;
      @include stripes($college-ruled-style...);
 }
```
* string interpolation { } - process of placing a variable string in the middle of two other strings.
  * handy when you want to make use of variables in selectors or file names
```
@mixin photo-content($file) {
  content: url(#{$file}.jpg); //string interpolation
  object-fit: cover;
}

//....

.photo { 
  @include photo-content('titanosaur');
  width: 60%;
  margin: 0px auto; 
  }
```
