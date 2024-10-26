# CMSIS Build CMakeLists generated on 2024-10-26T20:58:18

cmake_minimum_required(VERSION 3.22)

# Target options

set(TARGET stm32)
set(CPU Cortex-M4)
set(PRJ_DIR "C:/work/edge_impulse/st/example-csolution-stm32f466re/build/Nucleo_STM32F4466/GCC/Debug/stm32")
set(OUT_DIR "C:/work/edge_impulse/st/example-csolution-stm32f466re/build/Nucleo_STM32F4466/GCC/Debug/stm32/outdir")
set(INT_DIR "C:/work/edge_impulse/st/example-csolution-stm32f466re/build/Nucleo_STM32F4466/GCC/Debug/stm32/intdir")
set(FPU SP_FPU)
set(BYTE_ORDER Little-endian)
set(OPTIMIZE none)
set(DEBUG on)
set(CC_FLAGS_GLOBAL "-std=c99 -flax-vector-conversions -mthumb -fdata-sections -std=gnu11 -masm-syntax-unified -fomit-frame-pointer -ffunction-sections")
set(CXX_FLAGS_GLOBAL "-std=c++11 -Og -fdata-sections -mthumb -fno-rtti -fno-unwind-tables -masm-syntax-unified -fomit-frame-pointer -ffunction-sections")
set(LD_FLAGS_GLOBAL "--specs=nano.specs --specs=rdimon.specs --entry=Reset_Handler -Wl,-Map=.map,--cref,-print-memory-usage,--gc-sections -Wl,-Map=\"C:/work/edge_impulse/st/example-csolution-stm32f466re/build/Nucleo_STM32F4466/GCC/Debug/stm32/outdir/stm32.elf.map\" -Wl,--gc-sections")
set(LD_SCRIPT "C:/work/edge_impulse/st/example-csolution-stm32f466re/RTE/Device/STM32F446RETx/gcc_linker_script.ld.src")
set(LD_REGIONS "C:/work/edge_impulse/st/example-csolution-stm32f466re/RTE/Device/STM32F446RETx/regions_STM32F446RETx.h")
set(LD_SCRIPT_PP "C:/work/edge_impulse/st/example-csolution-stm32f466re/build/Nucleo_STM32F4466/GCC/Debug/stm32/intdir/gcc_linker_script.ld")

set(DEFINES
  STM32F446xx
  _RTE_
  USE_HAL_DRIVER
)

set(INC_PATHS
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Inc"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Inc/Legacy"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/CMSIS/Device/ST/STM32F4xx/Include"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/CMSIS/Include"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Inc"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/RTE/_Debug_Nucleo_STM32F4466"
  "C:/Users/franc/AppData/Local/Arm/Packs/ARM/CMSIS/6.0.0/CMSIS/Core/Include"
)

set(CC_SRC_FILES
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_cortex.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_dma.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_dma_ex.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_exti.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_flash.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_flash_ex.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_flash_ramfunc.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_gpio.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_pwr.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_pwr_ex.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_rcc.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_rcc_ex.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_tim.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Drivers/STM32F4xx_HAL_Driver/Src/stm32f4xx_hal_tim_ex.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Src/main.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Src/stm32f4xx_hal_msp.c"
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/STM32CubeMX/Nucleo_STM32F4466/STM32CubeMX/Src/stm32f4xx_it.c"
)

set(CXX_SRC_FILES
  "C:/work/edge_impulse/st/example-csolution-stm32f466re/app/src/main.cpp"
)

# Toolchain config map

set(REGISTERED_TOOLCHAIN_ROOT "C:/Program Files (x86)/Arm GNU Toolchain arm-none-eabi/12.3 rel1/bin")
set(REGISTERED_TOOLCHAIN_VERSION "12.3.1")
set(TOOLCHAIN_VERSION_MIN "12.3.1")
include ("C:/work/cmsis-toolbox/etc/GCC.10.3.1.cmake")
include ("C:/work/cmsis-toolbox/etc/CMSIS-Build-Utils.cmake")

# Setup project

project(${TARGET} LANGUAGES C CXX)

cbuild_get_running_toolchain(TOOLCHAIN_ROOT TOOLCHAIN_VERSION CXX)

# Global Flags

cbuild_get_system_includes(CC_SYS_INC_PATHS_LIST CC_SYS_INC_PATHS)
set(CMAKE_C_FLAGS "${CC_CPU} ${CC_BYTE_ORDER} ${CC_DEFINES} ${CC_OPTIONS_FLAGS} ${CC_FLAGS} ${CC_FLAGS_GLOBAL} ${CC_SYS_INC_PATHS}")
cbuild_get_system_includes(CXX_SYS_INC_PATHS_LIST CXX_SYS_INC_PATHS)
set(CMAKE_CXX_FLAGS "${CXX_CPU} ${CXX_BYTE_ORDER} ${CXX_DEFINES} ${CXX_OPTIONS_FLAGS} ${CXX_FLAGS} ${CXX_FLAGS_GLOBAL} ${CXX_SYS_INC_PATHS}")
set(CMAKE_CXX_LINK_FLAGS "${LD_CPU} ${_LS}\"${LD_SCRIPT_PP}\" ${LD_FLAGS_GLOBAL} ${LD_OPTIONS_FLAGS} ${LD_FLAGS}")

# Compilation Database

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
add_custom_target(database COMMAND ${CMAKE_COMMAND} -E copy_if_different "${INT_DIR}/compile_commands.json" "${OUT_DIR}")

# Setup Target

add_executable(${TARGET} ${CC_SRC_FILES} ${CXX_SRC_FILES})
set_target_properties(${TARGET} PROPERTIES PREFIX "" SUFFIX ".elf" OUTPUT_NAME "stm32")
set_target_properties(${TARGET} PROPERTIES RUNTIME_OUTPUT_DIRECTORY ${OUT_DIR} LINK_DEPENDS ${LD_SCRIPT})
target_include_directories(${TARGET} PUBLIC ${INC_PATHS})

# Linker script pre-processing

add_custom_command(TARGET ${TARGET} PRE_LINK COMMAND ${CPP} ARGS ${CPP_ARGS_LD_SCRIPT} BYPRODUCTS ${LD_SCRIPT_PP})
