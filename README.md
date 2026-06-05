# every-ai
Make every ai into my workflow

## 프로젝트 소개
이 프로젝트는 다양한 AI 도구와 프롬프트를 실제 업무 흐름에 연결하기 위한 개인 워크플로우 실험 레포지토리입니다.
ChatGPT, Claude, Gemini, Perplexity, Cursor 등 여러 AI 도구를 단순히 따로 사용하는 것이 아니라, 리서치, 문서 작성, 데이터 정리, 아이디어 구조화, 코드 작성, 회고까지 하나의 작업 흐름 안에서 자연스럽게 활용하는 것을 목표로 합니다.
즉, every-ai는 “AI를 더 많이 쓰는 것”이 아니라, “AI가 내 업무 방식 안에서 더 잘 작동하게 만드는 것”을 위한 프로젝트입니다.

## 주요기능
- 여러 AI 도구의 활용 목적과 사용 방식 정리
- 업무 유형별 프롬프트 템플릿 관리
- 리서치, 문서 작성, 데이터 분석, 코드 작성 워크플로우 설계
- 반복 작업을 줄이기 위한 자동화 아이디어 정리
- AI 활용 과정에서 얻은 실험 결과와 개선점 기록

# 사용방법
1. 레포지토리 다운로드

```bash
git clone https://github.com/your-username/every-ai.git
cd every-ai
```

2. 프로젝트 구조 확인

```bash
ls
```

예시 구조는 다음과 같습니다

```bash
every-ai/
├── prompts/
├── workflows/
├── scripts/
├── notes/
└── README.md
```

3. 필요한 폴더 생성

처음 사용하는 경우 아래와 같이 기본 폴더를 만들 수 있습니다

```bash
mkdir prompts workflows scripts notes
```

4. 업무 유형별 프롬프트 작성

예를 들어 리서치용 프롬프트는 `prompts/research.md`에 작성합니다

```bash
touch prompts/research.md
```

5. 워크플로우 문서 작성

반복적으로 사용하는 업무 흐름은 `workflows/` 폴더에 정리합니다

```bash
touch workflows/report-writing.md
touch workflows/data-analysis.md
touch workflows/coding-assistant.md
```

6. 자동화 스크립트 실행

반복 작업을 자동화하고 싶은 경우 `scripts/` 폴더에 코드를 작성한 뒤 실행합니다

```bash
python scripts/example.py
```

7. 작업 기록 남기기

AI를 사용하면서 얻은 결과, 실패 사례, 개선점을 `notes/` 폴더에 기록합니다

```bash
touch notes/experiment-log.md
```

8. 변경사항 저장

작업한 내용을 Git에 저장합니다

```bash
git add .
git commit -m "Add initial AI workflow structure"
git push origin main
```

# 라이선스
MIT License
