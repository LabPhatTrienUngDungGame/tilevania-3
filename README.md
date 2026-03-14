#  Lab 01 - Khám phá dự án Tilevania-3
##  Thông tin sinh viên -  
** Họ tên ** : Mai Quý Phước 
** MSSV ** : 2312716
** Lớp ** : CTK47B
##  Mô tả
Bài thực hành Lab 02 môn  ** Game 2D Development with Unity ** . 
Khám phá và phân tích dự án game tilevania-3 
##  Các thay đô  i đã thực hiện 
1.  Thay đô  i tô  c độ chạy: 7 → 15 
2.  Thay đô  i lực nha  y: 20 → 40 
3.  Thay đô  i trọng lực: 0.5 → 3.0 
4.  Thêm Coin vào scene tại vị trí màn 1 sẽ thấy 1 coin to hơn coin khác đó là coin đã thêm
##  Kiê  n thức đã học được 
1. Quản lý dự án chuyên nghiệp với Prefabs
Học được cách sử dụng Prefabs để tạo ra các đối tượng có thể tái sử dụng (như kẻ địch, đồng xu, hệ thống camera).
Việc hiểu cách tổ chức thư mục Assets/Prefabs giúp quy trình phát triển game khoa học hơn, cho phép chỉnh sửa một mẫu gốc và áp dụng thay đổi cho toàn bộ các màn chơi (Levels) ngay lập tức.

3. Mô hình thiết kế Singleton (Singleton Pattern)
Thông qua file GameSession.cs, đã nắm vững cách triển khai Singleton.
Đây là kỹ thuật đảm bảo chỉ có duy nhất một bộ quản lý trò chơi tồn tại xuyên suốt cảnh (Scenes), giúp lưu giữ những dữ liệu quan trọng như điểm số và mạng sống mà không bị reset mỗi khi chuyển màn.

5. Hệ thống Input System mới và Vật lý 2D
Biết cách sử dụng UnityEngine.InputSystem để xử lý các sự kiện điều khiển (OnMove, OnJump, OnAttack).
Đồng thời, việc vận dụng Rigidbody2D và Vector2 để điều khiển nhân vật theo cơ chế vận tốc (linearVelocity) giúp chuyển động của nhân vật Bronzo trở nên mượt mà và tuân thủ các quy luật vật lý.

7. Xử lý va chạm dựa trên Layer (Layer Mask)
Thay vì sử dụng các phương thức va chạm vật lý nặng nề, bạn đã áp dụng phương thức IsTouchingLayers.
Đây là cách tối ưu để nhân vật nhận biết đâu là mặt đất để nhảy, đâu là kẻ địch để xử lý "cái chết", và đâu là thang để leo trèo, giúp game chạy hiệu quả và ổn định hơn.

8. Giao tiếp giữa các Script (Script Communication)
Thực hành cách các đối tượng trong game "nói chuyện" với nhau. Ví dụ:Player gọi hàm của GameSession khi chết.

Enemy tự động quay đầu khi chân rời khỏi mặt đất (Trigger).

GameSession điều khiển nội dung hiển thị trên UI Canvas.
