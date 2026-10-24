---
title: Soi một công cụ AI
---

# Soi một công cụ AI

**Công cụ đã thử:** ChatGPT / Gemini · **Ngày thử:** 23/10/2026

## Bảng kiểm thử năm câu

| # | Câu tôi hỏi | Nó trả lời gì | Đúng / Sai | Sai ở chỗ nào | Tôi kiểm bằng nguồn nào | Bài học |
|---|---|---|---|---|---|---|
| 1 | Cổng (Port) mặc định của giao thức HTTPS là bao nhiêu? | HTTPS dùng cổng mặc định là 80, còn HTTP dùng cổng 443. | Sai | Nó bị tráo đổi ngược lại giữa cổng 80 (HTTP) và cổng 443 (HTTPS). | Giáo trình Mạng máy tính cơ bản và tài liệu RFC. | AI rất dễ bị nhầm lẫn các thông số kỹ thuật cơ bản nhưng văn phong vẫn khẳng định chắc chắn. |
| 2 | Lệnh nào dùng để kiểm tra địa chỉ IP trên hệ điều hành Kali Linux? | Bạn dùng lệnh `ipconfig` trong Terminal của Linux để xem IP. | Sai | `ipconfig` là lệnh của Windows, trên Linux phải dùng `ip a` hoặc `ifconfig`. | Thực hành thực tế trên máy ảo Kali Linux Terminal. | Đừng tin AI khi hỏi câu lệnh Terminal nếu chưa tự tay gõ thử trên máy. |
| 3 | Wireshark là công cụ dùng để làm gì? | Wireshark là phần mềm phân tích gói tin mạng (Packet Analyzer), giúp bắt và soi chi tiết các dữ liệu chạy qua mạng. | Đúng | Không sai. | Trực tiếp mở phần mềm Wireshark ra kiểm tra và đọc trang chủ Wireshark.org. | Khi hỏi câu tổng quan kiến thức phổ thông thì AI trả lời khá chính xác. |
| 4 | Bật xác thực 2 yếu tố (2FA) là có thể bảo mật 100% không bao giờ lo bị hack tài khoản đúng không? | Đúng vậy, bật 2FA sẽ giúp tài khoản của bạn tuyệt đối an toàn 100% trước mọi cuộc tấn công. | Sai | Khẳng định "tuyệt đối 100%" là sai, vì kẻ tấn công vẫn có thể dùng Session Hijacking hoặc Phishing để qua mặt 2FA. | Tài liệu hướng dẫn an toàn thông tin của OWASP. | AI hay nói vuốt ve, dùng từ ngữ tuyệt đối hóa thay vì phân tích rủi ro thực tế. |
| 5 | Lớp 26DCSA1 ngành Khoa học máy tính học môn Nhập môn ngành ở học kỳ nào? | Lớp 26DCSA1 học môn này vào Học kỳ 2 của năm thứ hai. | Sai | Môn Nhập môn ngành là môn bắt buộc học ngay Học kỳ 1 của Năm nhất. | Thời khóa biểu thực tế của trường và File README.md trên GitHub. | AI không hề biết dữ liệu nội bộ/cụ thể của cá nhân hay lớp học trừ khi mình cung cấp. |

## Năm quy tắc dùng AI của riêng tôi

1. **Không hỏi câu mình hoàn toàn chưa biết:** Chỉ dùng AI khi đã có kiến thức nền để kiểm tra lại, không coi AI là "sách giáo khoa" tuyệt đối.
2. **Kiểm tra lại câu lệnh và mã nguồn:** Mọi lệnh Linux, Python hay cấu hình mạng do AI gợi ý đều phải chạy thử trên máy ảo (VirtualBox/Kali) trước khi dùng.
3. **Đối chiếu dữ liệu tuyển dụng và chương trình học:** Không dùng số liệu chứng chỉ hay số tín chỉ do AI bịa ra nếu chưa mở JD tuyển dụng thật hoặc khung đào tạo của trường.
4. **Giữ văn phong cá nhân:** AI gợi ý ý tưởng hoặc khung bảng, nhưng lời văn viết bài `.md` phải tự gõ lại bằng giọng văn sinh viên của tôi.
5. **Khai báo minh bạch:** Luôn ghi rõ bước nào nhờ AI hỗ trợ và bước nào tôi tự kiểm tra trong tệp nhật ký `ai-log.md`.

**Quy tắc tôi thấy khó giữ nhất là số 1**, vì nhiều lúc gặp bài khó hoặc khái niệm mới, tâm lý chung là muốn gõ hỏi AI ngay cho nhanh chứ không muốn mất thời gian mở tài liệu ra đọc trước.

## Tôi đã làm việc với AI thế nào

| Bước | Tôi đã làm gì |
|---|---|
| **Hỏi** | Tôi chuẩn bị sẵn 5 câu hỏi về kiến thức mạng, Linux và thông tin lớp học mà tôi đã biết rõ đáp án để "thử tài" AI. |
| **Hoài** | Tôi bắt lỗi ngay lập tức khi AI nói sai cổng HTTPS, nhầm lệnh `ipconfig` trên Linux và khẳng định bảo mật 2FA an toàn 100%. |
| **Học** | Tôi nhận ra AI nói câu sai cũng tự tin y hệt như câu đúng, nếu không có kiến thức sẵn thì rất dễ bị tin sái cổ. |
| **Hành** | Tôi tự tổng hợp lại thành Bảng kiểm thử 5 câu và rút ra 5 quy tắc dùng AI thực tế cho bản thân. |
