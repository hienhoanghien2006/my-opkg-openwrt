Chuyển đến nội dung
Tìm kiếm hoặc chuyển đến…
Yêu cầu kéo s
Vấn đề
không gian mã
Thương trường
Khám phá
 
@hienhoanghien2006 
hienhoanghien2006
/
gói đầy đủ
Công cộng
rẽ nhánh từ lrdrdn/my-opkg-repo
Không thể rẽ nhánh vì bạn sở hữu kho lưu trữ này và không phải là thành viên của bất kỳ tổ chức nào.
Mã số
Yêu cầu kéo
hành động
dự án
Wiki
Bảo vệ
Thông tin chi tiết
Cài đặt
gói đầy đủ
/
README.md
TRONG
chủ yếu
 

không gian

2

bọc mềm
1
# Máy chủ OpenWrt OPKG cá nhân
2
Cài đặt gói nâng cấp và ứng dụng sửa đổi OpenWrt (có thể là: OpenClash, Passwall, ShadowSocksR+ Plus, Wegare STL, Tiny File Manager, Xderm Mini, v2rayA, Modeminfo, dll) sau đó.
3
​
4
Kelebihan cài đặt và cập nhật cho máy chủ tùy chỉnh theo từng bước:
5
1. Tidak perlu repot menggunakan wget dan curl yang sangat panjang dan rumit.
6
2. Cài đặt gói ipk bằng cách chọn `opkg install nama-paket`.
7
3. Gói cài đặt ipk chỉ được phép cài đặt **Hệ thống - Phần mềm** trên LuCI OpenWrt.
số 8
​
9
Daftar Isi:
10
- [Daftar Arsitektur](#daftar-arsitektur)
11
- [Kho lưu trữ Cara Menambah cập nhật phần mềm OpenWrt](#cara-menambah-repository-ke-software-update-openwrt)
12
- [Gói cài đặt cara và gói cập nhật](#cara-install-dan-update-paket)
13
- [Cara Memeriksa Paket Sudah Terinstal Atau Belum](#cara-memeriksa-paket-sudah-terinstal-atau-belum)
14
- [Tín dụng](#tín dụng)
15
​
16
## Daftar Arsitektur
17
Kho lưu trữ ini mendukung arsitektur dibawah ini:
18
​
19
```
20
aarch64_cortex-a53
21
aarch64_cortex-a72
22
aarch64_generic
23
arm_arm1176jzf-s_vfp
24
arm_cortex-a7_neon-vfpv4
25
i386_pentium4
26
mips_24kc
27
mipsel_24kc
28
x86_64
29
```
30
​
31
## Cara Menambah Kho lưu trữ cập nhật phần mềm OpenWrt
32
Cara menambahkan kho firmware ini ke, dapat menggunakan 2 cara yaitu:
33
- [Menggunakan LuCI](#menggunakan-luci)
34
- [Menggunakan Terminal](#menggunakan-terminal) được cung cấp bởi JuiceSSH/Termius/Termux
35
​
36
​
37
### Menggunakan LuCI
38
​
39
  1. Masuk IP LuCI (contoh: 192.168.1.1), Đăng nhập, Buka **Hệ thống -> Phần mềm -> Cấu hình**
40
  
41
  2. Tambahkan tanda # (pagar) di depan baris ```option check_signature```, contoh dibawah ini
42
  
43
      ubah tulisan dibawah ini
44
      
45
      ```
46
      tùy chọn check_signature
47
      ```
48
      
49
      menjadi seperti ini
50
      
51
      ```
52
      # tùy chọn check_signature
53
      ```
54
​
55
  3. Pada bagian tùy chỉnh nguồn cấp dữ liệu danh sách tambahkan dibawah ini
56
​
Không có tệp nào được chọn
Đính kèm tệp bằng cách kéo và thả, chọn hoặc dán chúng.
Tạo kiểu với Markdown được hỗ trợ
@hienhoanghien2006
Cam kết thay đổi
Tóm tắt cam kết
Cập nhật README.md
Mô tả mở rộng tùy chọn
Thêm mô tả mở rộng tùy chọn…
 Cam kết trực tiếp vớichủ yếuchi nhánh.
 Tạo một nhánh mới cho cam kết này và bắt đầu yêu cầu kéo. Tìm hiểu thêm về yêu cầu kéo.
 
chân trang
© 2023 GitHub, Inc.
điều hướng chân trang
Điều kiện
Sự riêng tư
Bảo vệ
Trạng thái
Tài liệu
Liên hệ với GitHub
định giá
API
Đào tạo
Blog
Về
Chỉnh sửa full-packgare/README.md tại main · hienhoanghien2006/full-packgare
