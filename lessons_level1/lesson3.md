**Giáo án Scratch Buổi 3: Vòng lặp và biến số trong Scratch**  

**Thời lượng:** 2 tiếng  

---

## I. Mục tiêu buổi học:
1. Hiểu khái niệm vòng lặp và biết cách sử dụng vòng lặp để thực hiện các hành động lặp lại.
2. Hiểu khái niệm biến số và cách sử dụng biến để lưu trữ giá trị trong Scratch.
3. Ứng dụng vòng lặp và biến số để tạo trò chơi ghi điểm đơn giản.

---

## II. Nội dung chi tiết:

### 1. Ôn tập buổi trước (10 phút)  
- **Ôn tập câu lệnh điều kiện (if-else):**
  - Hỏi: “Câu lệnh điều kiện được sử dụng để làm gì?”
  - Đặt câu hỏi: “Làm sao để kiểm tra nếu nhân vật chạm vào vật cản?”  
- **Chia sẻ sản phẩm:**  
  - Mời một số học sinh trình bày sản phẩm đã làm ở buổi trước và cùng lớp nhận xét.

---

### 2. Giới thiệu về vòng lặp (30 phút)

#### 2.1. Khái niệm vòng lặp  
- **Giải thích:** Vòng lặp là cách để lặp lại một hoặc nhiều hành động nhiều lần liên tục.  
- **Ví dụ trong đời sống:** Thói quen hàng ngày như đánh răng mỗi sáng là một vòng lặp.

#### 2.2. Các loại vòng lặp trong Scratch:
- **Forever:** Lặp lại mãi mãi cho đến khi nhấn nút dừng.
- **Repeat [n]:** Lặp lại một số lần nhất định.
- **Repeat until [điều kiện]:** Lặp lại cho đến khi một điều kiện được thỏa mãn.

#### 2.3. Thực hành với vòng lặp:  
- **Bài tập 1:** Tạo nhân vật di chuyển liên tục qua lại với vòng lặp.  
  **Gợi ý mã lệnh:**
  ```scratch
  when green flag clicked
  forever
    move 10 steps
    if on edge, bounce
  ```
- **Bài tập 2:** Sử dụng `Repeat [n]` để nhân vật quay vòng 10 lần.  
  **Gợi ý mã lệnh:**
  ```scratch
  when green flag clicked
  repeat 10
    turn 36 degrees
  ```

---

### 3. Giới thiệu về biến số (30 phút)  

#### 3.1. Khái niệm biến số:
- **Giải thích:** Biến là nơi lưu trữ giá trị (như điểm số, thời gian) để sử dụng trong chương trình.

#### 3.2. Tạo biến trong Scratch:
- Hướng dẫn học sinh:
  - Vào **Variables** → Nhấn **Make a Variable** → Đặt tên (ví dụ: “Điểm”).

#### 3.3. Thực hành với biến số:
- **Bài tập 3:** Tạo biến "Điểm" và tăng 1 điểm khi nhân vật chạm vào đối tượng.  
  **Gợi ý mã lệnh:**
  ```scratch
  when green flag clicked
  set [Điểm v] to 0
  forever
    if touching [Ball v]
      change [Điểm v] by 1
  ```

---

### 4. Thực hành cuối buổi: Tạo trò chơi ghi điểm đơn giản (40 phút)

**Yêu cầu trò chơi:**
1. Nhân vật di chuyển liên tục, người chơi phải điều khiển để tránh vật cản.  
2. Mỗi lần nhân vật tránh được vật cản trong vòng 5 giây, điểm số tăng 1.  
3. Khi điểm đạt 10, trò chơi kết thúc với thông báo “Bạn thắng!”.

**Gợi ý mã lệnh:**
```scratch
when green flag clicked
set [Điểm v] to 0
forever
  if timer > 5
    change [Điểm v] by 1
    reset timer
  if <[Điểm] = 10>
    say "Bạn thắng!"
    stop all
```

---

### 5. Đánh giá và kết thúc buổi học (10 phút)  
- **Chia sẻ sản phẩm:**  
  - Mời học sinh trình bày trò chơi của mình trước lớp.  
- **Tổng kết:**  
  - Tóm tắt lại kiến thức: Vòng lặp và biến số.  
  - Đặt câu hỏi ôn tập:  
    - “Biến số được dùng để làm gì trong Scratch?”
    - “Khi nào nên sử dụng vòng lặp Forever?”
- **Chuẩn bị cho buổi sau:**  
  - Yêu cầu học sinh cải tiến trò chơi với nhiều đối tượng và thêm các vòng chơi mới.

---

## Ghi chú cho giáo viên:
- Đảm bảo học sinh hiểu rõ khái niệm vòng lặp và biến số trước khi thực hành.
- Hỗ trợ học sinh nếu gặp khó khăn khi tạo và sử dụng biến số.
- Khuyến khích học sinh sáng tạo thêm tính năng cho trò chơi.

---

Buổi 3 giúp học sinh làm quen với các khái niệm quan trọng về **vòng lặp** và **biến số**, qua đó tăng cường khả năng tư duy logic và sáng tạo trong việc xây dựng các trò chơi và hoạt cảnh phức tạp hơn.