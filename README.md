# Dialogue Summarization

## Prerequisites
- wandb==0.17.8
- rouge==1.0.1
- python-mecab-ko==2.1.1
- nltk==3.9.1
- pandas==2.2.2
- pytorch_lightning==2.4.0
- pytorch==2.3.0
- torchmetrics==1.4.1
- torchvision==0.18.0
- transformers==4.44.2
- datasets==2.21.0
- evaluate==0.4.2

## 1. 개요
- 일상생활에서 대화는 항상 이루어지고 있음. 중요한 정보를 효율적으로 기록하기 위해 언어    모델을 통한 자동화 필요.
- 이를 위해, 일상 대화를 바탕으로 요약문을 생성하는 모델 구축.
- 사용자들이 중요 정보를 쉽게 확인하고 업무 효율을 높이는데 기여할 수 있음.


## 2.개발 환경
- NVIDIA GeForce RTX 3090 24GB
- AMD Ryzen Threadripper 3960X 24-Core Processor

## 3. Dataset - 대화 타입
- 일상 대화
- 쇼핑
- 전화 통화
- 직업 면접
- 음식 주문
- 인터뷰
- 길 묻기
- 영화
- 사회적 만남
- 체크인
- 면접
- 날씨
- 여행
- 초대
- 주말 계획
- 정보 요청
- 휴가
- 길 안내
- 약속 잡기
- 비즈니스 대화

## 4. Encoder Decoder fine-tuning 
![image](https://github.com/user-attachments/assets/e159d98f-01c4-4338-9c77-32872d7cb49d)
![image](https://github.com/user-attachments/assets/68259499-9123-4b86-96c6-f58093f5fca4)
## 5. Decoder only fine-tuning
![image](https://github.com/user-attachments/assets/204da899-5d3a-42e9-ac6b-d9ff41ac8fb2)

## 6. Example
![image](https://github.com/user-attachments/assets/57aaf29c-2950-48bb-8c6b-64c6753058bf)