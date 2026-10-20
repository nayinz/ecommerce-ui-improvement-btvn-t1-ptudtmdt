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