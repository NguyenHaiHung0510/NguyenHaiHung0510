![Minh họa góc học tập với laptop, cây ban công và phím đàn piano](assets/garden-banner.webp)

# Chào bạn, mình là Hưng

**Sinh viên PTIT, đang học AI engineering qua các dự án phần mềm.**

[English](README.md) · Tiếng Việt

Mình làm công cụ cho bản thân và cùng các bạn thực hiện đồ án ở trường. Mình thích tìm hiểu một hệ thống nên hoạt động thế nào, giúp mọi người bắt đầu và cùng cải tiến sản phẩm. Mình luôn trân trọng các cơ hội thực tập hoặc junior để tiếp tục học và đóng góp trong một nhóm phát triển.

Lịch học và các dự án trong kỳ khiến mình khá bận đến khoảng cuối tháng 11/2026; mình dự kiến sẽ dần có thêm thời gian từ đầu tháng 12.

## Dự án

### [microSched](https://github.com/NguyenHaiHung0510/microSched) — ứng dụng mình dùng hằng ngày

Ứng dụng web cá nhân để quản lý công việc, ghi chú, lịch và các mục theo dõi, sử dụng FastAPI, React và PostgreSQL. Mình dùng ứng dụng trong đời sống và tiếp tục điều chỉnh theo trải nghiệm thực tế.

Hành trình này bắt đầu từ một [công cụ C++ chạy trên dòng lệnh](https://github.com/NguyenHaiHung0510/Code_HoTro_HocTap), qua [ứng dụng desktop Python/Flet](https://github.com/NguyenHaiHung0510/VC_QuanLyThoiGian), rồi đến dự án chính để mình học về kiến trúc phần mềm, triển khai ứng dụng và làm việc với AI coding agents.

### [FANG](https://github.com/PTIT-TTCS-Team-5/Fang) — khám phá AI trong tuyển dụng

Đồ án nhóm về đánh giá mức độ phù hợp giữa ứng viên và công việc. Bên cạnh hệ thống xếp hạng, agent giúp HR tìm hiểu ứng viên trong một tin tuyển dụng, còn chatbot riêng hỗ trợ hỏi sâu về hồ sơ từng người.

Mình phát triển thuật toán xếp hạng theo cả hai chiều, kết hợp tìm kiếm ngữ nghĩa và từ khóa với điểm số về kỹ năng, kinh nghiệm và lương. Một phần mình thấy rất thú vị là tuning bằng Optuna, rồi so sánh chất lượng xếp hạng qua MRR và nDCG@10 trên dữ liệu ứng viên–công việc giả lập. HR có thể tự xem bảng xếp hạng hoặc yêu cầu agent gọi ranking tool và lọc ứng viên.

Mình làm trưởng nhóm, tham gia thiết kế kiến trúc và tích hợp hệ thống, viết báo cáo và thuyết trình. Nhóm dùng [miCareer-mini](https://github.com/PTIT-TTCS-Team-5/miCareer-mini), giao diện Streamlit, để phát triển và trình diễn backend FastAPI. Đây là bản thử nghiệm trong khuôn khổ môn học, chưa phải dịch vụ tuyển dụng vận hành thực tế.

### [miCareer](https://github.com/NguyenHaiHung0510/miCareer) — làm web cùng đồng đội

Website tuyển dụng IT và hệ thống quản lý hồ sơ ứng tuyển (ATS) nhỏ gọn, thực hiện trong đồ án nhóm. Với vai trò trưởng nhóm, mình xây dựng một số phần dùng chung như connection pool, viết hướng dẫn thiết lập và phát triển, review tích hợp và hỗ trợ các bạn xử lý lỗi.

Trải nghiệm đầu tiên dẫn dắt một nhóm làm web của mình là [microShop](https://github.com/NguyenHaiHung0510/microShop). Cả nhóm bắt đầu khi chưa biết làm web; chạy được ứng dụng Java Servlet trên Tomcat là bước tiến đầu tiên. Sau đó, mình cùng một nhóm thực hiện đồ án DevSecOps, dùng microShop làm ứng dụng thử nghiệm.

## Mình đang học gì

Mình học theo cuốn *AI Engineering* của Chip Huyền, kết hợp với các môn học và dự án.

Mình cũng học **harness engineering** từ chính cách phát triển microSched. Mình giữ quyền quyết định về sản phẩm và phạm vi công việc, còn agent điều phối có thể trực tiếp thực hiện hoặc giao các phần việc rõ ràng cho agents khác. Mình dùng review độc lập và bằng chứng kiểm thử để kiểm tra kết quả, rồi lưu các quyết định và bài học vào docs và memory. Mục tiêu là giữ được cách làm việc này khi đổi model hay công cụ.

Xung quanh microSched, mình đang thiết kế ba dự án kết nối với nhau:

- **Mimi**, trợ lý tích hợp trong microSched, làm việc với task, note, tracker và tài liệu, đồng thời thực hiện các thao tác với sự phê duyệt phù hợp. Xa hơn, nếu miGarden thành công, mình mong Mimi có thể giúp chăm hoa, từ gợi ý tưới đến thực hiện yêu cầu tưới đã được mình duyệt.
- **microLink**, kết nối môi trường coding agent mình đang dùng, hiện là Codex, với microSched qua MCP. Mình thiết kế nó để agent có thể đọc và cập nhật dữ liệu ứng dụng qua các công cụ cụ thể, với quyền truy cập và bước xác nhận phù hợp cho từng thao tác.
- **miGarden**, dự án nối sở thích trồng hoa với IoT: theo dõi điều kiện từng chậu và điều khiển tưới từ microSched. Phần cứng, mạng chập chờn và việc đưa nước vào hệ thống khiến đây là một dự án khó, có nhiều thứ có thể hỏng. Mình muốn bắt đầu bằng vài chậu thử nghiệm, học từ những lần không chạy như ý và kiên trì làm đến khi có một hệ thống dùng được, đáng tin.

Mình đặt mục tiêu làm ra những phiên bản đầu tiên thật chỉn chu trong kỳ này, rồi tiếp tục phát triển chúng sau môn học.

Một thử nghiệm cá nhân khác là [ClaudeRelay](https://github.com/NguyenHaiHung0510/ClaudeRelay), launcher trên Windows mình làm để tiếp tục dùng Claude Code CLI với backend model khác khi đường kết nối thông thường không khả dụng. Nó chỉ thay đổi routing cho tiến trình được khởi chạy, không sửa cấu hình Claude Code mình dùng thường ngày.

## Ngoài các dự án

Mình chơi bóng đá, piano, trượt patin và trồng hoa trên ban công. Mình thích những nơi yên tĩnh, cảnh sắc thiên nhiên và đọc sách khi có thời gian ngoài việc học.

Mình tự tin giao tiếp và làm việc bằng tiếng Anh. Hồi cấp ba, mình từng tham gia đội tuyển hùng biện tiếng Anh và đội tuyển học sinh giỏi Anh (dù chưa ra được “đấu trường” thật!). Ở đại học, mình thường là người thuyết trình chính cho đồ án nhóm: giải thích hệ thống, demo sản phẩm và trả lời câu hỏi về các lựa chọn thiết kế. Đó cũng là một trong những phần mình tự tin nhất khi làm đồ án nhóm.
