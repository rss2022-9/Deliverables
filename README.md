# Deliverables
Deliverables and other resources

## Lab 3: Wall follower
[Slides](https://docs.google.com/presentation/d/1hVHw4iFh6VHjNoDBnSe8HBMoHZDm97rcsHJwZnClQBY/edit?fbclid=IwAR0YZ17SbSYpcGlyNT4YjAzYX3gzDIqJbqoNr1YT-Xx2TUDqCIvZa1mCfOs#slide=id.g1175b30dbaa_0_124)
[LaTeX](https://www.overleaf.com/read/vcsspwgzycrt)

## Note (non-deliverable)
- [x] Ask TA and fix the unstable XTbattery issue: they are considering giving us a new car.
- [ ] Configure VNC on the racecar
- [ ] Our Team name!!
- [ ] Code of conduct


## Hardware is (not) fun
1. Check /vsec/joy for joystick message. If it doesn't work, make sure joy switch is on x (button on the top). And reboot the TX2
2. vesc serial timeout: vesc connection problem. try different cables.
3. why xtbattery dies? at certain moment (around 10s after turning on), the output power increases to 18 w. Maybe that is the time that fans start and also the time TX2 was killed. In theory, it should support up to 65W. In my view, it is probably the problem of both TX2 and power bank. Hopefully we get a new power bank to test.
