##===- utils/TableGen/Makefile -----------------------------*- Makefile -*-===##
#
#                     The LLVM Compiler Infrastructure
#
# This file is distributed under the University of Illinois Open Source
# License. See LICENSE.TXT for details.
#
##===----------------------------------------------------------------------===##

LEVEL = ../..
TOOLNAME = tblgen
USEDLIBS = LLVMSupport.a
REQUIRES_EH := 1
REQUIRES_RTTI := 1

# This tool has no plugins, optimize startup time.
TOOL_NO_EXPORTS = 1

include $(LEVEL)/Makefile.common

