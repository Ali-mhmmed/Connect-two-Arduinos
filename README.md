# Connect-two-Arduinos
This is the second task in the Internet of Things, where two Arduinos were connected through a system to UART

## whet is UART ?
UART stands for Universal Asynchronous Receiver/Transmitter. It is a hardware communication protocol used for serial communication between devices. UART is commonly used to transmit and receive data between microcontrollers, sensors, and other electronic devices.

The communication in UART is asynchronous, meaning that the data is sent without a shared clock signal between the sender and receiver. Instead, both the transmitting and receiving devices must agree on a specific baud rate (bits per second) to communicate effectively.

In UART communication, data is sent one bit at a time over two wires: one for transmitting data (TX) and the other for receiving data (RX). This allows devices to communicate over relatively long distances with minimal wiring.

The UART protocol is widely used in various applications, including connecting microcontrollers to sensors, GPS modules, Bluetooth modules, and other embedded systems. It is a fundamental and essential component in the field of embedded systems and Internet of Things (IoT) devices.


### TX - Transmit 
In this project, the transmitter is the component that has the button.


![لقطة الشاشة 2023-08-02 015443](https://github.com/Ali-mhmmed/Connect-two-Arduinos/assets/139057114/ffd3d93b-1260-41b1-823a-2065b5984c25)


#### RX - Receive
In this project, the receiver is the part that has an LED.




![لقطة الشاشة 2023-08-02 021047](https://github.com/Ali-mhmmed/Connect-two-Arduinos/assets/139057114/f8d6aa09-4211-492a-93d6-e255a1d78dca)


