# Installation
Follow instructions [here](https://github.com/homenc/HElib/blob/master/INSTALL.md).

One thing that caught me off guard is that it will be installed in `/usr/local/helib_pack/`. To get it to install in `/usr/local/`, set `PACKAGE_DIR=/usr/local/`

Don't forget to:
`export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/lib`

Then compile:
`g++ BGV_country_db_lookup.cpp -l helib -l ntl`

# Database Lookup Example
The code is adapted from [here](https://github.com/homenc/HElib/tree/master/examples/BGV_country_db_lookup).

