# younghwan-jeon.github.io
블로그 학습

1.

11월 18일에 댓글 생성 수업을 듣고나서 이제 만들어야겠다고 생각한 다음에 jekyll설치 후 테마 적용 전까지 완벽하게 설치.
테마적용에서 .git를 덮어씌워서 실패, 헷갈려서 동영상을 보려고 했는데, 동영상은 아직 올라와있지 않았습니다.(18일 아니면 11일이였겠네요.)
아무튼 진척이 없어서 다른 과제를 하기로 마음먹고 미뤄두고 있었습니다.
마침내 12월 10일, 기말고사 기간이지만 기말시험은 적은 탓에 지금 테마를 적용합니다.
인터넷에 jekyll을 이용한 블로그 작성, 테마 적용 등등 쳐보고 나서, .git은 덮어 씌울 필요없고, 
기본 테마로 주셨던lanyon도 안 써도 괜찮겠다고 생각하여 EasyBook 테마를 적용했습니다. 지금은 적당히 이름, 
이메일을 수정 중이지만 EasyBook에 있는 Read.md를 읽으면서 천천히 적용 중입니다.


2.
bundle exec jekyll serve는 _posts 디렉토리 안에서 사용할 수 없었습니다. 정확히는 다른 사이트로 보내버립니다
header에 Category에 글을 넣을 수 있게 됬습니다. welcome-to-jekyll이 여기에 있는 이유를 알았으니 지울 수 있게 됬습니다.
하지만 다른 기능을 이해할 때 도움이 될 수 있으니 나중에 삭제하겠습니다.


3.
comments가 댓글과 관련있어보여 네 번째 수업을 통해 이해하고 적용하였습니다. baseurl을 주석처리하여 원격 Repo에서도 나오게 되었습니다. 
우측상단의 기호를 클릭하지 않으면 아무것도 안 보여서 해결 방법을 찾는 중입니다.


4.
favicon을 추가하였습니다.(이름의 이니셜을 사용했습니다.)


5.
Jekyll-admin을 추가하였습니다.
Gemfile 맨 밑에 줄에 gem "jekyll-admin", group: :jekyll_plugins 을 추가하고
gem install jekyll-admin 을 터미널에 입력하고
bundle exec jekyll serve 을 입력하고
http://127.0.0.1:4000/admin 으로 실행해보았습니다.

https://younghwan-jeon.github.io/admin은 찾을 수 없었습니다. 
원격Repo에서 블로그를 지우면 안되니 당연한 것이였습니다.


6.
깃 명령어 정리


