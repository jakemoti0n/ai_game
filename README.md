# ai_game

게임 + AI 실험 모음 레포입니다. 프로젝트마다 하위 폴더 하나씩 사용합니다.

## 프로젝트

| 폴더 | 설명 |
|------|------|
| [bannerlord_bridge](bannerlord_bridge/) | 배너로드 LLM 모드의 Ollama 요청을 Vertex AI(Gemini)로 중계하는 브릿지 서버 |

## 구조 규칙

- 새 프로젝트는 루트에 폴더를 하나 만들고 그 안에 코드와 README를 둡니다.
- 각 폴더의 README에 실행 방법을 적고, 위 표에 한 줄 추가합니다.
- 파이썬 의존성은 각 폴더의 `requirements.txt`에 둡니다.
