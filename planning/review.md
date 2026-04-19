# whetstone — Review (2026-04-11)

## 1. 커밋 톤이 주장을 일관되게 지지하는가?

**판정: 평가 불가 (commit 1개) — 그러나 *single import의 정합성*이 매우 높음.**

```
006579b init: The Whetstone Paradox — AI demands more education science, not less  (~2026-04-04)
```

진화 패턴:
- **t=0 (4/4)**: README + outline.md (164줄) + paper main.tex (285줄) + references.bib (446줄) + 빌드 PDF (5,399 bytes) 모두 한 번에 import. ai-bubble / aichemist / elixir / pythia / silo와 같은 *완성도 높은 외부 작품 단일 import* 패턴.

톤 일관성:
- 핵심 주장(whetstone thesis: AI transforms what/how but not why / 2 dominant responses 거부 (obsolescence + retooling) / productive friction taxonomy / structured autonomy / 3-paper trilogy: case for change → assessment crisis → invariant functions → whetstone thesis)이 README → outline → main.tex 모두에서 동일.
- *Self-balanced framing*: §1에서 obsolescence thesis와 retooling thesis 두 dominant 입장을 명시 → 둘 다 misidentify 한다고 주장 → *whetstone thesis는 third position*. 학술 paper의 표준 *Hegelian* 구조.
- **References.bib 446줄**: 본 survey 21개 paper 중 *references 가장 많은* 케이스 중 하나. OECD, UNESCO, WEF 같은 institutional reports + Mayhew innovation + Coase firm + Durkheim socialization + Bjork desirable difficulties + 다양한 empirical studies 통합.
- *Empirical anchors*가 매우 강함:
  - 86% 학생 AI 사용 미탐지 (CognitiveParadox 2025)
  - WEF 39% job skills change by 2030
  - solo founders 23.7% → 36.3% (Carta 2025)
  - 41.8M 솔로프레너, $1.3T 경제 기여
  - 2.86M 중국 1인 회사 (47% YoY 성장)
  - $80-120K/월 → $300-500/월 (95-98% reduction)
  - 67% 신입 개발자 job postings 감소 (2022-2026)
  - GPA-innovation inverse correlation (Mayhew 2012)
- *cross-repo synergy*: 다른 repo와 명시적 인용 없음 (whetstone이 *standalone* 케이스).

## 2. 부가 서비스 품질

**판정: 부가 서비스 0개. paper만.**

레포 구성:
- `paper/main.tex` (285줄), `paper/references.bib` (446줄), `paper/main.pdf` (5,399 bytes — 매우 작음, 빌드 정상 여부 확인 필요)
- `outline.md` (164줄)
- `README.md`, `.zenodo.json`, `.gitignore`

코드, 데이터, instrument, 노트북, 데모, 서비스 — *전무*. position paper / critical synthesis 단독.

특이점:
- main.pdf가 5,399 bytes로 *매우 작음*. 빌드 실패 또는 *placeholder*일 가능성 있음. 정상 paper PDF는 보통 100KB+. 본 survey 다른 paper들의 빌드 PDF는 수십~수백 KB.
- references.bib(446줄)이 main.tex(285줄)보다 *훨씬 큼*. *literature integration*이 paper의 가장 강한 자산.
- TODO.md 미존재 — 다른 paper들이 모두 갖춘 TODO 트래커 없음.

## 3. 고도화 가능 파트

높은 우선순위:
1. **PDF 빌드 검증** — main.pdf가 5,399 bytes로 의심스럽게 작음. 정상 컴파일됐는지 확인. references.bib의 446줄이 모두 cite되는지 검증.
2. **Productive friction taxonomy의 *형식 분류표*** — paper §4의 핵심 contribution이 *어떤* friction이 productive인지 elimination인지 구분. 1쪽 매트릭스 (cognitive struggle / social negotiation / failure recovery / vs bureaucratic / arbitrary / credential).
3. **Empirical case study 1-2개** — paper가 *모든* 통계를 secondary citation. 한 case study(예: 한국 코딩 부트캠프 폐원 현상, 또는 미국 GA 폐쇄)를 first-person으로 분석한 1쪽 추가.
4. **Structured autonomy framework의 *operational definition*** — §4의 design principle이 sketch 수준. 어떤 *교육 활동*이 structured autonomy인지 case study 2-3개.
5. **Internal review** — README의 status가 [x] First draft → [ ] Internal review. 다른 사람의 검토 받기. independent researcher 단독 약점 보강.

중간 우선순위:
6. **Bjork desirable difficulties 인용 강화** — paper의 *foundational theory*. §3의 invariant functions를 더 강하게 정착.
7. **AI-induced cognitive decline empirical evidence** — META 2025 RCT, Microsoft Research, Stanford 등의 연구 인용. *productive friction의 정당화*가 더 강해짐.
8. **OECD/UNESCO/WEF 비교표** — 3 institutions의 권고가 어떻게 *diverge*하는지 1쪽 비교표. paper §2.1 강화.
9. **Coase 1937 → 2026 firm dissolution 매핑** — economic theory의 educational paradigm 함의. paper §2.2 강화.
10. **한국/중국 솔로프레너 데이터 강화** — 41.8M US, 2.86M China new registrations. cross-cultural empirical anchor.

낮은 우선순위:
11. arXiv preprint.
12. 한국어 abstract.
13. 5 venue 우선순위 결정.

## 4. 학술적 / 시장 가치 (글로벌, 2026-04-11 기준)

### 학술적 가치: **상위권 (working paper 기준 top ~15%, AI in education critique 한정 시 top ~10%)**

차별점:
- **Whetstone thesis naming**: 인용 가능한 새 명제. *AI removes friction indiscriminately, education science distinguishes which friction sharpens vs damages*. 1-line summary로 인용 surface area 강함.
- **Two-thesis rejection (obsolescence + retooling)**: 기존 두 dominant 입장을 *동시에* 거부하는 third position. 학술적 contribution 명료.
- **OECD + UNESCO + WEF 통합**: 세 institutional report를 한 paper에 통합한 사례 드물다. *institutional consensus + divergence* framing이 강함.
- **Economic theory bridge (Coase 1937 → 2026 firm dissolution)**: educational pipeline의 *destination 자체가 사라진다*는 강한 명제. *retooling thesis의 self-defeating nature*를 입증.
- **Productive friction taxonomy**: Bjork desirable difficulties + Durkheim socialization + Bjork + 본 paper의 새 분류. theoretical synthesis가 깊음.
- **Mayhew 2012 GPA-innovation inverse correlation**: paper가 인용 가능한 *strong empirical anchor*. assessment crisis section의 anchor.
- **2026 핫 데이터**: 67% 개발자 job 감소, 86% 학생 AI 사용, $80K → $500/월 비용 감소. 시의성 매우 강함.
- **Coding bootcamp 몰락 case**: General Assembly / App Academy / Hack Reactor 명시. *retooling thesis의 실패*를 visceral하게 입증.

위험:
- **Position paper / critical synthesis** — empirical 0건. 학술 venue에 따라 *empirical contribution 부족*으로 reject 가능.
- **PDF 5,399 bytes 의심** — main.pdf가 정상 컴파일됐는지 의심.
- **Independent researcher 단독 저자** — 교육 영역. educational research community의 명성 가중치 강함.
- **Productive friction 정의의 *경계 모호***: 어떤 friction이 productive인지 구분 기준이 *theoretical*. *operationalize* 어려움. reviewer가 짚을 수 있음.
- **5 venues 후보 명시했지만 *primary venue 선택* 부재**: README가 5개 후보를 list만 함. 어디를 1순위로 할지 결정 필요.

게재 전망:
- *Postdigital Science and Education* (Springer): **realistic, 50-60%**. critical AI in education 트랙에 적합.
- *AI & Society* (Springer, IF 4.7): **55-65%**.
- *British Journal of Educational Technology* (Wiley, IF 6.7): **40-50%**. empirical 부족이 약점.
- *Computers & Education* (Elsevier, IF 12.0): **30-40%**. top venue, empirical 강조.
- *ECNU Review of Education* (SAGE, IF 1.2): **65-75%**. 진입 가장 쉬움.
- *Studies in Higher Education* (Routledge): **40-50%**.
- *Higher Education* (Springer, IF 4.0): **40-50%**.

### 시장 가치: **상위 (교육 정책 + edtech 회사에서 매우 강함)**

- **Edtech 회사**: Khan Academy, Duolingo, Coursera, edX, Udacity, MasterClass 등이 *AI tutor* feature를 정당화/비판하는 학술 anchor로 사용. 본 paper의 *productive friction* taxonomy는 product design guideline으로 사용 가능.
- **교육 정책**: OECD, UNESCO, WEF 자체가 *재인용*할 가능성. EU Digital Education Action Plan, 한국 교육부 AI 기본법 정책에 인용 가능.
- **언론**: NYT/Atlantic/Wired/WSJ가 좋아할 톤. "AI는 교육을 죽이지 않는다 — 더 강하게 만든다" 헤드라인. viral potential 매우 강력.
- **고등교육**: 미국/한국/중국의 대학 administration이 *AI 정책 수립*에 인용 가능. 최근 ChatGPT 사용 정책 논쟁의 anchor.
- **기업 교육 / L&D**: 기업의 internal training program 재설계. McKinsey, Deloitte, BCG 같은 컨설팅의 자료로 사용.
- **K-12 교육 정책**: 한국 교육부, 미국 ED, OECD PISA에 인용. 시의성 정점.
- **언론/시민사회**: Future of Life Institute, AI Now Institute의 *AI literacy* 자료.

### 종합 평점 (2026-04-11)

| 축 | 점수 | 코멘트 |
|---|---|---|
| Originality of construct | 8/10 | whetstone thesis + two-thesis rejection + productive friction |
| Theoretical synthesis | 9/10 | Coase + Durkheim + Bjork + OECD/UNESCO/WEF |
| Empirical contribution | 2/10 | 0개. secondary citation 일색 |
| Literature integration | 9/10 | 446줄 references 매우 풍부 |
| Self-criticism | 7/10 | dimensional 거부 + 두 thesis 거부 |
| Repo health | 4/10 | 1 commit, no service, PDF 의심 |
| Submission readiness | 6/10 | LaTeX 빌드 의심, internal review 미진행 |
| Cross-repo synergy | 3/10 | standalone, 다른 paper 인용 없음 |
| Practical applicability | 9/10 | edtech + 교육 정책 즉시 사용 |
| Timing | 10/10 | 2026 코딩 부트캠프 몰락 + AI literacy 정점 |
| **Overall (working paper)** | **7.0/10** | "Internal review + empirical case study 1개만 추가하면 8.0+로 점프" |

핵심 격언: **"Position paper로서 잘 쓰였지만 *internal review + 1 case study + PDF 빌드 검증* 셋이 시급."** 본 survey 21개 paper 중 *AI in education critique*는 unique niche. references.bib 446줄의 literature integration이 paper의 가장 강한 자산. *Whetstone thesis*는 즉시 인용 가능한 1-line 명제. timing이 매우 강함 — 코딩 부트캠프 몰락 + WEF 2025 + 솔로프레너 폭증 모멘텀.
