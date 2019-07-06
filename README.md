# th.cross3~

**Please consider to download and donate via http://gumroad.com/tmhglnd**

A Max Abstraction to get the average amplitude values from an audio signal over 3 different frequency bands.

## About

Use the th.cross3~ to get the average amplitude values from an audio signal over 3 different bands. the values are reported as signal from the last 3 outlets and reported as a list from the first outlet. Use the render bang from jit.world or qmetro to output the list of values. Or use the other 3 outlets to get the signal value for every band.

Use the attributes to fit the cross-over frequencies to your own needs. The freq attribute takes 2 arguments, first cross and second cross. Use the slide attribute to change the reaction time. Use the gain attribute to scale the output values.

For visuals it is desired to have an amplitude value for every frame. That is why the th.cross3~ outputs a list of values when a bang is send. This list can be used in audio reactive visuals.

## Install

```
1. download zip 
2. unzip in Max searchpath (eg. on MacOS ~/Documents/Max 8/Library)
3. restart Max8
```

```
1. open terminal
2. navigate to Max searchpath (eg. on MacOS cd ~/Documents/Max\ 8/Library)
3. $ git clone https://github.com/tmhglnd/th.cross3.git
```
