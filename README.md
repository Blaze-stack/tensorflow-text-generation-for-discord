# tensorflow-text-generation-for-discord

this is a simple tensorflow model for text generation, i recommend using [google colab](https://colab.research.google.com/)

if you do use colab put the following in the web console to keep it from timing out:
```js
function ClickConnect(){
  console.log("Connnect Clicked - Start"); 
  document.querySelector("#top-toolbar > colab-connect-button").shadowRoot.querySelector("#connect").click();
  console.log("Connnect Clicked - End"); 
};
setInterval(ClickConnect, 60000)
```
## taining data

when making the file for your training file use a formate like the following 
```
blaze: hello world
edie: hello there

blaze: how are you doing?
edie: i'm doing great how are you?

blaze: i'm just fine thank you
edie: i'm glad to hear that
```

## what will be added to the repo soon?

- pre formed training data
- better models 


### thank you for all the support
