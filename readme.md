# EMBrace - Giao diện giỏ hàng

## 1. Giới thiệu

Đây là giao diện giỏ hàng minh họa cho website thương mại điện tử EMBrace, giới thiệu các sản phẩm phụ kiện và phần tóm tắt đơn hàng. Khu vực được tập trung cải tiến là trang giỏ hàng: danh sách sản phẩm ở cột chính và thông tin chi phí, ưu đãi, tổng thanh toán ở cột bên cạnh.

## 2. Website tham khảo

- **Tên website:** EMBrace (giao diện minh họa trong dự án)
- **URL:** Chưa có URL website tham khảo được cung cấp trong mã nguồn.
- **Khu vực đã khảo sát:** Trang giỏ hàng, gồm danh sách sản phẩm, điều chỉnh số lượng, gợi ý nâng cấp và tóm tắt đơn hàng.

> Nếu bài tập dựa trên một website cụ thể, hãy thay thông tin trên bằng tên và URL website thực tế đã khảo sát.

## 3. Chức năng

- Hiển thị danh sách gồm bốn sản phẩm trong giỏ hàng.
- Hiển thị tên, biến thể và giá của từng sản phẩm.
- Hiển thị tóm tắt chi phí, mã ưu đãi mẫu, phí vận chuyển và tổng thanh toán.
- Bố cục tự điều chỉnh theo nhiều kích thước màn hình: hai cột trên màn hình rộng, một cột trên màn hình nhỏ.

Đây là giao diện tĩnh bằng HTML/CSS. Các nút tăng/giảm số lượng, xóa sản phẩm, áp dụng mã và thanh toán hiện chỉ được trình bày trực quan, chưa có xử lý tương tác.

## 4. Công nghệ

- HTML5
- CSS3

## 5. Cách chạy

Mở file `index.html` bằng trình duyệt. Giao diện sử dụng font Inter từ Google Fonts nên cần kết nối Internet để tải font; ảnh sản phẩm mẫu cũng được tải từ `placehold.co`.

## 6. Cải tiến đã thực hiện

**Vấn đề ban đầu:** Giao diện giỏ hàng cần thể hiện sản phẩm và chi phí một cách rõ ràng, đồng thời vẫn dễ xem trên màn hình nhỏ.

**Thay đổi:** Tổ chức nội dung thành danh sách sản phẩm và bảng tóm tắt đơn hàng; sử dụng nền tối, màu nhấn rose-gold, thẻ sản phẩm dạng kính mờ, trạng thái hover và nút hành động nổi bật. Bố cục chuyển từ hai cột sang một cột ở màn hình nhỏ; ảnh sản phẩm và banner gợi ý cũng được điều chỉnh để vừa với thiết bị di động.

## 7. Hỗ trợ từ AI

AI hỗ trợ soạn thảo README và nhật ký sử dụng AI, đồng thời giúp tóm tắt cấu trúc giao diện và các điểm responsive dựa trên mã nguồn. Nội dung đã được đối chiếu với `index.html` và `css/style.css`; các nút chưa có xử lý được ghi rõ là phần trình bày tĩnh. Tên/URL website tham khảo không có trong dự án nên cần được bổ sung nếu có nguồn cụ thể.

Trong thư mục hiện tại, CSS được nhúng trực tiếp trong thẻ `<style>` của `index.html`; `css/style.css` là tệp CSS riêng nhưng chưa được liên kết từ trang HTML.
## 8 Ứng Dụng AI Trong Phát Triển Dự Án (AI Tools & Implementation)

Dự án tận dụng sức mạnh của các mô hình Trí tuệ Nhân tạo thế hệ mới (Generative AI & LLMs) như **ChatGPT (OpenAI)** / **Gemini (Google)** / **Claude (Anthropic)** và trợ lý lập trình như một "Co-pilot" hỗ trợ toàn diện từ khâu lên ý tưởng đến hoàn thiện mã nguồn:

### 8.1. Phân loại các nhóm tác vụ AI đã sử dụng

| Nhóm tác vụ | Công việc AI hỗ trợ thực tế | Kết quả đạt được |
| :--- | :--- | :--- |
| **Tối ưu cấu trúc ngữ nghĩa (Semantic HTML5)** | Rà soát phân cấp Heading (`h1` - `h4`), phát hiện thẻ thiếu ngữ nghĩa, chuẩn hóa cấu trúc `header`, `nav`, `main`, `article`, `footer`. | Cấu trúc code chuẩn W3C, thân thiện với SEO và công cụ đọc màn hình (Accessibility). |
| **Tạo kiểu & Bố cục nâng cao (CSS3 Layout)** | Thiết lập hệ thống lưới sản phẩm với **CSS Grid**, căn chỉnh khối nội dung linh hoạt bằng **Flexbox**, tối ưu **Box Model**. | Giao diện hiện đại, chuẩn Responsive trên cả máy tính bảng và di động. |
| **Thiết kế trải nghiệm tương tác (UI/UX Micro-interactions)** | Gợi ý bảng màu Dark Luxury (Vàng hồng Rose Gold, Vàng Champagne), hiệu ứng quầng sáng kim loại, chuyển động `hover`, `:active` và `:focus-visible`. | Tăng trải nghiệm thị giác cao cấp cho dòng sản phẩm trang sức công nghệ. |
| **Sáng tạo & Chuẩn hóa nội dung (Content & Copywriting)** | Xây dựng bảng so sánh chi tiết tính năng giữa 2 phiên bản (*Standard vs Guardian*), làm nổi bật công nghệ an toàn SOS độc lập. | Nội dung thuyết phục, minh bạch bài toán kinh tế cho người mua hàng. |
| **Gỡ lỗi & Tinh chỉnh mã nguồn (Code Refactoring & Debugging)** | Phát hiện lỗi giật khung hình (CLS) do thiếu `width`/`height` trên thẻ `img`, kiểm tra các thẻ lồng nhau và chuẩn hóa cú pháp. | Mã nguồn tinh gọn, sạch sẽ, không phụ thuộc vào thư viện bên thứ ba. |

---

### 8.2. Nguyên tắc kết hợp giữa Con người & AI

* **AI đóng vai trò cố vấn & tăng tốc (AI-Assisted)**: AI đưa ra các phương án giải pháp, gợi ý cấu trúc thẻ và sinh mã mẫu nhanh chóng.
* **Người phát triển kiểm soát & tinh chỉnh (Human-in-the-loop)**:
  * Trực tiếp lựa chọn màu sắc, kích thước và định dạng phù hợp với nhận diện thương hiệu EMBrace.
  * Tự tay chạy thử, kiểm tra trực quan trên DevTools và tối ưu theo yêu cầu thực tế của môn học.
