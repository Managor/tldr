# docker build

> Bir Dockerfile'dan imge yaratın.
> Daha fazla bilgi için: <https://docs.docker.com/reference/cli/docker/buildx/build/>.

- Mevcut dizindeki Dockerfile'dan bir Docker imgesi oluşturun:

`docker build .`

- Belirtilen URL'deki Dockerfile'dan bir Docker imgesi oluşturun:

`docker build {{ornekadres.com/ornek-dizin/ornek-docker-projesi}}`

- Bir Docker imgesi oluşturun ve etiketleyin:

`docker build {{[-t|--tag]}} {{isim:etiket}} .`

- İmge oluştururken çerez kullanımını etkisizleştirin:

`docker build --no-cache {{[-t|--tag]}} {{isim:etiket}} .`

- Belirtilen Dockerfile ile bir Docker imgesi oluşturun:

`docker build {{[-f|--file]}} {{Dockerfile}} .`

- Kişiselleştirilmiş yapım-zaman değerleriyle oluşturun:

`docker build --build-arg {{HTTP_PROXY=http://10.20.30.2:1234}} --build-arg {{FTP_PROXY=http://40.50.60.5:4567}} .`
