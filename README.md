# ML-for-Education

교육학 머신러닝 수업을 위한 학생 성취도 및 학습 행동 데이터셋

## 개요

이 레포지토리는 **교육학 머신러닝** 수업에서 활용하기 위한 학생 학습 행동 및 성취도 데이터셋을 포함합니다. 원본 데이터셋을 기반으로 교육 목적에 맞게 변형(가공)한 데이터를 제공합니다.

## 데이터셋 정보

| 항목 | 내용 |
|------|------|
| 원본 데이터셋 | Student Performance and Learning Behavior Dataset |
| 원저작자 | Kamal Najem (Mohammed V University) |
| 원본 출처 | [Zenodo (DOI: 10.5281/zenodo.16459132)](https://zenodo.org/records/16459132) |
| 원본 라이선스 | [CC BY 4.0 (Creative Commons Attribution 4.0 International)](https://creativecommons.org/licenses/by/4.0/) |
| 레코드 수 | 14,003건 |
| 변수 수 | 16개 |

## 원본 변수 목록

| 변수명 | 설명 |
|--------|------|
| StudyHours | 주당 학습 시간 |
| Attendance | 출석률 (%) |
| Resources | 학습 자원 접근 수준 |
| Extracurricular | 비교과 활동 참여 여부 |
| Motivation | 학습 동기 수준 |
| Internet | 인터넷 접근 여부 |
| Gender | 성별 |
| Age | 나이 |
| LearningStyle | 학습 스타일 유형 |
| OnlineCourses | 온라인 강좌 수강 수 |
| Discussions | 토론 참여 횟수 |
| AssignmentCompletion | 과제 완료율 (%) |
| ExamScore | 시험 점수 |
| EduTech | 교육 기술 활용 여부 |
| StressLevel | 스트레스 수준 |
| FinalGrade | 최종 성적 등급 |

## 폴더 구조

```
ML-for-Education/
├── README.md
├── LICENSE
├── data/
│   └── original/
│       └── merged_dataset.csv      # 원본 데이터셋
└── week01/
    └── (변형 데이터 예정)
```

## 라이선스 및 저작자표시

```
Dataset: Student Performance and Learning Behavior Dataset
Original Source: https://zenodo.org/records/16459132
Original License: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/)
Original Creator: Kamal Najem (Mohammed V University)
Changes: 교육학 수업 목적에 맞게 일부 변수 이름/구조 변경 적용
```

이 레포지토리의 데이터는 CC BY 4.0 라이선스에 따라 배포됩니다. 자유롭게 복제, 배포, 변형할 수 있으며, 상업적 이용도 가능합니다. 단, 원저작자 표시와 변경 사실 표기는 반드시 포함해야 합니다.

## 수업 정보

- **과목**: 교육학 머신러닝
- - **운영**: SJ-EduLab
  - - **학기**: 다음 학기 (2026)
