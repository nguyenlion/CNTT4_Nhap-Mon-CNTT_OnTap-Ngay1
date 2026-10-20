# bai_lam_ngay1

# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên: Hieu**
- **Lớp: CNTT4**
- **Link repository:**
- **Hệ điều hành (Windows/macOS): Window**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.
> 

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```bash
B1
pwd
B2
ls -Force
B3
Move-Item .\lich_hoc.txt .\docs\
Move-Item .\logo_trung_tam.PNG .\media\
Move-Item .\anh_lop_hoc.JPG .\media\
B4
Copy-Item .\media\logo_trung_tam.PNG .\archive\
B5
rm .\temp_201.tmp
rm .\temp_202.tmp
B6
cd .\logs\
ls 
cd ..
B7
cd docs
Copy-Item "..\media\anh_lop_hoc.JPG" "..\archive\"
cd ..
B8
ls -Force
```

### Kết quả B1 (pwd)

```
C:\Users\huyda\starter-kit\trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        20/10/2026   9:39 pm                archive
d-----        20/10/2026   9:24 pm                data
d-----        20/10/2026   9:26 pm                docs
d-----        20/10/2026   9:24 pm                logs
d-----        20/10/2026   9:27 pm                media
-a----        19/10/2026  10:04 am             83 .env
-a----        19/10/2026  10:04 am            902 bai_lam_ngay1.md
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm: 100**/100
- **Lỗi mình đã mắc và cách sửa:**