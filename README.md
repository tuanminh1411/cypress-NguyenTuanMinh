🧪 Cypress E2E Testing – Nguyễn Tuấn Minh
Dự án này là bài tập thực hành kiểm thử end-to-end (E2E) sử dụng Cypress. Mục tiêu là kiểm thử các chức năng chính của một ứng dụng web như đăng nhập, giỏ hàng và thanh toán.

📁 Cấu trúc thư mục
yaml
Sao chép
Chỉnh sửa
cypress-NguyenTuanMinh/
├── login_spec.cy.js
├── cart_spec.cy.js
├── checkout_spec.cy.js
├── README.md
└── cypress-exercise - Hồ sơ 1 - Microsoft Edge 2025-05-28 14-17-08.rar
🚀 Cách cài đặt và chạy
1. Khởi tạo dự án
bash
Sao chép
Chỉnh sửa
mkdir cypress-exercise
cd cypress-exercise
npm init -y
2. Cài đặt Cypress
bash
Sao chép
Chỉnh sửa
npm install cypress --save-dev
3. Mở giao diện Cypress
bash
Sao chép
Chỉnh sửa
npx cypress open
Sau khi chạy lệnh trên, Cypress sẽ tạo cấu trúc thư mục và các tệp mẫu trong thư mục cypress.

4. Thêm các tệp kiểm thử
Sao chép các tệp kiểm thử (login_spec.cy.js, cart_spec.cy.js, checkout_spec.cy.js) vào thư mục cypress/e2e/.

5. Chạy kiểm thử
Trong giao diện Cypress, chọn các tệp kiểm thử để chạy và quan sát kết quả.

🧾 Mô tả các tệp kiểm thử
login_spec.cy.js: Kiểm thử chức năng đăng nhập với các trường hợp hợp lệ và không hợp lệ.

cart_spec.cy.js: Kiểm thử chức năng thêm và xóa sản phẩm khỏi giỏ hàng.

checkout_spec.cy.js: Kiểm thử quy trình thanh toán, bao gồm nhập thông tin và xác nhận đơn hàng.

🛠️ Công nghệ sử dụng
Cypress: Framework kiểm thử E2E cho ứng dụng web.

Node.js: Môi trường chạy JavaScript phía máy chủ.

npm: Trình quản lý gói cho Node.js.

📌 Ghi chú
Đảm bảo đã cài đặt Node.js và npm trước khi bắt đầu.

Các tệp kiểm thử được viết bằng JavaScript và tuân theo cú pháp của Cypress.
