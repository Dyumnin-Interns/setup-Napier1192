SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../hdl/xor_gate.v
VERILOG_SOURCES += $(PWD)/wrappers/xor_test.v
TOPLEVEL = xor_test
MODULE = test_xor
include $(shell cocotb-config --makefiles)/Makefile.sim
