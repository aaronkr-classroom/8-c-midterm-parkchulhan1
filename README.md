# 8-c-midterm

## 중간고사

이 시험은 **OPEN BOOK**입니다. 인터넷, 책, 노트 등을 포함한 모든 자료를 사용할 수 있습니다. 시험 중에 다른 학생과 통신하거나 다른 자료를 사용할 수 없습니다.

---

### 학생 성적 처리 프로그램

**목표:** 주어진 10개의 학생 성적을 처리하는 C 프로그램을 작성하세요. 프로그램은 다음의 기능을 포함해야 합니다:

1. 배열에 미리 저장된 10개의 학생 성적을 사용합니다 (정수형).
2. 평균 성적을 계산합니다.
3. 가장 높은 성적과 가장 낮은 성적을 찾습니다.
4. 평균보다 높은 성적과 낮은 성적을 출력합니다.
5. 성적이 60점 이상이면 "합격", 60점 미만이면 "불합격"으로 분류하고, 몇 명의 학생이 합격하고 불합격했는지 카운트합니다.
6. 함수 선언을 위한 별도의 헤더 파일을 사용합니다.

---

### 필수 요건:

1. **함수 사용:** 최소 3개의 함수를 작성하세요 (필요한 경우 추가적인 헬퍼 함수도 작성하세요):
    1. `calculate_average`: 배열을 받아 평균 성적을 반환합니다.
    2. `find_min_max`: 배열을 받아 가장 높은 성적과 가장 낮은 성적을 반환합니다.
    3. `count_pass_fail`: 배열을 받아 몇 명이 합격했는지, 몇 명이 불합격했는지 계산합니다.
2. **배열 사용:** 주어진 성적 데이터를 배열로 저장하고, 이를 처리하는데 반복문을 사용하세요.
3. **조건문 사용:** 성적을 합격/불합격으로 분류하고, 평균보다 높은 성적과 낮은 성적을 출력할 때 조건문을 사용하세요.
4. **반복문 사용:** 배열의 성적 데이터를 처리하기 위해 반복문을 사용하세요 (예: 성적 출력 및 계산 등).
5. **연산자 사용:** 비교 및 계산을 위해 관계 연산자와 산술 연산자를 적절히 사용하세요.
6. **변수 사용:** 지역 변수와 전역 변수를 적절하게 선언하고 사용하세요.
7. **헤더 파일 사용:** 함수 선언을 위한 별도의 헤더 파일(`grade_funcs.h`)을 생성하고, 이를 프로그램에서 포함하세요.
8. **배열 데이터:** 다음 정수를 학생 성적 데이터로 사용합니다.
    - `85, 70, 55, 90, 45, 60, 78, 88, 92, 49`

---

### 출력 예시:

```c
Average grade: 71.2
Highest grade: 92
Lowest grade: 45

Grades above average: 85 90 78 88 92
Grades below average: 55 45 60 49

Number of students passing: 7
Number of students failing: 3
```
