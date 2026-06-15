# 🔮 Mèo Tiên Tri — Tự học Tarot

Một vũ trụ trong hệ sinh thái [Meomoe Multiverse](https://multiverse.meomoe.com).
Dạy đọc Tarot **từ con số 0** theo **Hành trình Chàng Khờ** (The Fool's Journey):
22 lá Ẩn Chính không rời rạc, mà là một câu chuyện liền mạch — mỗi lá một chặng nối tiếp nhau.

Một trang tĩnh, gói gọn trong **một file** `index.html` (không cần build).

## Có gì trong này
- **Lá hôm nay** — mỗi ngày rút 1 lá cố định (theo ngày) + nghĩa xuôi/ngược, lưu lịch sử rút.
- **Lộ trình** — 22 lá Ẩn Chính chia 3 chương (Thức tỉnh · Nội tâm · Giác ngộ). Chạm từng lá để học:
  nghĩa xuôi/ngược, từ khoá, nguyên tố–chiêm tinh, **vai trò trong hành trình** (nối lá trước & sau), lời Mèo dặn.
- **Ẩn Phụ** — 56 lá theo 4 chất Gậy 🔥 · Cốc 💧 · Kiếm 🗡️ · Tiền 🪙 (Át→10 + 4 lá Hoàng gia), màu riêng từng chất.
- **Trải bài 3 lá** — Quá khứ – Hiện tại – Tương lai, có diễn giải từng lá + lời Mèo nhắc.
- **Ôn tập** — *Lật thẻ* (flashcard) và *Đố từ khoá* (quiz), lọc theo Ẩn Chính / từng chất / "đã học".
- **Lưu tiến độ** trên máy (localStorage): lá nào *đã học*, lá nào *đã thuộc* — kèm thanh tiến độ.
- **Mascot + PWA** — Mèo Tiên Tri (sprite 4 frame động) ở hero; favicon/manifest/service-worker chạy offline.

## Xem thử trên máy
```
node serve.mjs
```
Rồi mở http://localhost:5510

## Đưa lên mạng (GitHub Pages)
- Bật **GitHub Pages** (Settings → Pages → branch `main` / root).
- File `CNAME` gắn tên miền **tarot.meomoe.com**.
- Tại nhà cung cấp tên miền `meomoe.com`, thêm bản ghi:
  `CNAME  tarot  →  <tài-khoản>.github.io`

## Bản sau
Cấu trúc dữ liệu `CARDS` đã sẵn sàng để thêm **56 lá Ẩn Phụ** (Gậy · Cốc · Kiếm · Tiền):
chỉ cần thêm các object mới với `ch` (chương/chất) tương ứng.

_Made with 🎀 & 🐾_
