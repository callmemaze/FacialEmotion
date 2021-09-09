# FacialEmotion

Implementation of two facial emotion recognition (FER) with fastai and Keras. Both model uses CNN model. 

CNN is used by fastai cnn leaner and Conv2d is used in Keras model

I have taken google images of human expressions sad, happy, surprise, laugh and anger.
Open google image and run the script

```javascript
urls=Array.from(document.querySelectorAll('.rg_i')).map(el=> el.hasAttribute('data-src')?el.getAttribute('data-src'):el.getAttribute('data-iurl'));
window.open('data:text/csv;charset=utf-8,' + escape(urls.join('\n')));
```
The model can identify sad, happy, surprise, laugh and anger.  

I have used google colab and mounted my drive so all the path are related to me.
