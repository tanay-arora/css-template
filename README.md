#  custom-ui-design

## How to use 

### to use the code provided

> clone all the files and place all the files in same directory.

### to change colors and other details

> use inline css for minor change, but for better results

  it is advised to edit in css file

### for editing css file in a proper way follow the instructions

#### 1. to edit text type, style , font-family and text decoration etc 

> just edit the css before media querries as it is responsible for 

> styling of full page.

#### 2. to edit font size, font-weight , line height , margin , 
#### padding or other sizing details etc

> edit the css file in media querries as it is responsible for

> responsivenes and sizing of text on different screen.


### to edit anything in mobile view 

> edit css under media querry.
```
@media all and (max-width:1000px){
}
```
> edit css under this media querry to get changes under moblie view

```
@media all and (max-width:1200px){
}
```
> change this for laptop and pcs screen 

```
@media all and (max-width:900px){
}
@media all and (max-width:800px){
}
@media all and (max-width:700px){
}
@media all and (max-width:600px){
}
@media all and (max-width:500px){
}
```

> edit these according to usage for lower screen sizes



```
@media all and (max-width:1300px){
}
@media all and (max-width:1250px){
}
```

> edit these for higher screen sizes.
