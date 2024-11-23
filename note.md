# Term
Repository (Repo): Folder dự án
Branch: cành mặc định là master
Conflict: xung đột
# Commands
- git --version: xem phiên bản git
- git config --global user.name {user name}: đặt tên người dùng
- git config --global user.email {email}: đặt email
- git init: biến dự án thành git Repository
- git status: xem trạng thái của dự án (đã thay đổi những j)
- git add + file name: chuẩn bị lưu lại thời điểm hiện tại của dự án
- git add.: chuẩn bị lưu tất cả file
- git reset: lấy ra file để ko lưu
- git restore --staged {file name}: đưa lại file về trạng thái bình thường
- git commit: chính thức lưu
- git commit -m 'ghi chú': ghi chú thời điểm lưu
- git log: xem lại những thời điểm đã lưu
- git log --oneline: xem ngắn gọn hơn
- git checkout + id git commit: quay lại thời điểm commit
- git checkout master: quay lại thời điểm ban đầu
- git checkout {branchname}: chọn branch
- git branch: xem các branch
- git checkout -b {branchname}: tạo branch mới
- git merge {branch name}: xác nhập 2 branch với nhau
- git branch -d {branchname}: xóa branch
- git push + link + branch_name: đẩy lên remote repo
- git remote add origin + link: gán link = origin
- git clone + đường dẫn: pull
# Note
- Tạo branch sau dựa trên branch trước thì branch sau vẫn có những commit của branch trước