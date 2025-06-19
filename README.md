Truyền file dữ liệu 
💡 Mục đích:
Ứng dụng được thiết kế nhằm cung cấp một nền tảng truyền tải file dữ liệu một cách an toàn, sử dụng chữ ký số để đảm bảo tính xác thực và toàn vẹn dữ liệu.

🎨 Giao diện:
Giao diện đẹp mắt, dễ thương, tông màu hồng nữ tính với hiệu ứng sparkle (✨) sinh động.

Gồm 3 tab chính:

📤 Upload & Ký Số: Cho phép người dùng chọn file, upload và ký số.

✅ Xác Minh: Dùng để kiểm tra tính hợp lệ của file dựa vào chữ ký số đã cung cấp.

📁 Danh Sách File: Hiển thị danh sách file đã upload, cho phép tải file và gói chữ ký đi kèm.

⚙️ Chức năng chính:
Ký số file:

Người dùng chọn một file bất kỳ từ thiết bị.

File được upload lên server kèm theo chữ ký số được tạo.

Hiển thị thông tin: tên file, kích thước, thời gian upload, hash, chữ ký số.

Xác minh chữ ký số:

Người dùng cung cấp file và chữ ký số tương ứng.

Hệ thống kiểm tra tính hợp lệ của chữ ký.

Nếu hợp lệ, hiển thị thông tin file và trạng thái chữ ký "Chữ ký hợp lệ ✅".

Quản lý và tải file:

Danh sách file đã upload được hiển thị.

Hỗ trợ tải file gốc hoặc tải "gói đầy đủ" (file + chữ ký).

🧪 Công nghệ sử dụng:
Frontend: HTML, CSS, JavaScript thuần, không sử dụng framework ngoài.

Backend (yêu cầu từ requirements.txt):

Flask: Xử lý các yêu cầu HTTP như upload, verify, danh sách file.

Flask-SocketIO: Có thể dùng cho giao tiếp thời gian thực nếu cần mở rộng.

PyCryptodome: Dùng cho mã hóa/băm file và tạo/kiểm tra chữ ký số.

💖 Điểm nổi bật:
Hỗ trợ kéo-thả file với hiệu ứng tương tác sinh động.

Thiết kế responsive – tương thích với cả máy tính và thiết bị di động.

Mã nguồn được tổ chức rõ ràng, dễ mở rộng.
