---
title: Thiết kế Web 🖥️
markmap:
  colorFreezeLevel: 2
  color:
      - "#4287f5"
      - "#34a853"
      - "#fbbc05"      
      - "#ea4335"
      - "#ff69B4"
---
# **Thiết kế Web** 🖥️

## **1. Kiến thức cơ bản**
### **1.1. Web hoạt động như thế nào?**
#### **→ Khi bạn nhập URL vào trình duyệt, điều gì xảy ra?**
#### **Trình duyệt gửi yêu cầu tư HTTP/HTTPS đến server.**
- Đây là cách trình duyệt giao tiếp với máy chủ để lấy dữ liệu.
#### **Server xử lý và phản hồi HTML, CSS, JS.**
- Máy chủ trả về các tệp cần thiết để trình duyệt hiển thị trang web.
#### **Trình duyệt tải và hiển thị nội dung web.**
- Trình duyệt diễn giải mã nguồn và hiển thị giao diện cho người dùng.
#### **Nếu có API, JavaScript sẽ gửi request đến API để lấy dữ liệu động.**

### **1.2. Ngôn ngữ lập trình**
#### **1.2.1. HTML (Cấu trúc nội dung)**
- Định nghĩa cấu trúc cơ bản của trang web.
#### **1.2.2. CSS (Trình bày giao diện)**
- Chịu trách nhiệm về màu sắc, bố cục và phong cách.
#### **1.2.3. JavaScript (Tương tác người dùng)**
- Thêm tính năng động, như xử lý sự kiện.
#### **1.2.4. Các ngôn ngữ backend (PHP, Python, Node.js,...)**
- Các ngôn ngữ này xử lý logic phía server.

### **1.3. Cơ sở dữ liệu**
#### **MySQL, PostgreSQL, MongoDB,...**
#### **Quản lý và truy xuất dữ liệu**

### **1.4. Kiến thức mạng**
#### **1.4.1. Giao thức HTTP/HTTPS**
- Đảm bảo dữ liệu được truyền tải an toàn giữa trình duyệt và server
#### **1.4.2. Domain, hosting**
- **Domain:** Tên miền là địa chỉ của trang web (ví dụ: example.com).
- **Hosting:** Dịch vụ lưu trữ để lưu các tệp của trang web trên máy chủ.
#### **1.4.3. Mô hình client-server**

### **1.5. Thiết kế UX/UI**
#### **Trải nghiệm người dùng (UX):** Tập trung vào việc tối ưu hóa trải nghiệm của người dùng khi sử dụng trang web.
#### **Giao diện người dùng (UI):** Liên quan đến thiết kế giao diện trực quan, như bố cục, màu sắc, và các yếu tố đồ họa.
#### **Tính thân thiện và dễ sử dụng:** Đảm bảo trang web hoạt động tốt trên nhiều thiết bị, từ máy tính để bàn đến điện thoại di động.

## **2. Thiết kế web từ công cụ trực tuyến**
### **2.1. Nền tảng kéo thả**
#### **Wix, Squarespace, Weebly,...:** Các công cụ phổ biến để thiết kế giao diện web tĩnh.
#### **Ưu điểm:** Dễ sử dụng, nhanh chóng
#### **Nhược điểm:** Hạn chế tùy chỉnh

### **2.2. Hệ thống quản trị nội dung (CMS)**
#### **WordPress, Joomla, Drupal,...:** Các nền tảng CMS phổ biến để quản lý nội dung.
#### **Ưu điểm:** Linh hoạt, nhiều plugin
#### **Nhược điểm:** Cần thời gian học

### **2.3. Công cụ thiết kế giao diện**
#### **Figma, Adobe XD, Sketch,...:** Các công cụ thiết kế giao diện trước khi phát triển.
#### **Thiết kế wireframe và mockup:** Tạo bản mẫu để kiểm tra ý tưởng trước khi lập trình.
#### **Tạo prototype tương tác:** Kiểm tra tính năng và trải nghiệm người dùng trước khi triển khai.

## **3. Thiết kế web thủ công**
### **3.1. Viết mã HTML, CSS, JavaScript**
#### **HTML tạo cấu trúc**
#### **CSS định dạng giao diện**
#### **JavaScript thêm tương tác**
#### **Kiểm soát hoàn toàn mã nguồn**
#### **Tùy chỉnh cao**
#### **Yêu cầu kiến thức lập trình vững chắc**

### **3.2. Tối ưu hóa hiệu suất**
#### **Nén và tối ưu hình ảnh**
#### **Tăng tốc độ tải trang**
#### **Cải thiện trải nghiệm người dùng**

### **3.3. Thiết kế responsive**
#### **Tương thích với nhiều thiết bị**
#### **Đảm bảo giao diện tương thích trên mọi thiết bị (PC, tablet, mobile).**
#### **Các kĩ thuật như Media query, flexbox, grid...**

### **3.4. Các kỹ thuật nâng cao**
#### **Các thư viện CSS giúp thiết kế nhanh và đẹp.**
#### **Tối ưu hiệu năng:** Giảm thời gian tải trang, cải thiện trải nghiệm người dùng.

## **4. Thiết kế web dựa trên framework**
### **4.1. Framework CSS**
#### **Bootstrap, Tailwind CSS, Materialize,...**
#### **Tạo giao diện nhanh chóng, nhất quán**
#### **Tiết kiệm thời gian lập trình**
#### **Ưu điểm:** Dễ sử dụng, tiết kiệm thời gian.
#### **Nhược điểm:** Có thể làm website nặng nếu không tối ưu.

### **4.2. Framework JavaScript**
#### **React, Angular, Vue.js,...**
#### **Xây dựng ứng dụng web phức tạp**
#### **Quản lý state, routing**
#### **Ưu điểm:** Tăng tính tương tác, hiệu quả cao.
#### **Nhược điểm:** Cần thời gian học hỏi, phức tạp hơn.

### **4.3. Framework backend:**
#### **Laravel, Django, Ruby on Rails,...:** Các framework để xử lý logic phía server.
#### **Xây dựng logic server-side**
#### **Kết nối cơ sở dữ liệu**
#### **Ưu điểm:** Hỗ trợ phát triển nhanh, bảo mật tốt.
#### **Nhược điểm:** Cần hiểu rõ ngôn ngữ lập trình liên quan.

## **📌Lưu ý**
### **Đây là dàn ý cơ bản, bạn có thể bổ sung thêm các nhánh con tùy theo nhu cầu.**
### **Mỗi nhánh lớn có thể được chia thành nhiều nhánh nhỏ hơn để chi tiết hóa nội dung.**
### **Việc thiết kế web cần có tư duy về SEO để tối ưu hóa trang web với các công cụ tìm kiếm.**