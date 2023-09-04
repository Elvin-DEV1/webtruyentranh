Hướng dẫn cài đặt:
Bước 1: Cài database:
Dùng xampp để tạo một database với tên "manga_web3", chọn mục import để nhập file sau đây https://drive.google.com/file/d/1HGoihwo5tBMR9Ohc1je2x5zlLLwZP_MR/view?usp=sharing
Bước 2: Hiệu chỉnh file env trong laravel
Copy file env vào api/.env: https://drive.google.com/file/d/1Nqg1HrV8PzwPJVco_KXrj5u3FbU2wqYo/view?usp=sharing
Bước 3: Tải composer
Trong thư mục chính chạy lệnh sau đây:
cd api
composer install
Bước 4: Tải npm
Trong thư mục chính chạy lệnh sau đây:
cd web
npm install
Bước 5: Tải thư mục ảnh
Tải thư mục “Mangas” để vào trong thư mục /web/public/
https://drive.google.com/drive/folders/1XA_2mGxIcwKw9sUz_As4fkORpEkNXuo9?usp=sharing
Hướng dẫn khởi động:
Bước 1: Chạy api
Trong thư mục chính chạy lệnh sau đây:
cd api
php artisan serve

Bước 2: Chạy front-end
Trong thư mục chính chạy lệnh sau đây:
cd web
npm run dev

