# DreamHack rev-basic-1 Writeup
워게임 주소: https://dreamhack.io/wargame/challenges/15

## 정적 분석

### IDA로 main 함수 분석

rev-basic-0과 크게 다를게 없는 코드이다. sub_140001000함수를 바로 분석해보겠다.

<img width="608" alt="스크린샷 2024-08-27 오후 7 58 15" src="https://github.com/user-attachments/assets/5f81d09a-9b40-47c5-a713-67037e96df2a">

### sub_140001000 함수 분석

배열을 하나씩 가져와 값을 비교하는 것을 알 수 있다.
파이썬을 활용해서 hex값을 문자로 치환하여 flag를 얻을 수 있다.

<img width="331" alt="스크린샷 2024-08-27 오후 7 58 31" src="https://github.com/user-attachments/assets/5bb9013f-6a4a-4259-bcae-9f6baec5d838">

<img width="565" alt="스크린샷 2024-08-27 오후 8 01 51" src="https://github.com/user-attachments/assets/5ab28668-a848-40d0-a4b2-a50761455970">

## 결론

<img width="805" alt="스크린샷 2024-08-27 오후 8 02 05" src="https://github.com/user-attachments/assets/4f6b9b05-885c-4e3a-b62d-647b8bbbe856">

<img width="797" alt="스크린샷 2024-08-27 오후 8 02 16" src="https://github.com/user-attachments/assets/27234537-477d-4b94-ae99-070cc6fcf7fd">
