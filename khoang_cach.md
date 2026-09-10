# Math: Công sai đối với cấp số cộng

**mục lục**


- 1.Công sai là gì?

- 2.Cách nhận biết một cấp số cộng

	- 2.1.Dãy số cách đều (cấp số cộng)

	   - 2.1.1.Công sai dương

	   - 2.1.2.Công sai âm

	   - 2.1.3.Công sai bằng 0

	- 2.2.Dãy số không cách đều (Khoảng cách thay đổi theo quy luật)

- 3.Công thức tính công sai

- 4.Công sai dương, âm và bằng 0

- 5.Mối quan hệ giữa các số hạng trong cấp số cộng

---

## 1.Công sai là gì?

khoảng cách của một dãy số (hay còn gọi là công sai đối với cấp số cộng) là giá trị chênh lệch (hiệu) giữa hai số hạng đứng liền kề nhau trong dãy số đó.

---

## 2.Cách nhận biết một cấp số cộng

### 2.1.Dãy số cách đều (cấp số cộng)

Đây là dãy số mà khoảng cách giữa hai số hạng liên tiếp luôn là một hằng số không đổi, trước hết ta cần phải tách hai khai niệm giữa dãy số và cấp số cộng nhưu sau :

- **Dãy số:** một danh sách các số được sắp theo thứ tự.

- **Cấp số cộng (CSC):** một dãy số đặc biệt, trong đó hiệu giữa hai số liên tiếp luôn giống nhau.

Công thức tìm khoảng cách ($$\large d$$) :

<div align="center">

$$\Large d=a_{n+1}-a_{n}$$

</div>

Số đằng sau trừ đi số liền trước với điều kiện số liền trước phải lớn hơn số đằng sau theo ($$\large x_{0} < x_{1} < x_{2}$$) .**Ví dụ:** Cho dãy số: $\large3, 7, 11, 15, 19, \dots$ Khoảng cách giữa các số: $\large7 - 3 = 4$, $11 - 7 = 4$, $\large15 - 11 = 4$.Vậy khoảng cách $\large d = 4$.

#### 2.1.1.Công sai dương

Đây là trường hợp nếu $$\large d>0$$, nó có nghĩa là mỗi lần đi sang số hạng tiếp theo, ta cộng thêm một lượng dương. **Ví dụ** cho dãy số $\large2, 5, 8, 11, 14, \dots$, ta tính :

<div align="center">

$$\Large5-2=3$$

$$\Large8-5=3$$

$$\Large11-8=3$$

$$\Large14-11=3$$

$$\Large\Rightarrow\text{ Vậy: } d = 3$$

</div>

Chúng ta có thể tính ngược lại cả dãy số với phép cộng như sau:

<div align="center">

$$\Large2$$

$$\Large2+3=5$$

$$\Large5+3=8$$

$$\Large8+3=11$$

$$\Large11+3=14$$

</div>

Tức là : $$\large a_{n+1} = a_{n} + d$$, với $$\large d=3$$ ta có $$\large a_{n+1} = a_{n} + 3$$

- **Tại sao nó lại gọi là dương? :** vì $$\large d=3>0$$, nên mỗi bước làm giá trị tăng lên, trên trục số:

<div align="center">

$$\Large2\rightarrow{+3}5\rightarrow{+3}8\rightarrow{+3}11$$

</div>

Ta luôn di chuyển sang phải

### 2.2.Dãy số không cách đều (Khoảng cách thay đổi theo quy luật)

Đây là dãy số mà khoảng cách giữa các số không cố định, nhưng chính bản thân các khoảng cách đó lại tạo thành một quy luật toán học (chẳng hạn như dãy số phụ, dãy khoảng cách tăng dần, hoặc khoảng cách nhân đôi).

