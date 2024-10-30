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
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2bb58h (179032) map
I (166) esp_image: segment 1: paddr=0003bb80 vaddr=3ffbdb60 size=04498h ( 17560) load
I (172) esp_image: segment 2: paddr=00040020 vaddr=400d0020 size=bba7ch (768636) map
I (436) esp_image: segment 3: paddr=000fbaa4 vaddr=3ffc1ff8 size=017a0h (  6048) load
I (438) esp_image: segment 4: paddr=000fd24c vaddr=40080000 size=1bfc0h (114624) load
I (501) boot: Loaded app from partition at offset 0x10000
I (501) boot: Disabling RNG early entropy source...
I (513) cpu_start: Multicore app
I (521) cpu_start: Pro cpu start user code
I (521) cpu_start: cpu freq: 160000000 Hz
I (522) app_init: Application information:
I (524) app_init: Project name:     test
I (529) app_init: App version:      1
I (533) app_init: Compile time:     Sep 26 2024 13:41:16
I (539) app_init: ELF file SHA256:  bfd5ab2cc...
I (545) app_init: ESP-IDF:          v5.3.1
I (549) efuse_init: Min chip rev:     v0.0
I (554) efuse_init: Max chip rev:     v3.99 
I (559) efuse_init: Chip rev:         v3.0
I (564) heap_init: Initializing. RAM available for dynamic allocation:
I (571) heap_init: At 3FFAFF10 len 000000F0 (0 KiB): DRAM
I (577) heap_init: At 3FFB6388 len 00001C78 (7 KiB): DRAM
I (583) heap_init: At 3FFB9A20 len 00004108 (16 KiB): DRAM
I (589) heap_init: At 3FFC9F90 len 00016070 (88 KiB): DRAM
I (596) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (602) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (608) heap_init: At 4009BFC0 len 00004040 (16 KiB): IRAM
I (617) spi_flash: detected chip: generic
I (619) spi_flash: flash io: dio
W (623) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (637) coexist: coex firmware version: 4482466
I (643) main_task: Started on CPU0
I (653) main_task: Calling app_main()
I (693) wifi:wifi driver task: 3ffcdf84, prio:23, stack:6656, core=0
I (703) wifi:wifi firmware version: ccaebfa
I (703) wifi:wifi certification version: v7.0
I (703) wifi:config NVS flash: enabled
I (703) wifi:config nano formating: disabled
I (713) wifi:Init data frame dynamic rx buffer num: 32
I (713) wifi:Init static rx mgmt buffer num: 5
I (723) wifi:Init management short buffer num: 32
I (723) wifi:Init dynamic tx buffer num: 32
I (733) wifi:Init static rx buffer size: 1600
I (733) wifi:Init static rx buffer num: 10
I (733) wifi:Init dynamic rx buffer num: 32
I (743) wifi_init: rx ba win: 6
I (743) wifi_init: accept mbox: 6
I (743) wifi_init: tcpip mbox: 32
I (753) wifi_init: udp mbox: 6
I (753) wifi_init: tcp mbox: 6
I (763) wifi_init: tcp tx win: 5760
I (763) wifi_init: tcp rx win: 5760
I (763) wifi_init: tcp mss: 1440
I (773) wifi_init: WiFi IRAM OP enabled
I (773) wifi_init: WiFi RX IRAM OP enabled
I (783) wifi_prov_scheme_ble: BT memory released
I (883) app: Button pressed
I (883) app: Starting provisioning
I (883) app: Development mode: using hard coded salt
I (893) app: Development mode: using hard coded verifier
I (893) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (973) wifi:mode : sta (94:b5:55:f3:54:48)
I (973) wifi:enable tsf
I (983) BTDM_INIT: BT controller compile version [b022216]
I (983) BTDM_INIT: Bluetooth MAC: 94:b5:55:f3:54:4a
I (1233) protocomm_nimble: BLE Host Task Started
I (1243) wifi_prov_mgr: Provisioning started with service name : PROV_F35448 
I (1243) app: Provisioning started
I (1253) app: Scan this QR code from the provisioning application for Provisioning.
I (1253) QRCODE: Encoding below text with ECC LVL 0 & QR Code Version 10
I (1263) QRCODE: {"ver":"v1","name":"PROV_F35448","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (1283) NimBLE: GAP procedure initiated: advertise; 
I (1283) NimBLE: disc_mode=2
I (1283) NimBLE:  adv_channel_map=0 own_addr_type=0 adv_filter_policy=0 adv_itvl_min=256 adv_itvl_max=256
I (1293) NimBLE: 


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


I (1563) app: If QR code is not visible, copy paste the below URL in a browser.
https://espressif.github.io/esp-jumpstart/qrcode.html?data={"ver":"v1","name":"PROV_F35448","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (32773) app: BLE transport: Connected!
I (32943) protocomm_nimble: mtu update event; conn_handle=0 cid=4 mtu=256
I (33783) security2: Using salt and verifier to generate public key...
I (34503) app: Secured session established!
