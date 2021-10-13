# Instagram_crawler

### 실행을 위한 파일
* Instagram.ipynb

실행코드
```
if __name__ == '__main__':
    """Main (runs the classes/functions)"""
    #자동로그인에 필요한 ID, PW
    username = "로그인아이디"
    password = "로그인비밀번호"
    
    #IG_BOT실행
    bot = IG_Bot(username, password)
    #인스타그램 로그인
    bot.login()
    #JSON파일로 로그인 쿠키 저장
    bot.save_cookie()
```

### 실행예시 이미지
![image](https://user-images.githubusercontent.com/89976847/137130154-0beb4fe5-7c04-44a2-a953-38789c5dc294.png)
![image](https://user-images.githubusercontent.com/89976847/137129853-b4753b5c-5bd6-4283-81a9-1ae45123b8a9.png)
