Jupiter/Mesa 22.0.0 Release Notes / 2022-01-13
==============================================

New features
------------

- Experimental support of Mesh shaders with VK_NV_mesh_shader

Performance fixes
-----------------

- Improved performance for Shadow of the Tomb Raider

Bug fixes
---------

- Fixed a rendering issue with Baldur's Gate 3 (https://gitlab.freedesktop.org/mesa/mesa/-/issues/5509)
- Fixed a rendering issue with F1 2021 (https://github.com/HansKristian-Work/vkd3d-proton/issues/950)
- Fixed a DCC clear issue on GFX10+ (https://gitlab.freedesktop.org/mesa/mesa/-/issues/5676)
- Fixed an use-after-free with Uplay (https://gitlab.freedesktop.org/mesa/mesa/-/issues/5789)
- Added a safety check for capturing with RGP (https://gitlab.freedesktop.org/mesa/mesa/-/issues/5260)
- Fixed a rendering issue with Forza Horizon 4 (https://gitlab.freedesktop.org/mesa/mesa/-/issues/5423)
- Fixed Horizon Zero Dawn artifacts
- Various VRS fixes
- Various ACO fixes
- Various VK_KHR_dynamic_rendering fixes
- Added a workaround for Battefield I&V to fix a regression
- Added a driconf workaround to fix a performance issue with Forza Horizon 5
