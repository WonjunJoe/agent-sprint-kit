# agent-sprint-kit

사람 한 명과 코딩 에이전트(Codex · Claude Code · Cursor)가 만들고, 끝에 사람이 혼자 설명까지 할 때 쓰는 작업 규칙.
결과물이 아니라 **일하는 방식**이다 

중복 없고 체계적인 workflow를 지향하고, 특이하고 새로운 방식보다 시장에서의 convention을 파악하고 적절히 따른다. 

- [`AGENTS.md`](AGENTS.md) — 에이전트가 읽는 규칙. 작업 폴더 맨 위에 두면 Codex 가 알아서 읽는다.
- 이 README — 사람이 보는 순서와 말 모음.

## 쓰는 법

```sh
git clone https://github.com/WonjunJoe/agent-sprint-kit ~/kit
cd <작업 폴더>
[ -f AGENTS.md ] || cp ~/kit/AGENTS.md .   # 이미 있으면 덮지 않는다
codex
```
