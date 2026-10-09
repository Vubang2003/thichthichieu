# Báo cáo Prompt và Logic Hiệu ứng - Thách thức Tuần 5
**Tên dự án:** Thichthichieu (Travel Website)

---

## 1. Liệt kê các Prompt đã dùng để xử lý lỗi hiệu ứng
Trong quá trình phát triển và hoàn thiện giao diện chuyển động, nhóm đã sử dụng các câu lệnh (prompt) sau để yêu cầu trợ giúp và sửa lỗi:

* **Prompt 1 (Xử lý hiệu ứng Intro Animation):** 
  > *"Viết giúp tôi các hiệu ứng CSS keyframes cho phần Intro Animation khi tải trang, bao gồm hiệu ứng trượt lên (slide-up) và mờ dần (fade-in) cho phần Header và Hero section, đảm bảo chỉ dùng transform và opacity để tối ưu hiệu năng."*
* **Prompt 2 (Xử lý lỗi cuộn trang và bố cục):** 
  > *"Tại sao khi thêm hiệu ứng chuyển động bằng top và left thì trang web bị giật cục (layout thrashing)? Hãy sửa lại các đoạn CSS này sang dùng transform: translateY() và giải thích cách khắc phục."*
* **Prompt 3 (Xử lý hiệu ứng Micro-interactions cho nút bấm):** 
  > *"Tạo hiệu ứng hover và active mượt mà cho các nút bấm (CTA buttons) và thẻ card du lịch bằng transition kết hợp với scale nhẹ, tạo cảm giác bấm sinh động."*

---

## 2. Giải thích lý do chọn hiệu ứng cho từng Section (Tư duy UX)

* **Section Header & Hero (Intro Animation):**
  * **Lý do:** Đây là phần đầu tiên người dùng nhìn thấy khi truy cập website du lịch. Việc áp dụng hiệu ứng mờ dần (fade-in) kết hợp trượt nhẹ lên trên (slide-up) giúp tạo cảm giác chào đón chuyên nghiệp, thu hút ánh nhìn ngay lập tức vào thông điệp chính mà không gây đột ngột cho thị giác.
* **Section Danh sách chuyến đi / Thẻ Card (Scroll Revelation & Hover):**
  * **Lý do:** Khi người dùng cuộn chuột khám phá nội dung, hiệu ứng các card xuất hiện từ từ tạo nhịp điệu sinh động, kích thích sự tò mò. Khi di chuột vào (hover scale nhẹ), hiệu ứng phản hồi xúc giác giả lập (micro-interactions) giúp tăng trải nghiệm tương tác, làm cho website mang tính hiện đại và sống động hơn.
* **Section Nút bấm / CTA (Micro-interactions):**
  * **Lý do:** Các nút bấm được thêm hiệu ứng đổi màu và phóng to nhẹ khi rê chuột nhằm xác định rõ vùng tương tác, giúp người dùng nhận biết ngay lập tức đâu là vị trí có thể bấm để đặt tour hoặc xem chi tiết.