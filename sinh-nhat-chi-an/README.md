# Happy Birthday chị An 🎂

Trang web chúc mừng sinh nhật: hộp quà mở đầu, bánh 3 tầng thổi nến (bấm hoặc thổi vào micro), nhạc Happy Birthday tự phát bằng Web Audio (có chế độ "hát lệch tông"), mèo Yên & mèo Trúc biết nói, hồ sơ nhân sự vui, album ảnh, thơ lục bát và nút rút lời chúc.

## Đưa lên GitHub Pages
1. Tạo repo mới (ví dụ `sinh-nhat-chi-an`), upload toàn bộ thư mục này (giữ nguyên `index.html` và thư mục `images/`).
2. Vào **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, thư mục `/ (root)` → **Save**.
3. Sau 1–2 phút, link sẽ có dạng `https://<username>.github.io/sinh-nhat-chi-an/`.

> Thổi nến bằng micro cần chạy trên https (GitHub Pages đã có sẵn). Mở file trực tiếp trên máy thì vẫn bấm nến bình thường.

## Chỉnh sửa nhanh (trong `index.html`)
- Ảnh & caption: mảng `PHOTOS` (thay file trong `images/`, giữ tên hoặc sửa đường dẫn).
- Lời chúc ngẫu nhiên: mảng `WISHES`.
- Câu mèo nói: `CAT_LINES`.
- Màu lông mèo: biến CSS `--cat-yen` và `--cat-truc` trong `:root`.
- Lời bài hát hiển thị: mảng `PHRASES`.
