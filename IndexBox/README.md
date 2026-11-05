# IndexBox — primeira versão Android

## Como compilar sem Android Studio
1. Envie todos os arquivos desta pasta para um repositório GitHub.
2. No GitHub, abra a aba **Actions**.
3. Se necessário, confirme que deseja habilitar workflows.
4. Selecione **Build IndexBox APK** e clique em **Run workflow**.
5. Quando terminar, abra a execução e baixe o artefato **IndexBox-debug-apk**.
6. Dentro do ZIP baixado estará `app-debug.apk`.

Também há compilação automática quando você envia alterações para a branch `main`.

## Importante sobre privacidade
O serviço Android só recebe notificações depois que a pessoa ativa manualmente o acesso especial nas configurações do Android. O protótipo guarda as notificações localmente no aparelho e não envia mensagens para um servidor.

A primeira versão mostra uma prévia curta do texto, não um resumo semântico de IA. Notificações podem conter informações privadas. Antes de publicar o aplicativo, acrescente política de privacidade, explicação clara do acesso, opção de apagar dados e testes em diferentes versões do Android.

## Requisitos
- Android 8.0 ou superior (API 26+)
- Java 17 e Gradle 8.9 para compilação local; ou GitHub Actions para compilar na nuvem.
