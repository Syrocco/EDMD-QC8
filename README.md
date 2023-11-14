# EDMD-QC8

EDMD code for the simulations in *Quasi-crystalline order in vibrating granular matter*.

### COMPILATION AND BASICS
To compile use ```make``` in the directory.

To run the simulation leading to the final configuration seen in Fig. 1 of the article: ``` ./a.out -N 5000 -p 0.85 -x 0.68 -q 0.5```. Then use *ovito* to open the dump file created in the directory ```dump/```.

### OPTIONS TO PASS IN COMMAND LINES
```-N```: Number of particles

```-p```, ```-x``` and ```-q```: Packing fraction, fraction of small particles and sizeratio

```-d```: Value of Delta

```-r```: Coefficient of restitution

```-t```: Total simulation time

```-D```: Interval of time between saved shapshots
