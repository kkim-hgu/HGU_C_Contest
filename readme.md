# 2025 Handong C Contest

> [!NOTE]
> This document is also available in English. Please refer to the [HGU Contest EN](#table-of-contents-en) file.

마지막 업데이트: 2025. 12. 11.

이 코드 저장소는 2025 한동대학교 C 프로그래밍 경진대회에 대한 정보를 담고 있습니다. 대회 참가자 분들 께서는 반드시 아래 내용을 숙지하시고, 대회에 임해주시기 바랍니다.

---

## 목차
- [대회 개요](#대회-개요)
- [대회 규칙](#대회-규칙)
- [대회 웹사이트 가이드](#대회-웹사이트-가이드)
    - [계정 생성](#계정-생성)
    - [문제 풀기](#문제-풀기)
- 부록
    - [컴파일러 정보](#컴파일러-정보)
    - [문의사항](#문의사항)

---

## 대회 개요

- 대회명 : 2025 한동대학교 C 프로그래밍 경진대회
- 일시 : 2025년 12월 12일 (금) 20:00 ~ 22:00
    - 테스트 대회
        - 대회 플랫폼이 익숙하지 않은 참가자 분들을 위해 미리 연습 문제를 풀어보고 제출해볼 수 있는 테스트 대회를 진행하고 있습니다.
- 참가 대상 : 한동대학교 GLS 학부생 및 전산전자공학부 비전공자
- 대회 진행 방식 : [온라인 (https://judge.walab.info/)](https://judge.walab.info/)

---

## 대회 규칙

> [!CAUTION]
> 대회 규칙을 준수하지 않는 경우 패널티가 있을 수 있으며, 이에 따른 모든 책임은 참가자에게 있습니다.

1. 모든 문제는 C 언어로만 풀어야 합니다.

1. 1학년, 혹은 비전공자들의 C프로그래밍 능력을 평가하는 컨테스트입니다. 수업내용의 수준을 훨씬 뛰어넘는 코드는 패널티가 부여될 수 있습니다.

1. 올바르게 등록하지 않은 참가자는 대회 참가자로 인정되지 않습니다.
    - [계정 생성](#계정-생성) 가이드를 참고하여 계정을 생성해주세요.

1. 대회 기간 중에는 원하는 만큼 문제를 풀고 제출할 수 있습니다.
    - 같은 문제를 여러번 제출할 경우, 가장 먼저 정답으로 인정된 제출물만 점수로 인정됩니다.

1. 대회 기간이 종료된 경우, 코드를 제출할 수 없습니다.


1. 모든 코드 제출물 최상단에 다음과 같은 아너코드 선언 주석을 포함해야 합니다.

   ```
   /*
   * [Full Name] : <이름>
   * [Student ID] : <학번>
   * [Honor Code Pledge] : 나 <이름>은(는) 하나님과 사람 앞에서 정직하고 성실하게 코딩 테스트를 수행하겠습니다.
   */
   ```

   e.g.

   ```
    /*
    * [Full Name] : 홍길동
    * [Student ID] : 22500123
    * [Honor Code Pledge] : 나 홍길동은(는) 하나님과 사람 앞에서 정직하고 성실하게 코딩 테스트를 수행하겠습니다.
    */
    ```

1. 문제 해결을 위해 허용되는 행위와 허용되지 않는 행위는 다음과 같습니다.
    - 허용되는 행위
        - 아래 명시된 웹사이트 참고
            - 이 Github 저장소
            - [모두의 코드](https://modoocode.com/)
            - [C Documentation](https://devdocs.io/c/)
    - 허용되지 않는 행위
        - 명시된 웹사이트 이외 타 사이트 참고
        - 모든 종류의 생성형 AI, LLM 및 그에 준하는 소프트웨어 사용 (e.g. ChatGPT, Cursor, Github Copilot, etc.)
        - 타인과의 소통, 협업
        - 타인의 계정을 이용하여 대회에 참가하거나 대리 참가하는 행위
        - 하드코딩 (e.g. 문제의 정답을 코드에 직접 입력)
        - 이 외 스스로 문제를 해결하지 않거나 대회의 공정성을 해치는 모든 행위

---

## 대회 웹사이트 가이드

### 계정 생성

1. 대회 웹사이트 접속

   [대회 웹사이트 (https://judge.walab.info/)](https://judge.walab.info/)에 접속합니다.

2. 계정 생성

   <br><img width="1512" height="825" alt="Image" src="https://github.com/user-attachments/assets/144190a6-0783-4a27-877b-e87dd2d071b9" />
   
   > **대회 웹사이트에 접속하면 다음과 같은 화면이 나타납니다.**
   
   <br><img width="1510" height="825" alt="Image" src="https://github.com/user-attachments/assets/34798e4d-ce44-4f35-a17c-d00471166185" />
   
   > **웹사이트에 처음 방문한 경우, 계정을 생성해야 합니다. 우측 상단의 로그인 버튼을 클릭하여 로그인 페이지로 이동합니다.**

   <br><img width="1511" height="825" alt="Image" src="https://github.com/user-attachments/assets/bcc8556c-4bc4-42c7-8044-5162727df185" />
   
   > **하단의  `Google 계정으로 로그인` 버튼을 클릭하여 로그인합니다**

   <br><img width="1512" height="823" alt="Image" src="https://github.com/user-attachments/assets/9c82a377-cba0-46a9-8678-cb9befb1baed" />
   
   > **@handong.edu @handong.ac.kr 이메일 아닌 계정으로 로그인 진행시, 로그인이 불가능합니다.**

   <br><img width="1507" height="826" alt="Image" src="https://github.com/user-attachments/assets/3f848dfc-f228-458b-9d72-90bcc34b25af" />
   
   > **회원가입이 완료되었으면, 기본 정보를 입력합니다.**



### 문제 풀기

대회 플랫폼에서는 다음과 같은 단계로 문제를 풀고 제출하게 됩니다.

1. 대회 진입
2. 문제 선택, 문제 확인
2. 문제 풀기, 코드 실행
3. 제출
4. 다음 문제 이동

단계별로 과정을 설명하겠습니다.

#### 1. 대회 진입

<img width="1512" height="829" alt="Image" src="https://github.com/user-attachments/assets/b1a202f8-4d11-4ac3-a7fb-8ae30549ff44" />

> **메인페이지 상단의 `대회` 탭을 클릭합니다.**

<br><img width="1511" height="828" alt="Image" src="https://github.com/user-attachments/assets/3698310a-c90d-40e7-bfde-9a47964e822c" />

> **대회 목록중 참여할 대회 (2025 Handong C Contest)를 클릭하여 대회 페이지로 이동합니다.**

<br><img width="1512" height="827" alt="Image" src="https://github.com/user-attachments/assets/0d81ded3-378c-44de-a05c-f558c3d571b4" />

> **대회 페이지로 이동 이후, 클릭하여 입장합니다.**

#### 2. 문제 선택, 문제 확인

<img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/b7b9183f-b327-44ff-a258-a19aaf90f64c" />

> **좌측의 `대회 문제`를 선택하여 문제 페이지로 이동합니다.**

<br><img width="1511" height="823" alt="Image" src="https://github.com/user-attachments/assets/0c36bc3b-59e4-43b0-8e36-5ad5e2a3f917" />

> **문제를 선택하여 온라인 IDE 페이지로 이동합니다.**

<br><img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/1ae22faa-edae-46e9-97a6-19273f66b6b0" />

> **IDE 의 좌측에서 문제의 상세를 확인할 수 있습니다.**

> [!CAUTION]
> **대회 규칙을 함께 확인해 주세요.**

#### 2. 문제 풀기, 코드 실행

<img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/c1089b14-42eb-42e5-a717-727695afeb81" />

> **우측 코드 편집기에서 코드 작성을 진행합니다.**

<br><img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/e9d91fb1-9f86-4de9-a024-bbe45a0ff4c7" />

> **코드를 작성중 테스트가 필요하다면 우측 상단 실행 버튼을 눌러 테스트 진행이 가능합니다.**

<br><img width="1512" height="825" alt="Image" src="https://github.com/user-attachments/assets/fb1b5650-e5ff-43ef-9149-8744b7bbd094" />

> **테스트시 프로그램에 입력될 값을 미리 입력하여 테스트를 진행할 수 있습니다.**

<br><img width="1512" height="828" alt="Image" src="https://github.com/user-attachments/assets/f21fdff6-383a-4f72-a4cf-6a980d0f32fe" />

> **`샘플` 란을 클릭하여 문제 설명에 표기되어있는 입력 예시 값을 가져올 수 있습니다.**

#### 3. 제출

<img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/395f63c1-a5e4-4a58-bdcb-0451bf8beb23" />

> **코드 작성이 완료되었다면, 우측 상단의 제출 버튼을 클릭하여 제출합니다.**


결과는 다음 중 하나로 나타납니다.

- `PENDING` : 제출한 코드가 검사 대기 중인 상태입니다.
- `JUDGING`	: 채점 중, 곧 결과가 업데이트됩니다.
- `AC / ACCEPTED` : 제출한 코드가 정답입니다.
- `WA / WRONG_ANSWER`: 제출한 코드의 결과가 정답과 다릅니다.
- `TLE / TIME_LIMIT...` : 제출한 코드가 실행 시간 제한을 초과했습니다.
- `MLE / MEMORY_LIMIT...` :	제출한 코드가 실행 메모리 제한을 초과했습니다.
- `OLE / OUTPUT_LIMIT...`: 제출한 코드가 출력 길이 제한을 초과했습니다.
- `RE / RUNTIME_ERROR`	: 제출한 코드가 실행 중 오류가 발생했습니다.
- `CE / COMPILE_ERROR`: 제출한 코드가 컴파일 중 오류가 발생했습니다.
- `SE / SYSTEM_ERROR`:	시스템 오류	채점 서버에 문제가 발생했습니다.
- `PAC / PARTIAL_AC...`: 일부 테스트 케이스만 통과했습니다.
- `PE / PRESENTATION...`: 형식 차이로 오답 처리되었습니다.

> [!CAUTION]
**> 최신 결과가 반영되지 않는다면 페이지를 새로고침하세요.**

#### 4. 다음 문제 이동

<img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/531c0f17-69ca-46d0-b85b-eb274fee7ef3" />

> **온라인 IDE 의 좌측 탭에서 문제를 선택하여 다른 문제로 이동할 수 있습니다.**

<br><img width="1512" height="827" alt="Image" src="https://github.com/user-attachments/assets/cb78658d-7362-4e4f-bb5f-fdbf0867943a" />

---

## 부록

### 컴파일러 정보

- 컴파일러 :
    ```txt
    GCC 9.4
    ```

- 컴파일 명령어 :
    ```bash
    gcc -DONLINE_JUDGE -O2 -w -fmax-errors=3 -std=c11 {src_path} -lm -o {exe_path}
    ```

### 문의사항

만약 플렛폼 사용 과정에서 질문할 내용이 있다면 <br>
[leehan416@handong.ac.kr](mailto:leehan416@handong.ac.kr) (TA 이한결) 혹은 <br>
[gktmzl12@handong.ac.kr](mailto:gktmzl12@handong.ac.kr) (TA 박준현) 에게 문의 바랍니다.


# 2025 Handong C Contest

> [!NOTE]
> This document is the English version of the contest guide. For the Korean version, please refer to the main README.

Last updated: 2025. 12. 11.

This repository contains information about the 2025 Handong University C Programming Contest.  
All participants must read the following information carefully before the contest.

---

## Table of Contents [EN]
- [Contest Overview](#contest-overview)
- [Contest Rules](#contest-rules)
- [Contest Website Guide](#contest-website-guide)
    - [Account Creation](#account-creation)
    - [Solving Problems](#solving-problems)
- Appendix
    - [Compiler Information](#compiler-information)
    - [Contact](#contact)

---

## Contest Overview

- Contest Name: 2025 Handong University C Programming Contest
- Date: December 12, 2025 (Fri) 20:00 ~ 22:00
    - Test Contest
        - A test contest is available for participants who want to familiarize themselves with the platform by solving and submitting practice problems.
- Eligibility: Handong University GLS undergraduate students and non-majors from the CSE Department
- Contest Format: Online (https://judge.walab.info/)

---

## Contest Rules

> [!CAUTION]
> Participants who fail to comply with the contest rules may receive penalties. All responsibility lies with the participant.

1. All problems must be solved **using only the C programming language**.

1. This contest is designed to evaluate the C programming proficiency of **first-year students or non-majors**.  
   Code that significantly exceeds the level taught in class may result in penalties.

1. Participants who are not properly registered will **not** be recognized as official contestants.
    - Please follow the [Account Creation](#account-creation) guide to create your account.

1. Participants may solve and submit problems as many times as they wish during the contest.
    - If multiple submissions are made for the same problem, **only the earliest accepted submission** will be counted as the final score.

1. After the contest has ended, **submissions will no longer be accepted**.

1. Every code submission must include the following **Honor Code Declaration** at the top of the file:

```
/*
* [Full Name] :
* [Student ID] :
* [Honor Code Pledge] : I, , will solve this coding test with honesty and integrity before God and people.
*/
```

e.g.

```
/*
* [Full Name] : Hong Gil-dong
* [Student ID] : 22500123
* [Honor Code Pledge] : I, Hong Gil-dong, will solve this coding test with honesty and integrity before God and people.
*/
```

1. Allowed and not allowed behaviors:
    - Allowed
        - You may refer to the following websites:
            - This GitHub repository
            - [modocode] https://modoocode.com/
            - [C Documentation] https://devdocs.io/c/

    - Not Allowed
        - Using any websites other than the ones listed above
        - Using any generative AI tools or LLM software  
          (ChatGPT, Cursor, GitHub Copilot, etc.)
        - Communication or collaboration with others
        - Using someone else’s account or participating on behalf of another person
        - Hardcoding (e.g., writing the answer directly in the code)
        - Any act that harms fairness or avoids solving the problem yourself


---

## Contest Website Guide

### Account Creation

1. Access the Contest Website

   Visit [Contest Website (https://judge.walab.info/)](https://judge.walab.info/).

2. Create an Account

   <br><img width="1512" height="825" alt="Image" src="https://github.com/user-attachments/assets/144190a6-0783-4a27-877b-e87dd2d071b9" />

   > **When you access the contest website, the following screen will appear.**

   <br><img width="1510" height="825" alt="Image" src="https://github.com/user-attachments/assets/34798e4d-ce44-4f35-a17c-d00471166185" />

   > **If this is your first visit, you must create an account. Click the Login button in the top-right corner to move to the login page.**

   <br><img width="1511" height="825" alt="Image" src="https://github.com/user-attachments/assets/bcc8556c-4bc4-42c7-8044-5162727df185" />

   > **Click the `Sign in with Google` button at the bottom to log in.**

   <br><img width="1512" height="823" alt="Image" src="https://github.com/user-attachments/assets/9c82a377-cba0-46a9-8678-cb9befb1baed" />

   > **Login is only possible using an @handong.edu or @handong.ac.kr Google account. Other Google accounts cannot be used.**

   <br><img width="1507" height="826" alt="Image" src="https://github.com/user-attachments/assets/3f848dfc-f228-458b-9d72-90bcc34b25af" />

   > **After completing registration, enter your basic information. You will be asked to fill in your Name, Student ID, and select your Department from the dropdown menu (in order from top to bottom).**



### Solving Problems

On the contest platform, you will solve and submit problems in the following steps:

1. Enter the contest
2. Choose a problem, view the problem
2. Solve the problem, run code
3. Submit
4. Move to the next problem

The steps are explained below.

#### 1. Enter the Contest

<img width="1512" height="829" alt="Image" src="https://github.com/user-attachments/assets/b1a202f8-4d11-4ac3-a7fb-8ae30549ff44" />

> **Click the `Contest` tab at the top of the main page.**

<br><img width="1511" height="828" alt="Image" src="https://github.com/user-attachments/assets/3698310a-c90d-40e7-bfde-9a47964e822c" />

> **From the list of contests, click the contest you want to participate in (2025 Handong C Contest) to move to the contest page.**

<br><img width="1512" height="827" alt="Image" src="https://github.com/user-attachments/assets/0d81ded3-378c-44de-a05c-f558c3d571b4" />

> **After moving to the contest page, click to enter.**

#### 2. Select Problem, View Problem

<img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/b7b9183f-b327-44ff-a258-a19aaf90f64c" />

> **Click `Contest Problems` on the left to move to the problem list.**

<br><img width="1511" height="823" alt="Image" src="https://github.com/user-attachments/assets/0c36bc3b-59e4-43b0-8e36-5ad5e2a3f917" />

> **Select a problem to move to the online IDE page.**

<br><img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/1ae22faa-edae-46e9-97a6-19273f66b6b0" />

> **You can check the problem details on the left side of the IDE.**

> [!CAUTION]
> **Please review the contest rules as well.**

#### 2. Solve Problem, Run Code

<img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/c1089b14-42eb-42e5-a717-727695afeb81" />

> **Write your code in the code editor on the right.**

<br><img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/e9d91fb1-9f86-4de9-a024-bbe45a0ff4c7" />

> **If you want to test your code, click the Run button at the top right.**

<br><img width="1512" height="825" alt="Image" src="https://github.com/user-attachments/assets/fb1b5650-e5ff-43ef-9149-8744b7bbd094" />

> **You can pre-enter the input values that will be used during testing.**

<br><img width="1512" height="828" alt="Image" src="https://github.com/user-attachments/assets/f21fdff6-383a-4f72-a4cf-6a980d0f32fe" />

> **Click `Sample` to automatically insert the example input from the problem statement.**

#### 3. Submit

<img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/395f63c1-a5e4-4a58-bdcb-0451bf8beb23" />

> **When you are ready, click the Submit button at the top right.**

The result will appear as one of the following:

- `PENDING` : Your code is waiting in the judging queue.
- `JUDGING` : Your code is being evaluated.
- `AC / ACCEPTED` : Your solution is correct.
- `WA / WRONG_ANSWER` : Your output does not match the expected answer.
- `TLE / TIME_LIMIT...` : Your code exceeded the time limit.
- `MLE / MEMORY_LIMIT...` : Your code exceeded the memory limit.
- `OLE / OUTPUT_LIMIT...` : Your output exceeded the allowed length.
- `RE / RUNTIME_ERROR` : A runtime error occurred during execution.
- `CE / COMPILE_ERROR` : A compilation error occurred.
- `SE / SYSTEM_ERROR` : A system error occurred on the judge server.
- `PAC / PARTIAL_AC...` : Only some test cases were passed.
- `PE / PRESENTATION...` : Your output format is incorrect.

> [!CAUTION]
> **If the latest result does not appear, please refresh the page.**

#### 4. Move to the Next Problem

<img width="1512" height="826" alt="Image" src="https://github.com/user-attachments/assets/531c0f17-69ca-46d0-b85b-eb274fee7ef3" />

> **You can move to another problem by selecting it in the left panel of the online IDE.**

<br><img width="1512" height="827" alt="Image" src="https://github.com/user-attachments/assets/cb78658d-7362-4e4f-bb5f-fdbf0867943a" />

---

## Appendix

### Compiler Information

- Compiler:
     ```txt
     GCC 9.4
     ```

- Compile Command:
     ```bash
     gcc -DONLINE_JUDGE -O2 -w -fmax-errors=3 -std=c11 {src_path} -lm -o {exe_path}
     ```

### Contact

If you have questions while using the platform, please contact:  
[leehan416@handong.ac.kr](mailto:leehan416@handong.ac.kr) (TA Han-gyeol Lee)  
[gktmzl12@handong.ac.kr](mailto:gktmzl12@handong.ac.kr) (TA Jun-hyun Park)
