1.Cài Docker và Docker Compose(hoặc Docker Desktop) về máy
2.Mở Microsoft Store, search Debian và cài về máy
3.Mở Docker Desktop vào 
3.Mở Debian, setup tài khoản cho lần đầu và chạy các lệnh sau
    sudo apt update
    sudo apt install git -y                                     #Cài git
    git config --global user.name "Tên của bạn"                 #Setup tài khoản Git
    git config --global user.email "email@example.com"
    sudo apt-get install wget
2.Clone repository
    git clone https://github.com/Haizeatk4/QLVB.git
3.Copy docker-compose.yml và docker-compose.env vào thư mục gốc của QLVB
4.Mở terminal tại thư mục gốc của QLVB và chạy lệnh:
    docker compose build
    docker compose up -d