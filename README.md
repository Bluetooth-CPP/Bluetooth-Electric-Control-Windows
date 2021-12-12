Bluetooth-CPP-Windows
=======
Control electric pins such as on an Arduino by allocating voltage values to arrays.

Documentation
=======
Add references to BluetoothWindows.h in your .cpp or .h files.

`#include "<Path of BluetoothWindows.h>"`

Bluetooth Windows Functions
-----------
  
`void connect(string deviceName)`
  
`void send(string text)`
  
`void recv(int pins[])`

You input an array and the function will set a value or "pin" of the array to the voltage input value of a microcontroller pin.
