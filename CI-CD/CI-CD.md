# Lý Thuyết về CI/CD

### CI/CD là gì ? 
Là viết tắt của hai khái niệm liên quan đến phương pháp phát triển phần mềm: Continuous Integration (CI) và Continuous Delivery/Deployment (CD).
 
CI - Continuous Integration là quá trình tự động hóa việc tích hợp mã nguồn từ nhiều thành viên trong nhóm phát triển phần mềm vào một dự án chung trên một máy chủ tích hợp. Mỗi khi một thành viên dev hoàn thành một tính năng , mã nguồn của họ sẽ được đẩy lên hệ thống CI và các kiểm tra tự động sẽ chạy để đàm bảo tính ổn định của mã nguồn.

CD - Delivery/Deployment là quá trình tự động hóa việc đóng gói, kiểm thử và phát hành phần mềm một cách liên tục. CD đóng gói phần mềm thành các gói cài đặt và triển khai các gói đó lên một môi trường staging để kiểm tra. Nếu kiểm thử thành công , các gói cài đặt được phát triển khai lên môi trường production. CD tự động triển khai phần mềm mới lên môi trường production ngay sau quá trình kiểm thử được hoàn tất.

-> Là một phương phát phát triển phần mềm có tính tự động cao , giúp đẩy nhanh quá trình phát triển phần mềm , giảm thiểu các lỗi và đảm bảo tính ổn định của phần mềm khi triển khai.

### CI/CD dùng để làm gì ? 
Nó dùng để đẩy nhanh tiến độ phát triển phần mềm và giảm thiểu các lỗi khi triển khai .

### Ưu điểm và nhược điểm của CI/CD
hỗ trợ build code, Đẩy code lên git , test code , đẩy lên bảng production , có 2 nhánh ở đây  , có thể set up pipeline - hỗ trợ automation chạy server các server mà không cần phải lấy code về và chạy code , trước khi đẩy code lên 