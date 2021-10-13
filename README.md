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

