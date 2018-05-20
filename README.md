# amdgpocl

This package allows the usage of AMD's proprietary user-space OpenCL driver along with the free amdgpu stack. It should work with upstream amdgpu and Mesa. Inspired by [this blog post][gog].

## Hardware support

Only tested with Vega GPUs.

Currently tested with Kernel 4.16. The Avermore miner and Claymore's Dual Miner seem to work without any problems.

## What this is not

You are not getting Vulkan support, faster 3D rendering or unicorns.

If you are looking for the full amdgpu-pro stack, including proprietary OpenGL and Vulkan implementations, move over to the [AUR][AUR-AMDGPU].

Expect maintainance of this package to be dropped when there is free OpenCL support on top of the [ROC] stack.

[AUR]: https://aur.archlinux.org/packages/opencl-amd/
[AUR-AMDGPU]: https://aur.archlinux.org/packages/?K=amdgpu
[Arch Wiki]: https://wiki.archlinux.org/index.php/AMDGPU#Enable_Southern_Islands_.28SI.29_and_Sea_Islands_.28CIK.29_support
[gog]: https://web.archive.org/web/20160609211126/http://www.gearsongallium.com/?p=2960
[ROC]: https://rocm.github.io/
