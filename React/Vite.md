# Lý Thuyết về Vite + Reacjt

### React 
React là một thư viện do Facebook là người đứng sau. Trong thằng
này còn có Reactjs và React Native.Reactjs cũng là một thư viện dùng để build web còn 
React Native là một Framework và sẽ tập trung vào build ứng dụng mobile.

### Component
là một hàm của react , nó là các thành phần trong quan trọng khi xây dựng ứng dụng , nó 
có thể chia được nhiều và nhỏ để dễ dàng quản lí hơn

### Functional
là một hàm đơn giản do JavaScrips đơn giản , chúng nhận những prop hay còn gọi là tham số truyền 
vào và return react elements. Vì nó không có lifecycle nên nó không có componentDidMount và 
các hooks khác

---

### Vite
Là một công cụ hỗ trợ xây dựng chương trình, nó tập trung vào cung cấp cho tốc khi build nên
khi một trình viên hoặc thực tập sinh có thể học tập và xây dựng chương trình nhanh chóng.

### Cách dùng Vite
 + Tạo một project Vite với lệnh :

`npm create vite@latest`

 + Đầu tiên nó sẽ hiện các ngôn ngữ sẽ dùng , thì sẽ chọn vào thằng nào muốn build project với Vite 
, ở đây đang demo Vite + React nên sẽ chọn vào thằng React.

 + Lựa chọn thứ 2 nó sẽ là hiện thị ngôn ngữ dùng , Ts hoặc Js và kèm theo lựa Chọn SWP.
Nếu bạn dùng Ts thì chọn Ts không thì ngược lại . Còn lựa chọn TS + SWP nó sẽ là dùng TS 
để code còn SWP nó sẽ thay chương trình build Bable.

Note :Babel là một trình biên dịch Javascript mã nguồn mở và miễn phí có chức năng 
chính dùng để biên dịch ECMAScript thành phiên bản tương thích ngược cho JavaScript 
có thể chạy trên các môi trường JavaScript cũ hơn. Babel là công cụ phổ biến để sử dụng
các tính năng mới nhất của Javascript.

 + Sau khi đã cài xong thì cho project React hiện tại vào Vite và code tiếp thôi.
