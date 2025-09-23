1. HTML5 문서 구조화

기존 HTML 한계: <div>, <table> 사용 → 구조 파악 어려움

문서 구조화 이유:

검색 엔진 최적화(SEO)

사물인터넷 시대의 정보 탐색 필요

시맨틱 웹: 의미 있는 구조화로 탐색 용이

주요 시맨틱 태그

<header>: 머리말, 제목, 소개

<nav>: 내비게이션, 목차

<section>: 문서의 장/절

<article>: 독립적 콘텐츠(게시글, 기사, 댓글 등)

<aside>: 본문과 직접 관련 없는 노트, 팁

<footer>: 저자/저작권 등 꼬리말

기타: <figure>, <figcaption>, <details>, <summary>, <mark>, <time>, <meter>, <progress>

특징

시맨틱 태그 자체는 모양을 정하지 않음 → CSS로 스타일링 필요

권장 구조:

전체 제목/소개: <header>

본문: <section> + <article>

메뉴: <nav>

보조 정보: <aside>

하단 정보: <footer>

2. 시맨틱 태그 활용 예시

<figure>: 그림/소스코드/차트와 설명 묶음

<details> + <summary>: 접고 펼치는 상세 정보

인라인 태그:

<mark>: 중요 텍스트 강조

<time>: 시간 정보

<meter>: 비율/수치 범위

<progress>: 진행 상황 표시

3. HTML5에서 제거된 태그

<big>, <center>, <font>, <u>, <strike> 등
→ 의미 없는 시각적 태그는 제거됨 (시맨틱 구조 저해)

4. 웹 폼(Form)

사용자 입력을 받는 요소

활용: 로그인, 검색, 등록, 쇼핑, 예약 등

<form> 태그

속성:

name: 폼 이름

action: 데이터 처리할 서버 주소

method: 전송 방식 (GET, POST)

주요 입력 요소

텍스트 입력

<input type="text">: 한 줄

<input type="password">: 비밀번호

<textarea>: 여러 줄

<input type="email|url|tel|search">: 형식 검증 있는 입력

placeholder: 힌트 텍스트

선택 입력

<input type="checkbox">: 다중 선택

<input type="radio">: 단일 선택 (같은 name 그룹)

<select><option>: 콤보박스

<datalist>: 자동완성 목록

버튼

<input type="button|submit|reset|image">

<button type="...">

색/시간/숫자 입력

<input type="color">: 색상

<input type="date|time|month|week|datetime-local">: 시간 정보

<input type="number">: 스핀 버튼

<input type="range">: 슬라이더

그룹화

<fieldset>: 폼 요소 묶음

<legend>: 그룹 제목

<label>: 입력 요소 캡션 연결 (텍스트 클릭해도 입력 선택됨)

5. 핵심 요약

HTML5는 의미(시맨틱)를 강조하는 구조적 태그 제공

문서의 모양은 CSS로, 구조는 시맨틱 태그로 분리

웹 폼은 다양한 입력 방식을 제공하여 사용자와 상호작용 구현

제거된 구식 태그는 사용 금지, 시맨틱 태그로 대체해야 함
