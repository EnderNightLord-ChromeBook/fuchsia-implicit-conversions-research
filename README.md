### Fuchsia IC research
Removing implicit conversion flags from Fuchsia one flag at a time.

## Kernel progress
Build files that need still need attention:
* zircon/system/ulib/hid/BUILD.gn ***(1 warning)***
> implicit conversion loses integer precision 
* zircon/system/ulib/image-format/BUILD.gn ***(8 warnings)***
> implicit conversion loses integer precision
* zircon/system/ulib/ktrace/BUILD.gn ***(1 warning)***
> implicit conversion loses integer precision
* zircon/system/ulib/ldmsg/BUILD.gn ***(8 warnings)***
> implicit conversion loses integer precision
* zircon/system/ulib/spi/BUILD.gn ***(1 warning)***
> implicit conversion loses integer precision
* zircon/system/ulib/sysconfig-client/BUILD.gn ***(1 warning)***
> implicit conversion loses integer precision
* zircon/system/ulib/sysmem-version/BUILD.gn ***(10 warnings)***
> implicit conversion loses integer precision
* zircon/system/ulib/tftp/BUILD.gn ***(63 warnings)***
> implicit conversion loses integer precision
* zircon/tools/blobfs/BUILD.gn ***(1 warning)***
> implicit conversion loses integer precision
