# banaNAS

This is a fun project that I did to learn about Linux, Docker, servers, and networking in general. It is a NAS device running the OpenMediaVault Linux distribution to manage my personal files and programs which I access through VPN. All of the hardware necessary for the build can be purchased for under $400. This repo is where I will share my config files and scripts.

### Hardware
- Motherboard / CPU / Graphics: 
	- ASRock J4205-ITX
	- Cost: $70.00
	- Manual: https://www.asrock.com/mb/Intel/J4205-ITX/index.us.asp#Manual
- Memory:
	- [Crucial 8GB Single DDR3/DDR3L 1866 MT/s (PC3-14900)](https://www.amazon.com/gp/product/B00LTV2BBK/ref=ppx_od_dt_b_asin_title_s01?ie=UTF8&psc=1)
	- Cost: $43.99
	- Manual: https://www.crucial.com/content/dam/crucial/dram-products/dram-family/documents/installation-guides/crucial-dram-install-guide-en.pdf
- Hard Drive 1: 
	- [Kingston 240GB A400 SATA 3 2.5" Internal SSD SA400S37/240G](https://www.amazon.com/gp/product/B01N5IB20Q/ref=ppx_od_dt_b_asin_title_s00?ie=UTF8&psc=1)
	- Cost: $38.95
	- Manual: https://www.kingston.com/datasheets/SA400_us.pdf
- Hard Drive 2: 
	- [Seagate IronWolf 4TB NAS Internal Hard Drive](https://www.amazon.com/gp/product/B07H289S79/ref=ppx_od_dt_b_asin_title_s01?ie=UTF8&psc=1)
	- Cost: $99.99
	- Manual: https://www.seagate.com/www-content/datasheets/pdfs/ironwolf-12tbDS1904-9-1707US-en_US.pdf
- Thumb Drive
- Power Supply Unit:
	- [Corsair CX Series 450 Watt 80 Plus Bronze Certified Modular Power Supply (CP-9020101-NA)](https://www.amazon.com/gp/product/B01B72VXE6/ref=ppx_od_dt_b_asin_title_s00?ie=UTF8&psc=1)
	- Cost: $58.54
	- Manual: https://assets.corsair.com/image/upload/corsairmedia/sys_master/productcontent/WW_Generic_PSU_Manual_WEB.pdf
- Chassis:
	- Fractal Design Core 500
	- Cost: $59.50
	- https://www.fractal-design.com/app/uploads/2020/07/Core-500-Manual.pdf

### Software
- OS: Debian GNU/Linux 12 (bookworm)
- Kernel: 6.1.0-20-amd64
- NAS: [OpenMediaVault](https://www.openmediavault.org/download.html)
	- Services: Docker, NFS, SMB, SSH, Wireguard
- Docker Services:
	- Immich
	- Jellyfin

### Why is it called banaNAS? 🍌🍌🍌
- My first NAS device was built using a [Banana Pi](https://www.banana-pi.org/en/banana-pi-sbcs/51.html) so I thought it was a cute name that just stuck!
