책상 위 젤리 친구 - 웹 AR
=========================

링크: https://h71168488-oss.github.io/desk-ar-character/

[파일]
  index.html      : AR 페이지
  character.glb   : 젤리버디 모델 (블렌더에서 내보낸 파일)

[엔진]
  8th Wall 엔진(무료 배포판)을 인터넷 주소(jsdelivr)에서 불러와요. 따로 올릴 파일은 없어요.
  아이폰·안드로이드·카카오톡 브라우저에서 모두 같은 화면으로 동작해요.

[기기별]
  폰 : 시작하기 → 카메라 켜짐 → 책상을 톡 누르면 그 자리에 등장
  PC : 같이 놀기 (화면 속 3D)

[조작]
  첫 탭       : 그 자리에 등장
  한 번 탭    : 그 자리로 걸어가기
  두 번 탭    : 순간이동
  캐릭터 탭   : 쓰다듬기 (> < 눈, 하트)
  아래 버튼   : 점프 / 빙글 / 쿵 / 놀라기 / 먹기

[모델 바꾸기]
  블렌더에서 File > Export > glTF 2.0, 형식 glTF Binary(.glb)로 내보내서
  이름을 character.glb로 바꿔 올리면 돼요. 크기는 자동으로 맞춰요.
  부위 이름(Jelly_Body, Jelly_Arm_L/R, Jelly_Foot_L/R, Jelly_Eye_L/R, Jelly_Cheek_L/R)을
  유지하면 동작도 그대로 붙어요.

[크기]
  index.html 안의 AR_SIZE = 0.25 (숫자를 키우면 커져요)
