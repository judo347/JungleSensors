# Project: Jungle Sensors

### Problem description

Company X wants to deploy devices with sensors throughout the Amazon jungle to do measurements. Each device is small and cheap, so technology like GPS is not an options, but the devices need to know their own location for research purposes. 

Each device is suited with radio-wave communication, with a limited range, and company X has deployed a few amount of radio towers which is equipped with GPS.

Company X has reached out to the software firm MK and requested a solution which will be run on all devices and should establish their location using what they are suited with.

**Key points:**

- Devices with sensors
  - Cheap and great quantity
  - All devices runs the same software solution
  - Has radio-wave communication (Can communicate with radio tower and other devices)
- Radio Towers
  - Few in numbers
  - Has GPS and knows their own location
  - Has radio-wave communication (Devices)



### Solution Proposal

- The solution running on the devices should be simple and efficient
- Devices should use triangulation on measurements gathered through radio-wave communication to establish their location
- During development the solution will be enhanced with a graphical interface using LibGdx
  - Allows for easier debugging and testing
  - It should allow the user to place radio towers and devices at will
  - The interface should have a time component, so the devices will regularly try to communicate and calculate their position.
  - Each device should visually display their status and location when established
  - Each device and radio tower should display their communication radius