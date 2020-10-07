# MQTT

![](https://raw.githubusercontent.com/mana147/Example-MQTT/master/DOCUMENT/mqtt_broker.png)

## 1. Khái niệm
- Message Queuing Telemetry Transport
- Giao thức gửi dạng publish/subscribe (xuất bản/theo dõi) sử dụng cho các thiết bị internet of things
- Giao thức chạy trên TCP/IP
- Sử dụng cho thiết bị với băng thông thấp, độ tin cậy cao và khả năng sử dụng cho mạng lưới không ổn định

## 2. Kiến trúc
- Gồm Broker và client

### 2.1.Broker
- Máy chủ trung tâm điều phối dữ liệu, có thể hiểu như 1 app chạy trên Server
- Nhận message từ publish
- Xếp các message theo hàng đợi
- Chuyển các message tới địa chỉ cụ thể
- Bảo mật mess

### 2.2. Client
- Chia thành **Publisher** và **Subscriber**
- Subscribe (đăng kí) 1 topic để nhận mess từ topic này
- Publish mess(gửi data) lên 1 topic cụ thể (topic như 1 kênh thông tin được điều phối bởi broker)
