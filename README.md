# Tên dự án: Phần mềm tính điểm OMG

>_Phần mềm sử dụng để tính điểm cho sinh viên_

>##Hướng dẫn cài đặt

>***Tên file : DAP304x_asm1_tuyenttFX18918@funix.edu.vn\Tran_Thanh_Tuyen_grade_the_exams.ipynb***

>_Dữ liệu nguồn: DAP304x_asm1_tuyenttFX18918@funix.edu.vn\data-files\Data Files_

>##Hướng dẫn sử dụng

>_Phần mềm gồm 4 task chính, mỗi task có 1 nhiệm vụ riêng biệt_

>###Task 1

>•	Người dùng giải nén file: DAP304x_asm1_tuyenttFX18918@funix.edu.vn.RAR

>•	Người dùng mở ứng dụng bằng cách: mở Jupiter notebook and tìm đến file: Tran_Thanh_Tuyen_grade_the_exams.ipynb trong thư mục vừa giải nén.

>•	Để con trỏ chuột vào mỗi cell tương ứng mỗi task sau đó ấn tổ hợp phím: Shift + Enter để kiểm tra chức năng từng task

>•	Người dùng nhập tên tệp tương ứng với tên lớp muốn tính điểm (ví dụ nhập class1 ứng dụng sẽ hiểu là class1.txt).

>•	Nếu tên tệp(tên lớp) có tồn tại và mở tệp thành công sẽ gửi thông báo: “Successfully opened class1” tới người dùng.

>•	Nếu người dùng nhập tên tệp không tồn tại trong tệp của dữ liệu nguồn sẽ gửi thông báo:”VD: File class100 not found” tới người dùng.

>•	Nếu có bất kỳ ngoại lệ nào trong quá trình mở file thì ứng dụng cũng sẽ gửi thông báo theo tên của ngoại lệ tới người dùng.

>###Task 2	

>•	Kiểm tra dữ liệu theo từng dòng tương ứng với từng học sinh thuộc từng lớp có đúng với định dạng quy định hay không.

>•	Dữ liệu mỗi dòng tương ứng 1 sinh viên và dữ liệu phải đúng định dạng sau:

	Giá trị đầu tiên là số ID của sinh viên. 25 chữ cái sau là câu trả lời của học sinh cho kỳ thi.

	Tất cả các giá trị được phân tách bằng dấu phẩy. Nếu không có chữ cái nào sau dấu phẩy, điều này có nghĩa là học sinh đã bỏ qua việc trả lời câu hỏi.

>•	Gửi thông báo không có lỗi nếu tất cả các dòng đều đúng định dạng.

>•	Gửi thông báo và in ra các dòng cụ thể có định dạng không đúng với quy định.

>•	Thống kê số dòng hợp lệ hoặc không hợp lệ và gửi báo cáo.

>###Task 3	

>•	Tính điểm theo từng học sinh

>•	Ứng dụng chỉ tính điểm cho những học sinh có định dạng dữ liệu đúng theo quy định. Những học sinh có định dạng dữ liệu sai sẽ không được chấm.

>•	Ứng dụng sẽ so sánh kết quả làm bài của học sinh với đáp án đúng. Và sẽ cho 4 điểm đối với câu trả lời đúng, -1 điểm với câu trả lời sai và nếu bỏ qua sẽ 0 có điểm sau đó sẽ tính tổng điểm theo từng học sinh.

>•	Ứng dụng sẽ gửi báo cáo thông kê một số thông tin như: Số lượng học sinh điểm cao nhất, điểm trung bình, điểm cao nhất, thấp nhất, range…. theo từng lớp.

>###Task 4

>•	Task 4 sẽ bao gồm chức năng đầy đủ của phần mềm hoàn chỉnh được tổng hợp lại từ 3 task trên và bổ sung thêm chức năng lưu kết quả chấm bài của học sinh vào file lưu trữ.

>•	Output sẽ được lưu vào thư mục: DAP304x_asm1_tuyenttFX18918@funix.edu.vn\data-files\Results

>•	Phần mềm sẽ tự tạo ra 1 file mới(trong trường hợp chưa có file kết quả) có tên tương ứng với tên lớp đã mở trước đó và có thêm phần đuôi là _grades(VD: Nếu trước đó mở file class1 thì sẽ có 1 file mới class1_grades.txt được tạo mới)

>•	Ứng dụng sẽ tự động ghi kết quả chấm điểm vào file mới theo ID của học sinh.

>•	Ứng dụng sẽ gửi thông báo tên file và thư mục chứa file kết quả tới người dùng.
