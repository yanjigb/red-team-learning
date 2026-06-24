DNS (Domain Name System)

Chuyển đổi tên miền thành IP

Provides a simple way for us to communicate with devices on the internet without remembering complex numbers

An IP address looks like the following 104.26.10.229, 4 sets of digits ranging from 0 - 255 separated by a period

Internet không thích tên miền.
Internet thích IP.

Bạn nhập:

```
google.com
```

DNS dịch thành:

```
142.x.x.x
```

Nhớ:

> DNS = Danh bạ điện thoại Internet

![[DNS Record Types]]

![[How DNS request working]]

Cách browser tìm google.ocm

1. Browser cache
2. OS DNS Cache
3. DNS Resolver
4. Root server
5. Connect !
6. IP Returned
7. Authoritative NS
8. TLD Nameserver

Luồng hoạt động khi nhấn enter tìm website

1. URL Parsed
2. DNS Resolution
3. IP Routing
4. TCP handshake
5. TLS handshake
6. HTTP Get request
7. Server response
8. Render