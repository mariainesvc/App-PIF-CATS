# App PIF Gatinha (Android)

## Como obter o APK (sem Android Studio)
1. Cria conta gratuita em github.com e um repositório novo e privado (ex.: `pif-gatinha`).
2. No repositório, carrega **todo o conteúdo** desta pasta (inclui a pasta oculta `.github`).
   Dica: descomprime o zip, usa "Add file → Upload files" e arrasta tudo; confirma que `.github/workflows/build.yml` ficou lá.
3. Separador **Actions** → corre "Build APK" (arranca sozinho ao carregares; demora ~5 a 8 minutos).
4. Quando ficar verde, abre a execução e descarrega **pif-gatinha-apk** (zip) → dentro está `app-debug.apk`.
5. Passa o APK para o telemóvel, abre-o e permite "instalar de fontes desconhecidas" quando pedir.
6. Na app: Definições → ativa as notificações → Guardar → aceita a permissão.

## Notas
- Dados guardados no telemóvel. Atualizações: instala o novo APK por cima (mantém os dados).
- Se os avisos atrasarem, tira a app da poupança de bateria nas definições do Android.
