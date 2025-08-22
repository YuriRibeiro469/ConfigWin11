### Instruções de Instalação/Importação

Para aplicar as configurações de política de grupo em seu computador, siga estes passos. As políticas estão contidas nas pastas `GroupPolicy` e `GroupPolicyUsers` que você deve ter recebido.

1.  No computador de destino, navegue até o diretório `C:\Windows\System32\`.
2.  **Importante:** Faça um backup das pastas `GroupPolicy` e `GroupPolicyUsers` existentes neste computador, caso precise reverter as alterações no futuro.
3.  Cole as pastas de backup que você recebeu, substituindo as pastas existentes no diretório `C:\Windows\System32\`.
4.  Abra o **Prompt de Comando como Administrador** e execute o seguinte comando para forçar a aplicação das políticas:

    ```cmd
    gpupdate /force
    ```

5.  Reinicie o computador para garantir que todas as configurações entrem em vigor.
