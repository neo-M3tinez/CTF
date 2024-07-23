# Outsiders 

![337219103-ffe74f5b-d5d8-4cfa-b6c0-621eec85f6d1](https://github.com/neo-M3tinez/n0psctf/assets/174318737/88cf3560-10fb-4271-96c3-765753bd2c72)


![337225501-f7ca0a68-be28-431c-a79f-88b21c8cb465](https://github.com/neo-M3tinez/n0psctf/assets/174318737/dd6c7975-2210-4646-859f-9bb1730d1583)

- ta có thông tin về website có vẻ nó đang từ chối và hiện thông là outsider and no trust thì dạng này có thể liên quan đến http header

+ chưa có thông tin về browser được chỉ định thì có thể nếu truy cập vào inside đồng nghĩa với sử dụng localhost = 127.0.0.1

ta sẽ sử dụng web X-Forwarded-For:127.0.0.1 

![337229057-1564d2f8-3583-4954-a238-ebc59150655b](https://github.com/neo-M3tinez/n0psctf/assets/174318737/5d4abee8-be66-4d23-b200-866c5ea2536b)

=>flag: N0PS{XF0rw4Rd3D}
