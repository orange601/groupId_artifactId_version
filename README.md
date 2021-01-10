# groupId_artifactId_version
Maven의 groupId 와 artifactId, 그리고 version

### groupId
* groupId는 당신의 프로젝트를 모든 프로젝트 사이에서 고유하게 식별하게 해 주는 것이다.
* 따라서, groupId에는 네이밍 스키마를 적용하도록 한다.
  - groupId는 package 명명 규칙을 따르도록 한다.
  - 즉, 최소한 당신이 컨트롤하는 도메인 네임이어야 한다.
  - 하위 그룹은 얼마든지 추가할 수 있다.
  - 예: org.apache.maven, org.apache.commons
* 프로젝트 구조를 사용하면 잘 구분되는 groupId를 만들 수 있다.
  - 현재 프로젝트가 다중 모듈 프로젝트라면, 부모 groupId에 현재 프로젝트의 식별자를 추가하는 방식.
  - 예: org.apache.maven, org.apache.maven.plugins, org.apache.maven.reporting

### artifactId
* artifactId는 버전 정보를 생략한 jar 파일의 이름이다.
  - 이름은 원하는 것으로 아무거나 정해도 괜찮다.
  - 단, 소문자로만 작성하도록 한다.
  - 단, 특수문자는 사용하지 않는다.
* 만약 써드 파티 jar 파일이라면, 할당된 이름을 사용해야 한다.
  - 예: maven, commons-math
