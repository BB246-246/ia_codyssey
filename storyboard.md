# 스토리보드(기획)

**캠페인 목표/핵심 메시지:** “ 크록스를 신는 순간, 하루가 시작된다 ”

## 브랜드 아이덴티티
- **브랜드명:** Crocs Kids
- **타겟:** 아동청소년(스포티/에너제틱)
- **톤앤매너:** 자유로움, 햇살, 역동적
- **USP:** 편안함, 활기찬 에너지, 컬러풀함.
- **핵심 메시지:** 크록스를 신으면 하루가 시작된다

## 사용 모델
- **이미지 생성:** GPT image 2.0
  - **선정 이유:** 광고의 의도에 맞게 가장 자연스러운 실사 이미지를 출력함.
- **이미지 기반 비디오 생성:** Google veo 3.1, Omni flash, Canva AI 2.0
  - **선정 이유:** 출력물의 퀄리티가 일률적인 Google veo와 무료 토큰이 주어지는 Omni flash를 이용하려 했으나 광고의 특성(아동 청소년이 등장)상 구글의 컨텐츠 심의 규정에 걸려 둘 다 이미지로 영상 생성이 불가능한 관계로 무료 토큰이 주어지고, 심의 규정 차단을 하지 않는 canva AI를 대안으로 결정.
- **비디오 생성:** sora 2
  - **선정 이유:** veo 등 타 모델에 같은 작업을 시키고 비교한 결과, 사진 기반의 영상은 veo가 우수했으나 무에서 유를 창조하는 영상 작업의 경우 가장 요구사항을 잘 준수하고 의도한 팝 스프링클 연출을 잘 뽑아낸 sora로 모델을 결정했다.
- **효과음 생성:** Suno ai music
  - **선정 이유:** 낮은 접근성, 무료로 동시에 다양한 시안을 뽑아낼 수 있어 선정.
  - **대안:** ElevenLabs
- **편집 툴:** Canva(씬 통합, 간단한 자막 작업)

---

## 씬별 필수 필드(모든 씬 공통):

### #1 / 4초
- **메시지:** 크록스를 신는 순간 오늘의 모험이 시작된다
- **설명:** 한 어린이가 크록스에 발을 넣고 현관문을 개방. 문이 열리는 순간 햇빛이 쏟아짐. 크록스를 신고 현관문을 여는 장면의 배경은 집 신발장.
- **내레이션:** x
- **사용 도구(이미지/비디오/오디오)와 사용 목적:**
  - GPT image 2로 생성한 이미지를 기반으로 veo로 모션 효과를 주어 제작한다.
  - Suno로 제작한 트로피컬 하우스 장르의 상업용 연주곡 오디오
- **오디오 프롬프트:** Bright tropical house at 100–110 BPM with sidechained four-on-the-floor kick, crisp offbeat clap, marimba and steel-drum plucks, airy synth pads, and a warm sub-bass pulse, Pop-ad-friendly hook, glossy vocal chop accents, clean EDM risers, polished radio-ready mix, playful commercial sheen.
- **입력 프롬프트(원문) + 출력 결과 요약(한 줄):**
  - **GPT image 2:** 한 어린이가 지비츠가 달린 노란색 crocs를 자신의 집 현관에 앉아서 신고 있는 중의 이미지를 생성해 줘. 앵글은 crocs를 신고 있는 발 부분만 카메라의 시선과 일치하는 높이로 보여줘. 배경은 여름이라서 아이가 맨발에 크록스를 신고, 반바지를 입고 있어.
  - **Omni flash:** Close-up shot of yellow Crocs at the front door. Camera at ankle height. The child prepares to run. One foot steps forward. At the exact moment the foot lands, the child suddenly accelerates out of frame. Motion blur trails behind the shoes. Bright sunlight. High-energy commercial advertisement. No face visible.
- **생성 결과 파일명 또는 링크 표기:** (파일명 규칙 자유, 단 일관성 유지)
  - <img width="480" height="480" alt="Image" src="https://github.com/user-attachments/assets/11c75ad0-7477-408e-8850-ebdae8536952" />
- **프롬프트 수정 이력 및 이유:**
  - **수정 전:** 한 어린이가 노란색 crocs를 자신의 집 현관에서 신고 있는 중의 이미지를 생성해 줘. 앵글은 crocs를 신고 있는 발 부분만 보여줘.
  - **수정 후:** 한 어린이가 지비츠가 달린 노란색 crocs를 자신의 집 현관에 앉아서 신고 있는 중의 이미지를 생성해 줘. 앵글은 crocs를 신고 있는 발 부분만 카메라의 시선과 일치하는 높이로 보여줘. 배경은 여름이라서 아이가 맨발에 크록스를 신고, 반바지를 입고 있어.
  - **변경사항 및 이유:** 유저의 포괄적이고 모호한 요구로 인해, GPT가 겨울 옷을 입고, 밋밋한 노란색 크록스를 신고 신발장에 서 있는 어린아이의 사진을 하이앵글로 출력함. 광고에서 의도한 스포티, 컬러풀, 활동적임, 하루를 시작하는 컨셉과 맞지 않아 구체적인 요구사항을 프롬프트에 추가함.
- **프롬프트 수정 전후 결과 비교:**

| 수정 전 | 수정 후 |
| :---: | :---: |
|<img width="240" height="240" alt="Image" src="https://github.com/user-attachments/assets/5c2347af-72bb-40f1-bc29-a2cd983e846f" />|<img width="240" height="240" alt="Image" src="https://github.com/user-attachments/assets/11c75ad0-7477-408e-8850-ebdae8536952" />|

### #2 / 4~5초
- **메시지:** 가볍고 편해서 어디든 갈 수 있음
- **화면 구성:** 문을 열자마자 자전거 타는 아이, 점프하는 아이, 보드를 타는 아이 등이 빠른 컷 편집으로 넘어감. 시야각은 발 위주, 날씨가 화창하고 모두 크록스를 신고 있음.
- **카피:** RUN. PLAY. REPEAT. (화면 중앙)
- **사용 도구(이미지/비디오/오디오)와 사용 목적:**
  - GPT image 2로 생성한 이미지를 기반으로 veo로 모션 효과를 주어 제작한다.
- **입력 프롬프트(원문) + 출력 결과 요약(한 줄):**
  - **GPT image 2:** 햇살 아래의 공원길에서 자전거를 타는 어린이, 달려가는 자세의 어린이 두 명이 모두 크록스를 신고 있다. 크록스의 색깔은 각각 다르다. 카메라 앵글은 크록스 신발이 주 요소가 되도록 앵글을 신발 위주로 조명한다. 사진 속의 어린이들은 모두 움직이던 도중 찍힌 듯한 자연스러운 자세를 하고 있으며 앞으로 가던 도중의 모습이고, 카메라는 아이들의 뒷쪽에서 비정형적인 구도로 아이들을 찍고 있다.
  - **Canva AI 2.0:** Tracking shot of children running through a sunny park while wearing colorful Crocs. The camera follows behind at foot level. Footsteps feel light, energetic, and playful. Sunlight shines through the trees. As the sequence approaches the end, one child kicks a small amount of dust and tiny pebbles from the path. The camera follows the motion downward. The kicked particles briefly fill the frame. The camera continues tilting toward the ground until the frame becomes completely dark.
- **생성 결과 파일명 또는 링크 표기:** (파일명 규칙 자유, 단 일관성 유지)
  - <img width="480" height="480" alt="Image" src="https://github.com/user-attachments/assets/ec8e1588-e7e2-487f-b29f-4ef76e440860" />

### #3 / 3초
- **목표 메시지:** 마음껏 뛰어도 좋다
- **화면 구성:** 아이 2명이 크록스를 신고 마구잡이로 뛰노는 모습을 발만 보여준다. 한 명이 발로 모래를 걷어차고, 모래를 맞은 카메라가 그대로 암전된다.
- **내레이션:** x
- **사용 도구(이미지/비디오/오디오)와 사용 목적:**
  - GPT image 2로 생성한 이미지를 기반으로 veo로 모션 효과를 주어 제작한다.
- **입력 프롬프트(원문) + 출력 결과 요약(한 줄):**
  - **GPT image 2:** 뜨거운 햇살이 내리쬐는 바닷가 모래사장에서 남자아이와 여자아이가 둘 다 지비츠가 붙은 크록스 신발을 신고 뛰놀며 장난치는 이미지. 각각 다른 색상의 크록스를 신고 있다. 카메라는 신발을 부분을 조명하고 있고 아이들의 얼굴은 보이지 않음. 주의해야 할 요소는 모래사장, 크록스, 당장이라도 모래를 걷어찰 듯이 활기차게 뛰노는 동작이다.
  - **Canva AI 2.0:** The children are running around playing with each other when one of them kicks the camera into the sand, burying it and causing the lights to go out. The camera keeps concentrating only on the shoes.
- **생성 결과 파일명 또는 링크 표기:** (파일명 규칙 자유, 단 일관성 유지)
  - <img width="480" height="480" alt="Image" src="https://github.com/user-attachments/assets/b2db3d19-30b0-4c05-a2df-e58dd9d1879a" />

### #4 / 4~5초
- **메시지:** 자유로운 어린이 에너지
- **화면 구성:** 암전되어있는 화면에 파티클이 터지고 크록스 키즈 로고가 뜬다. 밝은 컬러로 굵은 카피가 뜬다.
- **카피:** PLAY YOUR WAY (화면 중앙)
- **사용 도구(이미지/비디오/오디오)와 사용 목적:**
  - Sora 2로 암전된 화면에서 팝시클을 터트리는 연출의 배경 비디오 - 카피와 로고를 강조하기 위한 배경 효과.
  - 팡파레 효과음. 활기차고 에너제틱한 느낌을 주기 위해.
- **입력 프롬프트(원문) + 출력 결과 요약(한 줄):**
  - **Sora 2:** Black screen. A burst of colorful floating shapes and playful childhood imagination explodes from the center. Yellow, sky blue, green, and pink particles spread across the screen. Dynamic motion, cheerful energy, freedom and fun. The particles gradually settle and create a clean central area for brand logo placement. Just particles, no humans. Premium children's lifestyle commercial. Bright, colorful, energetic, modern motion graphics. Smooth animation.
  - **출력 결과:** 검은 바탕에 컬러풀한 파티클이 중앙에서부터 뻗어져나오는 4초의 영상
