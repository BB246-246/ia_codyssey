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
- **프롬프트 수정 이력 및 이유:**
  - **수정 전:** 한 어린이가 노란색 crocs를 자신의 집 현관에서 신고 있는 중의 이미지를 생성해 줘. 앵글은 crocs를 신고 있는 발 부분만 보여줘.
  - **수정 후:** 한 어린이가 지비츠가 달린 노란색 crocs를 자신의 집 현관에 앉아서 신고 있는 중의 이미지를 생성해 줘. 앵글은 crocs를 신고 있는 발 부분만 카메라의 시선과 일치하는 높이로 보여줘. 배경은 여름이라서 아이가 맨발에 크록스를 신고, 반바지를 입고 있어.
  - **변경사항 및 이유:** 유저의 포괄적이고 모호한 요구로 인해, GPT가 겨울 옷을 입고, 밋밋한 노란색 크록스를 신고 신발장에 서 있는 어린아이의 사진을 하이앵글로 출력함. 광고에서 의도한 스포티, 컬러풀, 활동적임, 하루를 시작하는 컨셉과 맞지 않아 구체적인 요구사항을 프롬프트에 추가함.
