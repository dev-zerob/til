## Semantic Tags 란?

`의미가 있는 태그` 라는 뜻으로, 웹 사이트에서 이 시맨틱 태그들은 브라우저와 개발자 사이에서 태그 이름으로 특정 `의미를 부여`하는 역할을 합니다.

> **사용하는 이유**
> 
> - 검색을 최적화하기 위해서 사용됩니다.
> - 웹 접근성을 위해 사용됩니다.
> - 개발자가 한눈에 구조를 파악하기 위해 사용됩니다.

<br />


## Semantic Tags

|Element|Description|
|:---|:---|
|`<header>`| 소개 및 탐색에 도움을 주는 콘텐츠를 나타냅니다. <br /> `제목`, `로고`, `검색 폼` 등의 요소를 주로 사용합니다. |
|`<nav>`| 문서의 부분 중 현재 페이지 내, 또는 다른 페이지로의 링크를 보여주는 영역을 나타냅니다. <br /> `메뉴`, `목차`, `색인` 등의 요소를 주로 사용합니다. |
|`<aside>`| 문서의 주요 내용과 간접적으로만 연관된 부분을 나타냅니다. <br /> `사이드바`, `콜아웃 박스` 로 표현합니다. |
|`<main>`| 문서의 주요 콘텐츠를 나타냅니다. |
|`<footer>`| 일반적으로 `작성자`, `저작권 정보`, `관련 문서` 등의 내용을 담습니다. |
|`<section>`| HTML 문서의 독립적인 영역을 나타내며, 적합한 의미를 가진 요소가 없는 경우 사용합니다. |
|`<article>`| 문서, 페이지, 애플리케이션, 또는 사이트 안에서 독립적으로 구분해 `재사용`할 수 있는 영역을 나타냅니다. |

<br />


### `<article>` vs `<section>`
- article : 독립적으로 따로 분리해도 문제가 없어야 합니다.
- section : 다른 태그들 안에서 연관있는 내용을 묶어줄 때 사용할 수 있습니다.

<br />


### `<em>` vs `<i>`
- em : 강조하는 이탤릭체를 의미합니다.
- i : 시각적인 이탤릭체를 의미합니다.

<br />


### `<strong>` vs `<b>`
- strong : 강조하는 볼드체를 의미합니다.
- b : 시각적인 볼드체를 의미합니다.

<br />


### `<ul>` vs `<ol>` vs `<dl>`
- ul : 순서가 없는 목록을 나타낼 때 사용합니다.
- ol : 순서가 있는 목록을 나타낼 때 사용합니다.
- dl : 단어에 대한 설명이 묶여있는 목록을 나타낼 때 사용합니다.
  - dt : 단어의 정의을 나타낼 때 사용합니다.
  - dd : 단어의 설명을 나타낼 때 사용합니다.

<br />


### `<img>` vs `background-image`
- img : 이미지가 문선와 관련있는 하나의 중요한 요소일 때 사용합니다.
- background-image : 이미지가 문서의 내용과 별개로 스타일링을 위한 경우 사용합니다.

<br />


### `<button>` vs `<a>`
- button : 사용자의 액션을 위해 경우 사용합니다.
- a : 사용자의 페이지 이동을 위한 경우 사용합니다.

<br />


### `<table>` vs css
- table : 많은 데이터 행과 열로 표현할 때 사용합니다.
- css : 아이템을 표현하기 위한 경우 `Flex`, `Grid`를 사용하여 유연하게 테이블을 생성할 수 있습니다.


<br />
<br />


> **출처**
>
> - [Semantic Tag - Youtube 드림코딩 by 엘리](https://www.youtube.com/watch?v=T7h8O7dpJIg&list=PLv2d7VI9OotQ1F92Jp9Ce7ovHEsuRQB3Y&index=29)
>