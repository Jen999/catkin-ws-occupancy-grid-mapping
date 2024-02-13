## Ensure python-dev and matplotlib is installed
```
sudo apt-get install python-dev
sudo apt-get install python-matplotlib python-numpy python2.7-dev
```

## Occupancy Grid Mapping
Output > ./Images/mapping.png
```
g++ main.cpp -o app -std=c++11 -I/usr/include/python2.7 -lpython2.7
./app
```

## Path Planning using A* Search algorithm
Output > ./Images/Path.png
```
g++ pathplanning.cpp -o app -std=c++11 -I/usr/include/python2.7 -lpython2.7
./app
```
