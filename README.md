# nco_pipes

For subsetting NetCDF files with NCO from pipes.

Example usage

```console
$ wget -O- https://www.unidata.ucar.edu/software/netcdf/examples/sresa1b_ncar_ccsm3-example.nc | ncks_piped -v plev | cat > sresa1b_ncar_ccsm3-example.nc

```
