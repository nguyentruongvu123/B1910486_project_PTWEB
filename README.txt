========= Cài đặt backend
B1: cd vào ./backend
B2: Tạo file .env với các nội dung sau
    PORT=8888
    TOKEN_KEY=acy1memt
    JWT_EXPIRES_IN=1d
B3: trong terminal chạy lệnh npm install
B4: để chạy backend chạy lệnh npm run dev

========= Cài đặt frontend
B1: cd vào ./frontend
B2: Tạo file .env với các nội dung sau
    API_SERVER=http://localhost:8888
    API_CLIENT=http://localhost:9999
B3: trong terminal chạy lệnh npm install
B4: để chạy frontend chạy lệnh npm run dev
