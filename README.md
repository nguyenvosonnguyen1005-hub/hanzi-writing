[README.md](https://github.com/user-attachments/files/33295710/README.md)
# Luyện viết Hán tự

Trang web một file (`index.html`) giúp luyện viết chữ Hán theo cấp HSK 1–6. Chạy hoàn toàn trên trình duyệt, không cần máy chủ.

## Cách hoạt động
- Hiện một từ (tiếng Việt hoặc English) kèm hình minh họa; người học viết chữ Hán bằng bút lông trên bảng.
- Trình duyệt tự so hình nét vừa viết với chữ mẫu (chỉ so hình dạng, không kiểm tra thứ tự nét) và báo đúng / gần đúng / chưa đúng.
- Nét viết không được gửi đi đâu; lựa chọn cấp HSK và ngôn ngữ chỉ lưu trên thiết bị của người học.

## Nguồn và giấy phép
- Dữ liệu nét chữ: [Hanzi Writer Data](https://github.com/chanind/hanzi-writer-data), gốc từ dự án Make Me a Hanzi và phông của Arphic Technology, theo Arphic Public License. Dữ liệu được tải từ jsDelivr khi trang chạy; không được nhúng vào kho này.
- Thư viện: [Hanzi Writer](https://github.com/chanind/hanzi-writer) (giấy phép MIT).
- Phông dự phòng: LXGW WenKai TC và Noto Sans SC qua Google Fonts (Open Font License).
- Giọng đọc: giọng tiếng Trung có sẵn trên thiết bị (Web Speech API).
- Hình minh họa: emoji của hệ điều hành.
- Kho từ (chữ, pinyin, nghĩa, bộ thủ, cấp HSK) do tác giả soạn, chưa đối chiếu với nguồn chính thức; có thể có sai sót.

## Triển khai
Bật GitHub Pages: Settings → Pages → Branch `main`, thư mục `/ (root)`.
