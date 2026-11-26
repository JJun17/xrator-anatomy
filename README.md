# xrator-anatomy

X-rator(엑스레이 촬영 실습 3D 시뮬레이터)가 실행할 때 내려받는 해부 데이터입니다.
3D 실습실의 팬텀과 결과 영상(DRR) 계산에 쓰입니다.

| 파일 | 사용하는 검사 |
|---|---|
| `headneck.json` | 머리뼈 가쪽방향·Waters, 목뼈 AP·가쪽방향 |
| `thorax.json` | 가슴 PA·AP·가쪽방향·전만 |
| `shoulder.json` | 어깨 AP (투명 수지 어깨 팬텀) |
| `abdomen.json` | KUB, 허리뼈 AP |
| `hand.json` | 손 PA |
| `knee.json` | 무릎 AP·가쪽방향 |

## 출처 (License)

BodyParts3D, © The Database Center for Life Science licensed under CC Attribution 4.0 International
(https://dbarchive.biosciencedbc.jp/en/bodyparts3d/)

변경 사항: 원본 표면을 닫힌 표면으로 다시 만들고 단순화·좌표 변환했습니다.
허파·코곁굴·기도 공기와 위·대장 가스는 교육용으로 합성한 형태이며, 일부 뼈는 팬텀 경계에서 잘랐습니다.
