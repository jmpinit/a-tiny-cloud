# A Tiny Cloud

**The Goal**: serve a blog from a load-balanced cloud of networked ATtiny10 microcontrollers.

**The Plan:**

1. Make a device that can program and communicate with an array of ATtiny10s via USB
2. Use the TUN/TAP driver in Linux to create a network interface for each ATtiny10. Behind the scenes data is shuffled over USB and then over serial to and from the microcontrollers.
3. Set up NGINX to load-balance requests from the WWW across the microcontrollers.
4. Write a blog engine in AVR assembly.
5. Uh...
6. Profit?

