# korean-writing

한국어 산출물(PRD·스펙·공지·목업 문구·노션 문서)의 문장을 사람이 쓴 글처럼 고치는 Claude Code 스킬입니다. 번역투, 빈 관용구, 리듬 문제를 잡고, 문서에 들어가면 안 되는 메타 문장과 미확정 예시까지 봅니다.

모든 항목은 실제 문서 작업에서 지적받은 것을 모았습니다.

## 설치

```bash
git clone https://github.com/yunju-happy/korean-writing.git
ln -s "$PWD/korean-writing/skills/korean-writing" ~/.claude/skills/korean-writing
```

Claude Code에서 "문장 어색한데", "AI 티 나는데", "읽기 좋게 다듬어줘"처럼 말하면 켜집니다.

## 출처와 라이선스

일부 분류(§1, §3-1~3-3, §3-7)는 [im-not-ai / humanize-korean](https://github.com/epoko77-ai/im-not-ai)(MIT)에서 가져와 줄였습니다. 이 저장소도 MIT 라이선스입니다.
