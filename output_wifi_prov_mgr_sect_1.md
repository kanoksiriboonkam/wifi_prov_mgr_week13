I (44) bo�ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:7176
load:0x40078000,len:15564
ho 0 tail 12 room 4
load:0x40080400,len:4
--- 0x40080400: _init at ??:?

load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.3.1 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 13:41:44
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v3.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00140000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2b8d8h (178392) map
I (165) esp_image: segment 1: paddr=0003b900 vaddr=3ffbdb60 size=04718h ( 18200) load
I (172) esp_image: segment 2: paddr=00040020 vaddr=400d0020 size=bb524h (767268) map
I (436) esp_image: segment 3: paddr=000fb54c vaddr=3ffc2278 size=014c8h (  5320) load
I (438) esp_image: segment 4: paddr=000fca1c vaddr=40080000 size=1bfc0h (114624) load
I (500) boot: Loaded app from partition at offset 0x10000
I (501) boot: Disabling RNG early entropy source...
I (513) cpu_start: Multicore app
I (521) cpu_start: Pro cpu start user code
I (521) cpu_start: cpu freq: 160000000 Hz
I (521) app_init: Application information:
I (524) app_init: Project name:     test
I (529) app_init: App version:      1
I (533) app_init: Compile time:     Sep 26 2024 13:41:16
I (539) app_init: ELF file SHA256:  bb250b3d9...
I (544) app_init: ESP-IDF:          v5.3.1
I (549) efuse_init: Min chip rev:     v0.0
I (554) efuse_init: Max chip rev:     v3.99 
I (559) efuse_init: Chip rev:         v3.0
I (564) heap_init: Initializing. RAM available for dynamic allocation:
I (571) heap_init: At 3FFAFF10 len 000000F0 (0 KiB): DRAM
I (577) heap_init: At 3FFB6388 len 00001C78 (7 KiB): DRAM
I (583) heap_init: At 3FFB9A20 len 00004108 (16 KiB): DRAM
I (589) heap_init: At 3FFC9F38 len 000160C8 (88 KiB): DRAM
I (595) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (601) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (608) heap_init: At 4009BFC0 len 00004040 (16 KiB): IRAM
I (616) spi_flash: detected chip: generic
I (619) spi_flash: flash io: dio
W (623) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (637) coexist: coex firmware version: 4482466
I (642) main_task: Started on CPU0
I (652) main_task: Calling app_main()
I (682) wifi:wifi driver task: 3ffcdd9c, prio:23, stack:6656, core=0
I (682) wifi:wifi firmware version: ccaebfa
I (682) wifi:wifi certification version: v7.0
I (682) wifi:config NVS flash: enabled
I (682) wifi:config nano formating: disabled
I (692) wifi:Init data frame dynamic rx buffer num: 32
I (692) wifi:Init static rx mgmt buffer num: 5
I (702) wifi:Init management short buffer num: 32
I (702) wifi:Init dynamic tx buffer num: 32
I (702) wifi:Init static rx buffer size: 1600
I (712) wifi:Init static rx buffer num: 10
I (712) wifi:Init dynamic rx buffer num: 32
I (722) wifi_init: rx ba win: 6
I (722) wifi_init: accept mbox: 6
I (722) wifi_init: tcpip mbox: 32
I (732) wifi_init: udp mbox: 6
I (732) wifi_init: tcp mbox: 6
I (732) wifi_init: tcp tx win: 5760
I (742) wifi_init: tcp rx win: 5760
I (742) wifi_init: tcp mss: 1440
I (752) wifi_init: WiFi IRAM OP enabled
I (752) wifi_init: WiFi RX IRAM OP enabled
I (762) wifi_prov_scheme_ble: BT memory released
I (762) app: Starting provisioning
I (772) app: Development mode: using hard coded salt
I (772) app: Development mode: using hard coded verifier
I (782) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (862) wifi:mode : sta (94:b5:55:f3:54:48)
I (862) wifi:enable tsf
I (862) BTDM_INIT: BT controller compile version [b022216]
I (872) BTDM_INIT: Bluetooth MAC: 94:b5:55:f3:54:4a
I (1112) protocomm_nimble: BLE Host Task Started
I (1122) wifi_prov_mgr: Provisioning started with service name : PROV_F35448 
I (1132) app: Provisioning started
I (1132) app: Scan this QR code from the provisioning application for Provisioning.
I (1142) QRCODE: Encoding below text with ECC LVL 0 & QR Code Version 10
I (1142) QRCODE: {"ver":"v1","name":"PROV_F35448","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (1172) NimBLE: GAP procedure initiated: advertise; 
I (1172) NimBLE: disc_mode=2
I (1172) NimBLE:  adv_channel_map=0 own_addr_type=0 adv_filter_policy=0 adv_itvl_min=256 adv_itvl_max=256
I (1182) NimBLE: 


  █▀▀▀▀▀█ ███ ▀▄▀▀▀▄▄▄█▄▀▀▄▄▀▀  █▀▀▀▀▀█   
  █ ███ █ █▄▀█ ▄▄▄█▀▀▀▄▀▀█▄▄ ▄█ █ ███ █
  █ ▀▀▀ █ ▄  ▄▄█▀▀▀  ▄▀█▄▀ ▀█▀  █ ▀▀▀ █   
  ▀▀▀▀▀▀▀ ▀▄▀ █ █ █▄▀ ▀▄▀▄▀ ▀▄█ ▀▀▀▀▀▀▀
  █▀▄ ▀▀▀ ▄ ▄▀▄▄█▄ ▀█▀▄▀██▀▄ █▀▄ █▄▀▀▀▀   
  ▀▄▄ █▄▀▀▀▄██▀▀ ▀█▄  ▄▄▄▀▄ ██▀██ ▀█▄█▄
   ▀▄▄▄█▀▀▀█  ▀  █▀██▀▀▀ ▄▀▄ ▄▀ ▀█▄▀█▄▀   
  ▄▄ ▀▄ ▀ ▀ ▀ ▄ █▀██▀▄▀▄██▀▀▄█▀█▄█ █▄     
  ▀ ▀▀▄█▀ ██▄▀▄▀█▄ ▀█▀▀█ █▀▄▄▄▀██▀▄ ▀▀▀
   ▀ █▀▀▀▄▀▀▀█▀█▀█▀▄ ▄ █▄▀█ ██ █ █▄▀▄▄▄   
  █ ▀ ▀ ▀ ▀▀▀ ▀█▄▄█▀ ▀▀▀ ▄ ▄ ▄▀██▀▄█▀█▀
  ▀ █▀ ▀▀█▀ █ ▄ ▄▀██▀ ▀▄█▀ ▀ ▀▄█▄▀ █▄▄▄
  █▄▀▄█▀▀▀▀██▀▄▀▀▄█▀ ▀▀▀█▄█ ▄▄▀▀█▀▄▀▀ ▀
    █▀█▀▀▀█▄▄█▀█▀▀ ▄ ▄ ██▀ ▀▀▀▀ █▄█▄█▀▄
  ▀▀ ▀  ▀ █▀▄ ▀█▄█▄▀▄▀██▀█▄▄▄ █▀▀▀█ ▀▄
  █▀▀▀▀▀█ ▄▀▄ ▄ ▄███▄▄ ▄ ▀  ▄▀█ ▀ ██▄▄▄
  █ ███ █ ▀██▀▄▀▀▄██▄ ▄▀█▄█ ▄▄████▀▄█▄▄
  █ ▀▀▀ █ ▄▄▄█▀█▀▀▄▄▀▄ ████ █ ▄  ▀▄██▄
  ▀▀▀▀▀▀▀ ▀▀  ▀▀  ▀▀ ▀▀▀  ▀  ▀   ▀▀ ▀▀▀


I (1452) app: If QR code is not visible, copy paste the below URL in a browser.
https://espressif.github.io/esp-jumpstart/qrcode.html?data={"ver":"v1","name":"PROV_F35448","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (175922) app: BLE transport: Connected!
I (176122) protocomm_nimble: mtu update event; conn_handle=0 cid=4 mtu=256
I (177982) security2: Using salt and verifier to generate public key...
I (178732) app: Secured session established!
W (209632) wifi:Password length matches WPA2 standards, authmode threshold changes from OPEN to WPA2
I (209672) app: Received Wi-Fi credentials
        SSID     : AIS 4G Hi-Speed Home WiFi_76947550769475
        Password : 50769475
I (215772) wifi:new:<11,0>, old:<1,0>, ap:<255,255>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (215782) wifi:state: init -> auth (0xb0)
I (215782) wifi:state: auth -> assoc (0x0)
I (215792) wifi:state: assoc -> run (0x10)
I (215812) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 5, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (215812) wifi:security: WPA2-PSK, phy: bgn, rssi: -58
I (215832) wifi:pm start, type: 1

I (215832) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (215872) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (215972) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:2, winSize:64
I (223332) app: Connected with IP Address:192.168.1.154
I (223332) esp_netif_handlers: sta ip: 192.168.1.154, mask: 255.255.255.0, gw: 192.168.1.1
I (223332) wifi_prov_mgr: STA Got IP
I (223342) app: Provisioning successful
I (223342) app: Hello World!
I (224342) app: Hello World!
I (225342) app: Hello World!
I (226212) NimBLE: GAP procedure initiated: stop advertising.

I (226212) NimBLE: GAP procedure initiated: stop advertising.

I (226212) NimBLE: GAP procedure initiated: terminate connection; conn_handle=0 hci_reason=19

E (226282) protocomm_nimble: Error setting advertisement data; rc = 30
I (226292) wifi_prov_mgr: Provisioning stopped
I (226292) app: BLE transport: Disconnected!
I (226292) wifi_prov_scheme_ble: BTDM memory released
I (226342) app: Hello World!
