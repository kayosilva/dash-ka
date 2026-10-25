# Dash Ka · site

Página de apresentação e download do Dash Ka (painel esportivo para o Ford Ka
no Android, via adaptador OBD2 ELM327 Bluetooth). Publicada pelo GitHub Pages
em https://dashka.app.br/ (o endereço antigo kayosilva.github.io/dash-ka redireciona).

O código do app fica num repositório privado; aqui ficam só a página, as
imagens e os vídeos. O APK vai nas **Releases** deste repositório, com o nome
`dash-ka.apk` (o botão da página aponta para `releases/latest/download/dash-ka.apk`).

## Nova versão

1. No repositório do app: subir `version:` no `pubspec.yaml` e compilar
   `flutter build apk --release --target-platform android-arm,android-arm64 --android-project-arg publico=true`
   (assinado com a chave própria: instala por cima da anterior).
2. Criar uma Release aqui (tag `v1.0.1`, por exemplo) com o APK renomeado para `dash-ka.apk`.
3. Atualizar a versão e o tamanho em `index.html` (`id="versao"`).

Projeto pessoal, não oficial, sem relação com a Ford Motor Company.
