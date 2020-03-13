# Cài đặt môi trường trên MAC

Yêu cầu thiết bị:
- Máy tính, laptop Mac.

### Cài đặt Xcode
* Vào Mac Appstore để tìm kiếm xCode sau đó click lên nút Get.
* Cài đặt Commandline Tools.
* Mở Terminal ( Trong /Applications/Utilities/) và thực hiện lệnh  `$ xcode-select --install`

### Cài đặt Homebrew

[Homebrew](https://docs.brew.sh/Installation) là công cụ quản lý package trên Mac. 
* Mở terminal và thực hiện lệnh:

```     
  $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

* Kiểm tra tình trạng cài đặt bằng thực hiện lệnh `$ brew --version`. Bạn sẽ nhìn thấy thông tin như dưới đây 

```
Homebrew 2.1.6
Homebrew/homebrew-core (git revision f0859; last commit 2019-06-26)
Homebrew/homebrew-cask (git revision 8055f; last commit 2019-06-26)
```

### Cài đặt Carthage
* Mở terminal và thực hiện lệnh sau: `$ brew install carthage`
   
### Cài đặt JAVA
* Để kiểm tra xem Java đã được cài đặt chưa, chúng ta thực hiện lệnh: `$ java -version`
	* Phiên bản nên là 1.8 hoặc lớn hơn.
* Tải jdk-8u221-macosx-x64.dmg [tại đây](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html).
* Bạn sẽ nhìn thấy file này được tải về và lưu trữ trong thư mục Download
* Click hai lần liên tiếp lên file này
* Click nút tiếp tục ( Continue)
* Click nut cài đặt ( Install)
* Nhập mật khẩu để cài đặt được tiến hành.
