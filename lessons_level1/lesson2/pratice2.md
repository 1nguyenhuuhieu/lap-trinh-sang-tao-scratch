### **Bài tập thực hành Buổi 2: Sử dụng câu lệnh điều kiện trong Scratch**

---

#### **Bài tập 1: Di chuyển và kiểm tra biên**
**Yêu cầu**:
1. Tạo một nhân vật **Sprite** (có thể là nhân vật mặc định hoặc nhân vật do học sinh chọn).
2. Lập trình để nhân vật tự di chuyển về phía trước.
3. Kiểm tra nếu nhân vật chạm vào biên của màn hình thì nó sẽ quay lại.
4. Thêm một âm thanh phát ra mỗi khi nhân vật chạm vào biên.

**Hướng dẫn**:
- Sử dụng khối lệnh **Move 10 steps** để di chuyển nhân vật.
- Sử dụng khối lệnh **If on edge, bounce** để kiểm tra biên.
- Sử dụng khối lệnh **Play sound "Meow"** hoặc bất kỳ âm thanh nào khác từ mục **Sounds** khi nhân vật chạm vào biên.

**Gợi ý mã lệnh**:
```plaintext
when green flag clicked
forever
  move 10 steps
  if on edge, bounce
  play sound "Meow"
```

---

#### **Bài tập 2: Nhân vật tránh vật cản**
**Yêu cầu**:
1. Tạo một nhân vật **Sprite** và một đối tượng khác (ví dụ: một quả bóng làm vật cản).
2. Lập trình để nhân vật tự di chuyển về phía trước.
3. Nếu nhân vật chạm vào quả bóng (vật cản), nhân vật sẽ quay lại và di chuyển ngược hướng.
4. Thêm hiệu ứng âm thanh khi nhân vật chạm vào quả bóng.

**Hướng dẫn**:
- Sử dụng khối lệnh **Move 10 steps** để di chuyển nhân vật.
- Sử dụng khối lệnh **If touching (object)** để kiểm tra nếu nhân vật chạm vào quả bóng.
- Sử dụng khối lệnh **Turn 180 degrees** từ mục **Motion** để nhân vật quay ngược lại.

**Gợi ý mã lệnh**:
```plaintext
when green flag clicked
forever
  move 10 steps
  if touching "Ball"
    turn 180 degrees
    play sound "Bark"
```

---

#### **Bài tập 3: Trò chơi né tránh vật cản**
**Yêu cầu**:
1. Tạo một nhân vật chính (ví dụ: mèo Scratch) và thêm 2-3 đối tượng làm vật cản (ví dụ: quả bóng, khối vuông).
2. Lập trình để nhân vật di chuyển liên tục.
3. Khi nhân vật chạm vào một vật cản, nhân vật sẽ quay ngược lại hoặc nhảy lên để tránh va chạm.
4. Khi chạm vào mép màn hình, nhân vật sẽ quay lại.
5. Thêm âm thanh và hiệu ứng thay đổi hình nền mỗi khi nhân vật chạm vào vật cản.

**Hướng dẫn**:
- Sử dụng khối lệnh **Move 10 steps** và khối lệnh **If on edge, bounce** để di chuyển và kiểm tra biên.
- Sử dụng khối lệnh **If touching (object)** để kiểm tra va chạm với vật cản và thực hiện hành động né tránh.

**Gợi ý mã lệnh**:
```plaintext
when green flag clicked
forever
  move 10 steps
  if on edge, bounce
  if touching "Ball" or "Box"
    turn 180 degrees
    play sound "Bark"
    switch backdrop to "Next_Backdrop"
```

---

#### **Bài tập 4: Chơi với điều kiện**
**Yêu cầu**:
1. Tạo một nhân vật **Sprite** di chuyển bằng phím mũi tên.
2. Nếu nhấn phím mũi tên lên, nhân vật sẽ di chuyển lên.
3. Nếu nhấn phím mũi tên xuống, nhân vật sẽ di chuyển xuống.
4. Kiểm tra nếu nhân vật chạm vào một đối tượng khác (ví dụ: quả bóng), chương trình sẽ phát ra âm thanh và hiển thị một thông báo "Chạm rồi!".

**Hướng dẫn**:
- Sử dụng khối lệnh **If key pressed** để kiểm tra các phím mũi tên.
- Sử dụng khối lệnh **If touching (object)** để kiểm tra va chạm với đối tượng khác.

**Gợi ý mã lệnh**:
```plaintext
when green flag clicked
forever
  if key "up arrow" pressed
    change y by 10
  if key "down arrow" pressed
    change y by -10
  if touching "Ball"
    say "Chạm rồi!"
    play sound "Meow"
```

---

### **Lời giải tham khảo và gợi ý mở rộng**:
- Sau khi học sinh hoàn thành bài tập, khuyến khích các em thử thêm các yếu tố khác như thay đổi tốc độ di chuyển, thay đổi kích thước nhân vật hoặc thêm nhiều vật cản khác nhau.
- Khuyến khích học sinh thử nghiệm với nhiều tình huống điều kiện phức tạp hơn, chẳng hạn như: 
  - "Nếu nhân vật chạm vào vật cản lần thứ hai thì trò chơi kết thúc."
  - "Tăng tốc độ di chuyển của nhân vật sau mỗi lần chạm vào vật cản."

### **Yêu cầu học sinh chia sẻ sản phẩm**:
- Sau khi hoàn thành, yêu cầu học sinh lưu lại sản phẩm và chia sẻ với bạn bè hoặc gia đình. Giáo viên cũng có thể yêu cầu một số học sinh trình bày và giải thích cách họ đã sử dụng câu lệnh điều kiện trong sản phẩm của mình.

### **Bài tập về nhà**:
- Yêu cầu học sinh tự phát triển một trò chơi né tránh vật cản hoặc câu chuyện có sự tương tác, sử dụng câu lệnh điều kiện và vòng lặp để nhân vật di chuyển liên tục, phát âm thanh, hoặc thay đổi hình nền khi có sự kiện xảy ra.