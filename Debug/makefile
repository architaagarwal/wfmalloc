################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
-include src/subdir.mk
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
all: libwfmalloc.so

# Tool invocations
libwfmalloc.so: $(OBJS) $(USER_OBJS)
	@echo 'Building target: $@'
	@echo 'Invoking: GCC C Linker'
	gcc -shared -o "libwfmalloc.so" $(OBJS) $(USER_OBJS) $(LIBS)
	@echo 'Finished building target: $@'
	@echo ' '

wfmalloc: $(OBJS) $(USER_OBJS)
		@echo 'Building target: $@'
	  	@echo 'Invoking: GCC C Linker'
	   	gcc  -o "wfmalloc" $(OBJS) $(USER_OBJS) $(LIBS)
	    	@echo 'Finished building target: $@'

# Other Targets
clean:
	-$(RM) $(OBJS)$(C_DEPS)$(LIBRARIES) libwfmalloc.so wfmalloc
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
