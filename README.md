# Graduate-Predict
DỰ ĐOÁN KHẢ NĂNG TỐT NGHIỆP CỦA SINH VIÊN TRƯỜNG ĐẠI HỌC CÔNG NGHỆ THÔNG TIN
# Đặt vấn đề
Hiện nay, công nghệ thông tin đang phát triển thần tốc và được áp dụng rộng rãi trong hầu hết các lĩnh vực, điều đó góp phần tạo nên một cuộc cách mạng công nghiệp lần thứ tư sôi động. Trong lĩnh vực giáo dục, rất nhiều trường học và trung tâm đã áp dụng công nghệ thông tin để số hóa quá trình giảng dạy của mình nhằm mục đích đưa tri thức đến mọi người một cách nhanh và tiện lợi hơn. Sau khi đợi dịch bệnh lớn bùng phát vào cuối năm 2019, quá trình số hóa này lại càng được đẩy mạnh thông qua việc học trực tuyến. Điều này đồng nghĩa với việc theo thời gian, lượng dữ liệu về giáo dục được lưu trữ tại các trường học tăng lên rất nhiều. Nếu lượng dữ liệu này được xử lý, phân tích, khai phá một cách khoa học thì sẽ góp một phần rất lớn vào việc hỗ trợ học tập cho các bạn học viên cũng như điều chỉnh phương pháp giảng dạy của các thầy cô giáo. Chính vì vậy mà lĩnh vực phân tích và khai phá dữ liệu giáo dục đã và đang thu hút được nhiều sự quan tâm. Khá nhiều vấn đề nhức nhối của giáo dục trước đây đã được giải quyết bằng máy vi tính nhờ các công nghệ khai phá dữ liệu nói riêng và khoa học dữ liệu nói chung. 

Hiện nay, tại một số cơ sở đào tạo sau trung học phổ thông như các trường đại học, cao đẳng đang áp dụng cơ chế học tín chỉ. Cơ chế này giúp cho các bạn sinh viên chủ động hơn trong việc lựa chọn thời khóa biểu học tập. Trong cơ chế học tín chỉ này, sinh viên có thể tùy ý lựa chọn đăng ký học nhiều môn học nếu cảm thấy mình đủ khả năng, thời gian để tiếp thu hết các môn đã đăng ký và đăng ký ít môn học nếu cảm thấy mình không có đủ khả năng tiếp thu nhiều môn hoặc không thể dành nhiều thời gian để học nhiều môn. Tuy nhiên trên thực tế thì các bạn sinh viên thường bị lúng túng khi lựa chọn môn học do có nhiều môn được giảng dạy trong môn học kỳ. Khi đó, bên cạnh khả năng tự tìm hiểu thì sinh viên cần đến sự trợ giúp của cố vấn học tập cùng với đội ngũ thầy cô giáo nhà trường để tư vấn giúp giải quyết triệt để tình trạng. Do đó các thầy cô cần được tra cứu thêm kết quả học tập của từng sinh viên, tìm hiểu để tư vấn, đưa ra các lời cảnh báo sớm cho các sinh viên. Với một trường đại học có hàng ngàn sinh viên đang theo học thì việc làm này không hề dễ triển khai. Chính vì vậy đồ án này được thực hiện hướng đến việc khai phá dữ liệu giáo dục, sau đó từ kết quả khai phá này xây dựng nên phần mềm hỗ trợ cho công tác giáo dục.
1.2. Mục tiêu
-	Mục tiêu đề tài: Dựa vào dữ liệu tốt nghiệp các khóa trước, dự đoán được khả năng tốt nghiệp của sinh viên (chưa tốt nghiệp / tốt nghiệp) tại trường Đại học Công nghệ Thông Tin – Đại học Quốc gia Thành phố Hồ Chí Minh
-	Mục đích nghiên cứu: Tìm ra những yếu tố ảnh hưởng đến khả năng tốt nghiệp của sinh viên Đại học Công nghệ Thông Tin – Đại học Quốc gia Thành phố Hồ Chí Minh để đưa ra lưu ý và phương pháp học tập hiệu quả cho các sinh viên khóa sau.
1.3. Đối tượng và phạm vi nghiên cứu
-	Dữ liệu đề tài nghiên cứu giới hạn trong trường đại học Công nghệ Thông tin – Đại học Quốc gia Thành phố Hồ Chí Minh gồm: 
o	Tập dữ liệu tuyển sinh: dữ liệu của sinh viên trước khi vào trường: Kết quả đầu vào(điểm thi THPTQG, điểm đánh giá năng lực, điểm xét tuyển học bạ, sinh viên được tuyển thẳng/ ưu tiên xét tuyển), các thông tin cá nhân của sinh viên, các chứng chỉ sinh viên đã đạt được(nếu có).
o	Tập dữ liệu kết quả trong tiến trình học: Dữ liệu điểm của các môn học trong từng học kỳ theo từng năm của sinh viên, điểm rèn luyện của sinh viên từng học kỳ, các chứng chỉ, những xử lý học vụ, bảo lưu của sinh viên.
