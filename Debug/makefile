################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include threads/subdir.mk
-include tests/vm/subdir.mk
-include tests/userprog/no-vm/subdir.mk
-include tests/userprog/subdir.mk
-include tests/threads/subdir.mk
-include tests/internal/subdir.mk
-include tests/filesys/extended/subdir.mk
-include tests/filesys/base/subdir.mk
-include tests/filesys/subdir.mk
-include tests/subdir.mk
-include lib/user/subdir.mk
-include lib/kernel/subdir.mk
-include lib/subdir.mk
-include examples/subdir.mk
-include devices/subdir.mk
-include subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: proj1

# Tool invocations
proj1: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: GCC C Linker'
	gcc  -o "proj1" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(OBJS)$(C_DEPS)$(EXECUTABLES) proj1
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
