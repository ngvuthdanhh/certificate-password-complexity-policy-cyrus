# Password Complexity Policy — Overview

## 🎯 Mục tiêu
- Đảm bảo mật khẩu đủ mạnh để chống lại brute-force và dictionary attacks.  
- Thiết lập baseline bảo mật nhất quán trong tổ chức.  
- Cân bằng giữa bảo mật và tính khả dụng cho người dùng.

## 🔑 Vai trò của mật khẩu mạnh
- Là lớp phòng thủ đầu tiên chống lại truy cập trái phép.  
- Giảm thiểu nguy cơ từ credential stuffing (tấn công dùng mật khẩu rò rỉ).  
- Ngăn chặn kẻ tấn công khai thác tài khoản yếu để leo thang đặc quyền.

## 🌍 So sánh các chuẩn
- **NIST SP 800-63B**: độ dài tối thiểu 8, khuyến nghị ≥ 12, không bắt buộc ký tự đặc biệt nhưng cần kiểm tra với blacklist.  
- **ISO 27001 A.9.4.3**: mật khẩu cần đủ độ phức tạp và được thay đổi định kỳ.  
- **PCI-DSS**: yêu cầu ≥ 7 ký tự, bao gồm số và chữ cái.  
- **CIS Benchmarks**: thường khuyến nghị ≥ 14 ký tự, có MFA bổ sung.
