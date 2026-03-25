# firmware_flash-arb-check
This flashable zip contains the firmware required for flashing AOSP custom ROMs, with built-in anti-rollback check logic to avoid triggering device security protections during flashing.
When building AOSP custom ROMs, it is recommended not to include firmware in the ROM package, but to flash it manually via this zip.
Special thanks to @syedinsaf, the author of arbscan, for providing the core technical support for this tool.


这个卡刷包包含了刷入AOSP自定义ROM所需的固件，并内置了防回滚（anti-rollback）判断逻辑，可避免刷机时触发设备安全保护。
编译AOSP自定义ROM时，建议不打包固件，而是通过此卡刷包单独手动刷入。
特别感谢 arbscan 的作者 @syedinsaf，为本工具提供了核心技术支持。



