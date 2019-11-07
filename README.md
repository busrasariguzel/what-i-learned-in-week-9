# `What I Learned In Week 9`
 * cs-tricks

## `Flexbox`
```
#app {
display : flex;
flex-direction : column;
justify-content : space-around;
height : 800px;
width : 800px;
}
.square {
height : 100px;
width : 100px;
}
```
---
## `InstaBox` 
---


## `Copy Ocelot`
We did a project where we tried to copy a website using flexbox. 


----

## `Responsive Design`
Designing flexbox so that it adjusts to the screen size such as phone and Ipad.
We do media functions for that. 
```
@media (min-width :501px)and (max-width: 1024px){
  #app {
    flex-direction: column;
    /* height: 100%; */

}
#middle {
  flex-direction: column;  
  align-items: stretch;
  height: 60%
}
}

```
---