# Buy a cat 

![image](https://github.com/neo-M3tinez/Junior.Crypt.2024-CTF/assets/174318737/476ded75-1527-4e9f-9d98-e4874fa11d0f)

- trang web có những options cho ta chọn các trường hợp có thể thấy yêu cầu để bài là buy a cat

![image](https://github.com/neo-M3tinez/Junior.Crypt.2024-CTF/assets/174318737/68e94058-e059-4a98-b01a-22af45fd969e)

=> trên url có hiện thông tin ta đã chọn submit lên hệ thống vì là phương thức get có thể đó là lỗ hổng nên ta sẽ thay T_shirt = Cat 

![image](https://github.com/neo-M3tinez/Junior.Crypt.2024-CTF/assets/174318737/c7ff0f20-0457-415e-a27a-4f06a0d8f257)

=> flag = grodno{15e790_1t_1s_v3ry_1mp0rt4nt_c4t_ef4a45}


# Very Secure App

![image](https://github.com/neo-M3tinez/Junior.Crypt.2024-CTF/assets/174318737/41c1968e-a030-4a5c-9137-cae077cd1fba)

- 1 trang web login với tài khoản bất kì nhưng mà khi vào đây và getflag thì ta nhận được thông tin

![image](https://github.com/neo-M3tinez/Junior.Crypt.2024-CTF/assets/174318737/3ffb8ca1-dc33-4e01-ac37-f8cc88a6e7d4)

 => rất có thể đây phải config thông tin của cookie để verify tài khoản là  admin

 + sau khi check cookie ta có được thông tin về token

```
token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImxvZ2luICIsInJvbGUiOiJ1c2VyIn0.O905-xinIWzzHBc0pcGKYuWRS1cV20DfM9Q2ur6skWk
```

![image](https://github.com/neo-M3tinez/Junior.Crypt.2024-CTF/assets/174318737/fb600528-fd4c-476e-be24-7b09f1717687)


=> sau khi giải mã ta được thông tin này ta cần phải có secret key để verfiy sign của token 

=> tình cờ tìm được trong robots.txt 1 thẻ comment với value là : s3cr3t_k3y_f0r_jwt 

![image](https://github.com/neo-M3tinez/Junior.Crypt.2024-CTF/assets/174318737/3a4401a7-a66f-4d92-9444-7ed64a02710c)


=> chỉnh sửa role thành admin và nhét key vào thì ta đã có token hợp lệ rồi

![image](https://github.com/neo-M3tinez/Junior.Crypt.2024-CTF/assets/174318737/bd074465-6b96-40c9-9847-a0248149e595)

=>flag: grodno{r0b0ts_k3y_jwt}

# Guest 
