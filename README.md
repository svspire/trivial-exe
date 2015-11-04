# trivial-exe

Tools for working with executables

# Usage

```lisp
CL-USER> (ql:quickload :trivial-exe)

CL-USER> (trivial-exe:executable-pathname)
#P"/usr/local/bin/sbcl"

CL-USER> (trivial-exe:ensure-executable #p"/path/to/binary")
T
```

# License

Copyright (c) 2015 Fernando Borretti

Licensed under the MIT License.