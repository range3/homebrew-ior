# homebrew-ior
## Usage
``` sh
$ brew tap range3/ior
$ brew install ior
```
(05/04/2018) If you want to install `mdtest` too, use `--HEAD` option
to install the latest commit of IOR.
``` sh
$ brew tap range3/ior
$ brew install ior --HEAD
```

## Note
If installing open-mpi does not succeed, try `--without-fortran` option.
``` sh
$ brew install open-mpi --without-fortran
```
