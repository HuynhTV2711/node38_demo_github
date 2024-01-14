# node38_demo_github
1. Khởi tạo
Bước 1: tạo repo => copy hết lệnh ở repo chạy ở command
Bước 2: git add -A =>  git commit -m "comment" => git push


2. tạo nhánh
- Nhánh chính là main hoặc master(thường nhóm trưởng quản lí)
- Các nhánh phụ được tạo ra để push code của từng thành viên lên 
- muốn merge code vào nhánh chính thì tạo 1 pull request 
2.1. tạo branch mới
- tạo branch git branch tenNhanhCon
- chuyển branch git check out tenNhanhCon
- tạo và chuyển branch git checkout -b tenNhanhCon
- xóa nhánh git branch -D tenNhanh
- kiểm tra nhánh đang ở đâu git branch
- đẩy nhánh mơi lên repo git push --set-upstream origin [tennhanh]

Lưu ý: Thói quen khi làm việc với git
1. Luôn pull code mới nhất của nhánh main về để làm việc( mỗi ngày )

