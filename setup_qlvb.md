1.  Cài Docker và Docker Compose(hoặc Docker Desktop) về máy
2.  Mở Microsoft Store, search Debian và cài về máy
3.  Mở Debian, setup tài khoản cho lần đầu và chạy các lệnh sau
    sudo apt update
    sudo apt install git -y                                     #Cài git

    git config --global user.name "Tên của bạn"                 #Setup tài khoản Git
    git config --global user.email "email của bạn@example.com"
    
4.  Mở Docker Desktop vào: Setting(Cài đặt) >> Resources >> WSL integration
    Chọn bật cho Debian rồi nhấn Apply & restart

5.  Mở VS Code vào Extensions tìm và cài WSL của Microsoft
6.  Mở lại Debian, Clone repository
    git clone https://github.com/Haizeatk4/QLVB.git
    cd QLVB/                                              

    sudo apt-get install wget
    code .                                                      #Mở VS Code

7.  Copy docker-compose.yml và docker-compose.env vào thư mục gốc của QLVB
8.  Mở terminal tại thư mục gốc của QLVB và chạy lệnh:
    docker compose build                                        #Chạy hai lệnh cho mỗi lần sửa code
    docker compose up -d