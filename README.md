# ScrimbaProjects

### What I have learnt from this project
- Debug Error
  - "TypeError: Cannot read properties of null (reading 'addEventListener')" when this error occurs, it means the when trying to call the addEventListener() method on a **DOM element that doesn't exist.**
  - here the mistake i made is that A is a class, but i get this element by id
- to display a block or hide a block use
```
a.style.display="none"
```
- modal css
  - by `position: absolute;` position the element above everything else
  -    make the overlay 100% height and 100% width so it fills the entire screen
  -    
```
.modal{
  background-color: white;
  margin: 0px auto;
  padding: 20px;
  max-width: 500px;
  height:150px;
  position: relative;
  top: 30%;
}
#overlay{ 
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  background-color: rgba(0, 0, 0, 0.3);
  border-radius: 7px;
}
}
```


