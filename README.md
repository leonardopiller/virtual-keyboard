# virtual-keyboard
A virtual keyboard using Vanilla JS and DOM manipulation was created.

First of all, an object called Keyboard was created with its attributes.

![image](https://github.com/leonardopiller/virtual-keyboard/assets/121625024/89c6f63b-cd07-46b9-a620-2c43c6ff2e08)


Then, methods were created in Keyboard.

Then, methods were created within the Keyboard object. The _createKeys() method is a private method that generates the keys for the virtual keyboard. For special keys like backspace, caps, done, and space, a Google API was linked in the HTML code.


![image](https://github.com/leonardopiller/virtual-keyboard/assets/121625024/9ba247ed-74fd-43ce-b695-8358ff5af329)
  
  The _createKeys() method creates attributes for each special key and general keys using a switch-case structure. It also inserts <br> tags to display the typical layout of a keyboard. The method returns the appended fragment.
 
  ![image](https://github.com/leonardopiller/virtual-keyboard/assets/121625024/90c551f8-4013-4b1c-b777-41c04507f3e3)


The init() method generates a fragment in the DOM, adds classes to interact with the "keyboard.css" file, and inserts the keys created by _createKeys(). This function gets the textarea with the class ".use-keyboard-input" and opens the keyboard using the open() method.


![image](https://github.com/leonardopiller/virtual-keyboard/assets/121625024/c50adbdc-0774-484f-b492-ca01c11be200)


![image](https://github.com/leonardopiller/virtual-keyboard/assets/121625024/a6a586d0-7e84-4010-9977-69538ff1083d)



To enable the CapsLock functionality, the _toggleCapsLock() method changes the letter case of the keys to upper or lower.

![image](https://github.com/leonardopiller/virtual-keyboard/assets/121625024/de353db2-fbc8-4956-abfa-a74e86f53381)

Finally, init( ) is called when the DOM is loaded 

![image](https://github.com/leonardopiller/virtual-keyboard/assets/121625024/3e4b97b9-a8da-478c-8a1e-a0e4568bdb70)

All JS Code can be checked in keyboard/
