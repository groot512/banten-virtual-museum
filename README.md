# 반튼 술탄국 버추얼 박물관 · 홈페이지 시안 (v0.1)

Museum Virtual Kesultanan Banten: 첫페이지(입구 홀) 시안, 에셋, 홈페이지 구축계획서.

- 시안 페이지: https://groot512.github.io/banten-virtual-museum/
- 상태: 내부 검토용 초안. 사료 고증·현지 감수 전이며 검색엔진 비노출(noindex).

## 구성

| 경로 | 내용 |
|---|---|
| `index.html` | 첫페이지 시안 (히어로, 3관 입구, 연표, 유물, 360° 비교, 안내도, 조감도) |
| `docs/banten-virtual-museum-build-plan-v0.1.docx` | 홈페이지 구축계획서 v0.1 (사이트맵, 첫페이지 설계, 도면, 기술 구성, 일정, 확인 필요 사항) |
| `assets/ai/` | AI 생성 이미지 4종 (웹용 JPG), `original/`에 원본 PNG |
| `assets/photos/` | Wikimedia Commons 실사 11장, `CREDITS.json`에 작가·라이선스 |
| `assets/drawings/` | 버추얼 박물관 공간 평면도, 반튼 라마 유적 배치도 (PNG, SVG) |

## 이미지 제작 방식

| 파일 | 방식 | 유의점 |
|---|---|---|
| `assets/ai/hero_ai`, `aerial_ai`, `entrance_hall_ai`, `artifact_hall_ai` | AI 생성 (OpenAI 이미지 모델) | 분위기 전달용 추정 이미지. 건축·유물 고증은 맞지 않을 수 있으며, 오픈 전 고증 CG로 교체 |
| `assets/photos/*` | 실사, Wikimedia Commons | 아래 출처·라이선스 표기 필수 |
| `assets/drawings/*` | 코드로 직접 작성 | 배치도는 OpenStreetMap 좌표 기준 위치도(경계·해안선 없음), 평면도는 가상 공간 개념안 |

## 사진 출처

- 반튼 대사원 첨탑: Tito Tri Kadafi, CC BY 4.0
- 대사원 첨탑(야경), 대사원 내부: Wibowo Djatmiko (Wie146), CC BY-SA 4.0
- 대사원 정면·정문, 스로소완 궁 터, 카이본 궁 터, 스페일베이크 요새, 타시카르디 호수: Arif Permana Putra, CC BY-SA 4.0
- 키 아묵 대포(옛 사진): G.F.J. Bley, KITLV, CC BY 4.0
- 좌표: © OpenStreetMap contributors

각 파일의 원본 페이지 URL은 `assets/photos/CREDITS.json` 참고.
