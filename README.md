# Sakura Rail

Sakura Rail là giao diện mô phỏng đặt vé tàu Shinkansen Nhật Bản. Ứng dụng cho phép tìm chuyến tàu, xem lịch trình, tạo vé mô phỏng và quản lý vé đã tạo trên trình duyệt.

## Công nghệ

- React 19 và TypeScript
- Vinext/Vite
- Tailwind CSS
- pnpm

## Cách chạy

Yêu cầu Node.js `>=22.13.0`.

```bash
corepack pnpm install
corepack pnpm dev
```

Mở trình duyệt tại [http://localhost:5173](http://localhost:5173).

Để dùng cổng khác:

```bash
corepack pnpm dev -- --port 3000
```

Sau đó truy cập [http://localhost:3000](http://localhost:3000).

## Kiểm tra bản build

```bash
corepack pnpm build
```

Ứng dụng hiện là bản demo; dữ liệu chuyến tàu và vé chỉ mang tính minh họa, không thực hiện thanh toán hoặc đặt chỗ thật.
