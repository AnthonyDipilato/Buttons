# Buttons for Arduino

Simple class for debouncing button inputs in Arduino. I use the internal pull up resistors because I am lazy. If you are not like me,  you can change the pinmode in the Buttons.cpp file.

### Setup

```c++
// Include the buttons.h in your main file
#include "Buttons.h"

// Declare your buttons and the pin
Buttons example_button(10);
Buttons example_button_two(9);

// Include check in your main loop
example_button.check();
example_button_two.check();

// Check the value of your buttons
// example_button.value
// example_button_two.value

```


### Author
Anthony DiPilato, Anthony@bumbol.com

### License
All code is available under the MIT license. See LICENSE file for info.
