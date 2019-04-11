# The Phaseblade Visualizer Framework/ System

## what it's about/ why it's cooler than everything else
- it's a highly flexible and hackable real-time and ahead-of time visualizer
- it's modular ~~(two modules)~~
    - modules are customizable and replaceable
- provides ~~xml syntax~~ markup-like language (possibly based on XML or even SGML? ) to define ~~the visual part~~ any part of the visualizer
- there's a cool standard visualizer
    - (sketch(es) will probably follow)
    - it looks somewhat like a blade / blades <hence the name>

## the modules
- define what kind of input and what kind of output data the module consumes/produces
- internally transform digital or analog signals or data into other data (or signals)

## important standard modules

### (Audio) Signal Processor
- can do common Signal Transformations, e.g. FFT

### Renderer
- takes a set of values, i.e. a rendering buffer and produces RGB data/ pixel values for display
- can do complex rendering tech, e.g.
  - rendering to a buffer which is used on the same or subsequent frames
  - AA
  - Physics, 3D Models
