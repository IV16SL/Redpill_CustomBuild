## mlx4_en  
>description: Mellanox ConnectX HCA Ethernet driver  
>depends: mlx4_core  
## scsi_transport_sas  
>description: SAS Transport Attributes  
## mdio  
>description: Generic support for MDIO-compatible transceivers  
## intel_auxiliary  
>description: Auxiliary Bus Standalone  
## igbvf  
>description: Intel(R) Gigabit Virtual Function Network Driver  
## usbip-core  
>description: USB/IP Core  
>depends: usb-common  
## e1000  
>description: Intel(R) PRO/1000 Network Driver  
## virtio_scsi  
>description: Virtio SCSI HBA driver  
>depends: virtio,virtio_ring,blk-mq-virtio  
## bnx2x  
>description: QLogic BCM57710/57711/57711E/57712/57712_MF/57800/57800_MF/57810/57810_MF/57840/57840_MF Driver  
>depends: mdio,vxlan  
## usbnet  
>description: USB network driver framework  
>depends: usbcore,mii  
## virtio_blk  
>description: Virtio block driver  
>depends: virtio,virtio_ring,blk-mq-virtio  
## ehci-pci  
>description: EHCI PCI platform driver  
>depends: usbcore,ehci-hcd  
## nct6775  
>description: Driver for NCT6775F and compatible chips  
>depends: hwmon-vid  
## alx  
>description: Qualcomm Atheros(R) AR816x/AR817x PCI-E Ethernet Network Driver  
>depends: mdio  
## cdc_ncm  
>description: USB CDC NCM host driver  
>depends: usbnet,cdc_ether,usbcore  
## ixgb  
>description: Intel(R) PRO/10GbE Network Driver  
## virtio_input  
>description: Virtio input device driver  
>depends: virtio,virtio_ring  
## e1000e  
>description: Intel(R) PRO/1000 Network Driver  
## thermal  
>description: ACPI Thermal Zone Driver  
>depends: thermal_sys  
## xhci-hcd  
>description: 'eXtensible' Host Controller (xHC) Driver  
## mlx5_core  
>description: Mellanox 5th generation network adapters (ConnectX series) core driver  
>depends: mlx_compat,vxlan  
## aqc111  
>description: Aquantia AQtion USB to 5/2.5GbE Controllers  
>depends: usbnet,usbcore  
## usb-common  
>description: null  
## auxiliary  
>description: Auxiliary Bus Standalone  
## atl1e  
>description: Atheros 1000M Ethernet Network Driver  
## igc  
>description: Intel(R) 2.5G Ethernet Linux Driver  
## sky2  
>description: Marvell Yukon 2 Gigabit Ethernet driver  
## failover  
>description: Generic failover infrastructure/interface  
## virtio_pci  
>description: virtio-pci  
## virtio_net  
>description: Virtio network driver  
>depends: virtio,net_failover,virtio_ring  
## r8169  
>description: RealTek RTL-8169 Gigabit Ethernet driver  
>depends: libphy,mdio_devres  
## ehci-hcd  
>description: USB 2.0 'Enhanced' Host Controller (EHCI) Driver  
>depends: usbcore  
## xhci-pci  
>description: xHCI PCI Host Controller Driver  
## qla2xxx  
>description: QLogic Fibre Channel HBA Driver  
>depends: scsi_transport_fc  
## usb-storage  
>description: USB Mass Storage driver for Linux  
>depends: usbcore  
## virtio_ring  
>description: null  
## cfbfillrect  
>description: Generic software accelerated fill rectangle  
## r8168  
>description: RealTek RTL-8168 Gigabit Ethernet driver  
## mlx4_core  
>description: Mellanox ConnectX HCA low-level driver  
>depends: mlx_compat  
## ixgbevf  
>description: Intel(R) 10 Gigabit Virtual Function Network Driver  
## vmxnet3  
>description: VMware vmxnet3 virtual NIC driver  
## fb  
>description: null  
## r8152  
>description: Realtek RTL8152/RTL8153 Based USB Ethernet Adapters  
>depends: usbcore,mii  
## atlantic  
>description: Marvell (Aquantia) Corporation(R) Network Driver  
>depends: crc-itu-t  
## mpt3sas  
>description: LSI MPT Fusion SAS 3.0 Device Driver  
>depends: scsi_transport_sas  
## atl1c  
>description: Qualcomm Atheros 100/1000M Ethernet Network Driver  
## vmw_pvscsi  
>description: VMware PVSCSI driver  
## mdio_devres  
>description: null  
## libphy  
>description: PHY library  
## virtio  
>description: null  
## hwmon-vid  
>description: hwmon-vid driver  
## mlx5_ib  
>description: Mellanox 5th generation network adapters (ConnectX series) IB driver  
>depends: mlx5_core,ib_core  
## i2c-algo-bit  
>description: I2C-Bus bit-banging algorithm  
## ixgbe  
>description: Intel(R) 10GbE PCI Express Linux Network Driver  
>depends: dca,vxlan  
## vesafb  
>description: null  
## atlantic_v2  
>description: Marvell (Aquantia) Corporation(R) Network Driver  
>depends: crc-itu-t  
## usbip-host  
>description: USB/IP Host Driver  
>depends: usbip-core,usbcore  
## acpi-cpufreq  
>description: ACPI Processor P-States Driver  
## blk-mq-virtio  
>description: null  
## cfbcopyarea  
>description: Generic software accelerated copyarea  
## rtc-cmos  
>description: Driver for PC-style 'CMOS' RTCs  
## cfbimgblt  
>description: Generic software accelerated imaging drawing  
## i40e  
>description: Intel(R) 40-10 Gigabit Ethernet Connection Network Driver  
>depends: intel_auxiliary  
## usbcore  
>description: null  
## skge  
>description: SysKonnect Gigabit Ethernet driver  
## iavf  
>description: Intel(R) Ethernet Adaptive Virtual Function Driver  
>depends: intel_auxiliary  
## r8153_ecm  
>description: Realtek USB ECM device  
>depends: cdc_ether,usbnet,usbcore  
## mlx4_ib  
>description: Mellanox ConnectX HCA InfiniBand driver  
>depends: mlx4_core,ib_core  
## be2net  
>description: Emulex OneConnect NIC Driver  
>depends: vxlan  
## font  
>description: Console Fonts  
## usbhid  
>description: USB HID core driver  
>depends: hid,usbcore  
## virtio_mmio  
>description: Platform bus driver for memory mapped virtio devices  
## net_failover  
>description: Failover driver for Paravirtual drivers  
>depends: failover  
## tg3  
>description: Broadcom Tigon3 ethernet driver  
>depends: libphy  
## usbserial  
>description: USB Serial Driver core  
>depends: usbcore  
## mii  
>description: MII hardware support library  
## igb  
>description: Intel(R) Gigabit Ethernet Linux Driver  
>depends: dca  
## efifb  
>depends: cfbimgblt,cfbcopyarea,cfbfillrect,fb  
## processor  
>description: ACPI Processor Driver  
## megaraid_sas  
>description: Avago MegaRAID SAS Driver  
## uhci-hcd  
>description: USB Universal Host Controller Interface driver  
>depends: usbcore  
## button  
>description: ACPI Button Driver  
## mptctl  
>description: Fusion MPT misc device (ioctl) driver  
>depends: mptbase  
## fbcon  
>depends: fb,font,bitblit  
## sdhci  
>description: Secure Digital Host Controller Interface core driver  
>depends: mmc_core  
## dvb-usb-dib0700  
>description: Driver for devices based on DiBcom DiB0700 - USB bridge  
>depends: dib7000m,dib9000,dibx000_common,dvb-usb,dib0090,dib0070,dib3000mc,usbcore,rc-core  
## mtk-sd  
>description: MediaTek SD/MMC Card Driver  
>depends: mmc_core  
## cpufreq_conservative  
>description: 'cpufreq_conservative' - A dynamic cpufreq governor for Low Latency Frequency Transition capable processors optimised for use in a battery environment  
## ice  
>description: Intel(R) Ethernet Connection E800 Series Linux Driver  
>depends: vxlan,auxiliary  
## r8125  
>description: Realtek RTL8125 2.5Gigabit Ethernet driver  
## dvb-core  
>description: DVB Core Driver  
## via-sdmmc  
>description: VIA SD/MMC Card Interface driver  
>depends: mmc_core  
## si2168  
>description: Silicon Labs Si2168 DVB-T/T2/C demodulator driver  
## mlx_compat  
>description: Kernel backport module  
## sp2  
>description: CIMaX SP2/HF CI driver  
>depends: dvb-core  
## 8139cp  
>description: RealTek RTL-8139C+ series 10/100 PCI Ethernet driver  
>depends: mii  
## cpufreq_ondemand  
>description: 'cpufreq_ondemand' - A dynamic cpufreq governor for Low Latency Frequency Transition capable processors  
## fb_sys_fops  
>description: Generic file read (fb in system RAM)  
## mmc_core  
>description: null  
## mlxsw_pci  
>description: Mellanox switch PCI interface driver  
>depends: mlxsw_core  
## atkbd  
>description: AT and PS/2 keyboard driver  
## mptscsih  
>description: Fusion MPT SCSI Host driver  
>depends: mptbase  
## ushc  
>description: USB SD Host Controller driver  
>depends: usbcore,mmc_core  
## crc-itu-t  
>description: CRC ITU-T V.41 calculations  
## sysfillrect  
>description: Generic fill rectangle (sys-to-sys)  
## hid-generic  
>description: HID generic driver  
>depends: hid  
## sr_mod  
>description: SCSI cdrom (sr) driver  
## scsi_transport_spi  
>description: SPI Transport Attributes  
## mptsas  
>description: Fusion MPT SAS Host driver  
>depends: mptscsih,mptbase  
## rc-core  
>description: null  
## vgastate  
>description: VGA State Save/Restore  
## mlxsw_core  
>description: Mellanox switch device core driver  
## m88ds3103  
>description: Montage Technology M88DS3103 DVB-S/S2 demodulator driver  
>depends: regmap-i2c,dvb-core  
## b44  
>description: Broadcom 44xx/47xx 10/100 PCI ethernet driver  
>depends: ssb,libphy,mii  
## dvb-usb  
>description: A library module containing commonly used USB and DVB function USB DVB devices  
>depends: rc-core,dvb-core,usbcore  
## cxgb3  
>description: Chelsio T3 Network Driver  
>depends: mdio  
## mptbase  
>description: Fusion MPT base driver  
## syscopyarea  
>description: Generic copyarea (sys-to-sys)  
## sysimgblt  
>description: 1-bit/8-bit to 1-32 bit color expansion (sys-to-sys)  
## dvb_usb_v2  
>description: DVB USB common  
>depends: rc-core,dvb-core,usbcore  
## megaraid_mbox  
>description: LSI Logic MegaRAID Mailbox Driver  
>depends: megaraid_mm  
## dvb-usb-dvbsky  
>description: Driver for DVBSky USB  
>depends: dvb_usb_v2,dvb-core,usbcore,rc-core,m88ds3103  
## cdrom  
>description: null  
## cpufreq_performance  
>description: CPUfreq policy governor 'performance'  
## vga16fb  
>description: Legacy VGA framebuffer device driver  
>depends: cfbfillrect,cfbimgblt,cfbcopyarea,fb,vgastate  
## bnx2  
>description: QLogic BCM5706/5708/5709/5716 Driver  
## cxgb4vf  
>description: Chelsio T4/T5/T6 Virtual Function (VF) Network Driver  
## crc-ccitt  
>description: CRC-CCITT calculations  
## fbdev  
>description: null  
## vub300  
>description: VUB300 USB to SD/MMC/SDIO adapter driver  
>depends: usbcore,mmc_core  
## bitblit  
>description: Bit Blitting Operation  
>depends: fb,softcursor  
## i8042  
>description: i8042 keyboard and mouse controller driver  
## mmc_block  
>description: Multimedia Card (MMC) block device driver  
>depends: mmc_core  
## si2157  
>description: Silicon Labs Si2146/2147/2148/2157/2158 silicon tuner driver  
## bnxt_en  
>description: Broadcom BCM573xx network driver  
>depends: vxlan  
## jc42  
>description: JC42 driver  
## jme  
>description: JMicron JMC2x0 PCI Express Ethernet driver  
>depends: mii  
## cxgb  
>description: Chelsio 10Gb Ethernet Driver  
>depends: mdio  
## cxgb4  
>description: Chelsio T4/T5/T6 Network Driver  
## it87  
>description: IT8705F/IT871xF/IT872xF hardware monitoring driver  
>depends: hwmon-vid  
## ts2020  
>description: Montage Technology TS2020 - Silicon tuner driver module  
>depends: regmap-i2c  
## softcursor  
>description: Generic software cursor  
>depends: fb  
## etxhci-hcd  
>description: 'eXtensible' Host Controller (xHC) Driver  
>depends: usbcore  
## mptspi  
>description: Fusion MPT SPI Host driver  
>depends: mptscsih,mptbase,scsi_transport_spi  
## megaraid_mm  
>description: LSI Logic Management Module  
## libsas  
>description: SAS Transport Layer  
>depends: scsi_transport_sas  
## amd-xgbe  
>description: AMD 10 Gigabit Ethernet Driver  
## marvell10g  
>description: Marvell Alaska X 10Gigabit Ethernet PHY driver (MV88X3310)  
## raid_class  
>description: RAID device class  
## mptlan  
>description: Fusion MPT LAN driver  
>depends: mptbase  
## video  
>description: ACPI Video Driver  
>depends: backlight  
## i915  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## iosf_mbi  
>description: IOSF Mailbox Interface accessor  
## backlight  
>description: Backlight Lowlevel Control Abstraction  
## i915.3E98  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## i915.9CA8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## drm  
>description: DRM panel infrastructure  
>depends: drm_panel_orientation_quirks  
## cpufreq_governor  
>description: null  
## i915.9BC5  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## i915.9BC8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## generic_bl  
>description: Generic Backlight Driver  
>depends: backlight  
## drm_kms_helper  
>description: DRM KMS helper  
>depends: drm,fb,fb_sys_fops,cfbfillrect,syscopyarea,cfbimgblt,sysfillrect,sysimgblt,cfbcopyarea  
## drm_panel_orientation_quirks  
>description: null  
## i915.9BA8+9BC8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## mpt2sas  
>description: LSI MPT Fusion SAS 2.0 Device Driver  
## nvidia  
>description: null  
## nvidia-uvm  
>depends: nvidia  
