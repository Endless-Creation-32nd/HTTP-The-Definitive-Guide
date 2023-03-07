<p align="center"><img width='300px' src="https://user-images.githubusercontent.com/24623403/215250157-1171a323-cef5-4e54-a5f3-258147a7597b.png"></p>
<p align='center'>
  <a href="https://github.com/Endless-Creation-32nd/HTTP-The-Definitive-Guide/issues"><img src='https://img.shields.io/github/issues/Endless-Creation-32nd/HTTP-The-Definitive-Guide'></a>
  <a href="https://github.com/Endless-Creation-32nd/HTTP-The-Definitive-Guide/pulls"><img src='https://img.shields.io/github/issues-pr/Endless-Creation-32nd/HTTP-The-Definitive-Guide'></a>
  <a href="https://github.com/Endless-Creation-32nd/HTTP-The-Definitive-Guide/graphs/contributors"><img src='https://img.shields.io/github/contributors/Endless-Creation-32nd/HTTP-The-Definitive-Guide'></a>
  <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FEndless-Creation-32nd%2FHTTP-The-Definitive-Guide&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
</p>

# HTTP: The Definitive Guide

도서<HTTP 완벽 가이드> 스터디 저장소 입니다.

<br>

## 스터디 방식

- 브랜치는 자신의 이름을 딴 브랜치로 만들고, 주마다 자신이 맡은 장 이름으로 PR을 미리 연다
- 브랜치명(자기 이름)
  - inseo
  - jeongjin
  - sangjun
  - hyorin
- PR에서 **주마다 궁금했던 점, 더 알고싶었던 점을 코멘트로 작성**하고 스터디를 하며 내용을 최종 검토한 뒤 main에 merge한다.
- **위 과정을 반복한다.**

<br>

## 인덱스

<table>
  <thead><tr><th>주제</th><th>장</th><th>담당자</th><th>상태</th></tr></thead>
  <tbody>
    <tr>
      <td rowspan="4">I. HTTP: 웹의 기초</td>
      <td>1장 HTTP 개관</td>
      <td>오정진</td>
      <td></td>
    </tr>
    <tr>
      <td>2장 URL과 리소스</td>
      <td>황인서, 이효린</td>
      <td></td>
    </tr>
    <tr>
      <td>3장 HTTP 메시지</td>
      <td>이상준, 오정진</td>
      <td></td>
    </tr>
    <tr>
      <td>4장 커넥션 관리</td>
      <td>오정진, 황인서</td>
      <td></td>
    </tr>
    <tr>
      <td rowspan="6">II. HTTP 아키텍처</td>
      <td>5장 웹 서버</td>
      <td>이상준, 이효린</td>
      <td></td>
    </tr>
    <tr>
      <td>6장 프락시</td>
      <td>이상준, 황인서</td>
      <td></td>
    </tr>
    <tr>
      <td>7장 캐시</td>
      <td>오정진, 이효린</td>
      <td></td>
    </tr>
    <tr>
      <td>8장 통합점: 게이트웨이, 터널, 릴레이</td>
      <td>이효린, 이상준</td>
      <td></td>
    </tr>
    <tr>
      <td>9장 웹 로봇</td>
      <td>황인서, 오정진</td>
      <td></td>
    </tr>
    <tr>
      <td>10장 HTTP/2.0</td>
      <td>이상준</td>
      <td></td>
    </tr>
    <tr>
      <td rowspan="4">III. 식별 인가 보안</td>
      <td>11장 클라이언트 식별과 쿠키</td>
      <td>이효린, 황인서</td>
      <td></td>
    </tr>
    <tr>
      <td>12장 기본 인증</td>
      <td>오정진</td>
      <td></td>
    </tr>
    <tr>
      <td>13장 다이제스트 인증</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>14장 보안 HTTP</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td rowspan="3">IV. 엔터티 인코딩 국제화</td>
      <td>15장 엔터티와 인코딩</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>16장 국제화</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>17장 내용 협상과 트랜스코딩</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td rowspan="4">V. 콘텐츠 발행 및 배포</td>
      <td>18장 웹 호스팅</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>19장 배포 시스템</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>20장 리다이렉션과 부하 균형</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>21장 로깅과 사용 추적</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

## 폴더 구조 및 컨벤션

- 폴더 구조
  ```
    📂 root
    - 📂 01-HTTP개관
      - 📃 README.md // README.md 파일에 정리합니다.
    - 📂 02-URL과-리소스
      - 📃 README.md // README.md 파일에 정리합니다.
    - 📂 03-HTTP메시지
      - 📃 README.md // README.md 파일에 정리합니다.
    - 📂 04-커넥션관리
      - 📃 README.md // README.md 파일에 정리합니다.
    - 📂 05-웹서버
      - 📃 README.md // README.md 파일에 정리합니다.
    ...
  ```
- 커밋 컨벤션
  - ex) [I. HTTP: 웹의 기초] 01장 HTTP개관
  - ex) [II. HTTP 아키텍처] 02장 URL과 리소스
- PR 컨벤션
  - 스쿼시 머지를 사용합니다.
  - ex) [I. HTTP: 웹의 기초] 01장 HTTP개관
  - ex) [II. HTTP 아키텍처] 02장 URL과 리소스

<br>

## 👨‍👩‍👧‍👦 팀원

<table>
  <tr align="center">
    <td>오정진</td>
    <td>이상준</td>
    <td>이효린</td>
    <td>황인서</td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/ojj1123"><img src="https://avatars.githubusercontent.com/u/33178048?v=4" width="150px" alt="오정진"/><br /></a>
    </td>
    <td align="center">
      <a href="https://github.com/Sangjun-man"><img src="https://avatars.githubusercontent.com/u/66112027?v=4" width="150px" alt="이상준"/><br /></a>
    </td>
    <td align="center">
      <a href="https://github.com/hyorish03"><img src="https://avatars.githubusercontent.com/u/108210492?v=4" width="150px" alt="이효린"/><br /></a>
    </td>
    <td align="center">
      <a href="https://github.com/sjsjsj1246"><img src="https://avatars.githubusercontent.com/u/24623403?v=4" width="150px" alt="황인서"/><br /></a>
    </td>
  <tr>
</table>
