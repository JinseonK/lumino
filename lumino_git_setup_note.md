# GitHub 연동 노트 - 루미노 프로젝트

🗓️ 날짜: 2025-06-11  
📁 프로젝트: **lumino**

---

## ✅ 1단계. GitHub 리포지토리 생성
- 이름: `lumino`
- 공개여부: Public
- 옵션: `Add README.md` ✅ 선택

---

## ✅ 2단계. 로컬 폴더 생성 및 VS Code 열기
- 바탕화면에 `lumino` 폴더 생성
- VS Code에서 열기

---

## ✅ 3단계. Git 초기화 및 테스트 파일 생성
```bash
git init
echo "Hello Lumino" > test.txt
```

---

## ✅ 4단계. 첫 커밋
```bash
git add .
git commit -m "Premier commit"
```

---

## ✅ 5단계. 브랜치 이름 변경
```bash
git branch -M main
```

---

## ✅ 6단계. 원격 저장소 연결
```bash
git remote add origin https://github.com/JinseonK/lumino.git
```

> 이미 연결돼 있다면:
```bash
git remote remove origin
git remote add origin https://github.com/JinseonK/lumino.git
```

---

## ✅ 7단계. Push 에러 해결 - 병합 처리
```bash
git pull origin main --allow-unrelated-histories
```

> 메시지 파일 열리면 `Ctrl + S` 후 닫기

---

## ✅ 8단계. 최종 push
```bash
git push -u origin main
```

---

## ✅ 9단계. test.txt 업로드
```bash
git add .
git commit -m "Ajout du fichier test.txt"
git push origin main
```

---

## 🏁 최종 확인
- ✅ README.md + test.txt 업로드 완료
- 🔗 https://github.com/JinseonK/lumino
