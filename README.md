# CoinVS_AutoDaily

Aidrop Free : https://t.me/HVchannelss/33

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 8u/1thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây

<img width="559" height="227" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/03d25b90-a12b-46d3-84dd-a49fb41b7713" />

================================================================================
HƯỚNG DẪN CÀI ĐẶT VÀ CẤU TRÚC DỮ LIỆU TOOL AUTO COINVS.IO
================================================================================

1. CÀI ĐẶT THƯ VIỆN (Mở CMD/Terminal tại thư mục tool và chạy lệnh)
--------------------------------------------------------------------------------
npm install axios uuid https-proxy-agent


2. TẠO CÁC FILE DỮ LIỆU (.txt)
--------------------------------------------------------------------------------
Bạn cần tạo 3 file sau nằm cùng thư mục với file bot.js:

A. File "Cokie.txt"
   - Chức năng: Lưu mã đăng nhập của tài khoản.
   - Định dạng: Mỗi dòng 1 Cookie đầy đủ lấy từ trình duyệt (F12 -> Network).
   - Ví dụ:
     _ga=GA1.1.1014392086.1768449089; auth_session=lkgkzwvzdifcyu7h2ozholzonpqku...

B. File "user_agents.txt"
   - Chức năng: Giả lập trình duyệt để tránh bị hệ thống quét bot.
   - Định dạng: Mỗi dòng 1 chuỗi User-Agent. Nên lấy đúng UA của trình duyệt dùng lấy Cookie.
   - Ví dụ:
     Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36

C. File "proxy.txt"
   - Chức năng: Đổi địa chỉ IP để chạy nhiều tài khoản không bị khóa.
   - Định dạng: Mỗi dòng 1 Proxy. Hỗ trợ cả Proxy có user/pass hoặc không.
   - Ví dụ:
     http://1.2.3.4:8080
     http://user:pass@5.6.7.8:9999

3. LƯU Ý QUAN TRỌNG
--------------------------------------------------------------------------------
- Thứ tự dòng: Dòng 1 của Cokie.txt sẽ đi kèm với Dòng 1 của user_agents.txt.
- Profile: Tool sẽ tự tạo file "profiles.json" sau lần chạy đầu tiên để lưu định danh thiết bị.
- Delay: Tool tự động nghỉ 60s - 180s giữa các tài khoản để mô phỏng người dùng thật.
- Khởi chạy: Gõ lệnh `node bot.js` để bắt đầu.
================================================================================
