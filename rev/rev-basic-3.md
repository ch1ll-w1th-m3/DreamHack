# Challenge
## rev-basic-3 
![image](https://github.com/user-attachments/assets/f18a09e4-141d-400c-a3d4-72a5609a30cb)

Cũng như 2 bài trước thì mình cũng mò tới hàm compare và mình tìm được thứ này.  
![image](https://github.com/user-attachments/assets/ce689955-7c6e-4f31-8ee3-f6874baf816b)

Trước tiên, mình sẽ dịch hàm này ra và thấy hàm này so sánh giá trị mảng a1 với byte_140003000. 

Hàm này sẽ lấy `*(a1 + i) + 2 * i` và compare với `byte_140004000`.

Công việc của mình bây giờ là tìm ra mảng a1, sau đó chuyển sang ascii và thu được flag. 

Mình code lại theo hàm của đề và mảng byte_14000300 có sẵn và thu được flag. 
![image](https://github.com/user-attachments/assets/d3317f1c-91ae-467d-bc67-f2ffd2a4ddd7)

![image](https://github.com/user-attachments/assets/e9850f0a-8fbf-4053-a830-a8c8c3589c25)

Flag: `DH{I_am_X0_xo_Xor_eXcit1ng}`
