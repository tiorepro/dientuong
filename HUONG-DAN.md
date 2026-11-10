# Diện Tướng Học — đưa lên GitHub Pages và cài vào điện thoại

## Trong thư mục này
- `index.html`: app
- `manifest.webmanifest`: khai báo tên app "Diện Tướng Học", màu, biểu tượng
- `sw.js`: để điện thoại nhận diện là app cài được (không lưu bản chạy khi mất mạng)
- `icons/`: biểu tượng ấn triện trên nền giấy dó ngà
- `.nojekyll`: giữ nguyên tệp khi GitHub Pages đăng

## Bước 1: Tạo kho trên GitHub
1. Vào github.com, đăng nhập (chưa có thì đăng ký miễn phí).
2. Bấm dấu **+** góc trên, chọn **New repository**.
3. Đặt tên, ví dụ `dien-tuong-hoc`. Chọn **Public**. Bấm **Create repository**.

## Bước 2: Tải tệp lên
1. Trong kho vừa tạo, bấm **uploading an existing file** (hoặc **Add file → Upload files**).
2. Giải nén tệp zip trên máy tính, kéo **toàn bộ nội dung bên trong** thư mục `dien-tuong-hoc` vào trang (gồm `index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll` và thư mục `icons`).
   - `index.html` phải nằm ngay ở gốc kho, không nằm trong thư mục con.
   - Trên máy Mac, tệp `.nojekyll` bị ẩn: bấm Cmd + Shift + . trong Finder để hiện ra. Nếu thiếu tệp này app vẫn chạy bình thường.
3. Bấm **Commit changes**.

## Bước 3: Bật GitHub Pages
1. Trong kho, vào **Settings → Pages**.
2. Mục **Source** chọn **Deploy from a branch**; **Branch** chọn `main`, thư mục `/ (root)`. Bấm **Save**.
3. Đợi 1–2 phút, tải lại trang, sẽ thấy địa chỉ dạng `https://ten-cua-ban.github.io/dien-tuong-hoc/`.

## Bước 4: Cài vào điện thoại
**iPhone (Safari):** mở địa chỉ trên bằng Safari, bấm nút **Chia sẻ** (ô vuông có mũi tên), chọn **Thêm vào MH chính**, bấm **Thêm**.

**Android (Chrome):** mở địa chỉ bằng Chrome, bấm menu ba chấm, chọn **Cài đặt ứng dụng** hoặc **Thêm vào màn hình chính**.

Biểu tượng ấn triện với tên "Diện Tướng Học" sẽ hiện ngoài màn hình chính; mở ra là toàn màn hình, không có thanh trình duyệt.

## Khi cần cập nhật
Vào kho, bấm vào `index.html` → biểu tượng bút chì để sửa, hoặc **Add file → Upload files** để tải bản mới đè lên, rồi **Commit**. Sau 1–2 phút, mở lại app trên điện thoại là có bản mới.

## Lưu ý
- Hồ sơ đã lưu nằm trong bộ nhớ của từng điện thoại, không đồng bộ giữa các máy. Gỡ app khỏi màn hình chính hoặc xóa dữ liệu trình duyệt sẽ mất hồ sơ.
- Kho để Public thì ai có địa chỉ cũng mở được app (nhưng không xem được hồ sơ của bạn).
