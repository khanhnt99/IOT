NFS

![](https://i.ibb.co/zxjrp2P/Screenshot-from-2020-10-07-15-57-37.png)

## Mục tiêu bài LAB:
- Mô phỏng chức năng của NFS
   + 3 Webserver chạy Keepalive và HAProxy để cân bằng tải và đảm bảo tính sẵn sàng cho WebServer
- Các máy trong mạng đều sử dụng Ubuntu 16.04
- Mô hình mangj: Các máy được NAT ra ngoài mạng thông quan Linux Gateway.

## Bước 1: Đặt IP như hình vẽ

### Linux Gateway

![](https://i.ibb.co/gD2VPRH/Screenshot-from-2020-10-07-16-04-55.png)

### Web 1

![](https://i.ibb.co/vsM10xP/Screenshot-from-2020-10-07-16-07-54.png)

### Web2

![](https://i.ibb.co/zJnpzL7/Screenshot-from-2020-10-07-16-10-04.png)

### Web3

![](https://i.ibb.co/ZWz6b1B/Screenshot-from-2020-10-07-16-12-11.png)

## Bước 2: Cấu hình truy cập mạng cho các máy trong mạng

### Trên Linux Gateway:

![](https://i.ibb.co/P1nJMZn/Screenshot-from-2020-10-07-16-15-55.png)

![](https://i.ibb.co/0JdQLqb/Screenshot-from-2020-10-07-16-17-56.png)

### Kiểm tra đã Ping thông trên 3 máy Web 1,2,3

![](https://i.ibb.co/F5knW4Y/Screenshot-from-2020-10-07-16-21-33.png)

![](https://i.ibb.co/K97vqXL/Screenshot-from-2020-10-07-16-22-34.png)

![](https://i.ibb.co/0FP5Td8/Screenshot-from-2020-10-07-16-23-29.png)













