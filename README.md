# BÁO CÁO VỀ BÀI TẬP KIỂM THỬ SỬ DỤNG APACHE JMETER

## I. Giới thiệu

Bài tập này nhằm mục đích thực hiện kiểm thử hiệu suất và tải trọng cho một ứng dụng web sử dụng công cụ Apache JMeter. Ứng dụng web được chọn là Simplilearn, và mục tiêu là đo lường và đánh giá hiệu suất của nó trong điều kiện tải trọng khác nhau.

## II. Mục tiêu

1. Thực hiện kiểm thử hiệu suất để đo lường thời gian phản hồi của ứng dụng web dưới tải trọng đồng thời.
2. Xác định các vấn đề hiệu suất, như thời gian phản hồi cao, lỗi ứng dụng, và đáp ứng dưới áp lực tải trọng.

## III. Phương pháp

1. **Xác định yêu cầu kiểm thử:** Phân tích các yêu cầu chức năng của ứng dụng web và xác định các trường hợp sử dụng quan trọng cần được kiểm thử.

2. **Tạo kịch bản kiểm thử trong JMeter:** Sử dụng JMeter để tạo các kịch bản kiểm thử tương ứng với các trường hợp sử dụng đã xác định trước. Mỗi kịch bản bao gồm các yêu cầu HTTP như đăng nhập, tìm kiếm, hoặc thực hiện các thao tác quan trọng trên ứng dụng.

3. **Cấu hình Thread Group và các thành phần khác:** Thiết lập số lượng người dùng (threads) và thời gian chạy cho mỗi kịch bản. Cấu hình các Listener để ghi lại kết quả kiểm thử.

4. **Chạy kiểm thử và thu thập kết quả:** Chạy kiểm thử trong JMeter dưới các điều kiện tải trọng khác nhau. Thu thập và ghi lại kết quả của mỗi lần chạy, bao gồm thời gian phản hồi, số lỗi, và thống kê khác.

## IV. Kết quả

1. **Thời gian phản hồi trung bình:** Xác định thời gian phản hồi trung bình của các yêu cầu trong các điều kiện tải trọng khác nhau. Đây là chỉ số chính để đánh giá hiệu suất của ứng dụng.

2. **Tài nguyên tiêu thụ:** Đánh giá tài nguyên hệ thống như bộ nhớ và CPU tiêu thụ trong quá trình kiểm thử. Điều này giúp xác định xem liệu ứng dụng có thể chịu tải trọng đó hay không.

3. **Các vấn đề hiệu suất:** Phát hiện và mô tả các vấn đề hiệu suất, bao gồm thời gian phản hồi cao, lỗi ứng dụng, và sự giảm sút hiệu suất dưới áp lực tải trọng.

## V. Đánh giá và Kết luận

Dựa trên kết quả kiểm thử, đánh giá hiệu suất của ứng dụng và các vấn đề hiệu suất đã được phát hiện. Đề xuất các biện pháp cải thiện và tối ưu hóa để cải thiện hiệu suất của ứng dụng trong tương lai.

## VI. Tóm lại

Bằng cách sử dụng Apache JMeter, chúng tôi đã thực hiện thành công kiểm thử hiệu suất cho ứng dụng web Simplilearn
