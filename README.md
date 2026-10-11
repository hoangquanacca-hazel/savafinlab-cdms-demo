# Sava CDMS — demo (GitHub Pages)

Trang `https://cdms.savafinlab.com.vn` phục vụ trực tiếp file `index.html` của repo này (GitHub Pages, tên miền trong `CNAME`).

## Cập nhật
Bản gốc đầy đủ của app nằm ở máy (`D:\Phần mềm Hải quan\cdms_local_mvp.html`) và repo riêng tư `savafinlab-cdms`.
Sau **mỗi lần** thay `index.html` bằng bản mới từ bản gốc, phải **chèn lại phần nhận diện Savafinlab**:

1. `<title>Sava CDMS | Savafinlab</title>`
2. Trước `</head>`: nguyên khối `SAVA-BRAND v2` (favicon, font Inter, `brand.css`, `sava-bar.js`, `theme-color`, và thẻ `<style id="sava-brand-v2">` đổi font + ô biểu tượng header).
3. Ngay sau `<body ...>`: `<sava-bar product="Sava CDMS"></sava-bar>`.
4. Chân trang giới thiệu tác giả + liên kết `www.savafinlab.com.vn` (cuối file; nền navy #0B1B3F, viền trên đỏ son #C0262D, chữ `savafinlab` với `finlab` #FF7A6B).

Kiểm tra sau khi đưa lên: mở trang, thấy thanh navy với logo Trục cân bằng và `savafinlab / Sava CDMS` ở đầu trang; favicon là icon vòng 0 + trục đỏ.
