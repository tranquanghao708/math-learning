# Math : phương trình bậc nhất hai ẩn

**mục lục**

- 1.Tổng quan về phương trình bậc nhất hai ẩn

- 2.Điều kiện nhận biết phương trình bậc nhất hai ẩn

- 3.Giải phương trình bậc nhất hai ẩn

- 3.1.Phương pháp thế

- 3.2.Phương pháp cộng đại số

- 4.Khi nào phương trình này vô nghiệm và có nghiệm, điều kiện gì để lúc đầu nhìn vào là biết ngay có nghiệm hay ko?

- 5.Khi nào phương trình này thực sự có giá trị và khi nào nên dùng nó?

---

## 1.Tổng quan về phương trình bậc nhất hai ẩn

- Đây là phương trình có hai ẩn là (x,y) hay các tên gọi khác, miễn là có hai ẩn. Chúng có kết quả sẵn, ta chỉ cần tìm hai ẩn sao cho nghiệm của chúng với phép tính làm thỏa mãn với kết quả theo logic toán học có quá trình tính toán rõ ràng, writeup này ghi lại cách quá trình tính toán, khi nào nên dùng và điều kiện để nó là có hay vô nghiệm thay vì đoán mò hai ẩn theo cảm tính

## 2.Điều kiện nhận biết phương trình bậc nhất hai ẩn

- Phương trình này nó có dạng sau $$\large x + y = 9$$, $$\large9y + x + x= 9$$ .. hễ là ta thấy các ký hiệu của nó là `x`, `y` là hai nghiệm. Rõ hơn, mỗi character ở một biểu thức tượng trưng cho mỗi nghiệm riêng cho chính character đó chẳng qua chúng ta dùng những tên đó biểu thị sự ngắn gọn, có thể dùng bất cứ tên nào ví dụ thay `x` bằng `nghiem` hay gì cũng được nhưng về bản chất nó là ẩn, mỗi tên khác nhau có mỗi nghiệm cho riêng nó, và mỗi tên cùng giống nhau nó sẽ là cùng một nghiệm

## 3.Giải phương trình bậc nhất hai ẩn

#### 3.1.Phương pháp thế

- Phương pháp thế dùng để biểu diễn một ẩn theo ẩn còn lại, sau đó thay (thế) biểu thức đó vào phương trình kia nhằm biến hệ hai phương trình hai ẩn thành một phương trình chỉ còn một ẩn. **Ví dụ** :

$$\large\begin{cases}
	4x + y = 9 \\
	9y + 3x = 18 \\
\end{cases}\begin{cases}
	y = 9 - 4x \\
	9(9-4x) + 3x = 18 \mathrm{(Lúc này 9(9-4x) là dùng phương pháp thế, nghĩa là thay y bằng cái ở trên vào như gán biến trong C)} \\
\end{cases}\begin{cases}
	y = 9 - 4x \\
	81 - 36x + 3x = 18 \mathrm{(dùng đơn nhân đa cho 9(9-4x))} \\
\end{cases}\begin{cases}
	y = 9 - 4x \\
	58x = 18 \mathrm{(rút gọn sau đó dùng quy tắc phương trình văn bản)} \\
\end{cases}\begin{cases}
	y = 9 - 4x \\
	x = \frac{18}{58} \mathrm{(khi nó nhân thì việc dùng phép chia để đi tìm x)} \\
\end{cases}\begin{cases}
	y = 9 - 4\frac{18}{58} \mathrm{(lúc này thế vào x để đi tìm y)} \\
\end{cases}$$