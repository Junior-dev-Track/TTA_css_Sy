# TTA_css_Sy
Transition transform and animation

- CREATE a new directory with the terminal ( mkdir tta_css ).
- CREATE two files ( index.html and style.css ) in it ( touch index.html, touch style.css ).
/!\ Don't forget to make a link in the head of your html.
( <link rel="stylesheet" href="./style.css"> )

Let's go to create our first transition.

In the Html file we'll go to create a div,
put a <p> with a message like : "Hello there !" ( in english ) or "coucou les pioupiou's" (in french ) 

Like this : ```html
<div class="divpiou">
        <p class="pioupiou">Coucou les pioupiou's</p>
</div>
```
/!\ Look in the browser for see it's good.

So continous with the CSS now.

Use a reset (*{} ),
after that make the body background color in black and make css on your div.
```css
.pioupiou {
    font-family: Arial;
    font-size: 0.85rem;
    font-weight: bold;

}
.divpiou {
     display: inline-block;
     padding: 20px;
     margin: 100px;
     color: whitesmoke;
     border: 2px solid white;
}
```
/!\ Look in the browser for see it's good.

Let's go to the transition :D : 
Still in the Css file :
put the transition property

```css
  .divpiou {
     display: inline-block;
     padding: 20px;
     margin: 100px;
     color: whitesmoke;
     border: 2px solid white;
    transition: color 0.5s, background-color 0.5s;
}
```
(You can see, I put color for changing the color of the typo, and background-color it's for changing color of the background of the div ).

Still in the css files again : 
Create a selector with :hover ( Like this : .divpiou:hover {} ).
Make the color and the background-color what you want, me I choose black for the color and whitesmoke for the background-color ) 

/!\ Don't forget to save the project with CTRL -S and now go on your browser for see the result ! 







