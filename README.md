# tr-n-quang-hi-p-
bài tập2 của:k225480106018-Trần Quang Hiệp-môn hệ quản trị 
BÀI TOÁN:
- Tạo csdl quan hệ với tên QLSV gồm các bảng sau:
  + SinhVien(#masv,hoten,NgaySinh)
  + Lop(#maLop,tenLop)
  + GVCN(#@maLop,#@magv,#HK)
  + LopSV(#@maLop,#@maSV,ChucVu)
  + GiaoVien(#magv,hoten,NgaySinh,@maBM)
  + BoMon(#MaBM,tenBM,@maKhoa)
  + Khoa(#maKhoa,tenKhoa)
  + MonHoc(#mamon,Tenmon,STC)
  + LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
  + DKMH(#@maLopHP,#@maSV,DiemTP,DiemThi,PhanTramThi)
BÀI LÀM
+ Tạo CSDL QLSV trên giao diện đồ họa:
+ ![image](https://github.com/user-attachments/assets/34ddf40f-735f-4a8d-a94f-bf458621b5b4)
+ ![image](https://github.com/user-attachments/assets/b0e2d427-e55a-4490-ba25-e0cd8fc3f46c)

Tạo bảng sinh viên:
+tại QLDL mới tạo chọn tables-new-tables..
![image](https://github.com/user-attachments/assets/30740b9a-9f99-4e18-8dd0-97e28c241519)


![image](https://github.com/user-attachments/assets/d41a6a6f-f730-43e1-af42-8bcc51c2649d)
CTRL+SHIFT+S Để lưu +đặt tên bản


+ lập lại các bước để tạo các bảng khác 
+ Lop(#maLop,tenLop)
![image](https://github.com/user-attachments/assets/68c92200-9437-4757-942f-36fb69ae9526)
+ GVCN(#@maLop,#@magv,#HK)
+ ![image](https://github.com/user-attachments/assets/af5c23d1-dfdf-4639-ad0f-f355deef8662)
+ LopSV(#@maLop,#@maSV,ChucVu)
+ ![image](https://github.com/user-attachments/assets/fd64609c-9971-47cd-8883-061314fff217)
+ GiaoVien(#magv,hoten,NgaySinh,@maBM)
+ ![image](https://github.com/user-attachments/assets/0ea38466-c96b-4749-940d-9f83704de311)
  + BoMon(#MaBM,tenBM,@maKhoa)
  + ![image](https://github.com/user-attachments/assets/27cdd7e2-d168-45e8-a6dd-64f3d179f537)
  + Khoa(#maKhoa,tenKhoa)
  + ![image](https://github.com/user-attachments/assets/22d004c5-0e56-4030-a47f-0584e9634daf)
 + MonHoc(#mamon,Tenmon,STC)
 + ![image](https://github.com/user-attachments/assets/96806037-86c4-4b51-9ab5-c789ca3e0512)
 + LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
 + ![image](https://github.com/user-attachments/assets/73edabee-b786-4810-8ab9-45074e14a7da)
  + DKMH(#@maLopHP,#@maSV,DiemTP,DiemThi,PhanTramThi)
![image](https://github.com/user-attachments/assets/26fa51b1-e5a1-4164-9590-e21a98c2ecbc)
+ Thiết lập các khóa FK, CK, PK cho bảng
+ ![image](https://github.com/user-attachments/assets/dbafd336-704d-45b1-b97c-dba454885bd4)
+ Các bảng dưới tương tự như các bảng trên
+ Thiết lập FK cho bảng GVCN
+ ![image](https://github.com/user-attachments/assets/7d62fb79-4287-443b-8b6a-421a942133a1)
Chuyển các thao tác đồ họa thành lệnh SQL tương đương


![image](https://github.com/user-attachments/assets/addd2d3c-9f3f-452a-96da-1cd440a95ff5)

![image](https://github.com/user-attachments/assets/1308b89f-020a-48d0-b3ab-715ac7792901)


