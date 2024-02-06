# 급해, 급행!

<br>

## 1. 프로젝트 개요

### - 프로젝트 소개

<h4>누구나 한 번쯤 경험했을 "비상 신호", 신호가 오면 정차 하지 않고 화장실로 "급해, 급행!"</h4>

<p>언제 어디서든 편리하게 급행을 이용하기만 하면 내 주변 위치로 화장실이 보인다! 평생의 흑역사를 만들지 않기 위해 달려가봅시다! 급하다 급행!</p>

<h4>🌟  프로젝트 목표</h4>

```
  [🚹] 누구나 편리하게 사용할 수 있어야 한다.
  [🔭] 한 눈에 모든 정보를 담을 수 있도록 한다.
  [📦] 나만의 화장실을 저장할 수 있도록 한다.
  [💣] 사용자가 급행을 이용한다는 것은 급박한 상황이므로 "길찾기", "남은 거리"를 표시할 수 있어야 한다.
  [🕊️] 사용자의 편안한 앞 날을 기원한다.
```

### - 사전조사

| 급해 ui/ux 기능 참고                                                                                                               | PooPee ui/ux ,기능 참고                                                                                                             |
| :-----------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/f08c85b1-85c0-4397-93a5-b2095a9acc8e" width="50%" align="center"> | <img src="https://github.com/wkd6262/wkd6262/assets/142865132/b43bb39d-4442-474e-b6f4-48c3e1e74589" width="50%" align="center"> |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/8c035713-45f1-48c0-8ace-8c13fefd6894" width="50%" align="center"> | <img src="https://github.com/wkd6262/wkd6262/assets/142865132/54add6f0-39c1-4224-b933-e55c0684b286" width="50%" align="center"> |


### - 고려사항

| FrontEnd                                                      | BackEnd                                                                                                                     | Data-Base                                                                                                                                                    |
| ------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| React의 이해, 프로젝트 기획 및 아이디어 도출, moduleCSS 사용 | Node.js, Express, Axios 활용한 서버 개발 <br> 엔드포인트, GET 및 POST 메소드 이해, Cloud Type을 이용해 완성된 프로젝트 배포 | mongoDB 연결을 통한 데이터 저장, 삭제, 수정 구현 <br> CORS 이슈 해결 및 데이터베이스 통신 원활하게 <br> Open API 사용법 숙지 및 데이터 가공 후 내보내기 계획 |

<br />

### - 디렉토리 구조

- back, front로 나눠서 작업

#### - back
      - controller를 이용해 서버를 모듈화 하여 간편하게 사용
      - env를 이용해 중요한 내용을 암호화 하여 해킹 방지
      
#### - front
      - login,page,style 3가지로 분리하여 작업
      - app.js에 컴포넌트를 삽입
      - react-router-dom 을 사용하여 SPA 형식으로 서버 페이지 생성
      - .module css를 이용해 css겹침 방지 및 간편하게 작업
      - minireset을 사용해 css를 더 간편하게 적용

<img width="60%" align="center" alt="디렉토리 구조" src="https://github.com/wkd6262/wkd6262/assets/142865132/cf88c208-3baf-4cab-a9a9-0a6e8c6cfd96">



<div align="center">
  
## 핵심기능 시연 ##

| 로그인                                                                                                          | 프로필 업로드                                                                                                  |
| --------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/43e8e3af-c7e4-4691-833d-f1c968fde05c" width="350" > | <img src="https://github.com/wkd6262/wkd6262/assets/142865132/af3a260b-3f1c-4892-bb30-8c58374905fc" width="350"> |
| 로그아웃                                                                                                        | 화장실 메인                                                                                                    |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/023f647a-f2b7-492a-8b50-163f250796aa" width="350">  | <img src="https://github.com/wkd6262/wkd6262/assets/142865132/cd0564ea-37df-407b-8599-9878016507c3" width="350"> |
| 길찾기                                                                                                          | 화장실 저장                                                                                                    |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/c49871b2-feb0-4ac6-889e-18d697a9ad9a" width="350">  | <img src="https://github.com/wkd6262/wkd6262/assets/142865132/d9fbd4a8-20a3-4836-b54a-1e445006cc29" width="350"> |
| 화장실 검색                                                                                                     | 화장실 저장소 메모 수정 및 삭제                                                                                |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/99447579-12d7-4100-8cce-030a7cb00aaf" width="350">  | <img src="https://github.com/wkd6262/wkd6262/assets/142865132/23523c76-9cd4-4a37-bb02-0287963e62f8" width="350"> |

</div>

<br/>

## 2. 개발 일정 및 진행 방식

### - 개발 일정

프로젝트 기획: 2023.01.06 ~ 2024.01.09
프로젝트 개발: 2023.01.09 ~ 2024.01.26

### - 초기 기획 진행방식

### 📌 실패 경험을 통해 얻은 아이디어

- 초기 기획 중 여러 아이디어를 직접 시현해보고 마음에 드는 것으로 계획 하기로 하였음.
- 초기 기획 기간 동안 여러 실패 경험이 있었음.
- 실시간 버스 조회, 지하철 조회 -> 공공데이터 특성 상 쿼리 값을 못 받아옴 x
- 고속버스만 조회 -> 데이터 출력에 대한 미숙함으로 x
- 여러 실패경험을 하다 평소 대중교통을 많이 이동하는데 이동 하면서 겪은 "비상 신호"의 아이디어가 떠올라 화장실 API로 결정
- 데이터를 추출, 검색어로 조회 이 두가지를 성공하면 개발 진행을 시작하기로 하였음

### - 개발 일지 ( 작업 하면서 기록 )

## 📝 2024-01-07

- 나의 스토리를 담고 싶은 아이디어를 구상 중 대중교통을 자주 이용하는 자신의 모습을 발견 하여 관련 정보를 수집

## 📝 2024-01-08

- 경기도 공공데이터 사이트를 알게 되어 둘러 보던 중 3가지 API에 흥미가 생겨 정보를 수집
- 지하철, 버스 등 사용자의 시점으로 생각해 평소 불편한 점을 개선하고 싶어 결정

## 📝 2024-01-09

- 지하철, 버스 API 출력하는 것을 시도함. 데이터 추출 및 검색어 기능을 추가하기로 함.
- 화장실 데이터도 함께 추가하기로 결정.

## 📝 2024-01-10

- 데이터가 배열 형태로 발생하는 문제가 발생함. Query를 이용하여 검색어로 데이터를 추출하려 했지만, 전체 데이터가 배열 형태로 반환되어 전체 데이터를 받아와야 함.
- 11개 페이지에 걸쳐 총 11000개의 데이터를 받아와야 하는 상황. 이를 해결하기 위해 1-11페이지의 서버를 생성할 수 없어서 foreach로 생성함.
- 데이터 문제로 인해 초기 로딩 시 많은 시간이 소요되고 렉이 걸림. 이를 해결하기 위해 검색어를 입력하면 해당 위치에 정보만 뜨도록 설정함.
- 또 다른 이슈는 내 주변 화장실이 표시되지 않는 것.

## 📝 2024-01-11

- 검색한 정보를 마커로 표시하는 데 성공함.
- 하지만 내 주변 화장실은 검색을 한 후에 생성됨.
- 이를 해결하기 위해 Rest 컴포넌트에서 지오코더를 활용하여 위도와 경도 값을 받아왔으나, 기본 값이 필터된 데이터인 것으로 보임.

## 📝 2024-01-12

- 선생님의 피드백을 받음.
- 마커의 가독성을 수정해야 함.
- 기능보다는 UI를 우선으로 만들고 작업해야 함.

## 📝 2024-01-16

- Infowindow를 따로 사용하려 했으나 스크립트 로드 오류가 발생함.
- 이를 해결하기 위해 infoBox 컴포넌트로 대체함.

## 📝 2024-01-17

- 구현한 것: infoBox, 검색 결과, 현재 위치 값 표시, 검색 결과를 클릭하면 해당 위치로 이동, 마커 UI 수정, 길찾기 구현, 마커를 클릭하면 infoBox에 정보 전달, 즐겨찾기 및 저장 기능 구현.
- 문제: Rest 컴포넌트가 메인이 아니라 KakaoMap을 메인으로 사용하기 때문에 모달로 분리할 수 없음.
- 해결: form을 따로 div로 감싸서 모달로 구현함.

## 📝 2024-01-18

- 구현한 것: 검색 및 정보 모달 CSS 작업, 닫기 버튼 토글 구현, 마커 UI 작업, Figma 디자인 개선, 스플래시 스크린 구현, 정보 모달 UI 수정.
- 추가하고 싶은 것: 메모 수정, 공중 화장실에서 다양한 정보 전달 (변기의 수, 공중 화장실 여부, 비밀번호 유무, 남녀 분리 여부 등).

## 📝 2024-01-21

- 문제점: MongoDB에 저장된 값이 삭제 버튼의 기능이 작동하지 않음.
- 해결: **`TypeError: Class constructor ObjectId cannot be invoked without 'new'`** 오류가 발생함. 이 오류는 MongoDB에서 사용하는 **`ObjectId`** 클래스를 인스턴스화할 때 **`new`** 키워드를 사용하지 않아서 발생함.

## 📝 2024-01-22

- 몽고DB에 화장실 정보를 저장하고 배포하려고 하니 회원가입 및 로그인 몽고의 오류가 발생함.
- 로그인이 있는데 프로필 요소가 없어서 추가 함.

## 📝 2024-01-23

- 몽고DB에서 프로필 이미지를 저장 및 수정 하도록 구현 하기로 생각
- 전체적인 UI 수정 및 적용

## 📝 2024-01-24

- 프로필 이미지 저장의 오류 및 해결이 되지 않아 GPT를 이용하여 구현
- 전체적인 코드 수정 및 파악 후 마무리 UI 수정 및 추가 기능 구상

## 📝 2024-01-25

- 추가 기능 -> 프로필 업로드 시 이미지 전환, 카카오 맵 확대 수정
- index.html에 og,meta 태그 추가, 파비콘 작업 및 추가

## 📝 2024-01-26

- 최종 마무리 후 클라우드 타입 배포를 위해 back, front를 나눠 배포

### 🛠️ 개발 진행 문제 해결

### 1️⃣ 데이터 출력의 어려움

| 문제 상황                                                                                                                     |
| ----------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/c523fb9d-a973-4914-bdfa-2c93c064f38d" width="500" align="center"> |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/2672da29-ccab-4b14-b6ca-12b17e93b32f" width="500" align="center"> |
| X 데이터 출력은 되었으니 .map으로 출력을 하려고 해도 어느 문제인지 자꾸 출력이 안 되는 점 발생                                |
| ✓ 출력 되는 key 값을 div를 사용해서 전체 값으로 출력이 되었음, ul li(key)를 이용하여 해결. (이런 단순한 실수는 줄이기)        |

<br/>

### 2️⃣ 데이터 출력 1000개 제한

| 문제 상황                                                                                                                     |
| ----------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/e3ebf452-a6c4-4854-88d5-79af3caf8155" width="500" align="center"> |
| X 데이터 출력은 되었으나 1개의 데이터 페이지당 1000개 출력 제한 발생.                                                         |
| ✓ 데이터 페이지가 총 11개인데 forEach를 이용하여 배열로 서버 데이터 추출.                                                     |

<br/>

### 3️⃣ 데이터 로드 렉 발생

| 문제 상황                                                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------------------------------------- |
| X 1000개의 데이터를 11페이지로 받아 총 11000개의 데이터를 동시에 받아와 처음 로딩 시 많은 렉이 걸리게 됨.                                      |
| ✓ 초기 값은 내 현재 위치 주변 화장실이 나오도록 설정, 검색어를 입력하면 해당 위치에 정보만 뜨게 설정 ex) 수원 → 수원화장실. 데이터 과부화 해결 |

```javascript
// 거리 계산 함수
const calculateDistance = (lat1, lon1, lat2, lon2) => {
  const R = 6371;
  const dLat = toRadians(lat2 - lat1);
  const dLon = toRadians(lon2 - lon1);
  const a =
    Math.sin(dLat / 2) * Math.sin(dLat / 2) +
    Math.cos(toRadians(lat1)) *
      Math.cos(toRadians(lat2)) *
      Math.sin(dLon / 2) *
      Math.sin(dLon / 2);
  const c = 2 * Math.atan2(Math.sqrt(a), Math.sqrt(1 - a));
  const distance = R * c;

  return distance;
};

// 각도를 라디안으로 변환하는 함수
const toRadians = (angle) => {
  return (angle * Math.PI) / 180;
};

// 주변 화장실을 찾는 함수
const findNearbyToilets = () => {
  if (userLocation) {
    const radius = 1.3;
    const nearbyToilets = toilets
      .map((toilet) => ({
        ...toilet,
        distance: calculateDistance(
          userLocation.latitude,
          userLocation.longitude,
          toilet.REFINE_WGS84_LAT,
          toilet.REFINE_WGS84_LOGT
        ),
      }))
      .filter((toilet) => toilet.distance <= radius)
      .sort((a, b) => a.distance - b.distance);

    return nearbyToilets;
  }
  return [];
};

// 데이터 필터링 함수
const filterData = () => {
  const searchTerm = inputRef.current.value.toLowerCase().trim();

  if (searchTerm === "") {
    const sortedToilets = [...toilets].sort((a, b) => {
      const distanceA = userLocation
        ? calculateDistance(
            userLocation.latitude,
            userLocation.longitude,
            a.REFINE_WGS84_LAT,
            a.REFINE_WGS84_LOGT
          )
        : 0;

      const distanceB = userLocation
        ? calculateDistance(
            userLocation.latitude,
            userLocation.longitude,
            b.REFINE_WGS84_LAT,
            b.REFINE_WGS84_LOGT
          )
        : 0;

      return distanceA - distanceB;
    });

    setFilteredToilets(findNearbyToilets());
    setVisibleResults(0);

    return;
  }
};
```

<br />

### 4️⃣ 몽고 DB 삭제 기능 오류

| 문제 상황                                                                                                                                                                  |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/7225eac2-c8e2-4909-8510-bead4220cf7a" width="500" align="center">                                              |
| X 몽고DB 저장된 값을 삭제하는 삭제버튼의 기능이 안됨.                                                                                                                      |
| ✓ TypeError: Class constructor ObjectId cannot be invoked without 'new' 이 오류는 MongoDB에서 사용하는 ObjectId 클래스를 인스턴스화할 때 new 키워드를 사용하지 않아서 발생 |

<br/>

### 5️⃣ 몽고 DB 저장 삭제 구현 후 로그인 기능 오류

| 문제 상황                                                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/1feb7682-3429-45b2-a166-f83e10b77cdb" width="500" align="center">                                  |
| X 이 코드를 restSaveController.js / express서버에 중복으로 2개를 넣어놔서포트가 겹쳐 몽고DB두 번 실행이 되어 겹침으로 인해 1개가 되면 1개가 안 되는 오류가발생 |
| <img src="https://github.com/wkd6262/wkd6262/assets/142865132/53768c44-d375-47be-a20b-d6ceabe88f95" width="500" align="center">                                  |
| ✓ restSaveController.js 에 mydb부분을 express에서 받아오는 걸로 해결                                                                                           |

<br/>

## 3. 기술 및 개발 환경

<h4>⚙️  사용 기술</h4>

|                                                                                                                                                                                                                     FrontEnd                                                                                                                                                                                                                     |                                                                                                                                                        BackEnd                                                                                                                                                        |                                               Design                                               |                                                                                                                                                    Tools                                                                                                                                                     |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/styledcomponents-CC6699?style=flat-square&logo=styledcomponents&logoColor=white"> <img src="https://img.shields.io/badge/axios-7F2B7B?style=flat-square&logo=axios&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat-square&logo=JavaScript&logoColor=black"> | <img src="https://img.shields.io/badge/REST API-000000?style=flat-square&logo=logoColor=white"> <img src="https://img.shields.io/badge/nodedotjs-green.svg?style=flat-square&logo=nodedotjs&logoColor=black"> <img src="https://img.shields.io/badge/express-red.svg?style=flat-square&logo=express&logoColor=black"> | <img src="https://img.shields.io/badge/figma-F24E1E?style=flat-square&logo=figma&logoColor=white"> | <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000.svg?style=flat-square&logo=Notion&logoColor=white"> |

<h4>- 기술스택 적용 이유</h4>

### 📌 axios 라이브러리를 통한 서버통신 관리

- 외부 API를 프로미스 기반에 비동기 작업으 관리하기 위해 사용.
- .get() 메서드를 사용하여 간단하게 GET 요청
- 코드를 간결하고 직관적으로 유지

### 📌 express 프레임워크를 사용한 이유

- 개발 규칙을 강제하여 코드 및 구조의 통일성 향상
- 보편적으로 많이 사용되기 때문에 충분한 래퍼런스와 구글링을 통해 초심자도 사용 가능
- 공공데이터 API 사용에서 발생되는 CORS 이슈 해결

### 📌 mongoDB를 이용한 데이터 저장

- 스키마 관리가 필요 없으며 쉽게 사용이 가능하고, 개발에서 편리성이 좋다
- 이미 성숙기에 접어들어 운용, 개발, 유틸리티에 부족함이 없다
- 데이터 저장, 수정, 삭제, 로그인, 회원가입 기능을 구현하기 위해 필수라고 생각한다

### 📌 CloudType을 이용한 서버 배포

- 작업 시 back, front로 나누면 배포하기 간단하며, gitHub와 연동이 되어 간편하게 서버를 열 수 있음
- 로컬 서버 필요 없이 서버를 유지할 수 있음

## 4. 주요 기능

- #### 내 주변 화장실 탐색

  - calculateDistance: 두 지점 간의 거리를 계산하는 함수입니다. 위도와 경도를 인자로 받아서, Haversine 공식을 사용하여 거리를 계산

  - toRadians: 각도를 라디안으로 변환하는 함수

  - findNearbyToilets: 사용자의 위치와 주변의 화장실을 찾는 함수입니다. 먼저 toilets 배열을 순회하면서 각 화장실까지의 거리를 계산하고, 일정 반경 내에 있는 화장실만 필터링하여 반환

- #### 검색 시 데이터 추출

  처음 부터 모든 화장실이 나타나면 마커가 지저분 할 수 있는데, 검색 시에만 데이터 추출이 가능하도록 하여 과부화 방지 및 최적화

- #### 화장실 검색 및 길찾기

  사용자가 원하는 화장실을 빠르게 찾을 수 있고 내 위치로 부터 거리 계산과 개방 시간 등 다양한 정보를 받아 오고, 해당 화장실을 누르면 해당 위치로 이동
  길찾기 버튼을 누르면 카카오 길찾기로 이동하여 사용자가 편리하게 이동할 수 있음

- #### 화장실 저장 기능

  화장실 이름 옆 별 버튼을 누르면 즐겨찾기가 된다, 간단한 메모 작성 및 자신만의 화장실을 저장 및 삭제 할 수 있음

- #### 마커 클릭 시 정보 추출

  내 주변이든 검색을 한 화장실이든 검색 정보에서 보지 못한 자세한 정보를 마커 클릭시 얻을 수 있음 (변기의 갯수, 유아 화장실, 장애인 화장실 등)

  <br>

## 🥲아쉬운 점 및 개선해야 할 점

  경기도 공공 데이터 API만 사용해서 경기도 공중 화장실만 받아와 서울,지방에서는 사용이 불가능하다.

  서울 공중화장실, 지방 공중화장실 데이터도 추가하여 모든 사용자들이 사용할 수 있게 추가 하고 싶다.

  즐겨찾기 저장소가 공용으로 사용 되어 기존에 다른 유저가 저장을 하면 공유가 되는 상태, 추후에 각자 저장소로 수정할 예정
  
  <br>

### [✨프로젝트 바로가기](https://port-0-back2-5r422alqn1n0hw.sel4.cloudtype.app/)(매일 8시에 서버가 꺼짐.)
  id= admin pw= admin
