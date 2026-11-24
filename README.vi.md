![Minh họa góc học tập với laptop, cây ban công và phím đàn piano](assets/garden-banner.webp)

# Chào bạn, mình là Hưng

**Mình là sinh viên PTIT. Mình muốn trở thành AI engineer nên đang tự học và làm dự án.**

[English](README.md) · Tiếng Việt

Còn nhiều thứ mình phải học. Với microSched, mình dùng chính thứ mình làm mỗi ngày, thấy chỗ nào vướng thì quay lại sửa. Trong các đồ án ở trường, mình thường làm trưởng nhóm và là người thuyết trình chính. Mình cũng sẵn sàng trao đổi về cơ hội thực tập hoặc vị trí junior.

## Dự án

### [microSched](https://github.com/NguyenHaiHung0510/microSched) — ứng dụng mình dùng hằng ngày

[Xem trang giới thiệu](https://microsched.fly.dev/home?lang=vi)

Ứng dụng web cá nhân để quản lý công việc, ghi chú, lịch và các mục theo dõi, sử dụng FastAPI, React và PostgreSQL. Mình dùng ứng dụng trong đời sống và tiếp tục điều chỉnh theo trải nghiệm thực tế.

Hành trình này bắt đầu từ một [công cụ C++ chạy trên dòng lệnh](https://github.com/NguyenHaiHung0510/Code_HoTro_HocTap), qua [ứng dụng desktop Python/Flet](https://github.com/NguyenHaiHung0510/VC_QuanLyThoiGian), rồi đến dự án chính để mình học về kiến trúc phần mềm, triển khai ứng dụng và làm việc với AI coding agents.

- [Mimi](https://github.com/NguyenHaiHung0510/microSched/blob/develop/docs/mimi/README.md) là trợ lý ngay trong microSched. Trước đó, cùng một việc mà mình đặt tên đủ kiểu, lúc sai chính tả, lúc viết hoa viết thường tùm lum. Mình dùng Mimi để chuẩn hóa tên 68 task qua ba lượt, xem trước đề xuất rồi mới áp dụng từng lượt.
- [miGarden](https://github.com/NguyenHaiHung0510/miGarden) giúp mình tự động hóa việc tưới cây và quản lý ngay trong microSched. Phần IoT của Khu A đã xong. Mình có thể sửa lịch và bật tưới từ điện thoại. Khi nhà sửa xong, mình sẽ đi ống nước dọc lan can tới các chậu.

### [FANG](https://github.com/PTIT-TTCS-Team-5/Fang) — phần AI của miCareer

FANG là một đồ án nhóm khá tham vọng. Tụi mình muốn đưa AI vào cả hai luồng trên web tuyển dụng miCareer, từ lúc ứng viên tìm việc phù hợp đến lúc HR xem kỹ từng hồ sơ.

- **Ứng viên** nhận gợi ý việc làm được xếp hạng theo CV và thông tin hồ sơ của mình.
- **HR** bắt đầu từ danh sách ứng viên được xếp hạng theo hồ sơ và tin tuyển dụng. Khi cần tìm hoặc lọc nhanh, HR có thể nhờ agent gọi các công cụ có sẵn. Khi muốn tìm hiểu kỹ một người, HR có thể hỏi chatbot riêng. Chatbot dựa vào CV và hồ sơ của đúng ứng viên đó để trả lời.

Mình xây dựng pipeline xếp hạng hai chiều, kết hợp tìm kiếm ngữ nghĩa và từ khóa với điểm về kỹ năng, kinh nghiệm và lương. Phần mình thích nhất là dùng Optuna để tinh chỉnh và đo chất lượng xếp hạng bằng MRR và nDCG@10 trên dữ liệu ứng viên và việc làm giả lập.

Mình làm trưởng nhóm, tham gia thiết kế kiến trúc và tích hợp, viết báo cáo và phụ trách thuyết trình chính. Nhóm dùng [miCareer-mini](https://github.com/PTIT-TTCS-Team-5/miCareer-mini), bản thử nghiệm với giao diện Streamlit, để thử và trình diễn backend FastAPI trong môn học.

### [miCareer](https://github.com/NguyenHaiHung0510/miCareer) — làm web cùng đồng đội

Website tuyển dụng IT và hệ thống quản lý hồ sơ ứng tuyển (ATS) nhỏ gọn, thực hiện trong đồ án nhóm. Với vai trò trưởng nhóm, mình xây dựng một số phần dùng chung như connection pool, viết hướng dẫn thiết lập và phát triển, review tích hợp và hỗ trợ các bạn xử lý lỗi.

Trải nghiệm đầu tiên dẫn dắt một nhóm làm web của mình là [microShop](https://github.com/NguyenHaiHung0510/microShop). Lúc đó cả nhóm chưa biết làm website. Mình đi tìm cách làm. Đến lúc chạy được ứng dụng Java Servlet đầu tiên, mình thấy như vừa làm được một kỳ tích xD. Sau đó, mình cùng một nhóm thực hiện đồ án DevSecOps với mục tiêu là tự động hóa quy trình kiểm thử bảo mật trong vòng đời phát triển phần mềm, dùng microShop làm ứng dụng thử nghiệm.

## Mình đang học gì

Mình rất thích *AI Engineering* của chị Chip Huyền. Mình mới đọc tới chương 4 và đang thử áp dụng những gì học được vào các dự án của mình.

Mình học **harness engineering** ngay trên microSched. Mình đặt phạm vi trước, cùng agent nghĩ qua các phương án kiến trúc, rồi ghi lại lựa chọn và bằng chứng mình dựa vào.

Một thử nghiệm cá nhân khác là [ClaudeRelay](https://github.com/NguyenHaiHung0510/ClaudeRelay), launcher trên Windows mình làm để tiếp tục dùng Claude Code CLI với backend model khác khi đường kết nối thông thường không khả dụng. Nó chỉ thay đổi routing cho tiến trình được khởi chạy, không sửa cấu hình Claude Code mình dùng thường ngày.

## Ngoài các dự án

Mình thích chơi bóng đá, chơi đàn piano, trượt patin và trồng hoa trên ban công. Mình thích những nơi yên tĩnh, cảnh sắc thiên nhiên và đọc sách khi có thời gian ngoài việc học.

Mình tự tin giao tiếp và làm việc bằng tiếng Anh. Hồi cấp ba, mình từng tham gia đội tuyển hùng biện tiếng Anh và đội tuyển học sinh giỏi Anh (dù chưa ra được “đấu trường” thật bao giờ xD). Thuyết trình là một trong những phần mình tự tin nhất khi làm đồ án nhóm. Mình thích tìm hiểu hệ thống chạy ra sao, rồi giải thích, demo và trả lời câu hỏi về những lựa chọn thiết kế.
