# 문서봇 응답 특성 조정하기



***



<문서봇 만들기> 화면의 **AI 설정** 영역에서는 다음 3개의 매개 변수를 사용하여 문서봇의 용도에 맞게 응답을 보다 정교하게 조정할 수 있습니다.



> * <mark style="color:$primary;">**Temperature**</mark><mark style="color:$primary;">: 답변의</mark> <mark style="color:$primary;"></mark><mark style="color:$primary;">**톤과 창의성**</mark> <mark style="color:$primary;"></mark><mark style="color:$primary;">조절</mark>
> * <mark style="color:$primary;">**Top p**</mark><mark style="color:$primary;">: 답변의</mark> <mark style="color:$primary;"></mark><mark style="color:$primary;">**단어 선택**</mark> <mark style="color:$primary;"></mark><mark style="color:$primary;">기준 조절</mark>
> * <mark style="color:$primary;">**Similarity**</mark><mark style="color:$primary;">: 검색된</mark> <mark style="color:$primary;"></mark><mark style="color:$primary;">**자료의 활용**</mark> <mark style="color:$primary;"></mark><mark style="color:$primary;">기준 조절</mark>



아래 화면과 표에 정리된 설명을 참고하여, 조정하고자 하는 매개 변수를 ❶토글 스위치로 활성화한 뒤 ❷슬라이더를 사용해 0.00 \~ 1.00 범위에서 값(소수점 둘째 자리 단위)을 설정합니다.



<div align="left"><figure><img src="../../../.gitbook/assets/image (64).png" alt="" width="563"><figcaption></figcaption></figure></div>



<table><thead><tr><th width="124.55548095703125">AI 매개 변수</th><th width="494.8887939453125">설명</th></tr></thead><tbody><tr><td><strong>Temperature</strong></td><td><p>답변의 <strong>창의성과 다양성</strong>을 조절하는 변수</p><p></p><ul><li>값이 낮으면: 정형화되고 정확한 표현이 사용된 답변 <br>⇒ 보고서·매뉴얼 같은 차분하고 안정적인 톤</li><li>값이 높으면: 다양한 표현과 새로운 아이디어가 포함된 답변 <br>⇒ 브레인스토밍이나 마케팅 문구에 적합한 톤</li></ul></td></tr><tr><td><strong>Top p</strong></td><td><p>답변 생성시 <strong>단어 선택의 범위</strong>를 조절하는 변수</p><p></p><ul><li>값이 낮으면: 가장 가능성이 높은 단어만 선택 <br>⇒ 안정적이고 일관된 답변</li><li>값이 높으면: 폭넓고 다양한 단어와 표현을 활용 <br>⇒ 다채롭고 풍부한 답변</li></ul></td></tr><tr><td><strong>Similarity</strong></td><td><p>질문과 검색된 <strong>자료의 유사도 기준</strong>을 설정하는 변수</p><p></p><ul><li>값이 낮으면: 질문과 다소 덜 관련된 자료까지 활용 <br>⇒ 정보량은 많지만 질문과 직접 관련성이 낮을 수 있는 답변</li><li>값이 높으면: 질문과 매우 밀접한 자료만 활용 <br>⇒ 정확도가 높은 답변</li></ul></td></tr></tbody></table>



예를 들어, **aichatter 매뉴얼**을 학습시키는 문서봇을 만드는 경우, 매뉴얼의 특성에 맞게 **정확도가 높고 질문과 밀접한 자료만 활용**해 답변하도록 **Top p** 값을 기본값(0.7) 보다 낮은 값(&#xC608;**:0.1**)로 조정할 수 있습니다.

