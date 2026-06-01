# HR Assistant – Sushi Circle
**Gebietsleiter: Duc Thang Duong**

## 🚀 Deployment lên GitHub Pages (5 phút)

### Bước 1 — Tạo GitHub account (nếu chưa có)
Vào https://github.com → Sign up (miễn phí)

### Bước 2 — Tạo repository mới
1. Nhấn dấu **+** góc trên phải → **New repository**
2. Repository name: `hr-sushi` (hoặc tên bất kỳ)
3. Chọn **Public**
4. Nhấn **Create repository**

### Bước 3 — Upload files
1. Trong repository vừa tạo, nhấn **uploading an existing file**
2. Kéo thả toàn bộ các file sau vào:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - Thư mục `icons/` (gồm icon-192.png và icon-512.png)
3. Nhấn **Commit changes**

### Bước 4 — Bật GitHub Pages
1. Vào tab **Settings** của repository
2. Mục **Pages** (thanh bên trái)
3. Source: chọn **Deploy from a branch**
4. Branch: **main** → Folder: **/ (root)**
5. Nhấn **Save**
6. Sau ~1 phút → URL của bạn sẽ là:
   `https://TEN-GITHUB-CUA-BAN.github.io/hr-sushi/`

### Bước 5 — Cài lên iPhone như app thật
1. Mở URL trên Safari iPhone
2. Nhấn nút **Chia sẻ** (hình vuông có mũi tên lên)
3. Chọn **Thêm vào Màn hình chính**
4. Đặt tên **HR Sushi** → nhấn **Thêm**
5. ✅ App xuất hiện trên màn hình chính!

## 📱 Lưu ý quan trọng
- Dữ liệu (nhân viên, verlauf, chữ ký) lưu trong Safari localStorage
- **Không dùng chế độ Private/Incognito** — localStorage sẽ bị xóa
- Khi cập nhật app: upload file `index.html` mới lên GitHub, app tự cập nhật sau vài phút

## 🔄 Cập nhật app
Khi có phiên bản mới từ Claude:
1. Vào repository trên GitHub
2. Click vào file `index.html` → nút bút chì (Edit) → hoặc upload lại
3. App iPhone tự cập nhật lần sau khi mở (service worker)
