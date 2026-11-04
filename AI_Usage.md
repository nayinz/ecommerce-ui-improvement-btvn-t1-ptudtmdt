# AI Usage Log

## 1. Công cụ AI

- **Tên công cụ:** Copilot SDK trong VS Code.

## 2. Mục đích sử dụng

- Hỗ trợ đọc cấu trúc HTML/CSS để nắm nội dung và bố cục trang giỏ hàng.
- Hỗ trợ soạn README và ghi lại quá trình sử dụng AI.
- Đối chiếu mô tả chức năng, thiết kế responsive và giới hạn hiện tại của giao diện với mã nguồn.

## 3. Prompt đã sử dụng

- “Hãy viết readme.md cho dự án này” kèm yêu cầu các mục Giới thiệu, Website tham khảo, Chức năng, Công nghệ, Cách chạy, Cải tiến đã thực hiện và Hỗ trợ từ AI.
- Yêu cầu nội dung nhật ký AI gồm công cụ, mục đích, prompt, kết quả đề xuất, kiểm tra/điều chỉnh và phần người thực hiện hiểu, có thể giải thích.

## 4. Kết quả AI đề xuất

- Mô tả dự án là giao diện giỏ hàng minh họa cho EMBrace.
- Tóm tắt danh sách sản phẩm, tên/giá, phần tổng kết đơn hàng và bố cục responsive.
- Ghi nhận các điểm thiết kế như nền tối, màu rose-gold, thẻ kính mờ và bố cục chuyển sang một cột trên màn hình nhỏ.
- Nêu rõ các nút hiện chỉ là giao diện, chưa có xử lý tương tác; không tự đặt URL website tham khảo khi mã nguồn không cung cấp thông tin đó.

## 5. Kiểm tra và điều chỉnh

- Đối chiếu tên sản phẩm, giá hiển thị và nội dung tóm tắt đơn hàng với `index.html`.
- Kiểm tra các breakpoint `992px` và `576px` cùng cách sắp xếp cột trong CSS.
- Ghi rõ trang hiện là giao diện tĩnh, không khẳng định các nút giỏ hàng hoặc thanh toán hoạt động.
- Ghi nhận URL website tham khảo chưa được cung cấp; cần bổ sung tên và URL thực tế nếu đã khảo sát một website cụ thể.
- Kiểm tra thấy CSS đang được nhúng trong `index.html`; tệp `css/style.css` hiện chưa được liên kết vào trang. Phần này được ghi chú để người thực hiện nắm rõ cấu trúc dự án.

## 6. Phần tôi hiểu và có thể giải thích

- `index.html` định nghĩa nội dung trang, gồm bốn thẻ sản phẩm, thông tin biến thể, bộ điều khiển số lượng ở dạng tĩnh và khu vực tóm tắt đơn hàng.
- CSS sử dụng biến màu trong `:root`, Grid để chia bố cục chính, Flexbox để căn chỉnh nội dung sản phẩm và `position: sticky` cho bảng tóm tắt trên màn hình rộng.
- Media query tại `992px` chuyển trang thành một cột và bỏ sticky; tại `576px` chuyển thông tin sản phẩm thành bố cục dọc, phù hợp màn hình nhỏ.
- Các nút hiện chưa gắn JavaScript nên chưa thay đổi số lượng, xóa sản phẩm, áp dụng mã giảm giá hay thực hiện thanh toán.