# Burglar Interview

Imagine you are a burglar trying to steal a precious diamond without the alarm
going off. In order to prevent you from stealing the diamond, several motion
sensors were put in place in the room which trigger the alarm. However, you, the
software engineer you are, managed to hack into the museum's servers and found
the blueprint, listing the location of each motion sensor. The motion sensors
are each built to trigger the alarm when you come too close to them, with
probability

```
P = exp[-l^2 / c^2]
```

where `l` is the distance between you and the sensor, and `c` is some length
characteristic of the type of sensor.

Now, given that you know exactly where each sensor is, your task is to prepare
for the robbery by calculating which path you should take to get through the
room with the lowest chance of triggering the alarm, and steal the diamond.

Given parameters:
- The room is of size `M` x `N`, with `M` and `N` given parameters.
- The diamond is located somewhere in the room (D_m, D_n).
- The entrance is at the bottom right corner, `(M, 0)`, and the exit at the top
  left corner, `(0, N)`.
- You have a list of sensor locations `(S_i, S_i)`.

All of this should be put in a Haskell repository on GitHub, which you invite me
to, that uses cabal, nix, stack or whichever tools you like. Tests are not
necessary, but a readme file is, where you describe the formulae that you are
using in your code, come from.

The goal of this exercise, is to test
- your ability to solve problemms
- your communication skills, including documentation and the readme
- the quality of your code itself, readability, modularity etc.

Particularly, I also want you to discuss any important choices you made in terms
of the usage of algorithms, data structures and time/space complexity in the
readme.

This task should take you 4-8 hours. Please don't work longer on it than this,
we really don't want you to waste too much time.

Good luck, and enjoy!
