# 1. Clone repo
git clone https://github.com/CJackHwang/ds2api.git
cd ds2api

# 2. Tạo file môi trường từ file mẫu
cp .env.example .env

sửa 
DS2API_ADMIN_KEY=matkhauwebui

# 3. Tạo file cấu hình từ file mẫu
cp config.example.json config.json

dùng config.json ở đây

# 4. docker-compose up -d

# 5. http://localhost:6011/v1/chat/completions

