# HCM_KS26_CNTT2_IT108_Session21_Ex04
# Bài 4: Đánh giá công cụ hỗ trợ xử lý lỗi lập trình

| Tiêu chí | Google Search (StackOverflow) | AI Assistant |
|---|---|---|
| Độ chính xác | Dựa trên thực tế, được cộng đồng kiểm chứng (upvote/tick xanh). | Trực diện theo log lỗi, nhưng dễ sai lệch với kiến trúc dự án phức tạp. |
| Tính cập nhật | Tức thời, phản ánh ngay các lỗi từ bản cập nhật mới nhất. | Bị giới hạn bởi thời gian cắt dữ liệu huấn luyện. |
| Khả năng giải thích | Phụ thuộc vào người trả lời, thường cung cấp mã lệnh để dùng ngay. | Cực kỳ chi tiết, giải thích rõ cơ chế từng lệnh và dễ dàng hỏi đáp thêm. |
| Rủi ro (Hallucination) | Không có. Chỉ có rủi ro áp dụng nhầm bài viết cũ. | Có nguy cơ bịa đặt tham số dòng lệnh hoặc file cấu hình không tồn tại. |

Trường hợp bắt buộc phải dùng Google Search để đảm bảo an toàn:

- Phát hiện tiến trình lạ có mã độc: Phải dùng Google để tra cứu tên tiến trình nhằm xác minh mã độc, tuyệt đối không tin AI vì nó suy đoán hoặc nhầm lẫn sang một tiến trình hệ thống hợp lệ rồi khẳng định là an toàn, khiến mình bỏ qua và gây nguy hiểm.
- Thực thi lệnh hệ thống quyền cao (Root/Admin): Cần dùng Google đối chiếu tài liệu chính thức trước khi chạy các lệnh ép buộc dừng tiến trình, tránh việc AI cấp sai tham số làm sập hệ thống hoặc mất dữ liệu.
  
