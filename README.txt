AJUN'S SPACE - 개인 소개 웹사이트

실행 방법
1. ZIP 파일 압축을 풉니다.
2. index.html 파일을 더블 클릭하면 브라우저에서 웹사이트가 열립니다.
3. 메모장 또는 VS Code로 index.html을 열어 소개 문구와 내용을 수정할 수 있습니다.

사진을 나중에 추가하는 방법
1. 압축을 푼 폴더 안의 images 폴더에 원하는 사진을 넣습니다.
2. 사진 파일 이름을 profile.jpg 로 바꿉니다.
3. index.html에서 아래 부분을 찾습니다.

   <span>PROFILE PHOTO<br><small>나중에 사진을 추가할 수 있어요</small></span>

4. 위 줄을 다음 코드로 교체합니다.

   <img src="images/profile.jpg" alt="Ajun profile photo">

연락처 수정
- index.html에서 your-email@example.com 을 공개해도 되는 이메일 주소로 바꿉니다.
- SNS 링크는 href="#" 부분을 본인의 공개 프로필 주소로 바꿉니다.

주의
- 실제 웹에 공개하기 전에는 이메일, SNS 등 공개할 개인정보를 신중하게 선택하세요.
- 현재 버전은 정적 웹사이트입니다. 사진 파일 교체는 웹사이트 폴더에서 직접 하면 됩니다.
