<p align="center">
<img src='https://github.com/vEduardovich/dodari/assets/20391482/972aee6d-383e-47ed-90b6-73e0cc513973' title='도다리'/>
<h1 align="center">도다리 Dodari</h1>
<p align='center'><a href='https://huggingface.co/NHNDQ/nllb-finetuned-en2ko' target='_blank'>NHNDQ</a>
AI 한영/영한 번역기를<br/> 일반 사람들도 쉽게 쓸수 있게 만든 로컬 웹서비스 입니다. (based on Gradio)</p>
</p>

<br/>

## 특징
자신의 컴퓨터에서 제한없이 `한영`-`영한` AI 번역이 가능합니다. 
- 일반 기계번역에 비해 품질이 우수합니다.
- txt와 epub파일 번역이 가능합니다. epub은 제목이나 목차등을 제외한 본문의 내용만 번역하였습니다.
- `번역문(원문)` 파일과 `번역문` 파일, 이렇게 두가지 파일로 출력됩니다. 번역이 이상할 경우 원문과 바로 비교할수 있습니다.

- 사용이 아주 쉽습니다. 번역이 필요한 파일들을 드래그한 후 `번역 실행하기` 버튼만 클릭하면 됩니다. 알아서 `한↔영` 으로 번역해 줍니다.
- 번역 성능이 뛰어난 모델로 최신 업데이트가 가능합니다 - 현재는 가성비가 가장 좋은 NHNDQ만 사용합니다.
<img src='https://github.com/vEduardovich/dodari/assets/20391482/6d46e5b9-3a49-4950-984f-5bbbbeb5f2b5' style='display:block;border-radius:10px;text-align:center;' title='도다리 실행화면'/>

<br/>

## 번역 결과
아래와 같이 두개의 파일이 만들어집니다. 

<p align="center">도다리 번역 - 번역문(원문)파일</p>
<img src='https://github.com/vEduardovich/dodari/assets/20391482/4227a0bc-9d37-4ebf-b2c1-2d50807ce3c7' style='border-radius:10px;margin-right:10px;' title='한영 번역화면'/>

<br/>

<p align="center" >도다리 번역 - 번역문파일</p>
<img src='https://github.com/vEduardovich/dodari/assets/20391482/a46d3608-4b88-4a18-9b85-406cb90713ff' style='border-radius:10px;' title='한글 번역화면'/>

<p align="center" >(참고) DeepL 번역</p>
<p>"토끼굴 아래로 앨리스는 언니 옆에 앉아서 할 일이 없는 것에 매우 지치기 시작했고, 언니가 읽고 있는 책을 한두 번 들여다봤지만, 그 책에는 그림이나 대화가 없었습니다."그림이나 대화가 없는 책이 무슨 소용이 있을까?"앨리스는 생각했습니다. "그래서 그녀는 데이지 사슬을 만드는 즐거움이 일어나서 데이지를 따는 수고로움의 가치가 있는지, (더운 날이 그녀를 매우 졸리고 멍청하게 만들었 기 때문에 가능한 한 잘 생각했습니다) 마음 속으로 생각하고 있었는데 갑자기 분홍색 눈을 가진 하얀 토끼가 그녀 곁으로 달려갔습니다."거기에는 그렇게 놀라운 것도 없었고 앨리스도 토끼가 스스로 말하는 것을 듣는 것이 그렇게 매우 이상하게 생각하지 않았습니다."오 맙소사! 오, 이런! 너무 늦겠어!" (나중에 곰곰이 생각해보니 앨리스가 이걸 궁금해했어야 했다는 생각이 들었지만, 그 당시에는 모든 것이 아주 자연스러워 보였습니다); 
"그러나 토끼가 실제로 양복 조끼 주머니에서 시계를 꺼내어 그것을 보고는 서둘러 가자 앨리스는 발걸음을 재촉했습니다. 왜냐하면 양복 조끼 주머니를 가진 토끼나 시계를 꺼내는 토끼를 본 적이 없다는 생각이 스쳐 지나갔고, 호기심에 불타서 그 토끼를 따라 들판을 가로질러 뛰어갔을 때 마침 울타리 아래 커다란 토끼 구멍으로 토끼가 튀어 나오는 것을 보았기 때문입니다."
"앨리스는 도대체 어떻게 다시 빠져나올 수 있을지 한 번도 생각하지 않은 채 토끼굴을 따라 내려갔고, 토끼굴은 터널처럼 곧장 이어지다가 갑자기 아래로 가라앉아 앨리스는 멈출 생각을 할 틈도 없이 아주 깊은 우물 속으로 떨어지는 자신을 발견했다."</p>
<p align="center" >(참고) 구글 번역</p>
<p>“앨리스는 은행에서 여동생 옆에 앉아 있고 할 일이 없는 것에 매우 지치기 시작했습니다. 한두 번 그녀는 여동생이 읽고 있는 책을 들여다 보았지만 그 안에 그림이나 대화가 전혀 없었습니다. "그림이나 대화가 없는 책이 무슨 소용이 있겠는가?"라고 앨리스는 생각했습니다. 데이지 체인을 만드는 즐거움이 일어나서 데이지를 따는 수고를 할 만큼 가치가 있을지에 대해 그녀 자신의 마음 속에서 (그리고 그녀는 할 수 있는 한, 더운 날 때문에 그녀는 매우 졸리고 멍청하다고 느꼈다) 갑자기 백인이 분홍색 눈을 가진 토끼가 그녀 옆으로 달려왔습니다. 그다지 주목할만한 점은 없었습니다. 앨리스는 토끼가 혼잣말하는 것을 듣고도 별로 이상하다고 생각하지 않았습니다. “오 이런! 이런! 너무 늦을 것 같아요!” (나중에 그녀가 곰곰이 생각해보니, 그녀는 이것에 대해 궁금해했어야 했다는 생각이 들었지만, 당시에는 모든 것이 아주 자연스러워 보였습니다.)
“그러나 토끼가 실제로 양복 조끼 주머니에서 시계를 꺼내서 살펴보더니 서둘러 갔을 때, 앨리스는 일어서기 시작했습니다. 그녀는 양복 조끼 주머니나 시계를 꺼내려고 호기심에 불타서 그것을 쫓아 들판을 가로질러 달려갔고, 때맞춰 그것이 울타리 아래 커다란 토끼 굴로 떨어지는 것을 보았습니다.”
"또 다른 순간에 앨리스는 그 뒤를 따라 내려갔습니다. 도대체 그녀가 다시 나갈 수 있다는 생각은 단 한 번도 하지 않았습니다. 토끼굴은 어떤 식으로든 터널처럼 곧게 이어지다가 갑자기 아래로 내려갔습니다. 너무 갑자기 내려가서 앨리스는 더 이상 빠져나갈 수 없었습니다. 그녀가 아주 깊은 우물처럼 보이는 곳으로 떨어지기 전에 자신을 멈추는 것에 대해 생각할 순간이었습니다.”</p>

<br/>

## 설치 및 실행
공통,
> 1. **먼저 파이썬이 설치되어 있어야 합니다.** 윈도우에는 파이썬이 기본으로 설치되어 있지 않습니다.
> 2. https://wikidocs.net/8 를 참고하여 쉽게 설치하실수 있습니다.

<br/>

초보자라면,
1. <a href='https://github.com/vEduardovich/dodari/archive/refs/heads/main.zip' title='압축 파일 다운로드' style='text-align:center'>압축 파일 다운로드</a> 클릭
2. 압축해제 후 
> - 윈도우 사용자는 start_windows.bat 더블 클릭
> - 맥이나 우분투 사용자는 터미널 창에서 sh start_mac.sh 실행
3. 처음 실행이라면 프로그램을 자동으로 설치한 후 실행합니다. 이미 설치가 되었다면 바로 실행합니다.

<br/>

고급 사용자라면,
1. git clone https://github.com/vEduardovich/dodari.git
2. cd dodari
3. 아래 방법으로 실행하기
> - 윈도우는 start_windows.bat 실행
> - 맥, 우분투는 sh start_mac.sh 실행

_첫 실행시 관련 프로그램 설치와 AI 모델을 다운로드 하는데 아주 오랜 시간이 걸립니다!</span>_

<br/>

## 번역 속도 비교
헤르만 헤세의 싯다르타 text과 이상한 나라의 앨리스(영문판).epub을 번역해봤습니다.
<table>
  <thead>
    <tr>
      <th>사양</th>
      <th>운영체제</th>
      <th>CPU</th>
      <th>GPU</th>
      <th>문장수</th>
      <th>싯다르타.txt</th>
      <th>이상한나라의 앨리스.epub</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>LG전자 2020 그램 17</td>
      <td>윈도우10</td>
      <td>i7 (1.3GHz)</td>
      <td>내장그래픽</td>
      <td rowspan=4>378KB<br/>2577개</td>
      <td>2시간 55분 24초</td>
      <td>3시간 45분 6초</td>
    </tr>
    <tr>
      <td>Mac Pro M1</td>
      <td>iOS</td>
      <td>10코어</td>
      <td>16코어</td>
      <td>54분 23초</td>
      <td>1시간 13분 5초</td>
    </tr>
    <tr>
      <td>데스크탑</td>
      <td>Ubuntu22.04</td>
      <td>i9-13900k</td>
      <td>RTX4090 24GB</td>
      <td>5분 25초</td>
      <td>7분 20초</td>
    </tr>
    <tr>
      <td>데스크탑</td>
      <td>윈도우11</td>
      <td>i9-13900k</td>
      <td>RTX4090 24GB</td>
      <td>11분 49초</td>
      <td>14분 36초</td>
    </tr>
  </tbody>
</table>

<br/>

<h3>> EEVE-Korean-Instruct-10.8B-v1.0 모델</h3>
이상한나라의 앨리스.epub, RTX 4090으로 테스트
<table>
  <thead>
    <tr>
      <th>상태</th>
      <th>걸린시간</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>vllm 미적용시</td>
      <td>4시간 7분 26초</td>
    </tr>
    <tr>
      <td>vllm 적용시</td>
      <td>40분 5초</td>
    </tr>
  </tbody>
</table>

<br/>

## 디렉토리 구조
```
dodari
├⎯ models : AI가 다운로드되는 폴더
├⎯ venv   : 도다리 실행을 위한 관련 파일들이 설치되는 폴더
├⎯ imgs   : 도다리 이미지
```

<br/>

## 최신 버전으로 업데이트 하기
초보자라면,
1. 위 압축파일을 다시 다운로드하고 압축을 푼후
2. 기존 도다리 폴더안에 덮어쓰면 됩니다.

고급 사용자라면,
1. git pull

<br/>

## 삭제하기
- 폴더 전체를 지우면 깨끗하게 지워집니다.

<br/>

## 최신 업데이트 정보[24.04.20]
1. ext dot 중복제거
2. 주요 라이브러리 버전 fix