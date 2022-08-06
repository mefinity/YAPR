<h1 align="center">W.I.P JANGAN LIAT2</h1>

![kom alt ><](https://cdn.discordapp.com/attachments/973116913045602334/1004377183902507079/kom.png)
<p align="center">Karna Kominfo ngeblok situs,ayo kita unblok lagi</p>

### Navigasi

- [Pilihan Tertinggi](#pilihan-tertinggi)

- [Memilih ISP yang tidak ketat](#memilih-isp-yang-tidak-ketat)

- [Memilih VPN yang aman](#memilih-vpn-yang-aman)

- [Memilih DNS yang tepat](#memilih-dns-yang-tepat)
  - [Aplikasi² DNS](#aplikasi-aplikasi-dns)
  - [Cara mengganti DNS](#cara-mengganti-dns)

- Cara unblok dengan menghilangkan DPI

- Cara unblok memakai Filehost

## Pilihan Tertinggi

Unbloking dengan DNS: [1.1.1.1](https://1.1.1.1)

Unbloking dengan DPI: [PowerTunnel](https://github.com/krlvm/PowerTunnel)

Unbloking dengan Filehost: [bebasid](https://bebasid.com)

VPN: [Windscribe](https://windscribe.com)

## Memilih ISP yang tidak KETAT
ISP adalah provider Internetmu,list ini akan buat kamu lebih tau bagaimana ISP² Indonesia memblokir
> Ambil ini dengan sedikit garam,semua ISP akan ganti cara blokingnya

| Nama | Pemblokiran menggunakan DNS | Pemblokiran menggunakan DPI |
| :---: | :---: | :---: |
| Indihome | DNS Nasional | Ya |
| CBN | DNS | Tidak |
| Biznet | DNS Nasional | Tidak |
| MyRepublic | DNS Nasional | Tidak |
| FirstMedia | DNS Nasional | Tidak |
| Megavision | DNS Nasional | Tidak |
| MNC | DNS | Tidak |
| PT Remala Abadi | DNS | Tidak |
| PT iForte Global internet | DNS | Tidak |
| lconnect PLN | Tidak | Ya |
| Telkomsel | DNS Nasional | Ya |
| XL | DNS Nasional | Ya |
| 3 | DNS Nasional | Ya |
| Indosat | Tidak | Ya |
| Smartfren | DNS Nasional | Ya |
| PT Cipta Informatika Cemeriang | DNS | Tidak |
| Oxygen | DNS Nasional | Tidak |
| Astinet | DNS Nasional | Ya |
| Lintasarta | DNS Nasional | Tidak |

## Memilih VPN yang aman
Ah,Virtual Private Network,cara yang tersenang untuk melewati blok

*Tapi* jangan pergi ke Playstore dan download VPN yang gak aman!
Nih,coba liat VPN yang kamu suka di list ini

| Nama | Positif | Negatif | Server |
| :---: | :---: | :---: | :---: |
| [Mullvad](https://mullvad.net/) | VPN Berbayar yang aman | Berbayar | 867 |
| [ProtonVPN](https://protonvpn.com) | VPN "gratis" yang "aman" | Tidak ada Split-tunneling di sub gratis | 100 |
| [Windscribe](https://windscribe.com/) | Ada Split-tunneling & banyak fitur lainnya | 15GB per bulan dan [ini](https://arstechnica.com/gadgets/2021/07/vpn-servers-seized-by-ukrainian-authorities-werent-encrypted) | ~15 |
| [IVPN](https://ivpn.net) | VPN yang fokusnya itu privasi | Berbayar | 77 |
| [OpenVPN](https://openvpn.net) | Open source | Disediakan oleh individual | ? |

## Memilih DNS yang tepat
Nih,list DNS yang bisa dipakai

| Nama | IPv4 | IPv4 2 | IPv6 | IPv6 2 | DoH | DoT |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Cloudflare DNS | `1.1.1.1` | `1.0.0.1` | `2606:4700:4700::1111` | `2606:4700:4700::1001` | `cloudflare-dns.com/dns-query`  | `1dot1dot1dot1.cloudflare-dns.com` |
| Google DNS | `8.8.8.8` | `8.8.4.4` | `2001:4860:4860::8888` | `2001:4860:4860::8844` | `dns.google/dns-query` | `dns.google` |
| Quad9 | `9.9.9.9` | `149.112.112.112` | `2620:fe::fe` | `2620:fe::9` | `dns.quad9.net/dns-query` | `tls://dns.quad9.net` |
| [AhaDNS](https://blitz-setup.ahadns.com) | ? | ? | ? | ? | ? | ? |
| BlahDNS | `45.91.92.121`  | X | `2a0e:dc0:6:23::2` | X | `doh-ch.blahdns.com/dns-query` | `dot-ch.blahdns.com` |
| [RethinkDNS](https://www.rethinkdns.com/configure) | ? | ? | ? | ? | ? | ? |
| NextDNS | `45.90.28.233` | `45.90.30.233` | `2a07:a8c0::c1:15a7` | `2a07:a8c1::c1:15a7` | `dns.nextdns.io/c115a7` | `c115a7.dns.nextdns.io` |
| LibreDNS | `116.202.176.26` | X | X | X | `doh.libredns.gr/dns-query`  | `dot.libredns.gr` |

## Aplikasi-Aplikasi DNS
Aplikasi² DNS ini bisa buat memakai DNS lebih senang

1.[Nebulo](https://nebulo.app) [Android]
>Aplikasi untuk mengganti DNS dengan mudah

2.[DNSCloak](https://apps.apple.com/app/id1452162351) [iOS]
>Aplikasi untuk mengganti DNS dan mengatur dnscrypt dengan mudah

3.[DNSCrypt](https://dnscrypt.info) [Windows,macOS,Linux]
>DNS untuk selfhost sendiri

4.[SimpleDNSCrypt](https://simplednscrypt.org) [Windows]
>Untuk yang males,ini aplikasi penginstalan DNSCrypt dengan senang

5.[DNS Profile Creator](https://dns.notjakob.com/tool.html) [Browser]
>Cara membuat mobileconfig Apple dengan senang

6.[YogaDNS](https://yogadns.com) [Windows]
>Client DNS untuk Windows

7.[RethinkDNS](https://rethinkdns.com) [Android]
>Aplikasi untuk mengganti DNS dengan mudah...lagi

## Cara mengganti DNS
Nah,tu udah ada List DNS,gimana makenya?

<details><summary><h3>Di Android</h3></summary>
1.Settings>Other Wireless Connections>Private DNS

2.Masukkan [hostname dns](#memilih-dns-yang-tepat) dan pencet Save
</details>

<details><summary><h3>Di iOS</h3></summary>

1.Settings>Wi-Fi>*wifi*

2.Ketuk ikon (i)

3.Ganti IP Adress jadi Static dan masukkan [hostname dns](#memilih-dns-yang-tepat) di kolom DNS
</details>

<details><summary><h3>Di Windows</h3></summary>
1.Control Panel>Network and Internet>Network and Sharing Center>Connections>Properties

2.Pencet Internet Protocol Version 4 (TCP/IPv4) 2 kali

3.Ganti "Obtain DNS server address automatically" ke "Use the following DNS server addresses"

4.Masukkan [hostname dns](#memilih-dns-yang-tepat) di kolom DNS dan pencet Ok
</details>

<details><summary><h3>Di macOS</h3></summary>
1.System Preferences>Network>Wi-Fi>Advanced>DNS

2.Pencet tombol “+” dan masukkan [hostname dns](#memilih-dns-yang-tepat) di kolom DNS,pencet Ok dan Apply
</details>

<details><summary><h3>Di Linux</h3></summary>
1.Buka Terminal

2.nano /etc/resolv.conf

3.
>nameserver [hostname dns](#memilih-dns-yang-tepat)

>nameserver [hostname dns](#memilih-dns-yang-tepat)
</details>

<details><summary><h3>Di Chromium</h3></summary>
1.Settings>Privacy and Security
  
2.Masukin [hostname dns](#memilih-dns-yang-tepat) di kolom DNS
</details>

<details><summary><h3>Di Firefox</h3></summary>
1.Settings>Network Settings
  
2.Masukin [hostname dns](#memilih-dns-yang-tepat) di kolom DNS
</details>

### kominfudge main roadmap:
- [x] Navigasi: Change might happen
- [x] Top picks
- [x] ISP
- [x] DNS
- [ ] DPI
- [ ] Filehost
- [x] VPN
- [ ] kredit: Kazuhot,lepz0r,Redacted for Privacy,PrivacytoolsIO,A\ndreas\Ding 🇺🇦🇷🇺
