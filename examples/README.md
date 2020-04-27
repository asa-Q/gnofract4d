# EXAMPLES

*Note: for all exmples make sure you have performed the setup previously:*
```
./setup.py build
```

## Python examples
### Creating a simple mandelbrot using fract4dc.controller

Execute:
```
examples/python/simple_mandelbrot.py
```
Then you should see a new file under `examples/output`.


## C++ examples
For these examples you'll need [docker](https://docs.docker.com/get-docker/)

### Creating a simple mandelbrot
Execute:
```
examples/cpp/simple_mandelbrot.sh
```
Then you should see a new file under `examples/output`.

### Creating a simple mandelbrot using multiple threads
Execute:
```
examples/cpp/multithread_mandelbrot.sh
```
Then you should see a new file under `examples/output`.

### Creating a simple mandelbrot using no high level model entities (fractfunc, workers, pointfunc)
In this example we use the compiled formula directly to calculate the fractal with no postprocessing (antialiasing) or improvements (ie. autodeepen)
Execute:
```
examples/cpp/raw_mandelbrot.sh
```
Then you should see a new file under `examples/output`.