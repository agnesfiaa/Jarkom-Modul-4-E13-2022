# Jarkom-Modul-4-E13-2022

- Rycahaya Sri Hutomo (5025201046)
- Agnesfia Anggraeni  (5025201059)

## TOPOLGOGI JARINGAN VLSM - CPT
Buat topologi dan bagi kedalam beberapa subnet kecil serta berikan nama sesuai kebutuhan :

![image](https://user-images.githubusercontent.com/94664966/204088570-6ed786a9-8d41-4e5b-982d-6c70c407b996.png)

Tentukan jumlah IP yang diperlukan beserta dengan Netmask untuk setiap subnet yang ada:

![image](https://user-images.githubusercontent.com/94664966/204088804-dafcc53f-927d-47a7-8d91-4797f0056153.png)

Berdasarkan data diatas, susulah tree VLSM seperti berikut:

![Tree VLSM drawio](https://user-images.githubusercontent.com/94664966/204089149-dbd1c751-c330-4a5e-8333-0f3230ccf4a7.png)

Dengan demikian, didapatkan NID untuk masing-masing subnet sebagai berikut:

![image](https://user-images.githubusercontent.com/94664966/204089287-788ddb85-0e58-42d9-9539-faf336739ff5.png)

Berikan IP pada masing-masing interface pada subnet sesuai dengan aturan yang telah diberikan diatas.

### Menambah Ethernet/Port
Port harus ditambah karena default hanya ada 2. <br>
![The Refonance_tambah port](https://user-images.githubusercontent.com/94664966/204094350-6044b4fb-7b83-430e-ada3-7a14a2a5a5bd.png)<br>

### Config IP pada Node
#### Router
![The Refonance_00](https://user-images.githubusercontent.com/94664966/204094444-71218691-1137-4464-8e80-098507e538a5.png)<br>
Pada TheMinister, tambahkan IP dan Subnet Mask sesuai perhitungan pembagian IP dan ditambah 1 dari subnet. Lalu, centang pada bagian Port Status agar menjadi on.

#### Server & Client
![ASHAF](https://user-images.githubusercontent.com/94664966/204094691-b43b4895-144e-4c1c-a88a-11b784ba640b.png)

## ROUTING
### The Refonance
```
10.8.0.4/30 via 10.8.0.10
10.8.0.64/26 via 10.8.0.10
10.8.8.0/22 via 10.8.0.10
10.8.0.0/30 via 10.8.0.10
10.8.2.0/24 via 10.8.0.10
10.8.0.24/30 via 10.8.0.26
10.8.6.0/23 via 10.8.0.26
10.8.0.16/30 via 10.8.0.18
10.8.0.128/30 via 10.8.0.18
10.8.0.20/30 via 10.8.0.18
10.8.1.128/25 via 10.8.0.18
10.8.1.0/25 via 10.8.0.18
10.8.0.12/30 via 10.8.0.18
10.8.4.0/23 via 10.8.0.18
10.8.3.0/24 via 10.8.0.18
10.8.0.28/30 via 10.8.0.18
```

### The Order
```
0.0.0.0/0 via 10.8.0.9
10.8.8.0/22 via 10.8.0.6
10.8.0.0/30 via 10.8.0.6
10.8.2.0/24 via 10.8.0.6
```

### The Minister
```
0.0.0.0/0 via 10.8.0.5
10.8.2.0/24 via 10.8.0.2
```

### The Daundless
```
0.0.0.0/0 via 10.8.0.1
```

### The Megical
```
0.0.0.0/0 via 10.8.0.25
```

### The Instrument
```
0.0.0.0/0 via 10.8.0.17
10.8.0.20/30 via 10.8.0.22
10.8.1.128/25 via 10.8.0.22
10.8.1.0/25 via 10.8.0.22
10.8.0.12/30 via 10.8.0.14
10.8.3.0/24 via 10.8.0.14
10.8.4.0/23 via 10.8.0.14
10.8.0.28/30 via 10.8.0.14
```

### The Poofound
```
0.0.0.0/0 via 10.8.0.21
```

### The Etefist
0.0.0.0/0 via 10.8.0.13
10.8.0.28/30 via 10.8.3.3

### The Queen
```
0.0.0.0/0 via 10.8.3.1
```

## TOPOLGI JARINGAN CIDR - GNS3


Dari gambar diatas dapat kita buat tree subnet seperti berikut :

![CIDR-REVISI drawio](https://user-images.githubusercontent.com/94664966/204090096-fcc07d43-5db5-4f8f-826a-c7c9839a16ea.png)

# Ashaf
![image](https://user-images.githubusercontent.com/94664966/204090415-0b796f32-1fca-4907-86d9-f9b433664c00.png)

# Convekt
![image](https://user-images.githubusercontent.com/94664966/204090469-cf8aff4a-5bdf-40c0-9790-3d638ef8de9a.png)

# Guideau
![image](https://user-images.githubusercontent.com/94664966/204090556-ddf43275-da30-499c-a82b-10e3b7a56df0.png)

# Haines
![image](https://user-images.githubusercontent.com/94664966/204090598-691505ab-136a-4431-ae9e-e88e7d522fc2.png)

# Helga
![image](https://user-images.githubusercontent.com/94664966/204090709-c2a18484-e9f4-473e-9808-cc955521e827.png)

# Johan
![image](https://user-images.githubusercontent.com/94664966/204090763-79246539-10b4-4a0a-9b04-204609b97300.png)

# Keith
![image](https://user-images.githubusercontent.com/94664966/204090821-d194c2e1-2d20-4873-b524-31a164670bc3.png)

# MattCugat
![image](https://user-images.githubusercontent.com/94664966/204091118-49faa2ea-4cf6-47d2-886f-0cb98be893fe.png)

# Oakleave
![image](https://user-images.githubusercontent.com/94664966/204091218-0775b164-96d7-4380-8567-851786d53df6.png)

# Phanora
![image](https://user-images.githubusercontent.com/94664966/204091266-d66811f3-cf4e-4831-820e-b7f00fdc75a8.png)

# Spendrow
![image](https://user-images.githubusercontent.com/94664966/204091390-cff09625-e167-4e5b-bfbb-b68732010154.png)

# The Beast
![image](https://user-images.githubusercontent.com/94664966/204091444-ecdcf4ba-3e5c-4d11-b126-781668c6b064.png)

# The Witch
![image](https://user-images.githubusercontent.com/94664966/204091485-e9152d83-d313-4ece-b6c0-d76f09e9cf29.png)

# The Dauntless
![image](https://user-images.githubusercontent.com/94664966/204091599-b4915416-c323-4917-960d-ccbbd2d3de6b.png)

# The Firefist
![image](https://user-images.githubusercontent.com/94664966/204091724-32ef20d5-7423-4442-8d0b-5c3df1079453.png)

# The Instrument
![image](https://user-images.githubusercontent.com/94664966/204091803-f50a6d0e-a47f-4051-b25a-d6a2560b601e.png)

# The Magical 
![image](https://user-images.githubusercontent.com/94664966/204091861-9942f4f0-dc0d-49ac-a49c-7e44aade5273.png)

# The Minister
![image](https://user-images.githubusercontent.com/94664966/204091946-a5021459-52fa-47e1-9fe5-5cfefbbf4458.png)

# The Poofound
![image](https://user-images.githubusercontent.com/94664966/204092059-655e8832-f47c-4220-9a4d-40574e1b842b.png)

# The Queen
![image](https://user-images.githubusercontent.com/94664966/204092081-33dfaa89-68e4-4718-911b-348ca86fec0a.png)

# The Resonance
![image](https://user-images.githubusercontent.com/94664966/204092138-523a790a-7797-4d55-a55e-24e4d7927e53.png)

The Order
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.28.32.1
route add -net 10.28.0.0 netmask 255.255.252.0 gw 10.28.8.2
route add -net 10.28.5.0 netmask 255.255.255.252 gw 10.28.8.2
route add -net 10.28.4.0 netmask 255.255.255.0 gw 10.28.8.2
```

The minister
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.28.8.1
route add -net 10.28.4.0 netmask 255.255.255.0 gw 10.28.5.2
```

the dauntless
```
route add 0.0.0.0 netmask 0.0.0.0 gw 10.28.5.1
```

the firefist
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.28.68.1
route add -net 10.28.65.0 netmask 255.255.255.252 gw 10.28.64.3
```
the instrument
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.28.96.1
route add -net 10.28.72.0 netmask 255.255.255.128 gw 10.28.73.2
route add -net 10.28.72.128 netmask 255.255.255.128 gw 10.28.73.2

route add -net 10.28.64.0 netmask 255.255.255.0 gw 10.28.68.2
route add -net 10.28.66.0 netmask 255.255.254.0 gw 10.28.68.2
route add -net 10.28.65.0 netmask 255.255.255.252 gw 10.28.68.2
```

the magical
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.28.130.1
```

the poofound
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.28.73.1
```



