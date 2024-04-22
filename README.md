# wepappTM-02

## https://parkhdo.github.io/wepappTM-02/

## 웹페이지에 웹캠을 통해 실시간으로 캡처된 이미지를 표시하고, 

## Teachable Machine을 사용하여 해당 이미지를 분류하는 기능을 구현한 것입니다. 여러 가지 기술과 리소스를 사용하여 이를 가능하게 합니다.

## HTML 구조:

- model-info: Teachable Machine 모델 정보를 표시하는 영역입니다.
- webcam-container: 웹캠 비디오를 표시하는 영역입니다.
- label-container: Teachable Machine 모델의 예측 결과를 표시하는 영역입니다.
- button: 웹캠을 시작하는 버튼입니다.

## CSS 스타일:
- body: 페이지 전체의 스타일을 설정합니다. 여기서는 페이지를 세로 중앙 정렬하고 배경색을 지정합니다.
- webcam-container: 웹캠 비디오 영역의 스타일을 설정합니다. 여기서는 웹캠 비디오를 원형으로 설정하고, 오버플로우를 숨겨 원형으로 보이게 합니다.
- 기타 스타일: 버튼과 모델 정보 등의 스타일을 설정합니다.

## JavaScript:
- init(): 페이지가 로드될 때 호출되는 함수입니다. Teachable Machine 모델을 로드하고 웹캠을 설정하여 비디오를 표시합니다.
- loop(): requestAnimationFrame()을 사용하여 화면을 반복적으로 업데이트합니다. 웹캠 이미지를 업데이트하고 모델을 사용하여 예측을 수행합니다.
- predict(): Teachable Machine 모델을 사용하여 웹캠 이미지의 예측을 수행하고 결과를 표시합니다.

## Teachable Machine:
- Teachable Machine은 구글에서 제공하는 온라인 플랫폼으로, 사용자가 간단한 방식으로 이미지 분류 모델을 만들고 훈련시킬 수 있습니다.
- 이 코드에서는 Teachable Machine에서 내보낸 이미지 분류 모델을 사용하여 웹캠 이미지를 실시간으로 분류합니다.
- 이 코드를 실행하면 웹페이지에서 시작 버튼을 클릭하여 웹캠을 활성화할 수 있습니다. 웹캠이 활성화되면 실시간으로 웹캠 비디오가 표시되고, Teachable - Machine 모델을 사용하여 해당 이미지를 분류합니다. 분류된 결과는 화면에 표시됩니다.
