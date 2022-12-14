```
 _____             _   _       _  ______          _   _ _   _              ______                     
/  ___|           | | (_)     | | | ___ \        | | (_) | (_)             |  _  \                    
\ `--. _ __   __ _| |_ _  __ _| | | |_/ /_ _ _ __| |_ _| |_ _  ___  _ __   | | | |___ _ __ ___   ___  
 `--. \ '_ \ / _` | __| |/ _` | | |  __/ _` | '__| __| | __| |/ _ \| '_ \  | | | / _ \ '_ ` _ \ / _ \ 
/\__/ / |_) | (_| | |_| | (_| | | | | | (_| | |  | |_| | |_| | (_) | | | | | |/ /  __/ | | | | | (_) |
\____/| .__/ \__,_|\__|_|\__,_|_| \_|  \__,_|_|   \__|_|\__|_|\___/|_| |_| |___/ \___|_| |_| |_|\___/ 
      | |                                                                                             
      |_|                                                                                             
```

# raylibdemo - Spatial Partition Pattern

A simple raylib project to demonstrate the "Spatial Partition Optimization Pattern" by following the example from:
https://gameprogrammingpatterns.com/spatial-partition.html

![Raylib Demo - Spatial Partition](https://user-images.githubusercontent.com/100346454/189760975-a70fe1e9-0f88-4f60-a6fa-5d1221a7f061.png)

## Usage

Before you start the programm change `NUM_CELLS` and `CELL_SIZE` in `grid.h`, which is located in `src/headerfiles`, to one of the four values, which are commented of to the side of the constants.

![grid constants](https://user-images.githubusercontent.com/100346454/189764487-a45f4709-b60b-4d04-a0da-968742abc356.png)

You can also experiment with the values to get different results.

### Controlls

Spawn amount of the objects is set by pressing the `arrow key up or down`.
Press the `left mouse button` anywhere on the screen to spawn objects.
The programm can be closed by pressing the `ESC` key or by pressing the `window close button` on the top right of the screen.

## License

see `LICENCE` file for details.
