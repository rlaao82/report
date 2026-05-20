# AI 활용 현황 대시보드

## Vercel 배포 방법 (클릭만으로 완료)

### 1단계 — GitHub에 올리기

1. [github.com](https://github.com) 로그인
2. 우측 상단 **+** → **New repository**
3. Repository name 입력 (예: `ai-dashboard`) → **Create repository**
4. **uploading an existing file** 링크 클릭
5. 이 ZIP 파일을 압축 해제한 폴더 안의 **모든 파일**을 드래그해서 업로드
6. **Commit changes** 클릭

### 2단계 — Vercel에서 배포

1. [vercel.com](https://vercel.com) 접속 → **Sign Up** (GitHub 계정으로 로그인)
2. **Add New... → Project** 클릭
3. GitHub 저장소 목록에서 방금 만든 저장소 선택 → **Import**
4. 설정 그대로 두고 **Deploy** 클릭
5. 1~2분 후 완료 → 링크 생성됨! 🎉

### 3단계 — 링크 공유 방법 (사내 인원 제한)

배포 후 생성된 `https://ai-dashboard-xxxx.vercel.app` 링크를
슬랙/이메일로 사내 인원에게만 전달하세요.

> 💡 URL을 외부에 공개하지 않으면 사실상 내부 공유로 운영 가능합니다.
> 더 강한 접근 제한이 필요하면 Vercel Pro (Password Protection) 또는
> 사내 서버 배포를 검토해보세요.

---

## 로컬에서 실행하는 방법 (선택사항)

```bash
npm install
npm run dev
```

브라우저에서 `http://localhost:5173` 접속
