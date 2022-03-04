# Deliverables
Deliverables and other resources

## General
[Code of Conduct](https://docs.google.com/document/d/1hpc_hRut5Czhh0Gf1D5xixF2WkMmqR8tzGPZMGBBHvU/edit)

[Our web](https://rss2022-9.github.io/website/labs/example_lab/)

## Lab 3: Wall follower
[Slides](https://docs.google.com/presentation/d/1hVHw4iFh6VHjNoDBnSe8HBMoHZDm97rcsHJwZnClQBY/edit?fbclid=IwAR0YZ17SbSYpcGlyNT4YjAzYX3gzDIqJbqoNr1YT-Xx2TUDqCIvZa1mCfOs#slide=id.g1175b30dbaa_0_124)

[LaTeX](https://www.overleaf.com/read/vcsspwgzycrt)

## Note (non-deliverable)
- [x] Ask TA and fix the unstable XTbattery issue: they are considering giving us a new car.
- [ ] Configure VNC on the racecar
- [ ] Our Team name!!
- [x] Code of conduct

## Potential Improvements
1. use polar coordinate for line fitting
2. High speed stability with MPC

## Hardware is (not) fun
1. Check /vsec/joy for joystick message. If it doesn't work, make sure joy switch is on x (button on the top). And reboot the TX2
2. vesc serial timeout: vesc connection problem. try different cables.
3. why xtbattery dies? at certain moment (around 10s after turning on), the output power increases to 18 w. Maybe that is the time that fans start and also the time TX2 was killed. In theory, it should support up to 65W. In my view, it is probably the problem of both TX2 and power bank. Hopefully we get a new power bank to test.
