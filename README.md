This is a sample .VMX file to run OpenVMS hobbyist VMDK.
It uses sata disks 0.0 for the cd and sata 0:1 for the vmdk supplied by VSI. Uses EFI boot. And the serial console is set up.
You'll need to change the switch and vm mac address and the path to the vmdk. And it should just work. You'll
need to connect via software serial port from a vm on the same host. Then you can enable tcp/ip services.
