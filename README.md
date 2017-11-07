# TODOs

 - All scripts should be chain-able, so that the output of one can be 
   used as an input to the other.
 - Should potentially read other formats, primarily lammpstrj.
 - XYZ with celldm is a good internal representation.

 - frame-getters:
  - first: first to n
  - frame: n to m
  - last : m to last
  - while `first` and `last` can use `frame`, probably more efficient to 
    do separately.

- do `tolmp`
- change the main name to trj from xyz; it should call the converters 
  `fromlmp` and `tolmp` if trj extension is `.lammpstrj`
