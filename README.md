# Nhóm 7 - Xây dựng ứng dụng mã hóa sử dụng thư viện OpenSSL
## Thành viên bao gồm
1. Võ Lê Huy
2. Trần Thị Ngọc
3. Phan Hoàng Trung
4. Lê Thanh Lâm
## Nội dung responsitory
1. Slide báo cáo __*.ppt__
2. Docx báo cáo __*.docx__
3. Hình ảnh (nếu có)
4. Tài liệu tham khảo về OpenSSL
5. Slide bài giảng
## Kế hoạch làm việc
1. __[Học code hệ mật mã DES trong OpenSSL](https://github.com/volehuy1998/Native-Des-Lib)__ (đã xong)
2. Học code hệ mật mã AES trong OpenSSL __(đang làm)__
3. Học code hệ mật mã RSA trong OpenSSL
4. Học code hệ mật mã RC2/4 trong OpenSSL
5. [**Viết docx (đang viết phần giới thiệu OpenSSL)**](https://github.com/volehuy1998/Nhom-7/tree/master/B%C3%A1o%20c%C3%A1o)
6. __Học cách [phát triển Cryptool 2](https://www.youtube.com/playlist?list=PLMuvAbyIl0PTTfPE2VhJ9PZ6qlOG0MMaX) (đang làm)__
7. Áp dụng những code những hệ mật mã OpenSSL vào Cryptool 2
## Môi trường
1. Windows 10 x64
1. Visual Studio 2019
2. OpenSSL API
## Cách cài đặt thư viện OpenSSL dành cho Visual Studio 2019
1. Tải chương trình vcpkg [tại đây](https://github.com/Microsoft/vcpkg)
2. Chạy chương trình bootstrap-vcpkg.bat để sinh vcpkg.exe
3. Để cài đặt thư viện, chạy dòng lệnh __C>vcpkg.exe install openssl__
4. Để liên kết thư viện vừa tải với Visual Studio, chạy dòng lệnh __C>vcpkg.exe integrate install__
5. Mở tệp tin solution có đuôi .sln ở link dưới và chọn chế độ x86 thay vì x64
6. Chạy project
## Tập code thủ công các hệ mật mã (Depending) </br>
https://github.com/volehuy1998/Cryptography-With-C-Sharp
## Đang code
[App](https://github.com/volehuy1998/CryptoApp) </br>
[Console](https://github.com/volehuy1998/Crypto-Manage-Service)

