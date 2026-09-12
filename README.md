# 🚀 CHIẾN CƠ TOÁN HỌC: VỆ BINH NGÂN HÀ (Math Sky Striker)

> **Web Game Bắn Máy Bay Học Toán Dành Cho Học Sinh Tiểu Học**  
> Chơi trực tiếp trên trình duyệt (PC, Laptop, iPad, Máy tính bảng) mà không cần cài đặt!

🌐 **Chơi Online Ngay Tại:** [https://phunbwork-create.github.io/gamemaybay/](https://phunbwork-create.github.io/gamemaybay/)

---

## 🌟 Giới Thiệu Trò Chơi

**Chiến Cơ Toán Học** kết hợp giữa thể loại bắn phi thuyền Arcade vui nhộn và việc rèn luyện tính nhẩm toán học tiểu học, giúp các bé vừa học vừa chơi:
- **Đồ họa Chibi ngộ nghĩnh, màu sắc rực rỡ**, âm thanh vui tai tổng hợp qua Web Audio API (chạy 100% offline).
- **Radar Chỉ Huy Viễn Thám:** Hiển thị phép tính to rõ ràng ở trung tâm phía trên (Ví dụ: `358 + 267 = ?` hoặc `8 x 7 = ?`).
- **Tàu địch mang số đáp án:** Các phi thuyền ngoài hành tinh mang 1 đáp án ĐÚNG và 2-3 đáp án BẪY bay xuống với tốc độ vừa vặn để trẻ quan sát và tính toán.
- **Bé lái máy bay:** Bắn tên lửa vào đúng kẻ địch mang kết quả chính xác để nổ pháo hoa sao vàng, nhận điểm và tích combo!

---

## 🎮 Cách Chơi & Điều Khiển

- **Chuột / Cảm ứng Touch:** Di chuyển chuột/ngón tay để lái phi thuyền lướt theo, click hoặc chạm để bắn tên lửa.
- **Bàn phím:**
  - `←` `→` hoặc `A` `D`: Di chuyển phi cơ sang trái/phải.
  - `Space` (Phím Cách): Bắn tên lửa laser.
  - `1`, `2`, `3`, `4`: **Phím tắt phóng tên lửa tự tìm mục tiêu** tương ứng với 4 vị trí kẻ địch trên màn hình.
  - `P` hoặc `Esc`: Tạm dừng game.

---

## 📚 Các Chế Độ Toán Học Tích Hợp Sẵn

1. ➕ **Cộng có nhớ 3 chữ số (trong phạm vi 1000):** Tự động sinh các số buộc phải nhớ ở hàng đơn vị hoặc hàng chục (VD: $358 + 267 = 625$).
2. ➖ **Trừ có nhớ 3 chữ số (trong phạm vi 1000):** Tự động sinh bài toán có mượn số (VD: $724 - 358 = 366$).
3. ✖️ **Bảng Cửu Chương Toàn Tập (Nhân & Chia 2 đến 9):** Ôn tập bảng nhân và bảng chia thần tốc.
4. 🌟 **Hỗn Hợp Siêu Cấp:** Thách đấu tổng hợp cả 4 phép tính.
5. 📊 **Tùy biến từ File Excel (.xlsx / .csv):** Giáo viên và phụ huynh có thể tự soạn đề bài theo chương trình học.

---

## 📊 Hướng Dẫn Soạn Đề Bài Bằng Excel

Ngay trên màn hình chọn chế độ, bấm nút **"Nhập Đề Từ File Excel (.xlsx)"**:
1. Bấm **"Tải File Mẫu (.xlsx)"** để tải về file Excel mẫu đã định dạng sẵn.
2. Mở file Excel điền thêm các bài toán theo các cột:
   - Cột A: STT
   - Cột B: Phép tính (Ví dụ: `125 + 387`, `9 x 8`)
   - Cột C: Đáp án Đúng
   - Cột D, E, F: Đáp án Sai (Tùy chọn, nếu để trống game sẽ tự tạo bẫy thông minh)
   - Cột G: Lời giải/Gợi ý cho bé khi làm sai
3. Kéo thả file Excel vào game và bắt đầu màn chơi!

---

## 🛠️ Công Nghệ Phát Triển

- **HTML5 Canvas 2D:** Xử lý hiệu ứng đồ họa 60FPS, hệ thống hạt Particle nổ sao lấp lánh (Confetti & Sparkles).
- **Vanilla CSS3:** Giao diện bo tròn phong cách Chibi Glassmorphism.
- **Web Audio API:** Tạo hiệu ứng âm thanh sống động trực tiếp bằng code, hoạt động offline 100% không lo lỗi file nhạc ngoài.
- **SheetJS (xlsx.full.min.js):** Đọc và tạo file Excel client-side an toàn và bảo mật.

---

## 👨‍💻 Tác Giả & Bản Quyền

Dự án được xây dựng với tình yêu dành cho giáo dục tiểu học Việt Nam. Mọi đóng góp và ý kiến phản hồi xin vui lòng tạo Issue hoặc Pull Request trên repository.
