# Color Changer Functionality

## working by clicking on buttons and links

```javascript
let buttons=document.querySelectorAll('.button')

let body=document.querySelector('body')

buttons.forEach(function(button){
    button.addEventListener('click',function(event){
        if(event.target.id==='grey'){
            body.style.backgroundColor=event.target.id
        }
        if(event.target.id==='white'){
            body.style.backgroundColor=event.target.id
        }
        if(event.target.id==='blue'){
            body.style.backgroundColor=event.target.id
        }
        if(event.target.id==='yellow'){
            body.style.backgroundColor=event.target.id
        }
        

    })
})

let links=document.querySelectorAll('a')

let nav=document.querySelector('.nav-bar')

links.forEach(function(link){
    link.addEventListener('click',function(event){
        if(event.target.id==='home'){
            nav.style.backgroundColor=event.target.id
        }
        if(event.target.id==='page'){
            nav.style.backgroundColor=event.target.id
        }
        

    })
})

```