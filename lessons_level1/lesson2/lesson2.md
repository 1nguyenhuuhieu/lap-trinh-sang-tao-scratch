### **Giáo án Scratch Buổi 2: Điều kiện và kiểm tra logic trong Scratch**

#### **Thời lượng**: 2 tiếng

---

### **Mục tiêu buổi học**:
1. Học sinh hiểu được khái niệm về câu lệnh điều kiện (if-else) trong lập trình.
2. Học sinh biết cách sử dụng khối lệnh điều kiện để kiểm tra logic trong Scratch.
3. Học sinh tạo ra trò chơi hoặc hoạt cảnh có sử dụng điều kiện để quyết định hành động của nhân vật.

---

### **1. Ôn tập buổi trước (10 phút)**

**1.1. Ôn tập kiến thức cũ**:
- Hỏi học sinh về kiến thức buổi trước:
  - "Làm thế nào để di chuyển nhân vật trong Scratch?"
  - "Làm sao để thêm âm thanh và thay đổi hình nền?"
  
**1.2. Yêu cầu học sinh chia sẻ bài tập về nhà**:
- Hỏi một vài học sinh chia sẻ câu chuyện mà các em đã tạo từ bài tập về nhà. Cho các học sinh khác góp ý hoặc thảo luận về sản phẩm.

---

### **2. Giới thiệu về điều kiện (if-else) trong Scratch (20 phút)**

**2.1. Khái niệm về câu lệnh điều kiện**:
- **Giải thích**: Câu lệnh điều kiện giúp kiểm tra một tình huống cụ thể và quyết định hành động dựa trên kết quả kiểm tra. Nếu điều kiện đúng, chương trình sẽ thực hiện hành động A. Nếu điều kiện sai, chương trình sẽ thực hiện hành động B.
  
- **Ví dụ trong đời sống**: 
  - "Nếu trời mưa, mình sẽ dùng ô. Nếu không mưa, mình sẽ không dùng ô."
  
- **Ứng dụng trong Scratch**: Câu lệnh điều kiện có thể giúp quyết định hành động của nhân vật trong trò chơi hoặc hoạt cảnh, ví dụ như "Nếu nhân vật chạm vào một đối tượng, sẽ phát âm thanh."

**2.2. Giới thiệu khối lệnh điều kiện trong Scratch**:
- Mở **Block Palette**, phần **Control** và giới thiệu các khối lệnh quan trọng:
  - **If __ then**: Khối lệnh kiểm tra điều kiện, nếu đúng thì thực hiện hành động.
  - **If __ then else**: Khối lệnh kiểm tra điều kiện và có hai nhánh (true/false) để thực hiện các hành động khác nhau dựa trên kết quả kiểm tra.

---

### **3. Thực hành với câu lệnh điều kiện (30 phút)**

**3.1. Hướng dẫn sử dụng khối lệnh điều kiện**:
- **Bài tập 1: Di chuyển và kiểm tra biên**:
  - Học sinh tạo một trò chơi mà nhân vật di chuyển và kiểm tra xem nó có chạm vào mép màn hình không.
  - Sử dụng khối lệnh:
    - **"If on edge, bounce"**: Nếu nhân vật chạm vào mép sân khấu, nó sẽ bật lại.
  
  - **Thực hiện cùng học sinh**: 
    - Hướng dẫn kéo thả khối lệnh này vào **Scripts Area** và cho học sinh thử chạy chương trình. Quan sát nhân vật di chuyển và bật lại khi chạm mép màn hình.

**3.2. Bài tập thực hành có điều kiện nâng cao**:
- **Bài tập 2: Chọn hướng đi cho nhân vật**:
  - Học sinh sẽ lập trình cho nhân vật tự động di chuyển. Nếu nó chạm vào một đối tượng khác, nó sẽ quay lại.
  
  - **Hướng dẫn thực hiện**:
    1. Chọn một **Sprite** là nhân vật chính.
    2. Chọn một **Sprite** khác làm vật cản (ví dụ: một quả bóng).
    3. Sử dụng khối lệnh **If touching (object) then** từ mục **Sensing** để kiểm tra nếu nhân vật chạm vào vật cản.
    4. Nếu chạm vào vật cản, sử dụng khối lệnh **Turn 180 degrees** từ **Motion** để quay lại.
  
  - **Tương tác với học sinh**: Để học sinh thực hành tạo kịch bản đơn giản và chạy thử.

---

### **4. Tích hợp điều kiện và vòng lặp (30 phút)**

**4.1. Khái niệm về vòng lặp kết hợp điều kiện**:
- **Giải thích**: Vòng lặp cho phép lặp lại một hành động nhiều lần, trong khi khối lệnh điều kiện giúp quyết định có tiếp tục lặp hay dừng lại.
  
- **Ứng dụng trong trò chơi**: Ví dụ, một trò chơi có thể yêu cầu nhân vật tiếp tục di chuyển liên tục đến khi chạm vào tường hoặc gặp một vật cản, lúc đó mới dừng lại.

**4.2. Hướng dẫn kết hợp vòng lặp và điều kiện**:
- **Thực hành cùng học sinh**:
  - Mở **Block Palette**, chọn mục **Control**, và giới thiệu khối lệnh **Repeat until** (Lặp lại cho đến khi điều kiện thỏa mãn).
  - Ví dụ: Di chuyển nhân vật liên tục cho đến khi chạm vào biên hoặc một vật cản.
  - Cho học sinh kéo khối lệnh **Repeat until** và kết hợp với khối lệnh điều kiện **If touching edge** để tạo vòng lặp liên tục cho đến khi nhân vật chạm vào biên.

---

### **5. Thực hành cuối buổi: Tạo trò chơi điều khiển nhân vật đơn giản (20 phút)**

**5.1. Bài tập cuối buổi**:
- Yêu cầu học sinh tạo một trò chơi đơn giản có sự kết hợp giữa điều kiện và vòng lặp:
  - Nhân vật sẽ di chuyển liên tục trên sân khấu.
  - Nếu nhân vật chạm vào vật cản hoặc mép màn hình, nó sẽ quay lại và tiếp tục di chuyển.
  - Thêm âm thanh mỗi khi nhân vật chạm vào mép hoặc vật cản.

**5.2. Tương tác với học sinh**:
- Khuyến khích các em thử sáng tạo thêm nhiều khối lệnh khác nhau để mở rộng trò chơi.
- Hỗ trợ học sinh khi gặp khó khăn trong việc kết hợp các khối lệnh.

---

### **6. Đánh giá và kết thúc (10 phút)**

**6.1. Chia sẻ sản phẩm**:
- Hướng dẫn học sinh lưu lại sản phẩm và yêu cầu một số em chia sẻ sản phẩm của mình với lớp.
- Khuyến khích học sinh nêu cảm nghĩ về trò chơi mình đã tạo ra.

**6.2. Tổng kết**:
- Tóm tắt lại các kiến thức đã học trong buổi học:
  - Câu lệnh điều kiện (if-else).
  - Cách sử dụng điều kiện kết hợp với vòng lặp.
- Đặt câu hỏi ôn tập:
  - "Làm sao để kiểm tra xem nhân vật chạm vào vật cản?"
  - "Vòng lặp có thể kết hợp với điều kiện để làm gì?"

**6.3. Chuẩn bị cho buổi sau**:
- Giao bài tập về nhà: Yêu cầu học sinh tạo một trò chơi hoặc hoạt cảnh, trong đó nhân vật di chuyển liên tục và phải tránh các vật cản bằng cách sử dụng câu lệnh điều kiện. Học sinh có thể thêm âm thanh hoặc hiệu ứng khi nhân vật chạm vào vật cản.

---

### **Ghi chú cho giáo viên**:
- Đảm bảo học sinh nắm chắc khái niệm về câu lệnh điều kiện trước khi bước vào phần thực hành.
- Hỗ trợ kịp thời khi học sinh gặp khó khăn với việc kết hợp điều kiện và vòng lặp.
- Tạo không khí học tập tích cực và khuyến khích học sinh sáng tạo với các khối lệnh điều kiện.

---

Buổi học này giúp học sinh nắm vững cách sử dụng câu lệnh điều kiện và cách kết hợp điều kiện với vòng lặp, từ đó có thể tạo ra các trò chơi hoặc hoạt cảnh phức tạp hơn trong Scratch.