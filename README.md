# GitPractice

Giả lập các tình huống khi dùng git

## 1 - merge bị conflic
- Tạo conflic:
    - tạo file app.text trên nhánh master và thêm dòng 1: branch master - dòng 1
    - commit lại file vừa rồi
    - checkout qua nhánh feature1 và thêm vào file app.text dòng số 2: branch feature1 - dòng 2
        - commit trên branch feature1
    - quay trở lại nhánh master
    - checkout qua nhánh feature1 và thêm vào file app.text dòng số 2: branch feature1 - dòng 2
        - commit trên branch feature1

    - merge feature1 vào master
    - merge fature2 vào master