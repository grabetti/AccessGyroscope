AccessGyroscope
===============

Imprime os valores do Giroscópio na tela.


--- Objetivo da aplicação
Esta é uma app simples que tem como objetivo imprimir os dados do Giroscópio na tela do mobile e,
ainda, enviar os dados à um server para este tbm imprimir no monitor.

--- Passos

1) Solicitar as permissões do GYROSCOPE e da INTERNET no AndroidManifest.xlm
    <uses-feature android:name="android.hardware.gyroscope"/>
    <uses-permission android:name="android.permission.INTERNET" />
    
2) Usar um TextView para mostrar os dados na tela.

3) Implementar os comandos da classe principal - AccessGyroscope

4) Implementar a classe de conexão com o Server.

5) Instanciar a classe de Conexão na classe principal e chamar o método "sendMessage(String ZYX);"
