# Buttons for Arduino

Simple class for debouncing button inputs in Arduino.


### Setup

```c++
// include the buttons.h in your main file
#include "Buttons.h"

//Declare you buttons and the pin
Buttons example_button(10);
Buttons example_button_two(9);

// Include check in your main loop
example_button.check();
example_button_two.check();

// check the value of your buttons
// example_button.value
// example_button_two.value

```


### Author
Anthony DiPilato, Anthony@bumbol.com

### License
All code is available under the MIT license. See LICENSE file for info.
