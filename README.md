# counter

accessible on https://aliyazakirova.github.io/counter/ 

counter project has 3 buttons: increase, reset, decrease and value area.
As soon as the decrease button is clicked, the value decreases accordingly. Click on increase button increases the value and reset button resets the value back to 0.

I'm selecting all classes with queryselectorAll that have a generic selector btn instead of reaching each class one by one. And then I'm setting a forEach method and loop over, and then I'm writing conditions for decrease, increase and reset. I'm also adding a color representation for decrease - red, increase - green, reset - black.

key methods used:
document.querySelectorAll()
forEach()
addEventListener()
currentTarget property
classList
textContent

![Screenshot at Aug 04 10-19-15](https://user-images.githubusercontent.com/93845260/182787799-3dae754b-df33-43a1-bb5d-5688fd22a34d.png)
