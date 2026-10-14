# SmartShelf – Tra cứu sản phẩm

## Tên đề tài

SmartShelf RetailTech OS – hệ thống hỗ trợ vận hành siêu thị bán lẻ.

## Trang thực hiện

`shopper-product-search.html` – trang tra cứu sản phẩm dành cho khách mua sắm.

Trang giúp khách tìm sản phẩm và xem thông tin tồn kho, thương hiệu, giá và vị trí kệ trong siêu thị.

## Chức năng chính

- Tìm kiếm theo tên, SKU, thương hiệu hoặc vị trí kệ.
- Lọc theo danh mục, khu vực, tình trạng hàng, thương hiệu và mức giá.
- Sắp xếp theo tên, giá hoặc số lượng tồn kho.
- Chọn gợi ý tìm kiếm nhanh và đọc từ khóa/danh mục từ URL (`q`, `category`).
- Xem trạng thái hàng hóa và liên kết tới thao tác xem vị trí hoặc gợi ý sản phẩm thay thế.

## Công nghệ sử dụng

- HTML5
- CSS3: Flexbox, Grid và media queries
- JavaScript thuần
- LocalStorage để lưu dữ liệu mẫu và trạng thái ứng dụng

## Cấu trúc thư mục

```text
.
├── shopper-product-search.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   ├── app.js
│   ├── data.js
│   └── store.js
└── README.md
```

Các file CSS và JavaScript được giữ riêng. Trang nạp `data.js`, `store.js` và `app.js`, là các file cần thiết cho dữ liệu, tìm kiếm và khung giao diện.

## Chạy thử

Mở `shopper-product-search.html` bằng trình duyệt. Nếu trình duyệt hạn chế một số tính năng khi mở file trực tiếp, chạy thư mục này bằng tiện ích Live Server.

## Liên kết nộp bài

- Figma: [Figma link](https://www.figma.com/design/oS4YO75RZd4Mo9WPVPliGs/shopper?node-id=0-1&p=f)
- Video trình bày: Chưa cập nhật.
- GitHub: [GitHub link](https://github.com/khanH-tqk/shopper)
