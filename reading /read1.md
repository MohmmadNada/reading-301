# Responsive Web Design (RWD)

## is the practice of building a website suitable to work on every device and every screen size

### Responsive vs. Adaptive vs. Mobile

Responsive generally means to react quickly and positively to any change,
adaptive means to be easily modified for a new purpose or situation
A combination of the two is ideal

1. Flexible Layouts : dynamically resizing to any width

Flexible Grid are built using relative length units,
take width and hieght as percantge(or em units) in css 30%, will create a completely dynamic website
new units : 
1. vw
Viewports width 
2. vh
Viewports height
3. vmin
Minimum of the viewport’s height and width
4. vmax
Maximum of the viewport’s height and width

> the best formula : 
> target ÷ context = result
> note : The flexible layout approach alone isn’t enough.

2. Media Queries
ability to specify different styles for individual browser and device circumstances

### use media queries
inside  existing style sheet
importing a new style sheet

> note :When a media feature and value allocate to true, the styles are applied. If the media feature and value allocate to false the styles are ignored.

#### Logical Operators in Media Queries
not ,and,  only 

> note : When using the not and only logical operators the media type may be left off. In this case the media type is defaulted to all.
     
    @media all and (min-width: 320px) and (max-width: 780px) {...}


3. Mobile First

For Viewport Height & Width

put html tag 
    <meta name="viewport" content="width=device-width">



# Float
to take the element out of the flow ,
Clear to put it in the bottom
options for clear :
* both
* Left 
* Right 
* None 

