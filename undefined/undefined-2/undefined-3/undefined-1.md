---
description: 사용자가 생성한 문서봇이나 전체 허용 권한으로 공유 받은 문서봇은 필요에 따라 특정 조직이나 개인에게 공유하여 함께 활용할 수 있습니다.
---

# 문서봇 공유하기

***



### 문서봇 권한

문서봇을 공유할 때는 공유 대상자별로 권한을 설정할 수 있습니다. 권한 수준에 따라 문서봇을 조회하거나 수정, 소스를 관리할 수 있으며, 이를 통해 문서봇의 활용 범위를 유연하게 조정할 수 있습니다.

\
설정 가능한 권한의 종류와 각 권한으로 수행할 수 있는 작업은 다음과 같습니다.&#x20;

<table><thead><tr><th width="142.44448852539062">권한</th><th width="103.5555419921875">문서봇 정보 조회</th><th width="101.33331298828125">문서봇 채팅</th><th width="95.77777099609375">소스 조회</th><th width="103.555419921875">소스 추가/ 삭제</th><th width="110.111083984375">문서봇 공유</th><th>문서봇 편집</th></tr></thead><tbody><tr><td><strong>전체 허용</strong></td><td>O</td><td>O</td><td>O</td><td>O</td><td>O</td><td>O</td></tr><tr><td><strong>소스 관리 허용</strong></td><td>O</td><td>O</td><td>O</td><td>O</td><td>X</td><td>X</td></tr><tr><td><strong>채팅만 허용</strong></td><td>O</td><td>O</td><td>O</td><td>X</td><td>X</td><td>X</td></tr><tr><td><strong>사용 권한 없음</strong></td><td>O</td><td>X</td><td>X</td><td>X</td><td>X</td><td>X</td></tr></tbody></table>



문서봇 생성자는 ‘전체 허용’ 권한과 함께 기본 언어 모델을 설정할 수 있는 권한을 갖습니다. 그리고, 동일 사용자에게 여러 권한이 부여된 경우, **가장 낮은 권한이 우선 적용**됩니다.



문서봇을 공유받은 사용자는 해당 문서봇의 ‘상세 보기’ 화면에서 본인에게 부여된 문서봇 권한을 확인할 수 있습니다.

<div align="left"><figure><img src="../../../.gitbook/assets/image (747).png" alt=""><figcaption></figcaption></figure></div>



***



### 문서봇 공유 대상 지정하기



1. 현재 문서봇 화면이 아닌 경우, aichatter 화면 상단의 메뉴에서 **문서봇**을 클릭합니다.

<figure><img src="/broken/files/7AspEhN17Y3FqIjfyTPf" alt=""><figcaption></figcaption></figure>



2. '모든 문서봇' 화면이 표시되면, 다음 2가지 방법 중 하나를 실행하여 공유 대상을 지정할 창을 표시합니다.    &#x20;

{% tabs %}
{% tab title="문서봇 목록에서" %}
문서봇 목록에서 공유할 문서봇으로 커서를 올려 호버 아이콘이 나타나면 공유 아이콘 <img src="../../../.gitbook/assets/image (371).png" alt="공유" data-size="line"> 을 클릭합니다.

<div align="left"><figure><img src="/broken/files/6wHkSM17F3ExK89V9HYb" alt=""><figcaption></figcaption></figure></div>


{% endtab %}

{% tab title="상세 보기 화면에서   " %}
문서봇 이름을 클릭하여 나타나는 문서봇 '상세 보기' 화면에서 **공유** 버튼을 클릭합니다.

<div align="left"><figure><img src="../../../.gitbook/assets/image (746).png" alt=""><figcaption></figcaption></figure></div>
{% endtab %}
{% endtabs %}



3. ‘문서봇 공유’ 팝업 창이 나타나면, 공유할 사용자를 검색해 선택하거나 조직도에서 직접 선택합니다.



{% tabs %}
{% tab title="검색하기" %}
공유 대상을 검색해서 선택하는 방법입니다.



❶ 팝업 창 중앙의 입력란에 사용자 이름, ID, 부서 또는 직위를 입력합니다. 입력한 내용이 포함된 사용자, 부서, 직위 목록이 아래에 표시되며, 목록에서 대상을 클릭하면 ‘**공유 대상**’ 목록에 추가됩니다.

<div align="left"><figure><img src="../../../.gitbook/assets/image (749).png" alt="" width="563"><figcaption></figcaption></figure></div>



❷ 공유 대상에게는 기본적으로 ‘채팅만 허용’ 권한이 설정됩니다. 다른 권한을 부여하려면 우측의 권한 목록을 클릭한 후 변경할 권한을 선택합니다.

<div align="left"><figure><img src="../../../.gitbook/assets/image (748).png" alt="" width="354"><figcaption></figcaption></figure></div>



➌ 검색을 통해 공유 대상을 더 추가하려면 ❶과 ❷ 과정을 반복합니다.



❹ 공유 대상을 모두 추가한 후 **저장** 버튼을 클릭합니다.

<div align="left"><figure><img src="../../../.gitbook/assets/image (750).png" alt="" width="310"><figcaption></figcaption></figure></div>
{% endtab %}

{% tab title="조직도에서 선택하기" %}


❶ 팝업 창에서 **조직도에서 선택**을 클릭합니다.&#x20;

<div align="left"><figure><img src="../../../.gitbook/assets/image (761).png" alt="" width="310"><figcaption></figcaption></figure></div>



❷ 조직도를 보여주는 창이 팝업됩니다. 이 창에서는 부서(**조직도**) 또는 직위(**직위 목록**)를 기준으로 공유 대상을 지정할 수 있습니다. 특정 부서 전체나 개별 부서원, 혹은 특정 직위의 모든 직원을 선택할 수 있습니다.



* **부서나 부서원 선택**\
  \
  조직도 트리에서 부서를 클릭하면 중앙 패널 상단에 부서명이, 그 아래에 해당 부서의 모든 부서원이 표시됩니다. 부서 전체를 공유 대상으로 지정하려면 부서명을, 특정 부서원만 지정하려면 해당 부서원의 이름을 선택합니다.

<div align="left"><figure><img src="../../../.gitbook/assets/image (762).png" alt=""><figcaption></figcaption></figure></div>



* **직위별 직원 선택**  \
  왼쪽 패널에서 **직위 목록**을 클릭하면 직위 트리가 표시됩니다. 직위 트리에서 원하는 직위를 클릭하면 중앙 패널 상단에 직위명이, 그 아래에 해당 직위의 직원들이 표시됩니다. 직위 전체를 선택하려면 직위명을, 특정 직원을 선택하라면 해당 직원의 이름을 선택합니다.

<figure><img src="../../../.gitbook/assets/image (763).png" alt=""><figcaption></figcaption></figure>



➌ 선택한 공유 대상이 오른쪽 패널에 표시됩니다. 공유 대상에게는 기본적으로 ‘채팅만 허용’ 권한이 설정됩니다. 다른 권한을 부여하려면 우측의 권한 목록을 클릭한 후 변경할 권한을 선택합니다.

<div align="left"><figure><img src="../../../.gitbook/assets/image (764).png" alt="" width="332"><figcaption></figcaption></figure></div>



❹ 조직도에서 공유 대상을 더 추가하려면 ❷와 ➌ 과정을 반복합니다.



❺ 공유 대상을 모두 추가한 후 **공유** 버튼을 클릭합니다.

<figure><img src="../../../.gitbook/assets/image (382).png" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}



