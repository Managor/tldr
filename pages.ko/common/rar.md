# rar

> RAR 압축 도구. 선택적으로 자동 추출이 가능한 다중 볼륨 아카이브를 지원.
> 더 많은 정보: <https://manned.org/rar>.

- 하나 이상의 파일을 아카이브로 압축:

`rar a {{경로/대상/아카이브_이름.rar}} {{경로/대상/파일1}} {{경로/대상/파일2}} {{경로/대상/파일3}}`

- 디렉토리를 아카이브로 압축:

`rar a {{경로/대상/아카이브_이름.rar}} {{경로/대상/폴더}}`

- 아카이브를 동일한 크기(50M)로 분할:

`rar a -v{{50M}} -R {{경로/대상/아카이브_이름.rar}} {{경로/대상/파일_또는_폴더}}`

- 결과 아카이브에 비밀번호 설정:

`rar a -p{{비밀번호}} {{경로/대상/아카이브_이름.rar}} {{경로/대상/파일_또는_폴더}}`

- 파일 데이터와 헤더를 비밀번호로 암호화:

`rar a -hp{{비밀번호}} {{경로/대상/아카이브_이름.rar}} {{경로/대상/파일_또는_폴더}}`

- 특정 압축 레벨 사용 (0-5):

`rar a -m{{압축_레벨}} {{경로/대상/아카이브_이름.rar}} {{경로/대상/파일_또는_폴더}}`
