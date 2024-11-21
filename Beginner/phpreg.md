# Challenge
## phpreg
![image](https://github.com/user-attachments/assets/6d6ac04a-a58b-4872-9900-9203af51c350)

Trước tiên, mình tải file vè giải nén, thu được 2 file. Mình mở file `step2.php` và thu được đoạn code này. 
![image](https://github.com/user-attachments/assets/d1cca3e9-9a0e-485e-9494-e3e50989e199)

Sau 1 hồi tìm hiểu, mình nhận ra đoạn code trên yêu cầu tìm user và pass trước khi mã hóa. 

Về user, user sau khi mã hóa là `dnyang0310` nên user trước khi mã hóa sẽ là `dnnyangyang0310`. 

Về pass, phần này làm mình khá mất thời gian. Mình sẽ dịch phần pass bên dưới. 
`\d*\@\d{2,3}(31)+[^0-8\"]\!`
* `\d: 123`
* `*\@: @`
* `\d{2,3}: 123`
* `(31): 31`
* `[^0-8\"]: 9`
* `\!: !`

Khi đó, pass trước khi mã hóa sẽ là: `123@123319!+1+13`. 

Nhập user và pass vào **Step 1** thì mình qua **Step 2**. 

![image](https://github.com/user-attachments/assets/93dd2c52-2877-4469-8fcc-97fd15232bca)

Mình cat thử đường dẫn mà đề đưa ra nhưng lại nhận được dòng chữ `Error!` đập ngay vào mặt :) 

Sau đó, mình có thử mày mò thì cuối cùng cũng thu được flag với đường dẫn `cat ../dream/f?ag.txt`. 
![image](https://github.com/user-attachments/assets/a5afb325-b3c6-456e-95c5-cdeb953bfc43)

Flag: `DH{ad866c64dabaf30136e22d3de2980d24c4da617b9d706f81d10a1bc97d0ab6f6}`
