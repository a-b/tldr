# gow

> Go 파일을 관찰하고 변경 사항이 있으면, 앱을 다시 시작.
> 더 많은 정보: <https://github.com/mitranim/gow>.

- 현재 디렉터리를 시작하고 감시:

`gow run .`

- 지정된 인수를 사용하여 애플리케이션을 시작:

`gow run . {{인수1 인수2 ...}}`

- 상세 모드에서 하위 디렉터리를 보기:

`gow -v -w={{경로/대상/디렉터리1,경로/대상/디렉터리2,...}} run .`

- 지정된 파일 확장자를 확인:

`gow -e={{go,html}} run .`

- 도움말 표시:

`gow -h`
