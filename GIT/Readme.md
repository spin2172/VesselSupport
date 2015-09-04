# 선박지원 Git 사용 매뉴얼

1. Git 설치
2. Git 에서 신규 프로젝트 생성하기


3. SSH 등록하기

``` javascript
    // 키 폴더 생성
    c:\Program Files (x86)\Git\mkdir .ssh
    
    // bin 폴더로 이동
    c:\Program Files (x86)\Git\cd bin
    
    // SSH Key 생성 - 개인 메일 주소로 수정합니다.
    c:\Program Files (x86)\Git\bin>ssh-keygen.exe -t rsa -C "youngbae.jeong@hmm21.com"  
    Generating public/private rsa key pair.  
    // ../.ssh/id_rsa로 파일을 지정합니다.
    Enter file in which to save the key (//.ssh/id_rsa): ../.ssh/id_rsa
    Enter passphrase (empty for no passphrase):
    Enter same passphrase again:
    Your identification has been saved in ../.ssh/id_rsa.
    Your public key has been saved in ../.ssh/id_rsa.pub.
    The key fingerprint is:
    xx:xx:xx:xx:xx:xx:xx:xx:xx:xx:xx:xx:xx youngbae.jeong@hmm21.com
    The key's randomart image is:
    +--[ RSA 2048]----+
    |          . .    |
    |           + E . |
    |        o . B =  |
    |              =o |
    |              ...|
    |               ..|
    +-----------------+
    
    // 노트패드에서 공개키 정보를 전체 복사합니다.
    c:\Program Files (x86)\Git\.ssh>notepad id_rsa.pub
```  


- **아래 그림과 같이 프로필 설정 페이지로 이동합니다.**  
![image](http://10.21.6.58:10080/VesselSupport/Manual/uploads/bef68f64febe370ed1b7d2d90261391d/image.png)  

- **SSH Keys 메뉴로 이동하여 우측 상단 Add SSH Key를 실행합니다.**  
![image](http://10.21.6.58:10080/VesselSupport/Manual/uploads/9126387243a42ac5b354e22862f2f9be/image.png)  

- **복사한 공개키를 붙여넣기 하고 Add Key를 실행하면 등록이 완료됩니다.**  
![image](http://10.21.6.58:10080/VesselSupport/Manual/uploads/d03567b605a2c88b3613251c1c77c998/image.png)

