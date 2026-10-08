# Tạo dự án mới trên GitHub

## Mục tiêu
Luyện tập quy trình tạo Local Repository, kết nối với Remote Repository trên GitHub và đồng bộ mã nguồn.

## Ý nghĩa các lệnh Git đã sử dụng

### 1. git init
Khởi tạo một Git Repository mới trong thư mục hiện tại. Git tạo thư mục .git để quản lý lịch sử và các thay đổi.

### 2. git remote add origin
Kết nối Local Repository với Remote Repository trên GitHub.

```bash
git remote add origin https://github.com/dtc245200344-ship-it/t-t-o-d-n.git
```

- `origin`: tên mặc định dùng để gọi Remote Repository.
- URL: địa chỉ Repository trên GitHub.

### 3. git add README.md
Đưa file README.md vào Staging Area để chuẩn bị commit.

### 4. git commit -m "Add README.md file"
Lưu các thay đổi trong Staging Area thành một commit.
- `-m`: thêm message mô tả nội dung thay đổi.

### 5. git push origin main
Đẩy các commit từ Local Repository lên nhánh main của Remote Repository.
- `origin`: tên Remote Repository.
- `main`: nhánh được đẩy lên GitHub.

## Quy trình thực hiện

```bash
git init
git remote add origin https://github.com/dtc245200344-ship-it/t-t-o-d-n.git
git add README.md
git commit -m "Add README.md file"
git push origin main
```

## Kết quả
README.md được đưa lên Repository GitHub và Local Repository được đồng bộ với Remote Repository.

## Repository
https://github.com/dtc245200344-ship-it/t-t-o-d-n
