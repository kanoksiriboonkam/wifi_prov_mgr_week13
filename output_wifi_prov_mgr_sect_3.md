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
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2a568h (173416) map
I (164) esp_image: segment 1: paddr=0003a590 vaddr=3ffbdb60 size=057b0h ( 22448) load
I (172) esp_image: segment 2: paddr=0003fd48 vaddr=40080000 size=002d0h (   720) load
I (173) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=a2c0ch (666636) map
I (409) esp_image: segment 4: paddr=000e2c34 vaddr=400802d0 size=15fech ( 90092) load
I (456) boot: Loaded app from partition at offset 0x10000
I (456) boot: Disabling RNG early entropy source...
I (468) cpu_start: Multicore app
I (476) cpu_start: Pro cpu start user code
I (476) cpu_start: cpu freq: 160000000 Hz
I (476) app_init: Application information:
I (479) app_init: Project name:     test
I (484) app_init: App version:      1
I (488) app_init: Compile time:     Sep 26 2024 14:07:58
I (494) app_init: ELF file SHA256:  62ee97e77...
I (499) app_init: ESP-IDF:          v5.3.1
I (504) efuse_init: Min chip rev:     v0.0
I (509) efuse_init: Max chip rev:     v3.99 
I (514) efuse_init: Chip rev:         v3.0
I (519) heap_init: Initializing. RAM available for dynamic allocation:
I (526) heap_init: At 3FFAE6E0 len 0000F480 (61 KiB): DRAM
I (532) heap_init: At 3FFC7570 len 00018A90 (98 KiB): DRAM
I (538) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (544) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (551) heap_init: At 400962BC len 00009D44 (39 KiB): IRAM
I (559) spi_flash: detected chip: generic
I (562) spi_flash: flash io: dio
W (566) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (580) coexist: coex firmware version: 4482466
I (585) main_task: Started on CPU0
I (595) main_task: Calling app_main()
I (625) wifi:wifi driver task: 3ffb816c, prio:23, stack:6656, core=0
I (635) wifi:wifi firmware version: ccaebfa
I (635) wifi:wifi certification version: v7.0
I (635) wifi:config NVS flash: enabled
I (635) wifi:config nano formating: disabled
I (635) wifi:Init data frame dynamic rx buffer num: 32
I (645) wifi:Init static rx mgmt buffer num: 5
I (645) wifi:Init management short buffer num: 32
I (655) wifi:Init dynamic tx buffer num: 32
I (655) wifi:Init static rx buffer size: 1600
I (665) wifi:Init static rx buffer num: 10
I (665) wifi:Init dynamic rx buffer num: 32
I (665) wifi_init: rx ba win: 6
I (675) wifi_init: accept mbox: 6
I (675) wifi_init: tcpip mbox: 32
I (685) wifi_init: udp mbox: 6
I (685) wifi_init: tcp mbox: 6
I (685) wifi_init: tcp tx win: 5760
I (695) wifi_init: tcp rx win: 5760
I (695) wifi_init: tcp mss: 1440
I (695) wifi_init: WiFi IRAM OP enabled
I (705) wifi_init: WiFi RX IRAM OP enabled
I (805) app: Button pressed
I (815) app: Starting provisioning
I (815) app: Development mode: using hard coded salt
I (815) app: Development mode: using hard coded verifier
I (815) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (895) wifi:mode : sta (94:b5:55:f3:54:48)
I (895) wifi:enable tsf
I (905) wifi:mode : sta (94:b5:55:f3:54:48) + softAP (94:b5:55:f3:54:49)
I (915) wifi:Total power save buffer number: 16
I (915) wifi:Init max length of beacon: 752/752
I (915) wifi:Init max length of beacon: 752/752
I (925) esp_netif_lwip: DHCP server started on interface WIFI_AP_DEF with IP: 192.168.4.1
I (925) wifi:Total power save buffer number: 16
I (935) esp_netif_lwip: DHCP server started on interface WIFI_AP_DEF with IP: 192.168.4.1
I (945) wifi_prov_mgr: Provisioning started with service name : PROV_F35448 
I (945) app: Provisioning started
I (955) app: Scan this QR code from the provisioning application for Provisioning.
I (955) QRCODE: Encoding below text with ECC LVL 0 & QR Code Version 10
I (965) QRCODE: {"ver":"v1","name":"PROV_F35448","username":"wifiprov","pop":"abcd1234","transport":"softap"}

  █▀▀▀▀▀█ █  ▄▄ ▀▀█▄▄▄█▄▀▀▄▄▀▀  █▀▀▀▀▀█   
  █ ███ █ ██▄ █▄█▄▀▀▀▀▄▀▀█▄▄ ▄█ █ ███ █
  █ ▀▀▀ █ ▄██ ▀▀▀▀▀  ▄▀█▄▀ ▀█▀  █ ▀▀▀ █   
  ▀▀▀▀▀▀▀ ▀ █▄▀ ▀ █▄▀ ▀▄▀▄▀ ▀▄█ ▀▀▀▀▀▀▀
  █▀  █▀▀   ▀ ▀▄ ▄ ▀█▀▄▀██▀▄ █▀▄ █▄▀▀▀▀   
  ▄ █▄▀ ▀▀▄▀▄ ▄ ▀▀█▄  ▄▄▄▀▄ ██▀██ ▀█▄█▄
  ██▄▄ ▀▀██▀▀▀▄▄▄█▀██▀▀▀ ▄▀▄ ▄▀ ▀█▄▀█▄▀   
  ▀▄█▄ █▀  ▄ █▀ ▄▀██▀▄▀▄██▀▀▄█▀█▄█ █▄     
  ▀ ▄▀██▀▀▀█  ▀▄ ▄ ▀█▀▀█ █▀▄▄▄▀██▀▄ ▀▀▀
  ▄▄▀▄▀▀▀▄███ ▄  █▀▄ ▄ █▄▀█ ██ █ █▄▀▄▄▄   
  ▀██ ▄▄▀▄▄▀ ▀▄▄█▄█▀ ▀▀▀ ▄ ▄ ▄▀██▀▄█▀█▀
  █▄▄▄█ ▀██ ██▀▀ ▀██▀ ▀▄█▀ ▀ ▀▄█▄▀ █▄▄▄   
  ▄▀  █ ▀▄▄▄▄ ▀  ▄█▀ ▀▀▀█▄█ ▄▄▀▀█▀▄▀▀ ▀
    █▄█▀▀▄ ▀  ▄ █▀ ▄ ▄ ██▀ ▀▀▀▀ █▄█▄█▀▄   
  ▀▀  ▀▀▀▀█▄█▀▄▀██▄▀▄▀██▀█▄▄▄ █▀▀▀█ ▀▄
  █▀▀▀▀▀█ ▄▄ █▀█▀███▄▄ ▄ ▀  ▄▀█ ▀ ██▄     
  █ ███ █ ▀ ▄ ▀█▄▄██▄ ▄▀█▄█ ▄▄████▀▄██▄   
  █ ▀▀▀ █ ▄▄▄ ▄ ▄▀▄▄▀▄ ████ █ ▄  ▀▄██▄
  ▀▀▀▀▀▀▀ ▀ ▀▀ ▀▀ ▀▀ ▀▀▀  ▀  ▀   ▀▀ ▀▀▀   


I (1235) app: If QR code is not visible, copy paste the below URL in a browser.
https://espressif.github.io/esp-jumpstart/qrcode.html?data={"ver":"v1","name":"PROV_F35448","username":"wifiprov","pop":"abcd1234","transport":"softap"}
I (15005) wifi:new:<1,0>, old:<1,1>, ap:<1,1>, sta:<0,0>, prof:1, snd_ch_cfg:0x0
I (15005) wifi:station: 72:dc:f3:85:9b:36 join, AID=1, bgn, 20
I (15005) app: SoftAP transport: Connected!
I (15385) wifi:<ba-add>idx:2 (ifx:1, 72:dc:f3:85:9b:36), tid:0, ssn:0, winSize:64
I (16765) esp_netif_lwip: DHCP server assigned IP to a client, IP is: 192.168.4.2
I (40385) security2: Using salt and verifier to generate public key...
I (40845) app: Secured session established!
W (54805) wifi:Password length matches WPA2 standards, authmode threshold changes from OPEN to WPA2
I (54835) app: Received Wi-Fi credentials
        SSID     : AIS 4G Hi-Speed Home WiFi_76947550769475
        Password : 50769475
I (58945) wifi:primary chan differ, old=1, new=11, start CSA timer
I (59345) wifi:switch to channel 11
I (59345) wifi:ap channel adjust o:1,1 n:11,2
I (59355) wifi:new:<11,0>, old:<1,0>, ap:<11,2>, sta:<0,0>, prof:1, snd_ch_cfg:0x0
I (59355) wifi:new:<11,2>, old:<11,0>, ap:<11,2>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (59365) wifi:state: init -> auth (0xb0)
I (59405) wifi:state: auth -> assoc (0x0)
I (59435) wifi:state: assoc -> run (0x10)
I (59525) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 5, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (59525) wifi:security: WPA2-PSK, phy: bgn, rssi: -60
I (59545) wifi:pm start, type: 1

I (59545) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (59575) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (59685) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (60545) app: Connected with IP Address:192.168.1.154
I (60545) esp_netif_handlers: sta ip: 192.168.1.154, mask: 255.255.255.0, gw: 192.168.1.1
I (60545) wifi_prov_mgr: STA Got IP
I (60545) app: Provisioning successful
I (60555) app: Hello World!
I (61555) app: Hello World!
I (62555) app: Hello World!
I (63555) app: Hello World!
I (64555) app: Hello World!
I (65555) app: Hello World!
I (66085) wifi:station: 72:dc:f3:85:9b:36 leave, AID = 1, reason = 4, bss_flags is 33721443, bss:0x3ffcb574
I (66085) wifi:new:<11,0>, old:<11,2>, ap:<11,2>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (66085) wifi:<ba-del>idx:2, tid:0
I (66095) wifi:mode : sta (94:b5:55:f3:54:48)
I (66105) wifi_prov_mgr: Provisioning stopped
I (66105) app: SoftAP transport: Disconnected!
I (66555) app: Hello World!
