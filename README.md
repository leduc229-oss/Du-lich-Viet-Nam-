# Du lịch Hà Nội · Hạ Long · Huế · Đà Nẵng · Ninh Bình

Trang web gợi ý địa điểm, giá vé, giờ mở cửa và bản đồ cho 5 tỉnh thành.

## Cấu trúc

```
index.html          # trang chính
data/*.json         # dữ liệu địa điểm từng tỉnh
assets/hero-*.jpg   # ảnh đầu trang từng tỉnh
```

## Chạy thử trên máy

Trang đọc dữ liệu bằng `fetch`, nên cần chạy qua máy chủ (mở trực tiếp file sẽ không tải được dữ liệu):

```bash
python -m http.server 8000
```

Rồi mở http://localhost:8000

## Đưa lên GitHub Pages

1. Đẩy toàn bộ thư mục này lên một repository.
2. Vào **Settings → Pages**, chọn nhánh `main` và thư mục `/ (root)`.
3. Chờ vài phút, trang sẽ có tại `https://<tên-github>.github.io/<tên-repo>/`.
