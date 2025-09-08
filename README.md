# thien_git

hello from local


Conflict khi merge 2 file có cùng tên team.txt nhưng khác nội dung 
<img width="1850" height="974" alt="image" src="https://github.com/user-attachments/assets/6d18cf71-b87e-4ea5-baaf-9e318afc5998" />

Sau khi resolve conflict thì file thay đổi là file được push.
Ở bài này, file team.txt sau thay đổi đã được push lên main nên chỉ có file team.txt ở main là được chỉnh sửa.

fast-forward là tình trạng các branch được merge khi lịch sử commit vẫn được giữ tuyến tính dù chúng ta đã tạo ra những commit ở nhánh khác. Ví dụ như việc ta commit main --> commit feature-info, khi đó lịch sử commit vẫn tuyến tính, chỉ thay đổi branch. Còn nếu chúng ta thực hiện commit ở cả nhánh main và feature-info không theo trình tự thời gian thì việc merge diễn ra như bình thường.
