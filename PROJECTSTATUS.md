# PROJECT STATUS

## 1. Dự án này là gì?
GreenForecast — CRM Cảnh báo Thời tiết (Next.js). Dashboard CRM cho cán bộ tỉnh/xã giám sát và phân phối cảnh báo thời tiết cực đoan (hệ thống DBWAS — tỉnh Điện Biên).
Tên miền dự kiến khi deploy: `greenarrow.io.vn`.

## 2. Mục tiêu hiện tại là gì?
Phát triển tính năng và kết nối API thật.

## 3. Hệ thống đã hoàn thành những gì?
- Giao diện UI với Next.js (App Router), bản đồ Leaflet.
- Mock data và logic cho 6 màn hình dashboard.
- Các tính năng lọc, chuyển vai trò.
- Đã khởi tạo Git và đẩy mã nguồn dự án lên GitHub.
- Đưa cấu hình kết nối API ra biến môi trường (.env).

## 4. Đang làm gì?
Kết nối với API thật để thay thế mock data (nếu có yêu cầu) hoặc phát triển các tính năng tiếp theo.

## 5. Chưa làm gì?
- Kết nối với API thật.
- Cập nhật số liệu realtime (WebSocket/SSE).

## 6. Những Block lớn là gì?
- App Router (`app/`)
- Components (`components/Dashboard.jsx`)
- Utils/Data (`lib/data.js`, `lib/style.js`)

## 7. Việc ưu tiên tiếp theo?
Kết nối API hoặc phát triển tính năng mới theo yêu cầu của người dùng.
