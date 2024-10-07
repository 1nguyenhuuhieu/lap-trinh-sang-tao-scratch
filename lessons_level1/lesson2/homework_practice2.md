Dưới đây là bài tập thực hành về nhà cho Buổi 2 về chủ đề câu lệnh điều kiện trong Scratch:

### **Bài tập thực hành về nhà: Trò chơi né tránh chướng ngại vật**

**Mục tiêu**: Sử dụng câu lệnh điều kiện (if-else) và các khối lệnh di chuyển để tạo ra một trò chơi đơn giản, trong đó nhân vật phải né tránh chướng ngại vật.

---

#### **Yêu cầu**:

1. **Chọn một nhân vật chính (Sprite)** và thêm 2-3 đối tượng làm vật cản. 
   - Ví dụ: Nhân vật chính có thể là **Mèo Scratch** và các vật cản có thể là **quả bóng, khối vuông, hoặc đám mây**.

2. **Lập trình cho nhân vật chính di chuyển bằng các phím mũi tên** (lên, xuống, trái, phải).
   - Khi nhấn phím mũi tên, nhân vật sẽ di chuyển theo hướng tương ứng.

3. **Thêm câu lệnh điều kiện** để kiểm tra xem nhân vật có chạm vào vật cản không.
   - Nếu chạm vào vật cản, trò chơi sẽ hiển thị một thông báo "Game Over" và phát ra âm thanh cảnh báo.

4. **Tạo hệ thống tính điểm**:
   - Mỗi lần nhân vật tránh được chướng ngại vật trong một khoảng thời gian nhất định (ví dụ: 10 giây), điểm số của người chơi sẽ tăng thêm 1.
   
5. **Thêm hình nền động**:
   - Hình nền sẽ thay đổi khi điểm số đạt được một mức nhất định (ví dụ: sau khi đạt 5 điểm).

6. **Thêm âm thanh**:
   - Thêm âm thanh khi nhân vật di chuyển và khi trò chơi kết thúc.

#### **Hướng dẫn thực hiện**:

- Sử dụng khối lệnh **"If key pressed"** để điều khiển nhân vật di chuyển bằng các phím mũi tên.
- Sử dụng khối lệnh **"If touching (object)"** để kiểm tra nếu nhân vật chạm vào vật cản.
- Sử dụng khối lệnh **"Change score by 1"** để tăng điểm số khi nhân vật tránh được chướng ngại vật.
- Thêm khối lệnh **"Say 'Game Over'"** và phát âm thanh nếu trò chơi kết thúc.

---

### **Bài tập bổ sung** (Tuỳ chọn):

1. **Tăng độ khó của trò chơi**: 
   - Sau mỗi lần đạt 3 điểm, vật cản sẽ di chuyển nhanh hơn hoặc xuất hiện nhiều hơn.

2. **Tạo màn chơi mới**:
   - Khi đạt được 10 điểm, trò chơi sẽ chuyển sang một màn chơi mới với hình nền và vật cản khác.

---

### **Gợi ý khối lệnh**:

```plaintext
when green flag clicked
forever
  if key "right arrow" pressed
    change x by 10
  if key "left arrow" pressed
    change x by -10
  if key "up arrow" pressed
    change y by 10
  if key "down arrow" pressed
    change y by -10

  if touching "obstacle"
    say "Game Over"
    stop all

  if timer > 10 seconds
    change score by 1
    reset timer
```

---

### **Lưu ý cho học sinh**:
- Hãy sáng tạo với trò chơi của bạn bằng cách thêm các yếu tố mới như nhiều vật cản hơn, thay đổi hình dạng và kích thước vật cản, hoặc thêm các hiệu ứng đặc biệt khi nhân vật tránh được vật cản.
- Lưu ý làm việc có kế hoạch và kiểm tra kỹ thuật từng phần của trò chơi trước khi thêm phần mới.

---

### **Cách nộp bài**:
- Học sinh lưu lại sản phẩm của mình và chia sẻ với giáo viên hoặc đăng tải lên cộng đồng Scratch. Giáo viên có thể yêu cầu học sinh gửi liên kết dự án để kiểm tra và nhận xét.

### **Mục tiêu học tập**:
- Phát triển tư duy logic và khả năng giải quyết vấn đề.
- Hiểu và áp dụng câu lệnh điều kiện trong lập trình.
- Tạo ra một sản phẩm sáng tạo và hoàn thiện dựa trên ý tưởng cá nhân.