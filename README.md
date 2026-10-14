# Quản lý sức khoẻ cán bộ – BVĐK khu vực Tuyên Hoá (bản GitHub Pages)

Trang web tĩnh (một tệp `index.html`, không cần máy chủ).

## Đăng lên GitHub Pages
1. Tạo tài khoản GitHub, tạo repository mới (ví dụ `suckhoe-canbo`).
2. Tải lên repository **chỉ 3 tệp**: `index.html`, `.nojekyll`, `README.md`.
3. Vào Settings > Pages > Build and deployment > Source: *Deploy from a branch*, chọn nhánh `main`, thư mục `/ (root)`, bấm Save.
4. Sau 1-2 phút trang chạy tại `https://<tên-tài-khoản>.github.io/suckhoe-canbo/`.
5. Tên miền riêng (tuỳ chọn): Settings > Pages > Custom domain, nhập tên miền, rồi tạo bản ghi CNAME (hoặc A) ở nơi bạn đăng ký tên miền theo hướng dẫn của GitHub; bật *Enforce HTTPS*.

## Nhập dữ liệu
Trang không chứa sẵn dữ liệu cán bộ. Mở trang > **Cài đặt > Nhập danh sách cán bộ (.csv)**, chọn tệp `DanhSachCanBo_NHAP_VAO_TRANG.csv` trên máy bạn (không tải tệp này lên GitHub). Bấm "Tải CSV mẫu" để xem định dạng.

## CẢNH BÁO QUAN TRỌNG
- GitHub Pages **công khai**: ai biết địa chỉ đều mở được trang, kể cả khi repository để chế độ private. Vì vậy **tuyệt đối không đưa CCCD, danh sách cán bộ, tệp sao lưu .json hay tệp đính kèm lên repository**. Trang chỉ là "vỏ", dữ liệu chỉ nằm trong trình duyệt của từng máy.
- Dữ liệu lưu riêng trong từng trình duyệt: máy khác không thấy dữ liệu của máy này. Chuyển dữ liệu bằng Cài đặt > Tải bản sao lưu / Nhập bản sao lưu (nhập sẽ ghi đè, không gộp).
- Xoá dữ liệu trình duyệt (cache, cookie) sẽ mất dữ liệu nếu chưa sao lưu.
- Nhiều máy nhập liệu chung một cơ sở dữ liệu cần máy chủ: dùng gói `bvdktuyenhoa-quanly-suckhoe.zip`.
