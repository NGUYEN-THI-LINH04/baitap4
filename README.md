# baitap4

# BÀI LÀM
 - TẠO THƯ MỤC
   
<img width="440" height="105" alt="Screenshot 2026-05-22 130852" src="https://github.com/user-attachments/assets/f2d88acc-5a4f-4f56-8225-f013eb3a66cf" />

 -Tạo file:
``` text
nano docker-compose.yml
```     
<img width="957" height="1018" alt="Screenshot 2026-05-22 130819" src="https://github.com/user-attachments/assets/fa601f2b-efb3-4df2-9b05-487948d5994b" />

<img width="947" height="729" alt="Screenshot 2026-05-22 130828" src="https://github.com/user-attachments/assets/be664b4b-8474-43a1-a0cb-a277db880853" />

- CHẠY DOCKER
```text
  chạy container
     docker compose up -d
  kiểm tra
     docker ps
```
<img width="988" height="218" alt="Screenshot 2026-05-22 124800" src="https://github.com/user-attachments/assets/0313fdc5-7248-4cc9-bcd7-9b4bc86880c6" />

<img width="1919" height="348" alt="image" src="https://github.com/user-attachments/assets/6d1a22fd-d9f0-4f5f-b99e-21a81767ec3b" />

Cấu hình cloudflare tunnel add router để public wordpress lên sub-domain1 (dùng để truy cập wordpress)

<img width="938" height="336" alt="wp" src="https://github.com/user-attachments/assets/b65119b0-4082-4b4a-a34b-76d983a808d4" />

Cấu hình cloudflare tunnel add router để public Phpmyadmin lên sub-domain2 (dùng để truy cập phpmyadmin)

<img width="938" height="336" alt="db" src="https://github.com/user-attachments/assets/038e0af5-558e-4b19-ad52-eb0f0beebad8" />

Cấu hình cloudflare tunnel add router để public n8n này lên sub-domain3 (dùng để truy cập và cấu hình n8n)

<img width="938" height="336" alt="n8n" src="https://github.com/user-attachments/assets/54b82ab2-27a3-480b-8549-b3858aed7ef7" />

Truy cập sub-domain2 để quan sát xem cơ sở dữ liệu chưa có bảng nào!
<img width="1920" height="1080" alt="Screenshot 2026-05-22 135505" src="https://github.com/user-attachments/assets/459893bd-7811-4784-82fd-f083d111342c" />

Truy cập sub-domain1 để cài đặt wordpress (làm theo hướng dẫn của wordpress)

Truy cập sub-domain2 để quan sát xem cơ sở dữ liệu có những bảng dữ liệu nào sau khi cài wp
