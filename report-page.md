# Report 1 Page – FIT4012 Lab 1

## 1. Mục tiêu
Bài lab nhằm giúp hiểu khái niệm entropy và redundancy trong thông tin, đồng thời nắm được cách tìm nghịch đảo modulo trong toán học ứng dụng cho bảo mật.

## 2. Cách làm
- Đọc hiểu chương trình entropy mẫu.
- Bổ sung hàm tính redundancy.
- Hoàn thiện hàm mod_inverse().
- Chạy thử trên nhiều test case.

## 3. Kết quả chính
### 3.1 Entropy và redundancy
| Input | Entropy | Redundancy | Nhận xét |
|---|---:|---:|---|
| aaaa | Thấp (~0) | Cao | Chuỗi lặp lại nên ít thông tin |
| abcd | Cao | Thấp | Các ký tự khác nhau hoàn toàn |
| hello world | Trung Bình | Trung Bình | Có lặp nhưng không hoàn toàn |

### 3.2 Modulo inverse
| a | m | Kết quả mong đợi | Kết quả chương trình |
|---:|---:|---|---|
| 3 | 7 | 5 | 5 |
| 10 | 17 | 12 | 12 |
| 6 | 9 | Không tồn tại | Không tồn tại |

## 4. Kết luận
Qua bài lab, em hiểu rõ hơn cách tính entropy để đánh giá lượng thông tin của dữ liệu và cách xác định redundancy. Ngoài ra, em nắm được điều kiện tồn tại của nghịch đảo modulo và cách cài đặt bằng thuật toán Euclid mở rộng. Khó khăn lớn nhất là hiểu cách hoạt động của thuật toán nghịch đảo modulo, nhưng việc thử nhiều test case đã giúp em hiểu rõ hơn.
