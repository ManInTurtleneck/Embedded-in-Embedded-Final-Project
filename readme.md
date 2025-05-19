# This was a final project from the Embedded In Embedded Group
# at University of Calgary in collaboration with Chamer5465.
# Please view his repository at https://github.com/Chamer5465/EIE_Project/tree/master

## Compiling reference

To compile the project

1. Open a new terminal
2. Run `./waf configure --board=<hardware>` replacing `<hardware>` with either `ASCII` or `DOT_MATRIX` depending on the board you have. This step should only need to be run once if successful.
3. Run `./waf build` to build or `./waf build -F` to build and flash the device.

python waf -?
python waf configure --board=ASCII
python waf configure --board=DOT_MATRIX
python waf build
python waf build -F
