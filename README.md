The uploaded notebook contains required commands to install RISC-V toolchain.
After toolchain installation, it compiles several exemplary programs from NEORV32 processor.
For more information about examples, look at https://github.com/stnolting/neorv32.


Q-LENET contains source codes of quantized 5-layer neural network (similar to LENET) to be run on NEORV32 processor. For simulation purposes just compile with the following flag (look at Makefile):

`USER_FLAGS += -DUART0_SIM_MODE`

