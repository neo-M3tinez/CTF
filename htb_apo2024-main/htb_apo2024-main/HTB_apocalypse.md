# Web1: Flag command

- Recon

+ vào bài thì ta thấy 1 trò chơi kiểu adventure có nhiều options sau khi chơi 1 lượt thì tui nghĩ mình đi nhầm hướng

 
![311600885-e8260a8e-dbf6-40b1-897d-7f48df583e2e](https://github.com/neo-M3tinez/htb_apo2024/assets/174318737/6cd6d65c-03a8-4ba6-acfc-058e7c0b57a2)

+ ta sẽ phải check thông tin trong src về mục main.js có phần thông tin về các options , về hướng đi của trò chơi nay ta thể thấy phần if có options secret
  
![311600957-17bcf5fa-1259-4513-9477-843183ac2893](https://github.com/neo-M3tinez/htb_apo2024/assets/174318737/ed60b22c-e161-4317-8831-65be327bcf37)

+ khi mở phần thông tin ta có thể bắt được request về thông tin options về hướng đi ta thấy về hướng đi mới trên mục secret

![311601040-74eee8b6-655e-4d18-8027-e1fca34f9d09](https://github.com/neo-M3tinez/htb_apo2024/assets/174318737/47f58fbf-1bdf-4aa0-a81e-52e08d986cb2)


![311482416-c63ddb11-ab90-4495-bcde-649a2cd830cd](https://github.com/neo-M3tinez/htb_apo2024/assets/174318737/4b0a0bc3-c443-41ba-b026-2090c6c87a01)

=> flag ta có 

![311482405-338daa50-9468-4a38-826a-a76ee5924787](https://github.com/neo-M3tinez/htb_apo2024/assets/174318737/67a5bb13-e3f5-40cf-b5c6-438eb049fde2)

=> flag: HTB{D3v3l0p3r_t00l5_4r5_b35t_wh4t_y0u_Th1nk??!}
