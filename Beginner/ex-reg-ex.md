# Challenge
## ex-reg-ex
![image](https://github.com/user-attachments/assets/cca51d6f-b512-4611-9c45-9238dae3baee)

Đầu tiên, mình download file về và giải nén, nhận được file app.py. 
![image](https://github.com/user-attachments/assets/d6419224-55a5-4ef7-be49-3a398f9dd38a)

Để ý kĩ thì thấy đoạn code này sẽ match các kí tự với input_val, nên mình sẽ tạo ra input bằng cách dịch ngược lại các kí tự đó.
Các kí tự này là: `dr\w{5,7}e\d+am@[a-z]{3,7}\.\w+`

Mình sẽ tách thành từng đoạn nhỏ để dịch. 
* dr: là 1 chuỗi dr
* \w{5,7}: /w là các kí tự từ a-z, \w{5,7} là 5 đến 7 kí tự a-z ngẫu nhiên
* e: kí tự e
* \d+: viết tắt của 1 số, có thể là nhiều số từ 0-9
* am@: chuỗi am@
* [a-z]{3,7}: 3-7 kí tự a-z
* \.: kí tự .
* \w+: 1 vài kí tự từ a-z

Mình sẽ dịch tạm các kí tự trên thành: `drancdefe123am@abcd.abc`

Nhập vào mục Input, mình thu được flag. 
![image](https://github.com/user-attachments/assets/3a9e8674-85da-43a5-8268-db29652ab1c5)

Flag: `DH{e64a267ab73ae3cea7ff1255b5f08f3e5761defbfa6b99f71cbda74b7a717db3}`
