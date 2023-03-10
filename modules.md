## mptctl  
>description: Fusion MPT misc device (ioctl) driver  
>depends: mptbase  
## vmw_pvscsi  
>description: VMware PVSCSI driver  
## cxgb4  
>description: Chelsio T4/T5/T6 Network Driver  
## mdio  
>description: Generic support for MDIO-compatible transceivers  
## e1000e  
>description: Intel(R) PRO/1000 Network Driver  
## ixgb  
>description: Intel(R) PRO/10GbE Network Driver  
## mtk-sd  
>description: MediaTek SD/MMC Card Driver  
>depends: mmc_core  
## marvell10g  
>description: Marvell Alaska X 10Gigabit Ethernet PHY driver (MV88X3310)  
## e1000  
>description: Intel(R) PRO/1000 Network Driver  
## mptscsih  
>description: Fusion MPT SCSI Host driver  
>depends: mptbase  
## m88ds3103  
>description: Montage Technology M88DS3103 DVB-S/S2 demodulator driver  
>depends: regmap-i2c,dvb-core  
## ushc  
>description: USB SD Host Controller driver  
>depends: usbcore,mmc_core  
## sysfillrect  
>description: Generic fill rectangle (sys-to-sys)  
## vub300  
>description: VUB300 USB to SD/MMC/SDIO adapter driver  
>depends: usbcore,mmc_core  
## scsi_transport_sas  
>description: SAS Transport Attributes  
## mmc_core  
>description: null  
## mii  
>description: MII hardware support library  
## atl1e  
>description: Atheros 1000M Ethernet Network Driver  
## crc-itu-t  
>description: CRC ITU-T V.41 calculations  
## jme  
>description: JMicron JMC2x0 PCI Express Ethernet driver  
>depends: mii  
## cfbfillrect  
>description: Generic software accelerated fill rectangle  
## softcursor  
>description: Generic software cursor  
>depends: fb  
## virtio_pci  
>description: virtio-pci  
## dvb-core  
>description: DVB Core Driver  
## si2157  
>description: Silicon Labs Si2146/2147/2148/2157/2158 silicon tuner driver  
## fb_sys_fops  
>description: Generic file read (fb in system RAM)  
## dvb-usb-dib0700  
>description: Driver for devices based on DiBcom DiB0700 - USB bridge  
>depends: dib7000m,dib9000,dibx000_common,dvb-usb,dib0090,dib0070,dib3000mc,usbcore,rc-core  
## virtio_mmio  
>description: Platform bus driver for memory mapped virtio devices  
## virtio_scsi  
>description: Virtio SCSI HBA driver  
>depends: virtio,virtio_ring  
## mmc_block  
>description: Multimedia Card (MMC) block device driver  
>depends: mmc_core  
## sp2  
>description: CIMaX SP2/HF CI driver  
>depends: dvb-core  
## it87  
>description: IT8705F/IT871xF/IT872xF hardware monitoring driver  
>depends: hwmon-vid  
## fbdev  
>description: null  
## vmxnet3  
>description: VMware vmxnet3 virtual NIC driver  
## mlxsw_pci  
>description: Mellanox switch PCI interface driver  
>depends: mlxsw_core  
## igc  
>description: Intel(R) 2.5G Ethernet Linux Driver  
## ehci-hcd  
>description: USB 2.0 'Enhanced' Host Controller (EHCI) Driver  
>depends: usbcore  
## sdhci  
>description: Secure Digital Host Controller Interface core driver  
>depends: mmc_core  
## button  
>description: ACPI Button Driver  
## 8139cp  
>description: RealTek RTL-8139C+ series 10/100 PCI Ethernet driver  
>depends: mii  
## cpufreq_ondemand  
>description: 'cpufreq_ondemand' - A dynamic cpufreq governor for Low Latency Frequency Transition capable processors  
## cxgb  
>description: Chelsio 10Gb Ethernet Driver  
>depends: mdio  
## crc-ccitt  
>description: CRC-CCITT calculations  
## mptsas  
>description: Fusion MPT SAS Host driver  
>depends: mptscsih,mptbase,scsi_transport_sas  
## mlxsw_core  
>description: Mellanox switch device core driver  
## atl1c  
>description: Qualcomm Atheros 100/1000M Ethernet Network Driver  
## atlantic  
>description: Marvell (Aquantia) Corporation(R) Network Driver  
>depends: crc-itu-t  
## bnxt_en  
>description: Broadcom BCM573xx network driver  
>depends: vxlan  
## vga16fb  
>description: Legacy VGA framebuffer device driver  
>depends: cfbfillrect,cfbimgblt,cfbcopyarea,fb,vgastate  
## xhci-hcd  
>description: 'eXtensible' Host Controller (xHC) Driver  
## rc-core  
>description: null  
## r8169  
>description: RealTek RTL-8169 Gigabit Ethernet driver  
>depends: mii  
## xhci-pci  
>description: xHCI PCI Host Controller Driver  
## scsi_transport_spi  
>description: SPI Transport Attributes  
## efifb  
>depends: cfbimgblt,cfbcopyarea,cfbfillrect,fb  
## virtio_net  
>description: Virtio network driver  
>depends: virtio,virtio_ring  
## ehci-pci  
>description: EHCI PCI platform driver  
>depends: usbcore,ehci-hcd  
## r8168  
>description: RealTek RTL-8168 Gigabit Ethernet driver  
## cdc_ncm  
>description: USB CDC NCM host driver  
>depends: usbnet,usbcore  
## bnx2  
>description: QLogic BCM5706/5708/5709/5716 Driver  
## atkbd  
>description: AT and PS/2 keyboard driver  
## raid_class  
>description: RAID device class  
## skge  
>description: SysKonnect Gigabit Ethernet driver  
## cxgb4vf  
>description: Chelsio T4/T5/T6 Virtual Function (VF) Network Driver  
## processor  
>description: ACPI Processor Driver  
## mlx_compat  
>description: Kernel backport module  
## bitblit  
>description: Bit Blitting Operation  
>depends: fb,softcursor  
## sky2  
>description: Marvell Yukon 2 Gigabit Ethernet driver  
## cpufreq_performance  
>description: CPUfreq policy governor 'performance'  
## dvb_usb_v2  
>description: DVB USB common  
>depends: rc-core,dvb-core,usbcore  
## r8125  
>description: Realtek RTL8125 2.5Gigabit Ethernet driver  
## ixgbe  
>description: Intel(R) 10GbE PCI Express Linux Network Driver  
>depends: vxlan  
## via-sdmmc  
>description: VIA SD/MMC Card Interface driver  
>depends: mmc_core  
## auxiliary  
>description: Auxiliary Bus Standalone  
## font  
>description: Console Fonts  
## i2c-algo-bit  
>description: I2C-Bus bit-banging algorithm  
## virtio_input  
>description: Virtio input device driver  
>depends: virtio,virtio_ring  
## cdrom  
>description: null  
## intel_auxiliary  
>description: Auxiliary Bus Standalone  
## mptbase  
>description: Fusion MPT base driver  
## jc42  
>description: JC42 driver  
## ixgbevf  
>description: Intel(R) 10 Gigabit Virtual Function Network Driver  
## ts2020  
>description: Montage Technology TS2020 - Silicon tuner driver module  
>depends: regmap-i2c  
## rtc-cmos  
>description: Driver for PC-style 'CMOS' RTCs  
## acpi-cpufreq  
>description: ACPI Processor P-States Driver  
## etxhci-hcd  
>description: 'eXtensible' Host Controller (xHC) Driver  
>depends: usbcore  
## virtio  
>description: null  
## igbvf  
>description: Intel(R) Gigabit Virtual Function Network Driver  
## aqc111  
>description: Aquantia AQtion USB to 5/2.5GbE Controllers  
>depends: usbnet,usbcore  
## cfbcopyarea  
>description: Generic software accelerated copyarea  
## mlx4_en  
>description: Mellanox ConnectX HCA Ethernet driver  
>depends: mlx4_core,mlx_compat,vxlan  
## sr_mod  
>description: SCSI cdrom (sr) driver  
## dvb-usb-dvbsky  
>description: Driver for DVBSky USB  
>depends: dvb_usb_v2,dvb-core,usbcore,rc-core,m88ds3103  
## amd-xgbe  
>description: AMD 10 Gigabit Ethernet Driver  
## megaraid_sas  
>description: Avago MegaRAID SAS Driver  
## i8042  
>description: i8042 keyboard and mouse controller driver  
## libsas  
>description: SAS Transport Layer  
>depends: scsi_transport_sas  
## thermal  
>description: ACPI Thermal Zone Driver  
>depends: thermal_sys  
## mlx5_core  
>description: Mellanox Connect-IB, ConnectX-4, ConnectX-5 core driver  
>depends: mlx_compat,vxlan  
## cxgb3  
>description: Chelsio T3 Network Driver  
>depends: mdio  
## mlx4_core  
>description: Mellanox ConnectX HCA low-level driver  
>depends: mlx_compat  
## cfbimgblt  
>description: Generic software accelerated imaging drawing  
## uhci-hcd  
>description: USB Universal Host Controller Interface driver  
>depends: usbcore  
## mpt3sas  
>description: LSI MPT Fusion SAS 3.0 & SAS 3.5 Device Driver  
>depends: scsi_transport_sas,raid_class  
## syscopyarea  
>description: Generic copyarea (sys-to-sys)  
## virtio_ring  
>description: null  
## mptspi  
>description: Fusion MPT SPI Host driver  
>depends: mptscsih,mptbase,scsi_transport_spi  
## hid-generic  
>description: HID generic driver  
>depends: hid  
## alx  
>description: Qualcomm Atheros(R) AR816x/AR817x PCI-E Ethernet Network Driver  
>depends: mdio  
## atlantic_v2  
>description: Marvell (Aquantia) Corporation(R) Network Driver  
>depends: crc-itu-t  
## vesafb  
>description: null  
## megaraid_mbox  
>description: LSI Logic MegaRAID Mailbox Driver  
>depends: megaraid_mm  
## bnx2x  
>description: QLogic BCM57710/57711/57711E/57712/57712_MF/57800/57800_MF/57810/57810_MF/57840/57840_MF Driver  
>depends: mdio,vxlan  
## si2168  
>description: Silicon Labs Si2168 DVB-T/T2/C demodulator driver  
## ice  
>description: Intel(R) Ethernet Connection E800 Series Linux Driver  
>depends: vxlan,auxiliary  
## sysimgblt  
>description: 1-bit/8-bit to 1-32 bit color expansion (sys-to-sys)  
## r8152  
>description: Realtek RTL8152/RTL8153 Based USB Ethernet Adapters  
>depends: usbcore  
## i40e  
>description: Intel(R) 40-10 Gigabit Ethernet Connection Network Driver  
>depends: vxlan  
## cpufreq_conservative  
>description: 'cpufreq_conservative' - A dynamic cpufreq governor for Low Latency Frequency Transition capable processors optimised for use in a battery environment  
## dvb-usb  
>description: A library module containing commonly used USB and DVB function USB DVB devices  
>depends: rc-core,dvb-core,usbcore  
## iavf  
>description: Intel(R) Ethernet Adaptive Virtual Function Driver  
>depends: auxiliary  
## nct6775  
>description: Driver for NCT6775F and compatible chips  
>depends: hwmon-vid  
## fb  
>description: null  
## megaraid_mm  
>description: LSI Logic Management Module  
## igb  
>description: Intel(R) Gigabit Ethernet Network Driver  
>depends: i2c-algo-bit  
## be2net  
>description: Emulex OneConnect NIC Driver 10.6.0.3  
>depends: vxlan  
## fbcon  
>depends: fb,font,bitblit  
## vgastate  
>description: VGA State Save/Restore  
## video  
>description: ACPI Video Driver  
>depends: thermal_sys,backlight  
## mpt2sas  
>description: LSI MPT Fusion SAS 2.0 Device Driver  
## tg3  
>description: Broadcom Tigon3 ethernet driver  
>depends: libphy  
## b44  
>description: Broadcom 44xx/47xx 10/100 PCI ethernet driver  
>depends: ssb,libphy,mii  
## cpufreq_governor  
>description: null  
## hwmon-vid  
>description: hwmon-vid driver  
## nvidia-uvm  
>depends: nvidia  
## libphy  
>description: PHY library  
## nvidia  
>description: null  
## mlx5_ib  
>description: Mellanox Connect-IB HCA IB driver  
>depends: mlx5_core,ib_core,mlx_compat  
## mlx4_ib  
>description: Mellanox ConnectX HCA InfiniBand driver  
>depends: mlx4_core,mlx_compat,ib_core  
## drm  
>description: DRM panel infrastructure  
>depends: drm_panel_orientation_quirks  
## drm_kms_helper  
>description: DRM KMS helper  
>depends: drm,fb,fb_sys_fops,cfbfillrect,syscopyarea,cfbimgblt,sysfillrect,sysimgblt,cfbcopyarea  
## backlight  
>description: Backlight Lowlevel Control Abstraction  
## iosf_mbi  
>description: IOSF Mailbox Interface accessor  
## i915.9BC8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## i915.9CA8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## i915.3E98  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## drm_panel_orientation_quirks  
>description: null  
## i915.9BC5  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## mptlan  
>description: Fusion MPT LAN driver  
>depends: mptbase  
## i915  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## generic_bl  
>description: Generic Backlight Driver  
>depends: backlight  
## qla2xxx  
>description: QLogic Fibre Channel HBA Driver  
>depends: scsi_transport_fc  
## i915.9BA8+9BC8  
>description: Intel Graphics  
>depends: drm_kms_helper,drm,iosf_mbi,backlight,video,fb,button,i2c-algo-bit  
## blk-mq-virtio  
>description: null  
## mdio_devres  
>description: null  
## virtio_blk  
>description: Virtio block driver  
>depends: virtio,virtio_ring,blk-mq-virtio  
## usbip-host  
>description: USB/IP Host Driver  
>depends: usbip-core,usbcore  
## usbnet  
>description: USB network driver framework  
>depends: usbcore,mii  
## usbip-core  
>description: USB/IP Core  
>depends: usb-common  
## failover  
>description: Generic failover infrastructure/interface  
## net_failover  
>description: Failover driver for Paravirtual drivers  
>depends: failover  
## r8153_ecm  
>description: Realtek USB ECM device  
>depends: cdc_ether,usbnet,usbcore  
## usb-storage  
>description: USB Mass Storage driver for Linux  
>depends: usbcore  
## usbhid  
>description: USB HID core driver  
>depends: hid,usbcore  
## usbcore  
>description: null  
## usbserial  
>description: USB Serial Driver core  
>depends: usbcore  
## usb-common  
>description: null  
