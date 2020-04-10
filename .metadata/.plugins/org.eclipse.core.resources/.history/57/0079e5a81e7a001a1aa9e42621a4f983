################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

# Each subdirectory must supply rules for building sources it contributes
%.obj: ../%.c $(GEN_OPTS) | $(GEN_FILES)
	@echo 'Building file: "$<"'
	@echo 'Invoking: ARM Compiler'
	"C:/ti/ccs910/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/bin/armcl" -mv7M3 --code_state=16 --float_support=vfplib -me --include_path="C:/Users/ycyoon/workspace_v9/Patch_TX_rev4" --include_path="C:/Users/ycyoon/workspace_v9/Patch_TX_rev4" --include_path="C:/Users/ycyoon/workspace_v9/Patch_TX_rev4/smartrf_settings" --include_path="/products/cc13xxware_2_04_03_17272" --include_path="C:/ti/ccs910/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/include" --define=DeviceFamily_CC13X0 --define=ccs -g --diag_warning=225 --diag_warning=255 --diag_wrap=off --display_error_number --gen_func_subsections=on --abi=eabi --preproc_with_compile --preproc_dependency="$(basename $(<F)).d_raw" $(GEN_OPTS__FLAG) "$<"
	@echo 'Finished building: "$<"'
	@echo ' '

build-1626760623:
	@$(MAKE) --no-print-directory -Onone -f subdir_rules.mk build-1626760623-inproc

build-1626760623-inproc: ../rfExamples.cfg
	@echo 'Building file: "$<"'
	@echo 'Invoking: XDCtools'
	"C:/ti/ccs900/xdctools_3_55_00_11_core/xs" --xdcpath= xdc.tools.configuro -o configPkg -t ti.targets.arm.elf.M3 -p ti.platforms.simplelink:CC1310F128 -r release -c "C:/ti/ccs910/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS" --compileOptions "-mv7M3 --code_state=16 --float_support=vfplib -me --include_path=\"C:/Users/ycyoon/workspace_v9/Patch_TX_rev4\" --include_path=\"C:/Users/ycyoon/workspace_v9/Patch_TX_rev4\" --include_path=\"C:/Users/ycyoon/workspace_v9/Patch_TX_rev4/smartrf_settings\" --include_path=\"/products/cc13xxware_2_04_03_17272\" --include_path=\"C:/ti/ccs910/ccs/tools/compiler/ti-cgt-arm_18.12.2.LTS/include\" --define=DeviceFamily_CC13X0 --define=ccs -g --diag_warning=225 --diag_warning=255 --diag_wrap=off --display_error_number --gen_func_subsections=on --abi=eabi  " "$<"
	@echo 'Finished building: "$<"'
	@echo ' '

configPkg/linker.cmd: build-1626760623 ../rfExamples.cfg
configPkg/compiler.opt: build-1626760623
configPkg/: build-1626760623


