# pdfxup

> PDF 페이지를 N-up으로 배치.
> N-up은 여러 페이지를 하나의 페이지에 축소 및 회전하여 그리드 형태로 배치하는 것을 의미합니다.
> 더 많은 정보: <https://ctan.org/pkg/pdfxup>.

- 2-up PDF 생성:

`pdfxup -o {{경로/대상/출력.pdf}} {{경로/대상/입력.pdf}}`

- 페이지당 3열 및 2행으로 PDF 생성:

`pdfxup -x {{3}} -y {{2}} -o {{경로/대상/출력.pdf}} {{경로/대상/입력.pdf}}`

- 소책자 모드(2-up, 페이지가 접혔을 때 책 형태로 정렬)로 PDF 생성:

`pdfxup -b -o {{경로/대상/출력.pdf}} {{경로/대상/입력.pdf}}`
