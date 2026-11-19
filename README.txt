책상 위 젤리 친구 - 웹 AR
=========================

링크: https://h71168488-oss.github.io/desk-ar-character/

[파일]
  index.html      : AR 페이지
  character.glb   : 젤리버디 모델 (블렌더에서 내보낸 파일)
  character.usdz  : (선택) 아이폰 '책상에 올려놓기'용. 없으면 페이지가 자동으로 만들어요.

[기기별]
  안드로이드 크롬 : 책상에 올려놓기(AR) / 카메라로 놀아주기
  아이폰          : 책상에 올려놓기(애플 AR, 버튼 없음) / 카메라로 놀아주기(버튼 있음)
  PC              : 같이 놀기(화면 속 3D)

[조작]
  한 번 탭   : 그 자리로 걸어가기 (캐릭터를 탭하면 쓰다듬기)
  두 번 탭   : 순간이동 (안드로이드 AR은 가운데 원 위치로)
  아래 버튼  : 점프 / 쓰다듬기 / 빙글 / 쿵 / 놀라기

[모델 바꾸기]
  블렌더에서 File > Export > glTF 2.0, 형식 glTF Binary(.glb)로 내보내서
  이름을 character.glb로 바꿔 올리면 돼요. 크기는 자동으로 맞춰요.
  부위 이름(Jelly_Body, Jelly_Arm_L/R, Jelly_Foot_L/R, Jelly_Eye_L/R, Jelly_Cheek_L/R)을
  유지하면 동작도 그대로 붙어요.

[크기]
  index.html 안의 AR_HEIGHT_M = 0.10 (10cm)
