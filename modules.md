## si2168  
>description: Silicon Labs Si2168 DVB-T/T2/C demodulator driver  
## bnxt_en  
>description: Broadcom BCM573xx network driver  
>depends: vxlan  
## virtio_mmio  
>description: Platform bus driver for memory mapped virtio devices  
## virtio  
>description: null  
## mlx5_core  
>description: Mellanox Connect-IB, ConnectX-4, ConnectX-5 core driver  
>depends: mlx_compat,vxlan  
## iavf  
>description: Intel(R) Ethernet Adaptive Virtual Function Driver  
>depends: auxiliary  
## vesafb  
>description: null  
## ehci-pci  
>description: EHCI PCI platform driver  
>depends: usbcore,ehci-hcd  
## sysfillrect  
>description: Generic fill rectangle (sys-to-sys)  
## i8042  
>description: i8042 keyboard and mouse controller driver  
## rc-core  
>description: null  
## jc42  
>description: JC42 driver  
## virtio_net  
>description: Virtio network driver  
>depends: virtio,virtio_ring  
## mlxsw_pci  
>description: Mellanox switch PCI interface driver  
>depends: mlxsw_core  
## vmxnet3  
>description: VMware vmxnet3 virtual NIC driver  
## fb  
>description: null  
## sdhci  
>description: Secure Digital Host Controller Interface core driver  
>depends: mmc_core  
## vgastate  
>description: VGA State Save/Restore  
## ice  
>description: Intel(R) Ethernet Connection E800 Series Linux Driver  
>depends: vxlan,auxiliary  
## bnx2x  
>description: QLogic BCM57710/57711/57711E/57712/57712_MF/57800/57800_MF/57810/57810_MF/57840/57840_MF Driver  
>depends: mdio,vxlan  
## ixgbe  
>description: Intel(R) 10GbE PCI Express Linux Network Driver  
>depends: vxlan  
## mptbase  
>description: Fusion MPT base driver  
## virtio_pci  
>description: virtio-pci  
## cxgb4vf  
>description: Chelsio T4/T5/T6 Virtual Function (VF) Network Driver  
## mlx4_en  
>description: Mellanox ConnectX HCA Ethernet driver  
>depends: mlx4_core,mlx_compat,vxlan  
## e1000e  
>description: Intel(R) PRO/1000 Network Driver  
## igbvf  
>description: Intel(R) Gigabit Virtual Function Network Driver  
## megaraid_mbox  
>description: LSI Logic MegaRAID Mailbox Driver  
>depends: megaraid_mm  
## uhci-hcd  
>description: USB Universal Host Controller Interface driver  
>depends: usbcore  
## dvb_usb_v2  
>description: DVB USB common  
>depends: rc-core,dvb-core,usbcore  
## dvb-usb-dvbsky  
>description: Driver for DVBSky USB  
>depends: dvb_usb_v2,dvb-core,usbcore,rc-core,m88ds3103  
## megaraid_mm  
>description: LSI Logic Management Module  
## atlantic_v2  
>description: Marvell (Aquantia) Corporation(R) Network Driver  
>depends: crc-itu-t  
## mptspi  
>description: Fusion MPT SPI Host driver  
>depends: mptscsih,mptbase,scsi_transport_spi  
## xhci-pci  
>description: xHCI PCI Host Controller Driver  
## atl1c  
>description: Qualcomm Atheros 100/1000M Ethernet Network Driver  
## megaraid_sas  
>description: Avago MegaRAID SAS Driver  
## dvb-usb-dib0700  
>description: Driver for devices based on DiBcom DiB0700 - USB bridge  
>depends: dib7000m,dib9000,dibx000_common,dvb-usb,dib0090,dib0070,dib3000mc,usbcore,rc-core  
## ehci-hcd  
>description: USB 2.0 'Enhanced' Host Controller (EHCI) Driver  
>depends: usbcore  
## scsi_transport_spi  
>description: SPI Transport Attributes  
## ixgbevf  
>description: Intel(R) 10 Gigabit Virtual Function Network Driver  
## cxgb  
>description: Chelsio 10Gb Ethernet Driver  
>depends: mdio  
## sr_mod  
>description: SCSI cdrom (sr) driver  
## jme  
>description: JMicron JMC2x0 PCI Express Ethernet driver  
>depends: mii  
## mii  
>description: MII hardware support library  
## cpufreq_ondemand  
>description: 'cpufreq_ondemand' - A dynamic cpufreq governor for Low Latency Frequency Transition capable processors  
## syscopyarea  
>description: Generic copyarea (sys-to-sys)  
## mptctl  
>description: Fusion MPT misc device (ioctl) driver  
>depends: mptbase  
## dvb-usb  
>description: A library module containing commonly used USB and DVB function USB DVB devices  
>depends: rc-core,dvb-core,usbcore  
## font  
>description: Console Fonts  
## igc  
>description: Intel(R) 2.5G Ethernet Linux Driver  
## cxgb3  
>description: Chelsio T3 Network Driver  
>depends: mdio  
## bitblit  
>description: Bit Blitting Operation  
>depends: fb,softcursor  
## si2157  
>description: Silicon Labs Si2146/2147/2148/2157/2158 silicon tuner driver  
## m88ds3103  
>description: Montage Technology M88DS3103 DVB-S/S2 demodulator driver  
>depends: regmap-i2c,dvb-core  
## it87  
>description: IT8705F/IT871xF/IT872xF hardware monitoring driver  
>depends: hwmon-vid  
## fbcon  
>depends: fb,font,bitblit  
## button  
>description: ACPI Button Driver  
## ts2020  
>description: Montage Technology TS2020 - Silicon tuner driver module  
>depends: regmap-i2c  
## alx  
>description: Qualcomm Atheros(R) AR816x/AR817x PCI-E Ethernet Network Driver  
>depends: mdio  
## marvell10g  
>description: Marvell Alaska X 10Gigabit Ethernet PHY driver (MV88X3310)  
## atlantic  
>description: Marvell (Aquantia) Corporation(R) Network Driver  
>depends: crc-itu-t  
## mdio  
>description: Generic support for MDIO-compatible transceivers  
## vub300  
>description: VUB300 USB to SD/MMC/SDIO adapter driver  
>depends: usbcore,mmc_core  
## mmc_block  
>description: Multimedia Card (MMC) block device driver  
>depends: mmc_core  
## r8152  
>description: Realtek RTL8152/RTL8153 Based USB Ethernet Adapters  
>depends: usbcore  
## mptsas  
>description: Fusion MPT SAS Host driver  
>depends: mptscsih,mptbase,scsi_transport_sas  
## virtio_input  
>description: Virtio input device driver  
>depends: virtio,virtio_ring  
## softcursor  
>description: Generic software cursor  
>depends: fb  
## rtc-cmos  
>description: Driver for PC-style 'CMOS' RTCs  
## atl1e  
>description: Atheros 1000M Ethernet Network Driver  
## r8169  
>description: RealTek RTL-8169 Gigabit Ethernet driver  
>depends: mii  
## mlx_compat  
>description: Kernel backport module  
## be2net  
>description: Emulex OneConnect NIC Driver 10.6.0.3  
>depends: vxlan  
## thermal  
>description: ACPI Thermal Zone Driver  
>depends: thermal_sys  
## virtio_ring  
>description: null  
## via-sdmmc  
>description: VIA SD/MMC Card Interface driver  
>depends: mmc_core  
## fbdev  
>description: null  
## cpufreq_performance  
>description: CPUfreq policy governor 'performance'  
## r8125  
>description: Realtek RTL8125 2.5Gigabit Ethernet driver  
## cfbfillrect  
>description: Generic software accelerated fill rectangle  
## i40e  
>description: Intel(R) 40-10 Gigabit Ethernet Connection Network Driver  
>depends: vxlan  
## hid-generic  
>description: HID generic driver  
>depends: hid  
## i2c-algo-bit  
>description: I2C-Bus bit-banging algorithm  
## ushc  
>description: USB SD Host Controller driver  
>depends: usbcore,mmc_core  
## mlxsw_core  
>description: Mellanox switch device core driver  
## sky2  
>description: Marvell Yukon 2 Gigabit Ethernet driver  
## mtk-sd  
>description: MediaTek SD/MMC Card Driver  
>depends: mmc_core  
## scsi_transport_sas  
>description: SAS Transport Attributes  
## cfbcopyarea  
>description: Generic software accelerated copyarea  
## mlx4_core  
>description: Mellanox ConnectX HCA low-level driver  
>depends: mlx_compat  
## vmw_pvscsi  
>description: VMware PVSCSI driver  
## sysimgblt  
>description: 1-bit/8-bit to 1-32 bit color expansion (sys-to-sys)  
## xhci-hcd  
>description: 'eXtensible' Host Controller (xHC) Driver  
## libsas  
>description: SAS Transport Layer  
>depends: scsi_transport_sas  
## amd-xgbe  
>description: AMD 10 Gigabit Ethernet Driver  
## mpt3sas  
>description: LSI MPT Fusion SAS 3.0 & SAS 3.5 Device Driver  
>depends: scsi_transport_sas,raid_class  
## crc-ccitt  
>description: CRC-CCITT calculations  
## cdc_ncm  
>description: USB CDC NCM host driver  
>depends: usbnet,usbcore  
## cxgb4  
>description: Chelsio T4/T5/T6 Network Driver  
## r8168  
>description: RealTek RTL-8168 Gigabit Ethernet driver  
## raid_class  
>description: RAID device class  
## cdrom  
>description: null  
## virtio_scsi  
>description: Virtio SCSI HBA driver  
>depends: virtio,virtio_ring  
## mmc_core  
>description: null  
## processor  
>description: ACPI Processor Driver  
## vga16fb  
>description: Legacy VGA framebuffer device driver  
>depends: cfbfillrect,cfbimgblt,cfbcopyarea,fb,vgastate  
## fb_sys_fops  
>description: Generic file read (fb in system RAM)  
## cfbimgblt  
>description: Generic software accelerated imaging drawing  
## auxiliary  
>description: Auxiliary Bus Standalone  
## bnx2  
>description: QLogic BCM5706/5708/5709/5716 Driver  
## igb  
>description: Intel(R) Gigabit Ethernet Network Driver  
>depends: i2c-algo-bit  
## ixgb  
>description: Intel(R) PRO/10GbE Network Driver  
## sp2  
>description: CIMaX SP2/HF CI driver  
>depends: dvb-core  
## e1000  
>description: Intel(R) PRO/1000 Network Driver  
## dvb-core  
>description: DVB Core Driver  
## intel_auxiliary  
>description: Auxiliary Bus Standalone  
## acpi-cpufreq  
>description: ACPI Processor P-States Driver  
## cpufreq_conservative  
>description: 'cpufreq_conservative' - A dynamic cpufreq governor for Low Latency Frequency Transition capable processors optimised for use in a battery environment  
## mptscsih  
>description: Fusion MPT SCSI Host driver  
>depends: mptbase  
## 8139cp  
>description: RealTek RTL-8139C+ series 10/100 PCI Ethernet driver  
>depends: mii  
## atkbd  
>description: AT and PS/2 keyboard driver  
## efifb  
>depends: cfbimgblt,cfbcopyarea,cfbfillrect,fb  
## skge  
>description: SysKonnect Gigabit Ethernet driver  
## nct6775  
>description: Driver for NCT6775F and compatible chips  
>depends: hwmon-vid  
## aqc111  
>description: Aquantia AQtion USB to 5/2.5GbE Controllers  
>depends: usbnet,usbcore  
## crc-itu-t  
>description: CRC ITU-T V.41 calculations  
## etxhci-hcd  
>description: 'eXtensible' Host Controller (xHC) Driver  
>depends: usbcore  
## libphy  
>description: PHY library  
## mlx5_ib  
>description: Mellanox Connect-IB HCA IB driver  
>depends: mlx5_core,ib_core,mlx_compat  
## tg3  
>description: Broadcom Tigon3 ethernet driver  
>depends: libphy  
## mlx4_ib  
>description: Mellanox ConnectX HCA InfiniBand driver  
>depends: mlx4_core,mlx_compat,ib_core  
## b44  
>description: Broadcom 44xx/47xx 10/100 PCI ethernet driver  
>depends: ssb,libphy,mii  
## qla2xxx  
>description: QLogic Fibre Channel HBA Driver  
>depends: scsi_transport_fc  
## video  
>description: ACPI Video Driver  
>depends: thermal_sys,backlight  
## mpt2sas  
>description: LSI MPT Fusion SAS 2.0 Device Driver  
## hwmon-vid  
>description: hwmon-vid driver  
## i915.3E98  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## iosf_mbi  
>description: IOSF Mailbox Interface accessor  
## i915.9BC8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## backlight  
>description: Backlight Lowlevel Control Abstraction  
## i915.9CA8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## i915  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## drm_kms_helper  
>description: DRM KMS helper  
>depends: drm,fb,fb_sys_fops,cfbfillrect,syscopyarea,cfbimgblt,sysfillrect,sysimgblt,cfbcopyarea  
## i915.9BC5  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## cpufreq_governor  
>description: null  
## drm  
>description: DRM panel infrastructure  
>depends: drm_panel_orientation_quirks  
## mptlan  
>description: Fusion MPT LAN driver  
>depends: mptbase  
## drm_panel_orientation_quirks  
>description: null  
## generic_bl  
>description: Generic Backlight Driver  
>depends: backlight  
## nvidia-uvm  
>depends: nvidia  
## nvidia  
>description: null  
## usb-storage  
>description: USB Mass Storage driver for Linux  
>depends: usbcore  
## usbserial  
>description: USB Serial Driver core  
>depends: usbcore  
## usbhid  
>description: USB HID core driver  
>depends: hid,usbcore  
## usbip-core  
>description: USB/IP Core  
>depends: usb-common  
## usbip-host  
>description: USB/IP Host Driver  
>depends: usbip-core,usbcore  
## r8153_ecm  
>description: Realtek USB ECM device  
>depends: cdc_ether,usbnet,usbcore  
## usbcore  
>description: null  
## usb-common  
>description: null  
## net_failover  
>description: Failover driver for Paravirtual drivers  
>depends: failover  
## blk-mq-virtio  
>description: null  
## virtio_blk  
>description: Virtio block driver  
>depends: virtio,virtio_ring,blk-mq-virtio  
## failover  
>description: Generic failover infrastructure/interface  
## mdio_devres  
>description: null  
## usbnet  
>description: USB network driver framework  
>depends: usbcore,mii  
## i915.9BA8+9BC8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
