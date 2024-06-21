# basic-Raspberry-Pi
## 라즈베리파이

## 1일차

- 전류: 전하의 흐름
- 전압: 전기장 안에서 전하가 갖는 전위의 차이
- 저항: 전기의 흐름을 방해하는 부품

- 모든 전류를 한 곳으로 모이게 하는 역할 > 그라운드
- 전압의 차이가 있어야 전류가 흐른다,

- Digital
    - 0,1 로 표기

- GPIO 설정함수
    - GPIO.setmode(GPIO.BOARD) - wpi
    - GPIO.setmode(GPIO.BCM) - BCM
    - GPIO.setup(channel, GPIO.mode)
    - channel : 핀번호, mode: IN/OUT
    1) GPIO.cleanup()
    - GPIO 출력함수
        - GPIO.output(channel, state)
        - channel: 핀번호, state: HIGH/LOW or 1/0 True/False
    - GPIO 입력함수
        - GPIO.input(channel)
        - channel : 핀번호, 반환값 : H/L or 1/0 or T/F
    - 시간지연 함수
        - time.sleep(secs)

- V(전압) = I(전류)R(저항)
옴의 법칙

2. 키르히호프 법칙
    - 전압, 전류법칙
    - 회로 중 임의의 전류의 분기점에서 흘러드는 전류의 합과 흘러나오는 전류의 합은 같아진다.
    - 회로중의 임의의 폐회로에서 전원전압(기전력)과 부하로 소비되는 전압(전압강하)의 합은 동일해진다.


## 2일차

- P