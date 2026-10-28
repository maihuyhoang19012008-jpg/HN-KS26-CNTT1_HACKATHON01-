


# BÀI LÀM – HACKATHON 01

  

-  **Mã đề:** 22

-  **Họ tên:** MAI HUY HOÀNG

-  **Lớp:** CNTT1

-  **Link repository:** https://github.com/maihuyhoang19012008-jpg/HN-KS26-CNTT1_HACKATHON01-

-  **Hệ điều hành (Windows/macOS):** WINDOWS

  

## 4.2. Thao tác máy tính cơ bản bằng CLI

  

### Các lệnh đã chạy

  

```shell

# pwd

mkdir  RUA  XE  WEBSITE  FINAL

cd  RUA  XE  WEBSITE  FINAL

new-item  bang_quy_trinh.txt

ni  Luot_rua_xe_thang  2.xlsx

  

```

  

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

  

```text

Get-ChildItem "ERROR"

```

  

## 4.3. Lọc log thủ công

  

### Lệnh đã chạy

  

```shell

# (get-content log-he-thong.log | select-string "error").count

```

  

### 2 dòng lỗi đầu tiên trong daily_report.txt

  

```text

2026-02-28 08:39:37 [ERROR] Het thoi gian cho (timeout)

2026-02-28 09:03:37 [ERROR] Dat lich that bai

  

```

  

## 4.4. Thao tác với tài liệu Markdown (README.md)

  

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

  

- [ ] Heading 1: RUA XE WEBSITE FINAL

- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*

- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu

- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án

- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành

- [ ] Blockquote nhắc không upload `.env`

  

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

  

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

  

```shell

# .\auto_report.ps1

```

  

### Kết quả hiển thị

  

```text

  
  

```

  

## 4.6. Đếm số dòng lỗi

  

### Lệnh

  

```shell

# (get-content log-he-thong.log | select-string "error").count

```

  

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

  

```text

6

  

```

  

## 4.7. Báo cáo tổng hợp

  

### Các lệnh đã chạy

  

```shell

# cd tong_hop.txt

  
  

```

  

### Nội dung file logs/tong_hop.txt

  

```text

tong hop ERROR

2026-02-28 08:39:37 [ERROR] Het thoi gian cho (timeout)

2026-02-28 09:03:37 [ERROR] Dat lich that bai

2026-02-28 09:07:37 [ERROR] Dat lich that bai

2026-02-28 09:15:37 [ERROR] Dat lich that bai

2026-02-28 09:19:37 [ERROR] Khong tim thay trang /bang-gia (404)

2026-02-28 09:35:37 [ERROR] Dat lich that bai

Tong hop WARING

2026-02-28 08:35:37 [WARNING] Anh truoc sau dung luong lon

2026-02-28 08:47:37 [WARNING] Anh truoc sau dung luong lon

2026-02-28 09:23:37 [WARNING] Khoang rua so 2 dong khach

2026-02-28 09:27:37 [WARNING] Thoi gian phan hoi cham

  

```

  

## 4.8. Excel

  

> Phần Excel được chấm trực tiếp trên file `data/luot_rua_xe_thang_2.xlsx`, không cần ghi vào đây.
