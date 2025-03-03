laptop-3ac2iad3
    description: Computer
    width: 64 bits
    capabilities: smp vsyscall32
  *-core
       description: Motherboard
       physical id: 0
     *-memory
          description: System memory
          physical id: 0
          size: 15GiB
     *-cpu
          product: AMD Ryzen AI 9 HX 370 w/ Radeon 890M
          vendor: Advanced Micro Devices [AMD]
          physical id: 1
          bus info: cpu@0
          version: 26.36.0
          width: 64 bits
          capabilities: fpu fpu_exception wp vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp x86-64 constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid pni pclmulqdq ssse3 fma cx16 sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext perfctr_core ssbd ibrs ibpb stibp vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid avx512f avx512dq rdseed adx smap avx512ifma clflushopt clwb avx512cd sha_ni avx512bw avx512vl xsaveopt xsavec xgetbv1 xsaves avx_vnni avx512_bf16 clzero xsaveerptr arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload avx512vbmi umip avx512_vbmi2 gfni vaes vpclmulqdq avx512_vnni avx512_bitalg avx512_vpopcntdq rdpid fsrm avx512_vp2intersect
          configuration: microcode=4294967295
     *-display:0
          description: 3D controller
          product: Microsoft Corporation
          vendor: Microsoft Corporation
          physical id: 2
          bus info: pci@1ff3:00:00.0
          version: 00
          width: 32 bits
          clock: 33MHz
          capabilities: bus_master cap_list
          configuration: driver=dxgkrnl latency=0
          resources: irq:0
     *-display:1
          description: 3D controller
          product: Basic Render Driver
          vendor: Microsoft Corporation
          physical id: 3
          bus info: pci@39f8:00:00.0
          version: 00
          width: 32 bits
          clock: 33MHz
          capabilities: bus_master cap_list
          configuration: driver=dxgkrnl latency=0
          resources: irq:0
     *-generic
          description: System peripheral
          product: Virtio file system
          vendor: Red Hat, Inc.
          physical id: 4
          bus info: pci@5199:00:00.0
          version: 01
          width: 64 bits
          clock: 33MHz
          capabilities: msix bus_master cap_list
          configuration: driver=virtio-pci latency=64
          resources: iomemory:e0-df iomemory:e0-df iomemory:c0-bf irq:0 memory:e00000000-e00000fff memory:e00001000-e00001fff memory:c00000000-dffffffff
        *-virtio1 UNCLAIMED
             description: Virtual I/O device
             physical id: 0
             bus info: virtio@1
             configuration: driver=virtiofs
     *-scsi:0
          description: SCSI storage controller
          product: Virtio 1.0 console
          vendor: Red Hat, Inc.
          physical id: 5
          bus info: pci@5582:00:00.0
          version: 01
          width: 64 bits
          clock: 33MHz
          capabilities: scsi msix bus_master cap_list
          configuration: driver=virtio-pci latency=64
          resources: iomemory:90-8f iomemory:90-8f iomemory:90-8f irq:0 memory:9ffe00000-9ffe00fff memory:9ffe01000-9ffe01fff memory:9ffe02000-9ffe02fff
        *-virtio0 UNCLAIMED
             description: Virtual I/O device
             physical id: 0
             bus info: virtio@0
             configuration: driver=virtio_console
     *-pnp00:00
          product: PnP device PNP0b00
          physical id: 6
          capabilities: pnp
          configuration: driver=rtc_cmos
     *-scsi:1
          physical id: 7
          logical name: scsi0
        *-disk:0
             description: SCSI Disk
             product: Virtual Disk
             vendor: Linux
             physical id: 0.0.0
             bus info: scsi@0:0.0.0
             logical name: /dev/sda
             version: 1.0
             size: 388MiB
             capabilities: extended_attributes large_files huge_files extents ext2 initialized
             configuration: ansiversion=5 filesystem=ext2 logicalsectorsize=512 sectorsize=512 state=clean
        *-disk:1
             description: Linux swap volume
             product: Virtual Disk
             vendor: Msft
             physical id: 0.0.1
             bus info: scsi@0:0.0.1
             logical name: /dev/sdb
             version: 1
             serial: 8c7cd9df-3f07-44f6-8f1e-215e46521908
             size: 4GiB
             capacity: 4GiB
             capabilities: swap initialized
             configuration: ansiversion=5 filesystem=swap logicalsectorsize=512 pagesize=4096 sectorsize=4096
        *-disk:2
             description: EXT4 volume
             product: Virtual Disk
             vendor: Linux
             physical id: 0.0.2
             bus info: scsi@0:0.0.2
             logical name: /dev/sdc
             logical name: /
             logical name: /mnt/wslg/distro
             version: 1.0
             serial: 15bffabf-30cf-47f8-9cf8-aa5036f56aa5
             size: 1TiB
             capabilities: journaled extended_attributes large_files huge_files dir_nlink recover 64bit extents ext4 ext2 initialized
             configuration: ansiversion=5 created=2025-03-03 17:03:37 filesystem=ext4 lastmountpoint=/distro logicalsectorsize=512 modified=2025-03-03 17:04:40 mount.fstype=ext4 mount.options=ro,relatime,discard,errors=remount-ro,data=ordered mounted=2025-03-03 17:04:40 sectorsize=4096 state=mounted
  *-usbhost:0
       product: USB/IP Virtual Host Controller
       vendor: Linux 5.15.153.1-microsoft-standard-WSL2 vhci_hcd
       physical id: 1
       bus info: usb@1
       logical name: usb1
       version: 5.15
       capabilities: usb-2.00
       configuration: driver=hub slots=8 speed=480Mbit/s
  *-usbhost:1
       product: USB/IP Virtual Host Controller
       vendor: Linux 5.15.153.1-microsoft-standard-WSL2 vhci_hcd
       physical id: 2
       bus info: usb@2
       logical name: usb2
       version: 5.15
       capabilities: usb-3.00
       configuration: driver=hub slots=8 speed=5000Mbit/s
  *-network
       description: Ethernet interface
       physical id: 3
       logical name: eth0
       serial: 00:15:5d:27:b3:63
       size: 10Gbit/s
       capabilities: ethernet physical
       configuration: autonegotiation=off broadcast=yes driver=hv_netvsc driverversion=5.15.153.1-microsoft-standard-W duplex=full firmware=N/A ip=172.31.199.248 link=yes multicast=yes speed=10Gbit/s
