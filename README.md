# AIoT_LLM_Steak_classifier
GPT-4-Vision 을 활용한 고기 익음정도를 알려주는 봇
# [AIoT] LLM Steak Classifier AIoT Bot

## 프로젝트 설명
이 프로젝트는 LLM을 사용하여 이미지를 인식하고, fewshot 프롬프팅을 통해 컨텍스트를 만들어 멀티모달을 구현합니다. 이를 임베디드 환경에 적용하여 AIoT 환경을 구축했습니다.

## 하드웨어 구성요소
- WIZnet - W6100-EVB-Pico x 1
- Raspberry Pi - Raspberry Pi 4 x 1

## 프로젝트 스토리
OpenAI의 발표로 GPT의 성능이 향상되었고, 이미지 캡처를 위한 GPT-4-Vision 모델이 소개되었습니다. 이 프로젝트는 AI와 프롬프트에 대한 지식을 활용하여 고기 요리와 같은 주관적인 작업을 얼마나 잘 수행할 수 있는지 탐구합니다.

## 프로젝트 흐름
1. GPT-4-vision을 사용하여 고기에 대한 설명과 함께 이미지를 인식하고 저장합니다.
2. Streamlit 웹 서버에서 이미지 인식 및 저장 프로세스를 실행합니다.
3. Raspberry Pi와 W5100S-EVB-PICO를 사용하여 위의 프로세스를 실행합니다.
4. 사용자는 고기의 익힘 정도에 대해 질문할 수 있으며, 시스템이 응답한 후 고기를 섭취할 수 있습니다.

## 소스 코드(S/W)
Vision 사용을 위해 공부한 코드를 기반으로 코드를 업로드했으며, LLM을 위한 langchain 라이브러리도 업로드했습니다.

## 소스 코드(H/W)
위의 SW 코드는 Raspberry Pi에서 실행되며, 웹 서버를 구축하고 서버를 pico에서 분리하여 독립적인 서버를 구축했습니다.
