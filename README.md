# KiCad를 이용한 PCB(ESP32) 제작 실습
`https://github.com/rlawlgns02/PCB` 이후 실습 과정입니다
## ESP32제작 과정
## 1. 프로젝트 생성
- 프로젝트를 생성한 후 **심볼 편집기** 클릭
- **파일 - 새 라이브러리 - 전역**으로 지정해서 확인
- 라이브러리를 저장할 디렉토리를 설정하고 이름을 설정
- 이름 추천 : 숫자 4 이하로 하는경우에 항목 최상단에 떠서 매우 작업하기에 편함<br>
추천 이름 `001MyLib`<br>
![Image](https://github.com/user-attachments/assets/b4e20849-403e-42fe-a7a8-4c9e4dc9cb47)

## 2. 제작하기
- 라이브러리를 우클릭 한 후 심볼 이름 `ESP32`로 설정
- 휠을 통해서 크기를 조절

- U라는 알파벳을 보기 좋은 위쪽으로 이동하고 큰 사각형을 사각형그리기를 통해 생성<br>
![image](https://github.com/user-attachments/assets/1e4dca65-fd60-4aec-9c26-a5158bca0ee1)

- 핀 그리기 P를 눌러서 핀 생성 이름은 나중에 변경 가능하니 크게 신경 안써도 됨 핀 번호가 중요<br>
![image](https://github.com/user-attachments/assets/206eef7e-85b1-4227-a95b-92d4e4f3ed34)
- 만약 방향이 안맞으면 R 키를 이용해 방향 회전<br>
![image](https://github.com/user-attachments/assets/c0134b70-8412-43d8-9ee0-3cbf98d4ee4f)
- 핀을 올바른 위치에 놓고 나머지 핀들을 전부 배치<br>
![image](https://github.com/user-attachments/assets/65c18e87-21cf-43a3-a72f-0c27309ff8b4)
![image](https://github.com/user-attachments/assets/51b0a374-05ce-4511-a966-b56baed345fa)

- 보기좋게 가운데에 사각형 박스와 ESP32라는 텍스트를 넣음
![image](https://github.com/user-attachments/assets/fc54b9ad-dcf9-4e97-92d2-99e1dd1cd249)

- 하단부도 마찬가지로 꾸며줌
![image](https://github.com/user-attachments/assets/79fd7724-1c74-45e8-b8f3-e10e2c0f2acc)

- 각각의 선을 더블클릭 하여 핀 속성에서 핀 이름을 알맞은 이름으로 변경후 확인 클릭
![image](https://github.com/user-attachments/assets/35fd733a-186c-4211-8425-9139dd535b8d)

- 마찬가지로 모든 핀들 전부 설정하기

- 회로도 편집기에서 다음과같이 설정

- 풋프린트 편집기 열기
![image](https://github.com/user-attachments/assets/20bf40e1-b211-43d1-a1c6-ad6f529d0f9b)

- 패드 추가를 하고 패드를 더블 클릭 하여 속성 변경
![image](https://github.com/user-attachments/assets/cf936096-b2a4-4b66-b7c6-3a857b8d2362)
![image](https://github.com/user-attachments/assets/2852588f-c519-4823-a69c-3c4c01b7f8f2)


- 라이브러리 위치를 설정해서 저장한 후 기존 회로도 편집기에 있는 풋 프린트에 만든 풋 프린트로 설정
