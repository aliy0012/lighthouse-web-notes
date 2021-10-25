### Tips
***

tips here
___


```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if(!hungry){
    console.log('wait till you are hungry');
    return ;
  }
  if(availableTime <= 20){
    console.log("pick a sandvich and eat in front of the comp");
  }else if(availableTime > 20 && availableTime < 30){
    console.log('you deserve a break, hit the bar!');
  }else{
    console.log('you should eat and go back to studies');
  }
  
}
```