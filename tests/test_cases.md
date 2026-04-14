# Test cases – FIT4012 Lab 1

Đánh dấu [x] khi đã chạy và kiểm tra kết quả.

## 1. Entropy / Redundancy
- [x] Input: `aaaa` -> entropy thấp, redundancy cao
- [x] Input: `abcd` -> entropy cao hơn `aaaa`
- [x] Input: `hello world` -> entropy và redundancy được tính hợp lệ

## 2. Modulo inverse
- [x] `a=3, m=7` -> nghịch đảo modulo là 5
- [x] `a=10, m=17` -> nghịch đảo modulo là 12
- [x] `a=6, m=9` -> không tồn tại nghịch đảo modulo

## 3. Ghi chú
- Có thể bổ sung thêm các test case đặc biệt như chuỗi rỗng ("") hoặc chuỗi chỉ chứa 1 ký tự để kiểm tra độ ổn định của chương trình.
- Kiểm tra các trường hợp biên (edge cases), ví dụ: số a và m không nguyên tố cùng nhau trong bài toán nghịch đảo modulo.
- Đảm bảo chương trình xử lý đúng với dữ liệu đầu vào lớn hoặc ký tự đặc biệt (space, dấu câu).
- Ghi nhận thời gian chạy và độ chính xác của kết quả để đánh giá hiệu năng.
- Nhóm có thể tự thiết kế thêm test để kiểm chứng các trường hợp thực tế hoặc phức tạp hơn.
