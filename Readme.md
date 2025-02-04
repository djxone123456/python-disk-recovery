# Hướng dẫn sử dụng ứng dụng khôi phục ổ đĩa trên USB/ SD Card có định dạng FAT32
1.	Chạy editor như VSCode với quyền Administrator.
2.	Import folder vào trong editor.
3.	Cài đặt các thư viện trong file ***requirements.txt***.
4.	Chạy dưới hàm main.py.
5.	Ta lựa chọn 1 ổ đĩa. Ví dụ ta chọn ổ E: cho FAT32.
6.	Chương trình sẽ list ra các danh sách file đã xóa theo cách quick format. Nếu muốn in ra kết quả như thế này, gõ lệnh QUICK.
7.	Ngoài ra muốn quét full ổ đĩa thì ta gõ lệnh FULL.
8.	Trong danh sách tìm được, nếu ta muốn khôi phục file nào đó, ta cần gõ index của file đó trong danh sách. \Ví dụ như Index 3: Filename: 09-12-2024_23-07-07_PP1, size: 205 bytes thì gõ số 3.
9.	Chương trình hỏi nơi muốn lưu. Hãy cho một đường dẫn. Ví dụ: **C:\Users\djxon\Downloads\New folder**
10.	Nếu chương trình chạy mà không thấy in ra Error thì thành công. Ta có thể kiểm tra kết quả khôi phục trong đường dẫn đã cho.

## Lưu ý
Tính năng quét ổ đĩa NTFS đang bị lỗi khi khôi phục nên hiện tại chỉ sử dụng được chức năng quét FAT32
