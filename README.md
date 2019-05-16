

# Particle Filter Localization( Monte Carlo Localization )
You will be able to observe the `MCL` in action through the generated images. 

### Editing the Program
Enter the code in the designated section:

### Compiling the Program
```sh
$ cd /home/workspace/
$ git clone https://github.com/zvatansever/particle-filter-localization
$ cd particle-filter-localization/
$ mkdir Images
$ rm -rf Images/*
$ g++ main.cpp -o app -std=c++11 -I/usr/include/python2.7 -lpython2.7
```

### Running the Program
Before you run the program, make sure the `Images` folder is empty!
```sh
$ ./app
```
Wait for the program to iterate `50` times.

### Generated Images
After running the program, `50` images will be generated in the `Images` folder.
