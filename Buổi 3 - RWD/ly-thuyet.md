# Mục tiêu

- Hiểu về RWD
- Lợi ích khi sử dụng RWD cho website
- Hiểu các chiến lược cho Thiết kế Web Responsive:
  - Identifying breakpoints
  - Lowering page load time
  - Optimizing image size
  - Mobile First
  - Research First

# Output: https://www.figma.com/design/12rqQOBjB2qunud8elbXoE/Bu%E1%BB%95i-3---Component---Prototype?node-id=0-1&t=JwQN6iCTcMDKUCAQ-1

---

# Slide 3

## RWD

**Responsive Web Design (RWD)** là cách thiết kế website để tối ưu trải nghiệm xem và sử dụng trên nhiều loại thiết bị khác nhau (PC, smartphone, tablet…).  
Trang web sẽ tự động thay đổi bố cục, kích thước, hiển thị để phù hợp nhất với từng loại màn hình mà không cần phóng to, cuộn ngang nhiều hoặc thao tác khó chịu.

---

## Lợi ích của RWD

- **Smooth navigation**: Dẫn hướng mượt mà
- **Easy reading**: Dễ đọc
- **Minimum pinching**: Hạn chế thao tác “bóp/zoom”
- **Reduces scrolling and zooming**: Giảm cuộn/zoom không cần thiết
- **Excellent user experience**: Trải nghiệm tuyệt vời

---

## Lợi ích đối với người dùng

- Linh hoạt, dễ sử dụng trên nhiều thiết bị
- Tự động sắp xếp nội dung, điều chỉnh hình ảnh & cỡ chữ
- Đọc thông tin thuận tiện, phù hợp cá nhân
- Hỗ trợ tìm kiếm nhanh, thông minh
- Tiết kiệm thời gian duyệt web
- Nâng cao trải nghiệm

---

## Lợi ích đối với Web Designer

- **Đơn giản hóa quy trình thiết kế**
  - Một giao diện duy nhất cho nhiều thiết bị
  - Nhanh gọn, dễ lên kế hoạch, giảm lỗi
- **Tiết kiệm thời gian & công sức**
  - Không cần nhiều bản code riêng
  - Dễ quản lý, chỉnh sửa, cập nhật
- **Giảm chi phí đầu tư ban đầu**
  - Một hệ thống duy nhất, giảm chi phí thiết kế, lập trình, kiểm thử
- **Loại bỏ duy trì nhiều website**
  - Một website chạy trên mọi thiết bị
  - Không cần đồng bộ dữ liệu nhiều phiên bản
- **Giảm chi phí bảo trì & phát triển**
  - Cập nhật một nơi duy nhất
  - Giảm rủi ro lỗi không đồng nhất
- **Tăng hiệu quả đầu tư lâu dài**
  - Website phù hợp nhiều thiết bị → nhiều người dùng hơn
- **Cải thiện SEO**
  - Google ưu tiên website responsive
- **Hiệu suất tốt hơn → doanh số tốt hơn**
  - Website tải nhanh, UX tốt → tăng tỷ lệ chuyển đổi
- **Tăng thị phần**
  - Đáp ứng mọi thiết bị, tiếp cận nhiều nhóm khách hàng

👉 **Kết luận**: RWD giúp designer & doanh nghiệp tiết kiệm thời gian, chi phí, dễ bảo trì, tăng hiệu quả kinh doanh & mở rộng thị trường.

---

## Các kỹ thuật cơ bản cho RWD

- **Fluid, Proportion-based Grids (Lưới tỉ lệ co giãn)**
  - Grid theo % thay vì px cố định.
  - Ví dụ: Cột chiếm 30% chiều rộng màn hình sẽ tự co giãn.
- **Flexible Images (Hình ảnh linh hoạt)**
  - Hình ảnh tự co giãn theo khung chứa.
- **CSS3 Media Queries & Screen Resolutions**
  - Áp dụng CSS khác nhau tùy device (width, height, orientation…).

---

# Slide 4

## Breakpoint là gì?

- **Breakpoint**: giá trị độ rộng màn hình (px) tại đó giao diện thay đổi bố cục/style.
- Ví dụ:
  - `<600px`: mobile
  - `601–1024px`: tablet
  - `>1024px`: desktop

---

## Media Query

**Media Query** là tính năng của CSS3 cho phép áp dụng CSS khác nhau tùy thiết bị.

- **Tại sao cần dùng?**
  - Hiển thị tốt trên mọi thiết bị
  - Tối ưu UX mà không cần nhiều phiên bản website
  - Dễ duy trì, tăng khả năng tiếp cận

---

## Adaptive Design

- **Định nghĩa**: nhiều layout cố định cho từng breakpoint.
- **Đặc điểm**:
  - Layout 320px, 768px, 1024px…
  - Không co giãn mượt, chỉ “nhảy” layout khi đổi breakpoint
  - Phát hiện thiết bị & render layout tương ứng

**So sánh Responsive vs Adaptive**:

| Responsive                            | Adaptive                                    |
| ------------------------------------- | ------------------------------------------- |
| Layout fluid, linh hoạt               | Layout cố định                              |
| Thay đổi mượt theo độ rộng            | Nhảy sang layout khác                       |
| Công nghệ: Flexbox, Grid, Media Query | Layout riêng biệt cho mobile/tablet/desktop |

---

## Chiến lược thiết kế

### Progressive Enhancement (Mobile-First)

- Bắt đầu từ mobile → mở rộng lên desktop
- Ưu tiên tối ưu cho mobile, tải nhanh
- Hạn chế: khó phóng to lên desktop phức tạp

### Graceful Degradation (Desktop-First)

- Bắt đầu từ desktop → thu nhỏ cho mobile
- Ưu điểm: dễ thiết kế chức năng phức tạp
- Hạn chế: mobile dễ rối, tải chậm

---

# Slide 7 – Content Audit

## 1. Content Audit

Quy trình kiểm tra, đánh giá & xác nhận nội dung website.

## 2. Full Content Inventory

Danh sách toàn bộ nội dung website để phân tích, đánh giá.

## 3. Partial Content Inventory

Danh sách một phần nội dung quan trọng/đại diện.

## 4. Content Sample

Mẫu nội dung được chọn để kiểm tra (blog, sản phẩm, video...).

**Tóm lại**: Content Audit giúp kiểm tra chất lượng nội dung, cải thiện UX, tối ưu SEO.

---

# Slide 8 – Các yếu tố trong Content Audit

- **Navigation Title**: Tiêu đề menu rõ ràng.
- **Page Name**: Tên trang chính xác, dễ hiểu.
- **URL**: Địa chỉ dễ nhớ, thân thiện.
- **Comments**: Kiểm tra tính hữu ích của bình luận.
- **Content Hierarchy**: Cấu trúc heading rõ ràng (H1, H2, H3).

---

# Slide 5 – Breakpoints nâng cao

## Major Breakpoints

- Thay đổi lớn về layout (vd: từ 2 cột → 4 cột).

## Minor Breakpoints

- Thay đổi nhỏ (vd: di chuyển nhãn form).

**Tóm lại**:

- Major: thay đổi lớn về giao diện.
- Minor: chỉnh chi tiết nhỏ.

---

## Tùy chỉnh Breakpoint

- **Tầm quan trọng**: tối ưu UX trên nhiều thiết bị.
- **Quy tắc**:
  - Dùng browser extensions (Resize Window for Chrome) để kiểm tra.
  - Khám phá giữa các breakpoints tiêu chuẩn để phát hiện lỗi giao diện.

---

# Navigation Drawer

- **Định nghĩa**: thành phần UI để điều hướng nhanh.
- **Khi dùng**:
  - Điều hướng cấp cao
  - Ứng dụng phức tạp, nhiều menu
  - Trên 3 chế độ xem cấp cao
- **Ví dụ**: Gmail, Facebook dùng drawer để chuyển nhanh giữa các phần.

---

# Thực hành Figma

## Các khái niệm

- **Component**: UI element tái sử dụng (button, input...)
- **Instance**: Bản con của component (nên dùng thay vì copy component).
- **Variants**: Quản lý nhiều trạng thái của component (vd: button hover, active...).
