# LG Smart TV — webOS

## Limite de plataforma

O procedimento Android TV/Google TV deste projeto **não se aplica diretamente ao LG webOS**. Não executar neste sistema:

- `adb shell pm uninstall ...`
- `pm disable-user ...`
- listas de pacotes do Universal Android Debloater (UAD NG)
- instalação de APK Android
- substituição de launcher/Home por métodos Android

Esses comandos e listas são específicos de Android e não constituem um método de debloat para webOS.

## Fluxo seguro

1. Confirmar o modelo exato e a versão do webOS em **Configurações → Todas as configurações → Suporte → Informações da TV** (o caminho pode variar conforme o modelo).
2. Usar apenas opções disponíveis no próprio webOS e documentadas para esse modelo.
3. Desinstalar aplicativos opcionais pela interface de gerenciamento de aplicativos, quando a TV permitir.
4. Revisar inicialização rápida, execução em segundo plano e opções de privacidade somente quando existirem no firmware e estiverem documentadas.
5. Instalar e atualizar aplicativos pela loja oficial ou pelo mecanismo oficial compatível com o modelo.
6. Manter atualizações de firmware e componentes essenciais.
7. Reiniciar a TV após ajustes e testar Home, controle remoto, rede, áudio/vídeo e aplicativos.
8. Não prometer ganhos específicos de RAM: medir apenas se o sistema oferecer uma forma confiável de obter essa métrica.

## Informações ainda necessárias

Para recomendações específicas, solicitar somente o modelo exato da TV e, se necessário, a versão do webOS. Não solicitar IP nem orientar depuração ADB para um fluxo Android que não se aplica.

## Relatório

Registrar:
- modelo e versão do webOS, se conhecidos;
- aplicativos removidos pela interface;
- ajustes aplicados;
- atualizações realizadas;
- verificações concluídas e pendentes;
- limitações de medição de RAM;
- método de reversão, quando houver.
