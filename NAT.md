**NAT (Dịch địa chỉ mạng)** có chức năng chính là chuyển đổi địa chỉ IP riêng (private IP - dùng trong nội bộ) thành địa chỉ IP công cộng (public IP - dùng trên Internet) khi dữ liệu đi ra khỏi mạng cục bộ.

- **Trường hợp 1 (Gửi đến ISP):** ISP nằm bên ngoài mạng nội bộ của bạn (trên Internet). Để giao tiếp được với họ, router phải "dịch" địa chỉ IP riêng của máy tính thành địa chỉ IP public của router thì gói tin mới đi ra Internet được.

- **Trường hợp 2 (Gửi đến trang web nhà sản xuất):** Đây cũng là một đích đến nằm trên Internet. Router bắt buộc phải thực hiện NAT để máy tính trong nhà có thể truy cập được vào server bên ngoài.