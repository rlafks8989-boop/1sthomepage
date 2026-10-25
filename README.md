[README.md](https://github.com/user-attachments/files/33920873/README.md)
# 솔루션 골프 스튜디오 홈페이지

GitHub + Vercel 배포용 경량 버전입니다.

## 업로드
1. ZIP 파일을 압축 해제합니다.
2. `index.html`과 `assets/` 폴더를 **함께** GitHub 저장소 루트에 업로드합니다.
3. Commit changes를 누릅니다.
4. Vercel에서 해당 저장소를 Import하고 Framework Preset `Other`로 Deploy합니다.

**주의:** `index.html`만 업로드하면 사진이 보이지 않습니다. 반드시 `assets` 폴더도 올려 주세요. 파일이 이미 Vercel에 연결되어 있으면 커밋 뒤 자동 배포됩니다.

HTML은 자체 이미지 데이터를 포함하지 않고 상대 경로 `assets/*.webp`를 사용합니다. Vercel은 별도 빌드 없이 정적 사이트로 호스팅할 수 있습니다.
