# Jarkom-Modul-2-IT27-2024

| Nama | NRP |
| ---------------------- | ---------- |
| Azzahra Sekar Rahmadina | 5027221035 |
| Zulfa Hafizh Kusuma | 5027221038 |

## List of Contents
- Official Report
  - [List of Contents](#list-of-contents)
  - [Topology](#topology)
  - [Network Configurations](#network-configurations)
  - [Prerequisite](#prerequisite)
- [Soal 1](#soal-1)
- [Soal 2](#soal-2)
- [Soal 3](#soal-3)
- [Soal 4](#soal-4)
- [Soal 5](#soal-5)
- [Soal 6](#soal-6)
- [Soal 7](#soal-7)
- [Soal 8](#soal-8)
- [Soal 9](#soal-9)
- [Soal 10](#soal-10)
- [Soal 11](#soal-11)
- [Soal 12](#soal-12)
- [Soal 13](#soal-13)
- [Soal 14](#soal-14)
- [Soal 15](#soal-15)
- [Soal 16](#soal-16)
- [Soal 17](#soal-17)
- [Soal 18](#soal-18)
- [Soal 19](#soal-19)
- [Soal 20](#soal-20)

## Topology
**Topology No. 2**
![image](https://github.com/Zaar97/arkom-Modul-2-IT27-2024/assets/128958228/007449aa-e092-4718-9105-e5a95d2e80cc)

## Network Configuration
- **Router**
  - Erangel
      ```bash
    auto eth0
    iface eth0 inet dhcp

    auto eth1
    iface eth1 inet static
        address 10.77.1.1
        netmask 255.255.255.0

    auto eth2
    iface eth2 inet static
        address 10.77.2.1
        netmask 255.255.255.0

    auto eth3
    iface eth3 inet static
        address 10.77.3.1
        netmask 255.255.255.0
  ```
- **Web Server**
  - Severny
    ```bash
    auto eth0
    iface eth0 inet static
        address 10.77.1.2
        netmask 255.255.255.0
        gateway 10.77.1.1
    ```
  - Lipovka
    ```bash
    auto eth0
    iface eth0 inet static
        address 10.77.1.3
        netmask 255.255.255.0
        gateway 10.77.1.1
    ```
    - Stalber
    ```bash
    auto eth0
    iface eth0 inet static
        address 10.77.1.4
        netmask 255.255.255.0
        gateway 10.77.1.1
    ```
- **Client**
  - Apartment
    ```bash
    auto eth0
    iface eth0 inet static
 	    address 10.77.2.2
 	    netmask 255.255.255.0
 	    gateway 10.77.2.1
    ```
  - Ruins
    ```bash
    auto eth0
    iface eth0 inet static
 	    address 10.77.2.3
 	    netmask 255.255.255.0
 	    gateway 10.77.2.1
    ```
- **Load Balancer**
  - Mylta
    ```bash
    auto eth0
    iface eth0 inet static
 	    address 10.77.2.4
 	    netmask 255.255.255.0
 	    gateway 10.77.2.1
    ```
- **DNS**
  - Slave Georgopol
    ```bash
    auto eth0
    iface eth0 inet static
 	    address 10.77.2.5
 	    netmask 255.255.255.0
 	    gateway 10.77.2.1
    ```
  - Master Pochinki
    ```bash
          auto eth0
    iface eth0 inet static
 	    address 10.77.3.2
 	    netmask 255.255.255.0
 	    gateway 10.77.3.1
    ```
- **Notes of Config**
  ```bash
  Erangel : 10.77.1.1 (Switch 1)
  Severny : 10.77.1.2
  Lipovka : 10.77.1.3
  Stalber : 10.77.1.4
  Erangel : 10.77.2.1 (Switch 2)
  Apartement : 10.77.2.2
  Ruins : 10.77.2.3
  Mylta : 10.77.2.4
  Georgopol : 10.77.2.5
  Erangel : 10.77.3.1
  Pochinki : 10.77.3.2
  ```

## Prerequisite

## Soal 1
Sebelum memulai pengerjaan, langkah awal yang perlu dilakukan adalah melakukan setup. Tahap selanjutnya adalah melakukan pengujian terhadap semua node yang ada. Pada tahap ini, pengujian dilakukan pada kedua client, yakni Apartment dan Ruins.

### Script
```bash
ping google.com -c 5
```

### Result


## Soal 2

## Soal 3

## Soal 4

## Soal 5

## Soal 6

## Soal 7

## Soal 8

## Soal 9

## Soal 10

## Soal 11

## Soal 12

## Soal 13

## Soal 14

## Soal 15

## Soal 16

## Soal 17

## Soal 18

## Soal 19

## Soal 20
