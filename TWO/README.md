# TWO

이 프로젝트는 https://twitter.com/ahastudio/status/1148550948018458624 트윗에 따른 도메인을 수정한 버전입니다.

## 도메인 정의

수행평가 관리 프로그램

## 기능적 요구사항

- 수행평가 일정을 알 수 있다.
- 수행평가에 들어가는 항목을 알 수 있다.
- 자신만의 수행평가 완료 리스트를 만들 수 있다.
- 수행평가가 아닌 과제들을 알 수 있다.
- 어떤 과목이 있는지 시간표를 알 수 있다.

## 유비쿼터스 언어 정의

- 학생 : 수업을 듣는 주체. 학년, 반, 번호의 고유한 값을 갖고있다.
- 수업 : 학생에게 어떠한 내용을 전달한다. 선생님 1명 이상이 수업을 진행한다. 학생이 수업을 들으면 출석상태로 기록된다.
- 교과목 : 수업을 듣는 주제. 과목마다 선생님이 있고 수행평가가 1개 이상 존재한다.
- 교과성적 : 교과목의 성적. 교과목의 성적은 수행평가와 시험이 있다면 시험을 포함하여 사전에 정해둔 규칙을 통하여 계산한다.
- 수행평가 : 내신에 들어가는 학생 평가 내역. 과제형, 체크형이 있으며 특정 날짜가 되면 수행평가가 확정된다. 수행평가는 수업에 종속적이며 수업을 듣는 모든 학생은 수행평가의 대상이다.
- 내신 : 학교에서 학생의 학업 성취도를 평가하는 주체이다. 내신은 한 학생이 듣는 모든 교과성적을 포함한 값이다.
- 전공 : 마이스터고등학교에서 2학년에 선탁해는 커리큘럼 방향. 전공과목의 경우 전공에 따라 과목의 내용이 바뀐다.
- 출석 : 수업에 참가한다면 출석으로 인정이 됩니다. 출석을 어느정도 해야 졸업/진급할 수 있습니다.
- 준비물 : 수업의 진행에 필요한 물건이며 학생이 준비해야 하는 물건이다. 수업전에 소지하고있어야 한다.
- 교과서 : 수업마다 1개씩 있는 책이다. 교과목과 관련된 내용이 수록되어있다.