# Huy Nhà Phố AI Studio – V1 prototype

## Đây là gì?
Bản mẫu giao diện web ưu tiên iPhone, chạy cục bộ trong Safari sau khi mở `index.html`.
Có thể nhập thông tin căn nhà, chọn nhiều video, xem trước video, tạo storyboard mẫu, chỉnh thời lượng/bỏ chọn cảnh, sao chép kịch bản và duyệt phương án.

## Giới hạn rất quan trọng
Đây CHƯA phải AI phân tích hình ảnh/video thực sự. Bản mẫu hiện chỉ tạo storyboard theo quy tắc và thông tin nhập vào; chưa tự chấm điểm cảnh đẹp, chưa tự cắt ghép, chưa tạo bản đồ có dữ liệu trực tiếp và chưa xuất MP4. Không nên giới thiệu đây là ứng dụng hoàn chỉnh.

## Dùng thử trên iPhone
1. Giải nén ZIP trong ứng dụng Tệp.
2. Mở `index.html` bằng Safari nếu iOS cho phép. Trải nghiệm file cục bộ có thể bị giới hạn tùy phiên bản iOS.
3. Chọn video từ Ảnh/Tệp, nhập thông tin, nhấn “Tạo phương án dựng thử”.
4. Chạm vào từng video trong danh sách để xem trước.

Để biến thành ứng dụng cài trên màn hình chính, cần đưa website lên một máy chủ HTTPS. Có thể thử dịch vụ hosting tĩnh có gói miễn phí, nhưng cần kiểm tra giới hạn và điều khoản hiện hành. Bản mẫu này không yêu cầu API key và không gửi video lên máy chủ.

## Hướng phát triển tiếp theo
- V1.1: thêm chọn điểm vào/ra (in/out) cho từng clip bằng bộ điều khiển video.
- V1.2: phân tích khung hình/độ sáng/chuyển động trên thiết bị, có bước anh xác nhận.
- V1.3: tích hợp AI qua API tùy chọn, có cảnh báo chi phí và bảo mật.
- V1.4: dựng timeline và thử xuất MP4 trên Safari iPhone; nếu không ổn định, chuyển sang xử lý cục bộ khác hoặc dịch vụ backend có kiểm soát chi phí.
- V2: bản đồ khu vực/tiện ích với nguồn dữ liệu và kiểm chứng; hiệu ứng nâng cao.

## Bảo mật
Không nhập dữ liệu khách hàng nhạy cảm. Địa chỉ đầy đủ chỉ nên dùng trong nội bộ; không xuất số nhà, tọa độ hay pin chính xác lên video công khai.
