
Là một khung khái niệm, một cách để viết tắt (open system interconnection). Mô tả cách thức hoạt động của giao tiếp mạng

Vì sao lại cần?
-> Vào những ngày đầu mỗi công ty đều tự sx phần cứng và phần mềm của riêng mình. Máy tính IBM chỉ giao tiếp với các máy tính IBM khác

Máy tính DMC chỉ giao tiếp với máy tính DC. Không có gì hoạt động ăn ý với nhau cả. Tình hình hỗn loạn. 

Vì vậy, vào những năm 1980, tổ chức OSI (tổ chức tiêu chuẩn hóa quốc tế) đã tạo ra mô hình OSI

1. **Physical (Lớp vật lý)**  
     Truyền bit thô qua cáp, sóng, tín hiệu điện.
    
2. **Data Link (Liên kết dữ liệu)**  
     Đóng gói frame, xử lý MAC address, phát hiện lỗi cơ bản.
    
     Sử dụng MAC Address
    
3. **Network (Mạng)**  
     Định tuyến (routing), IP address, tìm đường đi cho dữ liệu, ICMP, ARP, IPSec
    
4. **Transport (Giao vận)**  
     Đảm bảo truyền tin cậy (TCP) hoặc không tin cậy (UDP), kiểm soát lỗi và luồng.
    
5. **Session (Phiên)**  
     Thiết lập, duy trì và kết thúc phiên giao tiếp giữa hai hệ thống. NetBIOS, RPC, SIP
    
6. **Presentation (Trình bày)**  
     Mã hóa, giải mã, nén dữ liệu (format, encryption). TLS/SSL, JPEG, MPEG, ASCII
    
7. **Application (Ứng dụng)**  
     Tầng gần người dùng nhất: HTTP, FTP, DNS, email...


**Cách ghi nhớ**
VN (Anh Phải Sống Tới Ngày Động Phòng)
EN (Please Do Not Throw Sausage Pizza Away)


Cách thức tấn công từng Layer
 **Physical (Lớp vật lý)**  
     Dây cáp, Wiretapping, Rogue WAP
    
2. **Data Link (Liên kết dữ liệu)**  
     ARP Spoofing, MAC Flooding, MAC Spoofing
    
3. **Network (Mạng)**  
     IP Spoofing, BGP Hijack, ICMP Smurf
    
4. **Transport (Giao vận)**  
     SYNC Flood DoS, Port Scanning, UDP Flood
    
5. **Session (Phiên)**  
     Session Hijacking, Cookie thief, MTM
    
6. **Presentation (Trình bày)**  
     SSL Stripping, TLS Downgrade, Cert Spoofing
    
7. **Application (Ứng dụng)**  
     SQL injection, XSS, Phising, Malware


![[Cách OSI hoạt động]]
