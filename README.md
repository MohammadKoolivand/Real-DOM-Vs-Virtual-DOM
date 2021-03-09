# DOM Vs Virtual DOM

## Deffinitions

**DOM** is for **Document-Object-Model** is an application programming interface that helps to manipulate the project. In **DOM** project structures have a tree-like structure in which components are placing inside each other.  elements re-render after updating. here is the difference between **Real DOM** & **Virtual DOM**. in **Real DOM**, after updating an element, any child of it will re-render too, also in **Virtual DOM**, no need to change in any other elements. So in **Virtual DOM**, the exact element that has changed will re-renders and this makes Project much faster and reliable.

 **Virtual DOM** like :`React js & Vue Js`
 
**Real DOM** like :`Angular Js`

## Graphical deffinition
![dom](https://user-images.githubusercontent.com/48600357/110433327-8d272e80-80c5-11eb-8155-7eac90f235f4.png)

## Comparison between Real & Virtual DOM 




```js
import ReactDOM from 'react-dom'

document.getElementsByTagName('body')
ReactDOM.render(
  <ConfigProvider direction="rtl">
    <App />
  </ConfigProvider>,
  document.getElementById('root')
)
```
