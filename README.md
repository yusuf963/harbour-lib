**Validate Password**<br>
Password matching expression. Password must be at least 6 characters, no more than 24 characters, and must include at least one upper case letter, one lower case letter, and one numeric digit. Symbols are optional e.g (/,%,-,.), this check methods returns true if the check passes or false in it didn't  
Matches (asD1 | asDF1234 | ASPgo123 | ASPgo123_%)<br>
**implament in your code is:**<br>
```validatePassword(password)``` 
**Validate Email**<br>
***Implemantation***
```validateEmail(password)``` 
this method returns true if the check passes or false in it didn't  
<br>
**y-shadow-box.js** <br>
A JavaScript library to style your box outter border with shadow.
 the box can be any HTML tag e.g img, div as logn as the tag has the class attribute 'shadowbox'

**How it Works**<br>
1- install the lib as npm dependency by running this on your terminal<br>
```npm install shadowbox```<br>
<br>
2- add the the class name ```class ="shadowbox"``` to the selected tag/tages, e.g..<br> 
```  <img src="https://picsum.photos/200/300" class="shadowbox" alt"logo"/>``` <br>
3-import the lib at the top of your js file <br>
```import {shadowbox} from 'y-shadow-box'```<br>
4-write this snipet in your code<br>

```
shadowbox({
    shadow_type: 'soft', //default
    shadow_color:'rgba(0,0,0,0.3)', //default or(add your own rgba value)
    padding: false, //default or (toggle to true to set 1em padding or specify your value)
    margin: false  // default or (toggle to true to set 1em margin or specify your value)
}) 
```
**acceptance value for shadowbox boject**
```
bool
string
```