\# Phần 1: Phân tích lỗi cú pháp:

\- Lỗi ở tiêu đề phụ (###Lưu ý quan trọng): Thiếu dấu cách (space) sau các dấu thăng (###).

\- Lỗi ở danh sách các bước (-Bước 1, -Bước 2, ...): Thiếu dấu cách sau dấu gạch ngang (-).

\- Lỗi in đậm thiếu thẻ đóng (\*\*HNKS25CNTT1\_IT101\_Session08): Thiếu cặp dấu \*\* đóng ở cuối tên repository.

\- Lỗi đường dẫn (\[GitHub](github.com)): Thiếu tiền tố giao thức mạng (https://) trong URL của link.

\- Lỗi định dạng văn bản trong Blockquote (\*Nộp muộn sẽ bị trừ 50% điểm!\*\*): Dùng lẫn lộn thẻ mở in nghiêng (\*) nhưng lại đóng bằng thẻ in đậm (\*\*).

\*\*Hậu quả khi render trên trang web\*\*

\- Tiêu đề dính liền: ###Lưu ý quan trọng sẽ không được nhận diện là thẻ Heading cấp 3 (<h3>), mà hiển thị nguyên văn dạng chữ thường có kèm 3 dấu thăng ở đầu (ví dụ: ###Lưu ý quan trọng).



\- Danh sách mất định dạng: Các dòng -Bước 1, -Bước 2 không được chuyển thành danh sách dạng dấu chấm (bullet points) mà hiển thị thành các đoạn văn bản thường dính liền với dấu gạch ngang.

&#x20;

\- Lỗi hiển thị in đậm: Do thiếu \*\* ở cuối, từ \*\*HNKS25CNTT1\_IT101\_Session08 có thể làm toàn bộ phần văn bản phía sau bị ảnh hưởng hoặc hiển thị thừa dấu sao thô trên giao diện.



\- Link không bấm được hoặc dẫn sai trang: Không có https://, hệ thống sẽ coi đây là đường dẫn tương đối (relative link) gắn liền với trang chủ GitHub Pages hiện tại, dẫn đến lỗi 404 Not Found khi sinh viên click vào.



\- Lỗi ký tự thừa: Dòng cuối chứa cặp thẻ đánh dấu không khớp (\* và \*\*) khiến cú pháp in nghiêng/in đậm bị hỏng, hiển thị nguyên các dấu sao thừa thãi trên trang web.



\# Phần 2: Sửa lỗi

\## Hướng Dẫn Nộp Bài Tập - Session 08



\### Lưu ý quan trọng



Các bước nộp bài:

\- Bước 1: Tạo tài khoản GitHub tại \[GitHub](https://github.com)

\- Bước 2: Tạo repository mới đặt tên theo định dạng \*\*HNKS25CNTT1\_IT101\_Session08\*\*

\- Bước 3: Upload file .md của bài làm lên repository

\- Bước 4: Copy đường dẫn và nộp lên Portal



> Deadline: Chủ nhật 23:59 — \*Nộp muộn sẽ bị trừ 50% điểm!\*



\*\*Nếu sinh viên dán (paste) đường link dạng github.com mà không có https:// ở đầu,trình duyệt và Markdown sẽ hiểu đó là một đường dẫn tương đối (relative path) bên trong website hiện tại, khi người dùng click vào, trình duyệt sẽ truy cập vào một trang có địa chỉ dạng:

https://<User-Name>.github.io/<Name-repo>/github.com và web sẽ trả về lỗi 404 Not Found vì đường dẫn này không tồn tại trên hệ thống lưu trữ của repository\*\*

