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

Truy cập sub-domain2 để quan sát xem cơ sở dữ liệu chưa có bảng nào

+ https://db.nguyenthilinhk58.id.vn
  
<img width="1920" height="1080" alt="Screenshot 2026-05-22 170403" src="https://github.com/user-attachments/assets/58157376-3c8d-4c40-a64c-fb04cea00923" />

Truy cập sub-domain1 để cài đặt wordpress (làm theo hướng dẫn của wordpress)
   + https://wp.nguyenthilinhk58.id.vn

<img width="955" height="909" alt="Screenshot 2026-05-22 135244" src="https://github.com/user-attachments/assets/d7e2eae5-a9a4-4e45-9f1f-266377b740e9" />

<img width="1920" height="1080" alt="Screenshot 2026-05-22 135304" src="https://github.com/user-attachments/assets/a66e36cc-1048-46f8-8254-ae1440b2af81" />

<img width="1920" height="1080" alt="Screenshot 2026-05-22 135321" src="https://github.com/user-attachments/assets/5b33ce50-69e2-4682-bd0f-7f88b975e88f" />

Truy cập sub-domain2 để quan sát xem cơ sở dữ liệu có những bảng dữ liệu nào sau khi cài wp

+ https://db.nguyenthilinhk58.id.vn
  
<img width="1920" height="1080" alt="Screenshot 2026-05-22 135505" src="https://github.com/user-attachments/assets/459893bd-7811-4784-82fd-f083d111342c" />

Tạo 1 bài viết trong wordpress giới thiệu về bản thân sinh viên: thông tin cá nhân, sở thích, ... bài viết có thể chứa hình ảnh, âm thanh, video, ...

<img width="1920" height="1080" alt="Screenshot 2026-05-22 170232" src="https://github.com/user-attachments/assets/7c935c2c-6ca5-4318-b029-78117c8721a5" />

<img width="1920" height="1080" alt="Screenshot 2026-05-22 170238" src="https://github.com/user-attachments/assets/365afc8d-033c-4478-8f71-f999a89973d8" />

Tạo 1 bài viết trong wordpress giới thiệu về nhữn kiến thức mà em đã học được ở môn Phát triển ứng dụng với mã nguồn mở

<img width="1920" height="1080" alt="Screenshot 2026-05-22 170253" src="https://github.com/user-attachments/assets/b25d9b58-ea8a-4e0e-987c-5fb6a647bdfd" />

- Truy cập sub-domain3 để cấu hình n8n
 https://n8n.nguyenthilinhk58.id.vn

   + tạo tài khoản admin : nhớ điền đúng email

<img width="1920" height="1080" alt="Screenshot 2026-05-22 135900" src="https://github.com/user-attachments/assets/0e97aae3-195f-4c43-a377-619b930af100" />

- Send me a Licence key, bước này điền đủ thông tin, làm chậm sẽ thấy mục gửi License key về mail (n8n sẽ gửi email KEY cho dùng), check email để lấy KEY

  <img width="828" height="1792" alt="image" src="https://github.com/user-attachments/assets/6946ee3e-8df6-46e9-b99d-3a6190c74ba9" />

- Activate License key: vào trang chủ => SETTING (góc dưới trái) => Usage and plan => Enter activation key: paste key từ email vào đây => Activate => sẽ nhận đc thông báo (góc dưới phải) Your Registered Community Edition has been successfully activated.

  <img width="1920" height="1080" alt="Screenshot 2026-05-22 144248" src="https://github.com/user-attachments/assets/5cb06e7e-a871-42d0-8121-7fabbb62676d" />

- Create workflow (home page => overview => Create workflow)

- Add trigger node: tìm node: Telegram => OnMessage ; cấu hình Credential: Set up Credential => cần Nhập Access Token

  <img width="1376" height="825" alt="Screenshot 2026-05-22 143455" src="https://github.com/user-attachments/assets/98a6a336-fc9a-468f-8a51-e536c16754c9" />

- Access Token thì lấy ở Telegram qua việc chát với @BotFather

  <img width="828" height="1792" alt="image" src="https://github.com/user-attachments/assets/1f5af429-5f01-4ed3-a469-8c1ec9546d92" />

- Cần chát với bot @BotFather để đẻ ra bot mới của riêng mình. bot này sẽ là nơi nhận lệnh (promt) để AI sinh html => n8n sẽ dùng html này để đăng bài lên wp

  <img width="828" height="1792" alt="image" src="https://github.com/user-attachments/assets/ba1f470a-f3d4-449e-b523-5fb4002f2830" />

- Sau khi tạo bot mới cần copy lấy Token, và chát lần đầu với bot mới này, nội dung bất kỳ (bước này quan trọng!)

  <img width="1920" height="1080" alt="Screenshot 2026-05-22 143626" src="https://github.com/user-attachments/assets/6622541e-2614-43db-a2f4-d50f18b85655" />

- Add (nối tiếp vào sau node Telegram Trigger) node: AI Google Gemini => Message a model => Set up Credential => cần Nhập API KEY

  <img width="1920" height="1080" alt="Screenshot 2026-05-22 151136" src="https://github.com/user-attachments/assets/2447bd91-9717-4fa5-925e-80ec6f7df221" />

- Lấy API KEY tại trang: https://aistudio.google.com => https://aistudio.google.com/api-keys

- Cần tạo project mới, sẽ lấy được API KEY

  <img width="959" height="1049" alt="Screenshot 2026-05-22 145239" src="https://github.com/user-attachments/assets/bf31a49f-57fb-48d4-8510-ee91776d113b" />

- Nhập API Key lên giao diện n8n

  <img width="1920" height="1080" alt="Screenshot 2026-05-22 151320" src="https://github.com/user-attachments/assets/42b570c9-46f6-4905-9c2b-cc50e86dfb83" />

- kéo thả nội dung đã chát với bot của telegram (phía bên trái) vào nội dung phần PROMPT kết quả được {{ $json.message.text }}, cần gõ thêm vào sau {{ $json.message.text }} để promt dài hơn : vd ({{ $json.message.text }}. Kết quả sinh ra ở định dạng HTML+CSS để tôi dùng HTML+CSS này tạo bài viết cho wordpress.)
  
- Turn on Output Content as JSON : để kết quả trả về dạng json
  
- Có thể thử nghiệm các thành phần khác trong Options (add Options: System message, ...) => đưa ra cái nào đáng dùng?
  
+  Bấm nút Execute step và chờ Gemini xử lý. Khi thành công, ở cột Output bên phải sẽ thấy AI trả về một chuỗi text thô lộn xộn nhưng chứa cấu trúc post_title và post_content.
 
  <img width="1920" height="1080" alt="Screenshot 2026-05-22 152004" src="https://github.com/user-attachments/assets/3ca1c680-d730-4d65-9c24-e7a345e60424" />

- Add (nối tiếp vào sau node Message a model) node: Code in JavaScript
  
    + Code js ở dạng này, có thể phải thay đổi tuỳ theo json AI trả về.
 ``` text
 // 1. lấy dữ liệu gốc
const rawText = $input.first().json.content.parts[0].text;

// 2. Chuyển đổi chuỗi (đã được bọc JSON) thành Object trong JavaScript
const cleanData = JSON.parse(rawText);

// 3. Trả về kết quả định dạng lại gọn gàng cho n8n sử dụng
return {
  title: cleanData.post_title,
  content: cleanData.post_content
};  
```
<img width="1920" height="1080" alt="Screenshot 2026-05-22 152224" src="https://github.com/user-attachments/assets/8b0ae310-5575-4854-a801-ba34cebbbbef" />

- Add (nối tiếp vào sau node Code in JavaScript) node: WordPress => Create a Post

  <img width="961" height="1019" alt="Screenshot 2026-05-22 152357" src="https://github.com/user-attachments/assets/e2ad10a5-1ac3-4fa3-84e5-4e19d8f9094d" />

  <img width="1919" height="938" alt="Screenshot 2026-05-22 152443" src="https://github.com/user-attachments/assets/8799d147-9bc3-4d05-8a4b-d30969f7ec6d" />

- Set up Credential: vào wp tại url: https://wp.nguyenthilinhk58.id.vn/wp-admin => vào mục Tài Khoản => chọn user đã tạo lúc setup wordpress => Mật khẩu ứng dụng => Nhập n8n và bấm "Thêm mật khẩu ứng dụng" => copy chuỗi 24 kí tự : Đây là mật khẩu ứng dụng => paste vào mục Password của n8n Credential

  <img width="955" height="913" alt="Screenshot 2026-05-22 152757" src="https://github.com/user-attachments/assets/088d25e1-83bc-455b-8855-f2c667f2aac8" />

- Wordpress URL: điền giá trị https://wp.nguyenthilinhk58.id.vn/ (giá trị này cũng khai báo trong biến môi trường WEBHOOK_URL của n8n)

- Ignore SSL Issues (Insecure): TURN ON

<img width="1341" height="735" alt="Screenshot 2026-05-22 152835" src="https://github.com/user-attachments/assets/740b2ca2-219b-48fd-8465-68e85f1c3246" />

- Cấu hình node Create a Post: bấm nút Execute previous nodes để thấy trường giá trị của node trước trả về, kéo nội dung phần title (bên trái) vào trường title, tương tự kéo nội dung content vào content

  <img width="1920" height="1080" alt="Screenshot 2026-05-22 153010" src="https://github.com/user-attachments/assets/ed6a5eec-416e-4361-bd51-ff1edb74a0d3" />

  <img width="1920" height="1080" alt="Screenshot 2026-05-22 153448" src="https://github.com/user-attachments/assets/8d1a871e-0e26-4039-a837-33a3bcbe3752" />

- Add field (Thêm thuộc tính): Status == Publish (bài đăng sẽ ở trạng thái xuất bản ngay lập tức, mặc định nó ở giá trị Draft bản nháp)
- PUBLISH flow (góc trên phải) Nút này thực hiện việc xuất bản flow <=> flow sẽ tự động thực thi khi thoả mãn điều kiện trigger

<img width="1920" height="1080" alt="Screenshot 2026-05-22 154512" src="https://github.com/user-attachments/assets/ab0f97cd-082d-4023-ae83-f8d250d985e7" />

# Kết quả cuối cùng cần đặt được:

- từ điện thoại, chát với telegram bot

<img width="828" height="1792" alt="image" src="https://github.com/user-attachments/assets/95d8bfbd-c45a-4d2f-8b67-d6c6cc8b5c77" />

- nội dung chát được tự động gửi tới node Telegram trigger => Gửi tới Google Gemini Message a model (bản chất là gửi Prompt) : Nhận về json kết quả của Prompt => Gửi sang node Code in JavaScript để tách tiêu đề và nội dung => gửi đến node WordPress để Create a Post(đăng bài) với tiêu đề và nội dung từ node trước gửi sang.
  
<img width="1920" height="1080" alt="Screenshot 2026-05-22 154512" src="https://github.com/user-attachments/assets/5d181070-fdc3-4112-a31e-ce7be9b6efb4" />

- f5 wordpress để thấy bài viết mới đã lên sóng.
  
<img width="1909" height="1033" alt="image" src="https://github.com/user-attachments/assets/00a018e1-de38-4455-a230-403a3d50eac2" />

# Nhận xét thành quả đạt được!!!

- Sau khi hoàn thành bài tập, em đã triển khai thành công hệ thống WordPress trên Ubuntu bằng Docker Compose với các service gồm MariaDB, PhpMyAdmin, WordPress, Cloudflared và n8n. Các container hoạt động ổn định và có thể truy cập từ Internet thông qua subdomain bằng Cloudflare Tunnel.

- Trong quá trình thực hiện, em đã cài đặt và cấu hình WordPress thành công, kiểm tra cơ sở dữ liệu bằng PhpMyAdmin và tạo được các bài viết theo yêu cầu của đề bài. Đồng thời, em cũng cấu hình n8n kết hợp với Telegram Bot và Google Gemini AI để xây dựng hệ thống tự động tạo và đăng bài lên WordPress.

- Tuy nhiên, trong quá trình làm bài em cũng gặp một số lỗi như lỗi cấu hình Cloudflare Tunnel, lỗi route DNS bị trùng, lỗi kết nối giữa n8n với Telegram/Gemini và một số lỗi trong quá trình cấu hình workflow. Ngoài ra, có lúc workflow không hoạt động đúng do chưa publish hoặc lỗi credential bị mất kết nối. Sau khi tìm hiểu tài liệu và kiểm tra lại cấu hình từng bước, em đã khắc phục được các lỗi trên và hệ thống hoạt động ổn định.

- Kết quả cuối cùng đạt được là chỉ cần gửi nội dung qua Telegram, hệ thống sẽ tự động gửi yêu cầu đến Gemini AI để tạo nội dung bài viết, xử lý dữ liệu bằng JavaScript và đăng trực tiếp lên website WordPress. Qua bài tập này, em hiểu rõ hơn về Docker, Docker Compose, Cloudflare Tunnel, n8n automation cũng như cách tích hợp AI vào một bài toán thực tế.

  
