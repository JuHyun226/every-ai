# every-ai

## 프로젝트 소개
이 프로젝트는 AI를 활용해 전략적 의사결정을 시뮬레이션하기 위한 개인 오픈소스 프로젝트입니다

시장 진입, 신사업 검토, 수익성 개선, 경쟁 대응과 같은 전략 과제를 여러 시나리오로 나누고, 각 선택지의 기대효과, 리스크, 실행 난이도를 비교하는 것을 목표로 합니다

단순히 AI에게 답을 묻는 것이 아니라, 전략 가설을 세우고 시나리오별 결과를 비교하며 더 나은 의사결정에 가까워지는 과정을 실험합니다

## 주요기능
- 전략 과제별 시뮬레이션 템플릿 제공
- Best Case / Base Case / Worst Case 시나리오 분석
- 전략 옵션별 기대효과, 리스크, 실행 난이도 비교
- KPI Driver Tree 기반 가설 검증
- AI를 활용한 전략 가설 생성 및 Red Team 검토
- 최종 추천안과 실행 우선순위 정리

# 사용방법
1. 레포지토리 다운로드

```bash
git clone https://github.com/your-username/every-ai.git
cd every-ai
```

2. 프로젝트 구조 생성

```bash
mkdir scenarios simulations prompts outputs notes
```

예시 구조는 다음과 같습니다

```bash
every-ai/
├── scenarios/
├── simulations/
├── prompts/
├── outputs/
├── notes/
└── README.md
```

3. 전략 과제 작성

`scenarios/` 폴더에 시뮬레이션할 전략 과제를 작성합니다

```markdown
# Strategy Case

## Situation
국내 AI SaaS 기업이 B2B 시장으로 확장하려고 한다

## Objective
3년 내 매출 성장을 극대화할 진입 전략을 선택한다

## Strategic Options
1. 대기업 대상 엔터프라이즈 영업
2. 중소기업 대상 셀프서브 SaaS
3. 특정 산업군 특화 Vertical AI 솔루션
4. 파트너사와 공동 GTM
```

4. 시나리오 분석

각 전략 옵션을 Best Case, Base Case, Worst Case로 나누어 검토합니다

```markdown
# Scenario Simulation

## Option 1. Enterprise Sales

### Best Case
대기업 고객을 빠르게 확보해 높은 계약 단가로 매출을 성장시킨다

### Base Case
PoC는 진행되지만 실제 계약 전환까지 시간이 오래 걸린다

### Worst Case
영업 사이클이 길고 커스터마이징 비용이 커져 수익성이 악화된다
```

5. AI 프롬프트 실행

```markdown
You are a strategy consultant.

Compare the strategic options based on:
1. Revenue impact
2. Cost requirement
3. Execution difficulty
4. Key risks
5. Required data
6. Scenario where this strategy would fail

Then recommend the best option.
```

6. 최종 추천안 작성

`outputs/` 폴더에 시뮬레이션 결과와 최종 전략을 정리합니다

```markdown
# Final Recommendation

## One-line Answer
문제의 핵심은 단순히 시장을 넓히는 것이 아니라, 가장 높은 승산을 가진 고객 세그먼트에서 반복 가능한 성장 공식을 찾는 것입니다

## Recommended Strategy
Vertical AI 솔루션을 우선 개발하고, 특정 산업군의 명확한 업무 문제를 해결하는 방식으로 진입합니다

## Key Risks
- 초기 산업 선택이 잘못될 수 있음
- 고객별 커스터마이징 요구가 커질 수 있음
- 데이터 접근성과 업무 이해도가 병목이 될 수 있음

## Next Step
1. 산업별 pain point 조사
2. 고객 인터뷰 진행
3. PoC use case 선정
4. 매출 및 비용 구조 시뮬레이션
```

# 라이선스
MIT License
