# Tải phần mềm Dựng Phim / Cắt Highlight

Bộ cài cho Windows 10 / 11 (64-bit). Nhấp đúp file vừa tải để cài, không cần quyền admin. Đã cài bản cũ thì cài đè lên.

| Phần mềm | Dùng để | Tải về |
|---|---|---|
| **Dựng Phim** 0.12.2 | Tự dựng video từ kịch bản: giọng đọc AI, cắt ghép footage, phụ đề, xuất 16:9 và 9:16. Mọi dự án dùng giao diện kiểu CapCut (tự lưu): to dần / nhỏ dần âm thanh kéo chuột như Premiere (đường thẳng / Cosine, độ cong), cắt ngắn / tách / thay riêng âm thanh track chính, mẫu video, tốc độ / đường cong tốc độ, phụ đề tự động (dịch song ngữ), đọc chữ thành giọng, nhãn dán, chọn vùng để xuất. Trình dựng kiểu CapCut / Premiere: âm thanh, chữ tự đi theo hình khi thêm / xoá / kéo mép / đổi thứ tự cảnh; bỏ liên kết hình – tiếng, khoá / tắt tiếng / solo từng track, menu chuột phải, nhân bản footage bằng Alt + kéo. Dựng vlog tự động từ footage điện thoại, dựng tự do không cần kịch bản, lưu dự án để dựng tiếp (bấm đúp file .dungphim), mask, bản đồ động từ link Google Maps, motion graphic minh hoạ, chống rung, ghi âm + hiệu ứng âm thanh, tự cân bằng âm lượng khi xuất, chỉnh màu (LUT, preset Lightroom), AI chọn nhạc từ kho của bạn, tách giọng / nhạc nền / tiếng động, logo kênh, hàng chờ dựng nhiều video | [DungPhim-Setup-0.12.2.exe](https://github.com/phudangngoc244/phanmem/releases/download/dungphim-v0.12.2/DungPhim-Setup-0.12.2.exe) (1.5 GB) |
| **Cắt Highlight** 0.7.2 | Cắt highlight phim: tự chia phân cảnh, tóm tắt nội dung, giữ / cắt / lật hình, ghép nhiều tập. Khung hình, logo kênh, chèn hình, tách / thay nhạc nền (nhạc thay thế to dần / nhỏ dần kéo chuột như Premiere), hàng chờ xuất nhiều phim | [CatHighlight-Setup-0.7.2.exe](https://github.com/phudangngoc244/phanmem/releases/download/cathighlight-v0.7.2/CatHighlight-Setup-0.7.2.exe) (236 MB) |

Các bản cũ hơn và ghi chú từng bản: [Releases](https://github.com/phudangngoc244/phanmem/releases).

## Cần biết trước khi cài

- **Cần tài khoản.** Mở phần mềm lần đầu sẽ hiện màn hình đăng nhập. Tài khoản do người gửi phần mềm cho bạn cấp.
  Mỗi tài khoản dùng trên số máy đã được cấp; không có mạng vẫn dùng tiếp được 3 ngày.
- **Đổi sang máy khác:** trên máy cũ bấm **Đăng xuất** (màn hình đầu, hoặc Cài đặt → Tài khoản) để trả lượt máy, rồi
  đăng nhập trên máy mới. Một tài khoản dùng chung cho cả hai phần mềm.
- **Windows có thể cảnh báo** "Windows protected your PC" vì bộ cài chưa ký số: bấm **More info** → **Run anyway**.
- **API key do bạn tự nhập.** Phần tóm tắt / dịch / giọng đọc bằng AI trên mạng cần key của chính bạn, nhập trong
  **Cài đặt**. Key Gemini miễn phí lấy tại [aistudio.google.com/apikey](https://aistudio.google.com/apikey).
- **Lần đầu dùng** phần mềm tự tải thêm model AI chạy trên máy (vài chục MB đến khoảng 1.6 GB tuỳ tính năng).
- **Bộ cài Dựng Phim từ 0.10.0 nặng khoảng 1.5 GB** vì kèm thư viện để chép lời bằng card đồ hoạ NVIDIA (Dựng vlog).
  Máy không có card NVIDIA vẫn cài và dùng bình thường.
- **Mở lại dự án Dựng Phim:** bấm đúp file `.dungphim` trong thư mục dự án (từ bản 0.11.0), hoặc mở Dựng Phim →
  **Dự án gần đây** / **Mở dự án**. Giữ file `.dungphim` cùng thư mục với footage của dự án.
- **Cắt Highlight → Dựng Phim:** nút "Mở trong Dựng Phim" của Cắt Highlight cần cài cả Dựng Phim trên cùng máy.
- **Hàng chờ:** làm xong video nào thì bấm **Xuất video → Thêm vào hàng chờ** rồi làm tiếp video khác; khi sẵn sàng mở
  **Hàng chờ** bấm **Bắt đầu** để máy xuất lần lượt (giống Adobe Media Encoder).

