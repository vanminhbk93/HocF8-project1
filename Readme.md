## Cách đẩy lên github

## ở web github.com
- lên web github.com; login vào; tạo repository

- Lần đầu thì phải xác thực SSH key (chứ ko phải ai cũng push lên web của mình được)
        Cài và mở GitGui, vào help show SSH key
        mở web github, click vào user account -> Settings -> SSH and GPG keys -> Tạo mới 1 SSH key với tên tự đặt, SSH key là key của GitGui ở trên
- copy "link" ssh ở trên github

## ở VS Code
- ở project đang làm (index.html), mở bằng vscode; mở terminal
    git init
    git add .
    git commit -m"viết commment ở đây"
    git remote add origin "link"
    git remote -v (kiểm tra lại xem remote vào github.com/repository được chưa)
    git branch -M main (tạo branch, default là main)
- git push (câu lệnh này sau. chạy lại lệnh recommend ở terminal)
    
## vào github.com
- Vào web github, settings -> General -> tích vào template repository
- Vào setting -> pages -> cấu hình lại source
