# NHẬT KÝ LÀM VIỆC VỚI AI - [Tên bài]

## Lần 1

**Prompt:** dán nguyên văn.

**AI trả về:** tóm tắt.

**Đánh giá:** Dùng được / Phải sửa / Sai, bỏ.

**Chỗ sai:** mô tả cụ thể, kèm dòng mã hoặc dữ liệu đối chiếu.

**Cách sửa:** sinh viên đã làm gì.

**Ai phát hiện:** AI tự nhận / Sinh viên phát hiện.
## Lab 4: Nhận diện hợp đồng có rủi ro

**Prompt đã dùng:** "Bạn là chuyên viên thẩm định rủi ro tài sản số. Dưới đây là mã nguồn một hợp đồng token..."

**So sánh kết quả:**
- **Đọc thủ công tìm được:** Phát hiện được hàm `mint` ở dòng 24 và hàm `blacklist` ở dòng 35.
- **AI tìm thêm được:** AI chỉ ra thêm hàm `pause` ở dòng 45 mà lúc đọc bằng mắt thường dễ bị bỏ sót.
- **Đánh giá AI:** AI phân tích chính xác, trả lời đúng số dòng và không tự bịa ra thông tin nhờ câu lệnh ràng buộc nghiêm ngặt trong prompt
## Lab 6: Triển khai Smart Contract đầu tiên

**Prompt đã dùng:** "Hướng dẫn tạo và deploy hợp đồng Greeter.sol lên mạng Sepolia bằng Remix IDE và MetaMask..."

**So sánh & Đánh giá:**
- **Thực thi:** Hoàn thành quy trình compile và deploy hợp đồng `Greeter.sol` lên mạng thử nghiệm Sepolia.
- **Kết quả:** Hiểu rõ cách tương tác trực tiếp với các hàm Read (`greet`) và Write (`setGreeting`) thông qua giao diện Deployed Contracts.