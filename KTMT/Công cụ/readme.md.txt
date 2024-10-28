Xây Dựng RARS Từ Mã Nguồn
Nếu bạn muốn tùy chỉnh hoặc xây dựng RARS từ mã nguồn, làm theo các bước sau:

Cài Đặt Git (nếu chưa có): Tải và cài đặt Git.

Clone Repository: Mở Command Prompt và chạy:

bash
Copy code
git clone https://github.com/TheThirdOne/rars --recursive
Chạy Script Xây Dựng: Nếu bạn đang sử dụng Windows, bạn có thể sử dụng WSL (Windows Subsystem for Linux) hoặc Git Bash. Chạy lệnh:

bash
Copy code
./build-jar.sh
Nếu bạn đang sử dụng Git Bash, bạn có thể cần chạy lệnh này trong thư mục chứa mã nguồn đã clone.

Chạy File JAR Đã Xây Dựng: Sau khi quá trình xây dựng hoàn tất, bạn sẽ có file rars.jar trong thư mục build. Bạn có thể chạy nó bằng lệnh:

bash
Copy code
java -jar rars.jar