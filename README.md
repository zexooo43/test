# test
Rebuild started at 4:42 AM...
1>------ Rebuild All started: Project: Stroke, Configuration: Debug x64 ------
1>  Preprocessing OpenCL to Strings for Stroke_Kernel.cl
1>  Stroke_Kernel.cl
1>C:\Users\miyuk\Downloads\stroke-aex-devin-1776637129-stroke-effect-plugin\Effect\Stroke\Stroke_Kernel.cu(4): fatal error C1083: Cannot open include file: 'PrGPU/KernelSupport/KernelCore.h': No such file or directory
1>  Custom build step: Building Stroke_Kernel.cu
1>  The system cannot find the path specified.
1>  Preprocessing HLSL to CSO/RS for Stroke_Kernel.chlsl
1>  Stroke_Kernel.chlsl
1>C:\Users\miyuk\Downloads\stroke-aex-devin-1776637129-stroke-effect-plugin\Effect\Stroke\Stroke_Kernel.cu(4): fatal error C1083: Cannot open include file: 'PrGPU/KernelSupport/KernelCore.h': No such file or directory
1>  Traceback (most recent call last):
1>    File "C:\Users\miyuk\Downloads\stroke-aex-devin-1776637129-stroke-effect-plugin\GPUUtils\ParseHLSL.py", line 174, in <module>
1>      main(sys.argv)
1>      ~~~~^^^^^^^^^^
1>    File "C:\Users\miyuk\Downloads\stroke-aex-devin-1776637129-stroke-effect-plugin\GPUUtils\ParseHLSL.py", line 171, in main
1>      postprocessHLSL(args)
1>      ~~~~~~~~~~~~~~~^^^^^^
1>    File "C:\Users\miyuk\Downloads\stroke-aex-devin-1776637129-stroke-effect-plugin\GPUUtils\ParseHLSL.py", line 158, in postprocessHLSL
1>      processedHLSL = hlsl_defines + processHLSL(args.input_file, args.entrypoint)
1>                                     ~~~~~~~~~~~^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
1>    File "C:\Users\miyuk\Downloads\stroke-aex-devin-1776637129-stroke-effect-plugin\GPUUtils\ParseHLSL.py", line 126, in processHLSL
1>      if data_dict[in_entrypoint]["shared_decls"]:
1>         ~~~~~~~~~^^^^^^^^^^^^^^^
1>  KeyError: 'StrokeKernel'
1>  The system cannot find the path specified.
1>  Compiling the PiPL
1>  Microsoft (R) C/C++ Optimizing Compiler Version 19.50.35729 for x64
1>  Copyright (C) Microsoft Corporation.  All rights reserved.
1>
1>  StrokePiPL.r
1>  Microsoft (R) C/C++ Optimizing Compiler Version 19.50.35729 for x64
1>  Copyright (C) Microsoft Corporation.  All rights reserved.
1>
1>  StrokePiPL.rrc
1>C:\Program Files\Microsoft Visual Studio\18\Community\MSBuild\Microsoft\VC\v180\Microsoft.CppCommon.targets(254,5): error MSB8066: Custom build for '..\Stroke_Kernel.cl;..\Stroke_Kernel.cu;..\Stroke_Kernel.chlsl;..\StrokePiPL.r' exited with code -1.
========== Rebuild All: 0 succeeded, 1 failed, 0 skipped ==========
========== Rebuild completed at 4:42 AM and took 03.645 seconds ==========
