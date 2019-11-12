# `What I Learned In Week 9`


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
* We used flexbox to make instagram's official page.This was the first project we did using flexbox and it was very helpful for me. 

```
#sub-div-2 {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding-left: 100px;
    padding-right: 100px;
    /* width: 1200px;
    height: 100px; */
    padding-top: 55px
}


.Highlights {
    text-align: center;
    /* width: 70px; */
    /* height: 100px; */
}
```

---


## `Copy Ocelot`
* We did a project in which we tried to copy a website using flexbox. I liked this project because it helped me to learn some flexbox tools.
* Some of the code I have for this project is :
```
#main-1 {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    border-bottom:  rgb(187, 184, 184) solid 0.6px;
    height: 70px;
    color: #3e4348;
    font-family: Arial, Helvetica, sans-serif;
    font-size:12px;
    font-weight:550;
    height : 65px
}

#main-2{
    display: flex;
    flex-direction: row;
    font-size: 44px;
    justify-content: center;
    align-content: space-between;
    /* align-items: center; */
    font-family: Helvetica, Arial;
    color: #3e4348;
    height: 70%;
    /* font-weight:590; */
}
```

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

## `Flexbox Portfolio`
We used our html portfolio and added flexbox to improve our portfolios. We had to adjust our portfolios to Iphone and Ipad layouts. Doing this project helped me to practice responsive methods. Some of the codes I used for my portfolio include:

```
#portfolio {
display: flex;
flex-direction: column;
}

#main-1 {
display: flex;
flex-direction: row;
justify-content: space-between;
border-bottom: solid grey 2px;
}
```

---