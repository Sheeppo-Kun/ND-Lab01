# NDLab01 - Packet Tracer Introduction

## 1. Giới thiệu
Bài thực hành triển khai và kiểm thử một mô hình mạng bằng Cisco Packet Tracer.

## 2. Thành phần mạng
- R1-ISP
- R2-Central
- S1-Central
- Eagle Server
- 11 Pod, mỗi Pod gồm 2 máy tính

## 3. Nội dung thực hiện
- Cấu hình địa chỉ IP cho các thiết bị.
- Cấu hình kết nối Serial giữa R1-ISP và R2-Central.
- Cấu hình kết nối LAN giữa R2-Central và S1-Central.
- Cấu hình Eagle Server.
- Cấu hình static route giữa các mạng.
- Kiểm tra kết nối giữa các thiết bị.

## 4. Kiểm thử
Các lệnh và công cụ được sử dụng:
- `show ip interface brief`
- `show ip route`
- `show running-config`
- `ipconfig`
- `ping`
- `tracert`
- Simulation Mode với ARP/ICMP

Kết quả kiểm thử T1–T7: **PASS**.

## 5. File trong Repository
- `NDLab01.pkt`: File mô hình Cisco Packet Tracer của bài thực hành.
- `README.md`: Tài liệu mô tả bài thực hành.

## 6. Cách sử dụng
Mở file `NDLab01.pkt` bằng Cisco Packet Tracer để xem topology, cấu hình thiết bị và thực hiện lại các bước kiểm thử.
