# 🐔 CHIẾN CƠ TOÁN HỌC: BẮN GÀ & KHỦNG LONG KHÔNG GIAN 🦖

> **Web Game Bắn Gà & Khủng Long Học Toán Dành Cho Học Sinh Tiểu Học**  
> Đồ họa chuẩn phong cách *Chicken Invaders* huyền thoại kết hợp biệt đội Khủng Long Vũ Trụ Chibi siêu đáng yêu!

🌐 **Chơi Trực Tiếp Trên Trình Duyệt:** [https://phunbwork-create.github.io/gamemaybay/](https://phunbwork-create.github.io/gamemaybay/)

---

## 🌟 Những Điểm Mới Trong Phiên Bản Nâng Cấp

1. **Phi Thuyền Chuẩn Phong Cách Chicken Invaders:**
   - Thân tàu kim loại màu bạc bóng bẩy, cánh hình bán nguyệt vòm rộng đặc trưng.
   - Luồng xả phản lực hạt plasma màu xanh neon rực rỡ phía sau.
   - Đạn Laser màu đỏ/cam hoặc đạn Sao Vàng khi vào Fever Mode!

2. **Kẻ Địch Đàn Gà Không Gian (Space Chickens):**
   - Thân tròn mập mạp màu đỏ, mào gà xinh xắn, mắt to tròn hài hước.
   - Cánh lông vũ trắng xòe ra hai bên **vỗ cánh phành phạch sống động** theo nhịp bay.
   - Bắn trúng gà: lông gà bay tung tóe, rơi ra **Đùi Gà Nướng Vàng Rượm 🍗** hoặc **Trứng Vàng 🥚** cho tàu bay vào nhặt lấy thêm điểm!

3. **Biệt Đội Khủng Long Vũ Trụ (Space Dinosaurs):**
   - Khủng long Chibi màu xanh lá siêu cute (T-Rex không gian) đội mũ phi hành gia bong bóng khí, vảy lưng cam vàng lấp lánh, răng sún ngộ nghĩnh.
   - Tùy chọn 3 chế độ biệt đội: *Cả Gà & Khủng Long*, *Chỉ Đàn Gà*, hoặc *Chỉ Khủng Long*.

4. **Background Tinh Vân Tím Huyền Ảo (Cosmic Nebula):**
   - Mây tinh vân tím, hồng và xanh neon phát sáng mờ ảo cùng bụi sao lấp lánh giống hệt 100% bản gốc Chicken Invaders.

5. **Đại Đế Khủng Long Bạo Chúa & Mẹ Gà Khổng Lồ (Boss Battle):**
   - Vòng 10 xuất hiện Boss khổng lồ với 3 nấc máu thách đấu các bài toán hóc búa!

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

- **HTML5 Canvas 2D:** Render 60FPS mượt mà với chuyển động vỗ cánh của đàn gà, hoạt ảnh đùi gà/trứng rơi, hiệu ứng tinh vân vũ trụ.
- **Web Audio API:** Hiệu ứng tiếng gà kêu quác quác, tiếng gầm khủng long cute, tiếng laser, chuông khải hoàn 100% offline.
- **SheetJS (xlsx.full.min.js):** Đọc và tạo file Excel client-side an toàn và bảo mật.
