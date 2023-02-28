# Reverse Engineering KVM Switch
This is a LaTeX document detailing the process of reverse engineering the USB signal of a KVM switch using Wireshark and Python.

## Team Members
  - [Matthias Enderlein](https://github.com/programming-matthias)
  - [Sebastian Feustel](https://github.com/53845714nF)

## Background
Our team was tasked with reverse engineering the USB signal of a KVM switch. 
To ensure that the software signal also works under Ubuntu Linux.

## Methodology
We used Wireshark to capture USB packets sent between the KVM switch and a connected computer. We then analyzed the captured packets to identify patterns and gain insights into the USB signal.
Using Python, we wrote scripts to use this USB signal on Linux Computers.

## Results
Our analysis of the recorded packets showed that the KVM switch uses a different signal to switch between the computer inputs. And the computer can determine the state of the switch.

## Conclusion
Reverse engineering the USB signal of a KVM switch using Wireshark and Python was a challenging but rewarding process. Our findings have the potential to help others.
