# BlackBerry Keyboard 설치 및 설정 가이드 (Key2 + LineageOS)

> ⚠️ 주의: 이 가이드는 **개인 간 공유용**입니다.

---

## 1️⃣ 준비

1. 압축 파일을 해제합니다.
2. APK 파일 2개를 준비합니다:

- `BBKeyboard.apk`
- `BlackBerryKeyboard.apk`

> https://drive.google.com/drive/folders/179OaVKUlvlhCRFaNlnutaVMijCxAzX6-?usp=sharing

---

## 2️⃣ 설치

> krab 버전의 ROM을 사용하고 있다면 BlackBerry Keyboard R을 설치해주시면 됩니다.

> 아래의 내용은 krab ROM에는 해당되지 않습니다.
> 
> krab ROM을 사용할 것을 권장합니다.

APK 파일 2개를 디바이스에 설치합니다.

- 설치 순서는 상관없습니다.
- 설치 방법 예시: ADB 또는 직접 설치 가능

```bash
adb install BBKeyboard.apk
adb install BlackBerryKeyboard.apk
```

---

## 3️⃣ 키보드 활성화 및 언어 설정

1. 설정 → **System** → **Keyboard** → **On-screen keyboard** 로 이동
2. 설치된 키보드 확인 및 활성화

- `BBKeyboard`
- `BlackBerry Keyboard`

3. 각 키보드의 **Input languages** 설정:

- `Korean`
- `Alphabet(QWERTY)`

> ⚠️ 한영 전환 키가 기존 `$`키가 아닌 **sym 키**로 변경되어 있습니다.
> 스크린에서 터치하여 한영 전환을 수행해야 합니다.

---

## 4️⃣ BBKeyboard 종속성 문제

- BBKeyboard는 **종속성 문제**가 있어 수정된 버전을 사용합니다.
- 수정 및 빌드 후 배포된 버전을 사용하면 정상 동작합니다.

---

## 5️⃣ 사용 팁

- 한글 입력 모드에서도 영문 입력 가능
- 재부팅 후 잠금을 해제하고 IME가 로드 되는 시간(15초) 정도 기다리고 사용하는 것을 추천드립니다.

