
# 84EC(S) Pro-Ble Keyboard (Non-RGB)
한국어 번역 메뉴얼

_by smallbee_ \
_last edit  2018.11.20_

<br>

pull request는 언제나 환영합니다 :)


<br>


## 5.1 Modes
키보드에 '오피스', '프로그램' 두 가지 모드가 있습니다. 기본적으로 오피스모드가 적용되며, 프로그램 모드에서는 KB84 설정 프로그램으로 키를 맵핑할 수 있습니다.
모드를 변경하기 위해서는 Fn + F12/(M) 를 동시에 3초 동안 누르십시오.
프로그램 모드에 진입하면 F12(M) 키에 붋이 들어오게 됩니다. 오피스모드로 다시 돌아가려면 다시 한번 키를 누르면 됩니다.

<br>


## 5.2 단축키, Hotkeys
* Fn + ⤓ (F9) : APC(입력 포인트 깊이 조절) 모드 스위치로 낮은(로우) 단계(CAPSLOCK 1번 점멸)와 높은(하이) 단계(CAPSLOCK 2번 점멸)가 있음

    * 기본 모드 = 2.5mm ; 로우 모드 = 2mm ; 하이 모드 (2 flashes) = 3mm
    * pc에 다시 연결하면 기본 모드가 적용됩니다. (2.5mm)
    * 이전 버전의(F9키에 ⤓ 모양이 없는) plum84를 사용하고 계신분은 “FN + PAGEUP / PAGEDOWN” 키를 누르십시오.

* Fn + Win : 윈도우 키 잠금
* Fn + Win⇌Alt : 윈도우 키와 Alt 키 바꾸기
* Fn + ⥮ (F8) : Caps Lock 키와 Ctrl 키 바꾸기
* Fn + Pause : ScrLock
* Fn + PrScr : NumLock
* Fn + Esc : NumLock 잠금 (다른 키보드의 NumLock도 잠금)

<br>


## 5.3  블루투스 기능
* Fn + 1 or 2 or 3 : 새로 블루투스 연결을 하는 경우 3초간 해당키 입력 (해당 키 불빛이 빠르게 점등)
* Fn + 1 or 2 or 3 : 기존에 등록된 블루투스 간에 이동을 할 경우 빠르게 해당 키 입력 (연결에 성공하면 5초간 불빛 점등)
* Fn + `(~) : 블루투스 모드와 유선 모드 전환

<br>


## 6.1 블루투스 불빛
* 빠른 점등 = 페어링 모드(연결 대기 모드)
* 느린 점등 = 연결됨
* 계속 점등 = 연결됨 (5초 후에 꺼짐)

<br>


## 6.2 배터리 불빛 (`(~) 키)
* on = 충전 중
* off = 충전 완료
* blinking = 배터리 부족

<br>


## 6.3 불빛 세기 조정
* Fn + ↑/↓ : 4 단계의 불빛 세기 조정

<br>


## 7.0 고속 충전
빠른 충전을 위해서는 2A USB 충전기를 사용하십시오

<br>


## 8.0 공장 초기화

키보드 네 구석의 키를 동시에 5초간 입력 (Esc, Ctrl(Left), →(우측 방향키), Delete)

<br>


# 추가 사항

## 9. 맥OS에서 블루투스 모드로 사용시에 F1-F12에서 정상적으로 작동하지 않는 문제

맥 OS에서 블루투스 모드로 키보드를 사용할 경우 Fn + F1 - F12 키가 정상적으로 작동하지 않게 됩니다. \
이 문제는 NiZ 키보드에서 Fn + F1-F12 키를 미디어 키로 사용하는데 이것이 NiZ 키보드를 지원하는 맥OS의 애플 키보드 드라이버의 기본 동작과 충돌이 일어나는데 그 원인이 있습니다. \
이 때문에 기존 맥 OS에서 사용하던 Fn + F1-F12 키가 정상적으로 작동하지 않게 되는 것입니다.
문제에 대한 근본적인 해결방법은 아니지만, F1-F12 키 또는 Fn + F1-F12 키 기능 중 하나만 사용하는 경우 다음과 같은 기본 맥 설정 방법을 이용할 수 있습니다.
('시스템 환경설정' > '키보드' > 'F1, F2 등의 키를 표준 기 키로 사용' 에서 사용하기 원하는 설정으로 지정) 

<br>

(*해당 문제 해결에 레딧의 ksmigrod 유저의 글을 참고했습니다.) \
"On Linux in Bluetooth mode this keyboard is supported by Apple keyboard driver. This driver tries to mimic Apple keyboard behaviour and does conversion from function key (F1-F12) to media key codes on the fly. NiZ keyboard does not send any codes for its function key, so Linux's keyboard driver cannot map Fn+F1 to F1." \
 https://www.reddit.com/r/MechanicalKeyboards/comments/6yieo6/review_plum_84_35g_bluetooth_nonrgb/   

<br>


## 10. KBD84 소프트웨어 관련
KBD84 소프트웨어를 통해 키를 변경할 경우, ReadAll 버튼을 통해 현재 키보드에 맵핑된 키를 먼저 읽어들어야 합니다. \
ReadAll 버튼을 누르지 않고 맵핑을 진행할 경우 실제 키보드에 어떠한 변경사항도 적용되지 않습니다.

<br>


## 11. 키 작동 불능 시 Calibration 방법
파일 위치 : Software > CalibrationiLite > CalibrationLite.exe

(본 프로그램은 윈도우 환경에서만 작동합니다)

동영상 참고 : http://v.youku.com/v_show/id_XMzQxMjg5MzA0NA==.html?x&sharefrom=android&sharekey=b64f9bbcfb7ce67d6be729c0b98844d92 \
(모바일 환경에서 접속하세요.)


1. 'ReadVersion' 버튼 클릭 \
(※ Fn + Win⇌Alt 로 윈도우 키와 Alt 키를 변경하였을 경우 'Keyboard disconnect'라는 에러 메시지 발생)


2. 'InitialCalib' 버튼 클릭 \
(2-3 초 뒤 InitialCalib 작업 종료)


3. (작동 안되는 키를 누른 채로) 'PressCalib' 버튼 클릭 \
('Press Key Calibration Finished' 라는 메시지가 나오면 완료)


4. (작동 안되는 키를 여전히 누른 채로) 소프트웨어 종료


5. 누르던 문제되는 키를 떼고, 다시 PC에 연결해서 키의 정상 작동 여부 확인

<br>

(※ 위 1-5번 방법으로도 작동되지 않을 경우 2번에서부터 작동 안되는 키를 누른 채로 진행하고, 위 과정을 여러번 거칠 것)

<br>


### 기타 사항
plum87이나 plum108을 사용하시는 분은 아래 링크를 참고하십시오. \
http://randombits.me/?p=155


### **Acknowledgements**
plum84 중국어 메뉴얼의 최초 영어 번역제공자인 레딧의 kschang에 감사를 드립니다. \
https://www.reddit.com/r/MechanicalKeyboards/comments/76pudv/can_anyone_translate_the_manual_for_the_plum_84
