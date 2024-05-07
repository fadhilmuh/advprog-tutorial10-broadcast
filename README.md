# Reflections

## 2.1 Original code of broadcast chat.

Untuk menjalankan server, kita jalankan `cargo run --bin server`. Untuk menjalankan klien, kita jalankan `cargo run --bin client`. Kita baru saja menerapkan komunikasi websocket antara server dan klien. Ketika klien mana pun mengirim pesan, pesan tersebut akan disiarkan ke semua klien. Kita dapat menjalankan beberapa klien dan melihat pesan-pesan yang disiarkan ke semua klien.

Server:
![](assets/2.1-server.png)

Client #1:
![](assets/2.1-client1.png)

Client #2:
![](assets/2.1-client2.png)

Client #3:
![](assets/2.1-client3.png)