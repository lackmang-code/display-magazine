# display-magazine

성균관대학교 첨단디스플레이공학과 월간 Letter **"첨디공 ON"** 배포 저장소.

- **배포**: Cloudflare Pages → https://display-magazine.pages.dev/
- **정식 발행본**: `magazine/<YYYY-MM>/` — `index.html`이 기기(PC/모바일) 자동 분기 → `book.html`(PC 펼침면) / `phone.html`(모바일) / `print.html`(인쇄용)
- **검수용 프리뷰**: `review-*`, `preview/*` 같은 `noindex` 슬러그 폴더 — 검토 끝나면 삭제
- 과거 호는 새 호 발행 시에도 건드리지 않음 (자동 아카이브)

발행 파이프라인·칼럼 작업 방식은 `03_Magazine/성균관대_디스플레이/CLAUDE.md` 참고 (별도 관리 저장소).
