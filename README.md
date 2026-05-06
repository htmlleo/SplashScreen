# AppIntegrantesCalculadora

Este é um aplicativo Android desenvolvido em Kotlin como parte de um projeto acadêmico.

## Funcionalidades:
*   **SplashScreen (IntroActivity)**: Uma tela de introdução com um logotipo e um texto "Carregando...", exibida por 5 segundos. A Activity é configurada com `android:noHistory="true"` no `AndroidManifest.xml` para que não seja possível retornar a ela após a transição.
*   **Tela Principal (MainActivity)**: Contém um `TabLayout` com duas abas:
    *   **Aba de Integrantes**: Exibe uma lista de cards com informações dos integrantes da equipe. Ao clicar em um integrante, uma nova tela (`MemberDetailActivity`) mostra os detalhes completos.
    *   **Aba de Calculadora de Médias**: Uma calculadora simples que permite inserir três notas e calcula a média. Com base na média, exibe o status do aluno (Reprovado direto, Em recuperação, Aprovado) utilizando um `Snackbar`. Inclui um botão de reset para limpar os campos.

## Integrantes da Equipe:
*   **Leonardo Estevão Alves** - R.A: 00250458-1
*   **Vinicius Correia De Andrade** - R.A: 251953-1

## Como Importar e Executar no Android Studio:
1.  **Baixe o arquivo ZIP** fornecido.
2.  **Extraia** o conteúdo do ZIP para uma pasta de sua preferência.
3.  Abra o **Android Studio**.
4.  Na tela de boas-vindas, selecione **"Open an existing Android Studio project"** ou, se já estiver com um projeto aberto, vá em `File > Open`.
5.  Navegue até a pasta onde você extraiu o projeto (**AppIntegrantesCalculadora**) e selecione-a.
6.  O Android Studio irá carregar o projeto e sincronizar o Gradle automaticamente. Aguarde a conclusão da sincronização (pode levar alguns minutos na primeira vez).
7.  Após a sincronização, você pode **executar o aplicativo** clicando no botão `Run` (ícone de play verde) na barra de ferramentas, selecionando um emulador ou um dispositivo físico conectado.
