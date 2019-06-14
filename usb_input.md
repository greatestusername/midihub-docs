# USB Input

The entry point of USB MIDI data. The data received from PC via the USB cable from matching USB MIDI device will be forwarded as is to the pipe on the right. See [The USB MIDI Port Mapping](the_usb_midi_port_mapping) for OS device mapping to USB port letter used by the device.

The first 4 USB MIDI ports on the computer map to A, B, C, D letters. The 5th USB MIDI port is reserved for Editor communication and shouldn't be used.

| Parameter | Description                    |
| --------- | ------------------------------ |
| Bypass    | Whether processing is enabled. |
| Source    | The source of MIDI data.       |

[List of Pipes](index.md#the-list-of-pipes)