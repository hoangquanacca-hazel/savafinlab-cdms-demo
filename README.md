# Sava CDMS — demo (GitHub Pages)

Trang `https://cdms.savafinlab.com.vn` phục vụ trực tiếp file `index.html` của repo này (GitHub Pages, tên miền trong `CNAME`).

## Cập nhật
Bản gốc đầy đủ của app nằm ở máy (`D:\Phần mềm Hải quan\cdms_local_mvp.html`) và repo riêng tư `savafinlab-cdms`.
Sau **mỗi lần** thay `index.html` bằng bản mới từ bản gốc, phải **chèn lại phần nhận diện Savafinlab**:

1. `<title>Sava CDMS | Savafinlab</title>`
2. Trước `</head>`: 3 thẻ (favicon, `brand.css`, `sava-bar.js`) trong khối chú thích `SAVA-BRAND v1`.
3. Ngay sau `<body ...>`: `<sava-bar product="Sava CDMS"></sava-bar>`.
4. Chân trang giới thiệu tác giả + liên kết `www.savafinlab.com.vn` (đã có ở cuối file).

Kiểm tra sau khi đưa lên: mở trang, thấy thanh navy `sava finlab / Sava CDMS` ở đầu trang.
