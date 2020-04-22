# Graphhic
AR/VR graphic tookit, enter or leave front buffer mode with following functions
```
int xr_graphic_init(void* display, void* surface, void* nativeWindow);
void xr_graphic_deinit(void* display, void* surface);
```

# Sensor
Kalman 3DOF Fusion mode
```
int xr_init_sensor();
void xr_destroy_sensor();
```