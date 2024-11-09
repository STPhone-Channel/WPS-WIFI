# WPS-WIFI
KIỂM TRA BẢO MẬT PIN VÀ MẬT KHẨU - MODEM WIFI

# HƯỚNG DẪN SỬ DỤNG - VUI LÒNG ĐỌC KĨ TRƯỚC KHI DÙNG:
0. ÁP DỤNG CHO CÁC ĐẦU MODEM WIFI CŨ CÓ TRONG DANH SÁCH HỖ TRỢ
             (HIỂN THỊ MÀU XANH LÁ CÂY TRÊN TERMUX)

A: CHUẨN BỊ:
1. Unlock và Root thiết bị - Tải ứng dụng Termux và cấp quyền su (Root)
2. Mở ứng dụng Termux và sao chép CODE 2 PHẦN dưới dây vào. 
		(Copy tất cả theo từng phần - thao thác 2 lượt)


Phần 1: Thiết lập tài nguyên thư viện
* pkg update && pkg upgrade -y
* pkg install root-repo -y
* pip install pycryptodome
* pkg install git tsu python wpa-supplicant pixiewps iw openssl -y
* git clone https://github.com/STPhone-Channel/WPS-WIFI.git

Phần 2: Khởi chạy chương trình và CHEAT
* cd WPS-WIFI
* chmod +x WPS-WIFI.py
* sudo python WPS-WIFI.py -i wlan0 -K

# Lưu ý:
# - trong quá trình tải và cài đặt tài nguyên thư viện, nếu có yêu cầu từ mã nguồn vui lòng nhập Y để đồng ý.
# - khi khởi động chương trình và cheat vui lòng nhập số tương ứng được hiển thị trên modem xanh lá vào để thực hiện CHEAT.
