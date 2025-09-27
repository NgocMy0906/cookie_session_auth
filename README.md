-Truy cập route register - thành công
Method: POST
URL: http://localhost:3000/auth/register
Kết quả: "message": "User registered successfully!"
![alt text](<public/images/Screenshot 2025-09-25 201649.png>)

-Truy cập route login - thành công
Method: POST
URL: http://localhost:3000/auth/login
Kết quả: "message": "Login successful!"
![alt text](<public/images/Screenshot 2025-09-27 154930.png>)

-Truy cập route login -không thành công sai mật khẩu
Method: POST
URL: http://localhost:3000/auth/login
Kết quả: "error": "Invalid username or password"
![alt text](<public/images/Screenshot 2025-09-27 155138.png>)

-Truy cập route login -không thành công sai tên đăng nhập
Method: POST
URL: http://localhost:3000/auth/login
Kết quả: "error": "Invalid username or password"
![alt text](<public/images/Screenshot 2025-09-27 155306.png>)

-Truy cập route profile -thành công khi đã đăng nhập
Method: GET
URL: http://localhost:3000/auth/profile
Kết quả: 
            "_id": "68d540b7186d5f9234ddbedb",
            "username": "My",
            "__v": 0
![alt text](<public/images/Screenshot 2025-09-27 155610.png>)

-Truy cập route logout -thành công 
Method: GET
URL: http://localhost:3000/auth/logout
Kết quả: "message": "Logout successful!"
![alt text](<public/images/Screenshot 2025-09-27 160218.png>)

-Truy cập route profile - thất bại - sau khi đăng xuất
Method: GET
URL: http://localhost:3000/auth/profile
Kết quả: "error": "Unauthorized"
![alt text](<public/images/Screenshot 2025-09-27 160429.png>)


![alt text](<public/images/Screenshot 2025-09-27 164453.png>)
![alt text](<public/images/Screenshot 2025-09-27 164437.png>)