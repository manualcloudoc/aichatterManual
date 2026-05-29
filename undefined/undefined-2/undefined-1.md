# 새 문서봇 만들기



***



새 문서봇을 만드는 방법은 다음과 같습니다.



{% stepper %}
{% step %}
#### 메뉴 선택하기

aichatter 화면에서 **문서봇** 메뉴를 클릭합니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (276).png" alt=""><figcaption></figcaption></figure></div>


{% endstep %}

{% step %}
#### 문서봇 만들기 시작하기

[사용 가능한 문서봇](#user-content-fn-1)[^1]이 있는지에 따라 다음 두 화면 중 하나가 표시됩니다. 각 화면에서 **문서봇 만들기** 버튼을 클릭합니다.

{% tabs %}
{% tab title="사용 가능한 문서봇이 없는 경우" %}
<div align="left"><figure><img src="../../.gitbook/assets/image (36).png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endtab %}

{% tab title="사용 가능한 문서봇이 있는 경우" %}
<div align="left"><figure><img src="../../.gitbook/assets/image (203).png" alt=""><figcaption></figcaption></figure></div>
{% endtab %}
{% endtabs %}

&#x20;
{% endstep %}

{% step %}
#### 문서봇 만들기 화면 살펴보기

<문서봇 만들기> 화면이 표시됩니다. 문서봇 생성은 다음 세 단계로 이루어집니다.&#x20;



* **기본 정보 입력(기본 구성): 필수**
* **AI 매개 변수 설정(AI 설정): 선택**
* **소스 등록: 필수**



화면 우측에 표시된 단계 항목을 클릭하면, 해당 설정 영역으로 이동합니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (37).png" alt="" width="563"><figcaption></figcaption></figure></div>


{% endstep %}

{% step %}
#### 문서봇 기본 정보 입력하기

[**문서봇 기본 정보 입력하기**](../undefined-1/undefined-1/undefined.md)의 설명을 참고하여 **기본 구성** 영역의 항목을 설정합니다.



<div align="left"><figure><img src="../../.gitbook/assets/image (38).png" alt="" width="563"><figcaption></figcaption></figure></div>


{% endstep %}

{% step %}
#### AI 매개 변수 조정하기

AI 매개 변수는 문서봇이 질문에 답변할 때&#x20;



* **어떤 자료를 중심으로 답변할지**
* **얼마나 다양하거나 보수적으로 답변할지**
* **답변의 길이와 표현 방식은 어떻게 할지**

등의 **응답 특성**을 조정하는 항목입니다.&#x20;



필요한 경우, [**문서봇 응답 특성 조정하기**](../undefined-1/undefined-1/undefined-1.md)의 설명을 참고해 **AI 설정** 영역에 있는AI 매개 변수 값을 설정합니다. 기본값을 그대로 사용할 경우에는 별도로 설정하지 않아도 됩니다.



<div align="left"><figure><img src="../../.gitbook/assets/image (39).png" alt="" width="443"><figcaption></figcaption></figure></div>


{% endstep %}

{% step %}
#### 소스 등록하기

**소스 등록** 영역에서 [**문서봇 소스 등록하기**](../undefined-1/undefined-1/undefined-2/)의 설명을 참고하여 문서봇이 학습할 소스를 등록합니다. 하나의 문서봇에는 **파일**, **웹 페이지**, **직접 작성한 텍스트** 등 여러 종류의 텍스트를 함께 등록할 수 있습니다.&#x20;

**사용자 PC** 또는 **클라우드 스토리지**(Google Drive, Dropbox, BOX 등)에 저장된 파일을 업로드할 수 있으며, 클라우드독과 연동된 경우에는 **클라우독 문서함**에 저장된 파일을 학습하도록 할 수 있습니다. 등록 가능한 파일 유형에는 **문서**, **이미지**, **비디오**, **오디오** 파일 등이 포함됩니다.



<div align="left"><figure><img src="../../.gitbook/assets/image (65).png" alt="" width="563"><figcaption></figcaption></figure></div>


{% endstep %}

{% step %}
#### 문서봇 만들기

**기본 정보 입력**, **AI 매개 변수 설정**, **소스 등록**을 모두 완료한 후 화면 하단의 **만들기** 버튼을 클릭합니다.



<div align="left"><figure><img src="../../.gitbook/assets/image (850).png" alt="" width="563"><figcaption></figcaption></figure></div>


{% endstep %}

{% step %}
#### 새 문서봇 추가 확인하기

<모든 문서봇> 화면 상단에 새로 생성한 문서봇이 추가됩니다. 문서봇이 생성되면 등록한 소스를 기반으로 학습이 자동으로 시작됩니다. 소스의 학습 상태를 확인하려면 추가된 문서봇의 **이름** 또는 **설명**을 클릭합니다.



<div align="left"><figure><img src="../../.gitbook/assets/image (851).png" alt=""><figcaption></figcaption></figure></div>




{% endstep %}

{% step %}
#### 소스 학습 상태 확인하기

문서봇의 상세 화면이 표시됩니다. 소스 학습은 **대기** > **학습 중** > **성공** 또는 **실패** 순으로 진행되며 각 소스의 현재 학습 상태를 상세 화면에서 확인할 수 있습니다. 모든 소스의 학습이 완료되면 **문서봇과 채팅**을 시작하거나, 다른 사용자에게 **문서봇을 공유**할 수 있습니다.

<div align="left"><figure><img src="../../.gitbook/assets/image (852).png" alt=""><figcaption></figcaption></figure></div>



{% hint style="success" %}
소스의 학습 상태는 대기, 학습 중, 성공, 부분 성공, 실패의 다섯 가지로 구분됩니다. ‘대기’는 다른 소스가 학습 중이어서 학습 순서를 기다리는 상태이며, ‘부분 성공’은 소스가 폴더인 경우 일부 항목만 학습에 성공한 상태를 의미합니다.
{% endhint %}

{% hint style="success" %}
일부 소스의 학습이 실패하더라도 문서봇 채팅과 공유는 가능합니다. 이 경우 정상적으로 학습된 소스만을 기준으로 답변이 생성됩니다. 학습에 실패한 소스 개수는 상세 화면 상단에 표시되며, 해당 개수를 클릭하면 실패한 소스 목록을 확인할 수 있습니다. 실패한 소스는 [**문서봇 소스 관리하기**](undefined-4/undefined.md)를 참고해 삭제한 후 다시 등록합니다.
{% endhint %}

<div align="left" data-with-frame="true"><figure><img src="../../.gitbook/assets/image (61).png" alt=""><figcaption><p>학습에 실패한 소스의개수와 목록</p></figcaption></figure></div>


{% endstep %}
{% endstepper %}





[^1]: 사용 가능한 문서봇은 사용자가 만들었거나 다른 사용자로부터 공유 받은 문서봇입니다.
