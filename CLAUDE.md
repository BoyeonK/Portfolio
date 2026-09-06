# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

김보연(kby)의 개발자 포트폴리오 저장소입니다. 코드 프로젝트가 아니라 GitHub에서 렌더링되는 `README.md` 문서가 결과물의 전부입니다. 빌드, 테스트, 린트 명령은 없습니다.

## Structure

- `README.md` — 포트폴리오 본문. 소개, 기술 스택, 프로젝트 목록으로 구성됩니다.
- `docs/images/` — README에서 참조하는 이미지 파일.

## Conventions

- 문서는 한국어로 작성하되, 기술 용어(io_uring, RUDP, Dedicated Server 등)는 영문을 그대로 사용합니다.
- README는 GitHub 렌더링을 전제로 HTML 태그(`<table>`, `<details>`)와 Markdown을 혼용합니다. 수정 시 GitHub Flavored Markdown에서 실제로 렌더링되는지 기준으로 판단해야 합니다.
- 각 프로젝트는 요약 테이블(개발 기간/인원/담당 영역/주요 기술) + 링크 + `<details>`로 접힌 상세 구현 내용 형식을 따릅니다. 새 프로젝트 추가 시 이 형식을 유지합니다.
- 커밋 메시지는 한국어로 작성합니다.

## Related repositories

실제 프로젝트 코드는 이 저장소에 없습니다. README에서 링크로 연결됩니다:

- Salvage Protocol 서버: https://github.com/BoyeonK/ExtractionServer (C++17, Linux, io_uring)
- Salvage Protocol 클라이언트: https://github.com/BoyeonK/ExtractionClient (Unity, C#)
