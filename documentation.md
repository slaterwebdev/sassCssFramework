A file to outline what classes are available to use for styling

//COLORS//
"primary": #326dee,
"secondary": #1ac886,
"error": #d32752,
"info": #f6c31c,
"blue": #1919e6,
"red": #e61919,
"yellow": #e6e619,
"green": #19e635,
"orange": #ffa600,
"purple": #9900ff,
"gray": #808080,
"black": black,
"white": white,

.text-COLOR (text color)
.text-#{$key}-hover (text color with hover effect)
.bg-COLOR (background color)
.b-COLOR (border color)
.navbar-COLOR (navbar background color)
//--------------//

//LAYOUT CLASSES//
-display
.d-none 
.d-inline 
.d-block 
.d-inline-block
.d-flex

-justify content
.justify-flex-start
.justify-flex-end
.justify-center
.justify-space-between
.justify-space-around

-align items
.align-flex-start
.align-center
.align-flex-end    

-text align
.text-left
.text-center
.text-right

-12 columns in grid system 
.container (centred container)
.row (flex container)

-COL must be within a row
-Each column will be 1/12th of breakpoint size
.col-(1 to 12) 
.col-(1 to 12)-xs 
.col-(1 to 12)-sm 
.col-(1 to 12)-md 
.col-(1 to 12)-lg 
.col-(1 to 12)-xl 

-breakpoint sizes
"xs" : 0px,
"sm" : 480px,
"md" : 720px,
"lg" : 960px,
"xl" : 1200px

-grid gaps
.g-0 
.g-1
.g-2 
.g-3  
//--------------//

//COMPONENTS
-navbar
.navbar
.navbar-COLOR 

-card
.card (small self contained inline card)
.card-title (prestyled card title)
.card-body (prestyled card body)

-button
.btn
.btn-COLOR
.btn-outlined-COLOR
//--------------//

//UTILITIES
-padding
.p-(0 to 4)
.pt-(0 to 4)
.pr-(0 to 4)
.pb-(0 to 4)
.pl-(0 to 4)

-margin
.m-(0 to 4)
.mt-(0 to 4)
.mr-(0 to 4)
.mb-(0 to 4)
.ml-(0 to 4)

-opacity
.o-10
.o-20
.o-30
.o-40
.o-50
.o-60
.o-70
.o-80
.o-90
.o-100

-border-rad
.br-xs
.br-sm
.br-md
.br-lg

-fonts
.font-sm
.font-md
.font-lg
.font-xl
.font-xxl
//--------------//