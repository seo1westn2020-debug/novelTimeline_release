# Release Repo Assets

`novelTimeline_release` (공개 배포 리포)의 **README·페이지 노출용** 이미지를
보관한다. **로고 원본은 여기에 두지 않는다** — 원본은 소스 리포
(`novel-timeline/assets/branding/`)에 있고, 여기엔 그 중 공개용 복사본만.

## 권장 파일

| 파일명 | 용도 | 크기 권장 |
|---|---|---|
| `logo.png` | README.md 상단 히어로 이미지 | 512~1024px |
| `screenshot-timeline.png` | 타임라인 뷰 스크린샷 | 1280×800 |
| `screenshot-graph.png` | 관계도 뷰 스크린샷 | 1280×800 |
| `screenshot-writing.png` | 집필 에디터 스크린샷 | 1280×800 |

## 참조 방법 (README.md)

```markdown
<p align="center">
  <img src="./assets/logo.png" alt="novel-timeline" width="200" />
</p>
```

## 규칙

- **이 폴더의 파일은 가공본** — 수정이 필요하면 원본
  (`novel-timeline/assets/branding/`)에서부터 재가공 후 복사.
- 스크린샷 업데이트 시 UI 변경 일자와 버전을 커밋 메시지에 기록.
