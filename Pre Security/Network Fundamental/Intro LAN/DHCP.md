Alamat IP dapat diberikan secara manual, dengan memasukkannya secara fisik ke dalam perangkat, atau secara otomatis dan paling umum dengan menggunakan server DHCP (*Dynamic Host Configuration Protocol*). Saat perangkat terhubung ke jaringan, jika belum ditetapkan alamat IP secara manual, perangkat akan mengirimkan permintaan (*DHCP Discover*) untuk melihat apakah ada server DHCP di jaringan. Server DHCP kemudian membalas kembali dengan alamat IP yang dapat digunakan perangkat (*DHCP offer*). Perangkat kemudian mengirimkan balasan yang mengonfirmasi bahwa ia menginginkan Alamat IP yang ditawarkan (*DHCP request*), dan terakhir, server DHCP mengirimkan balasan yang menyatakan bahwa ini telah selesai, dan perangkat dapat mulai menggunakan Alamat IP (DHCP ACK).

![dhcp](https://raw.githubusercontent.com/yingcrackerhades/cybersec-module/main/Pre%20Security/Network%20Fundamental/Intro%20LAN/Image/DHCP.png)