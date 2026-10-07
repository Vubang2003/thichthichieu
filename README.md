# AURA Voyages

Landing page du lịch cao cấp theo hướng Minimalist & Luxury, kết hợp nhịp chuyển động Vibrant & Immersive và chất liệu bản địa Eco-Cozy.

## Chạy nhanh

Mở trực tiếp `index.html` trong trình duyệt. Trang không dùng JavaScript hay framework; toàn bộ layout, responsive và tương tác nằm trong `styles.css`.

## Các điểm chính

- Intro animation cho header/hero bằng `opacity` + `transform`.
- Bộ lọc hành trình ở hero/discovery section.
- Card tour có hover zoom, CTA có hover/active state.
- Scroll reveal bằng CSS scroll-driven animation native (`animation-timeline: view()`), có fallback và `prefers-reduced-motion`.
- Bố cục semantic HTML5, responsive desktop/tablet/mobile.

Đề bài có nhắc AOS nhưng cũng yêu cầu chỉ HTML5/CSS, nên phần scroll reveal được triển khai bằng CSS native thay cho thư viện JavaScript.
