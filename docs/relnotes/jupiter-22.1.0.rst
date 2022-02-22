Jupiter/Mesa 22.1.0 Release Notes / 2022-02-22
==============================================

New features
------------

- Vulkan 1.3 (including CTS 1.3.0 conformance on RDNA2 GPUs).
- Performance profile should be automatically set by RADV for capturing with
  RGP (for recent kernels).
- RADV_FORCE_VRS can be controlled dynamically from a configuration file.
- Dynamic swapchain override for Gamescope limiter (specific to SteamOS).

Performance fixes
-----------------

- Various ACO optimizations.
- Few micro RADV CPU optimizations.
- Increased slab allocator size to reduce shaders buffer objects.

Bug fixes
---------

- Fixed a rendering issue with Proton SotTR.
- Fixed raytracing with Wave32.
- Fixed a bug with optimized MSAA copies and suballocated images.
- Fixed a bug with mixed clip/cull distances.
- Fixed a bug by using reference counting for descriptor set layouts.
- Fixed a winsys bug related to zerovram and vkd3d-proton.
- Fixed a bug with dynamic topology and experimental mesh shaders.
- Fixed a GPU hang with IB2 on the compute queue.
- Various RADV fixes.
- Various ACO fixes.
- Added a workaround for The Evil Within 1&2 to fix a regression
