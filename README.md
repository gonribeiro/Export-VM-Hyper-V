# Realiza a exportação de uma VM no Windows Server Hyper-V

Para um caso MUUUUITO específico (realizar backup diário de uma VM que ficava fora do cluster/storage/snapshot).

- O backup ocorria pela execução do .bat diariamente através de um agendador de tarefas no próprio Windows.
- Primeiro, apaga a pasta/VM onde estaria a cópia já armazenada anteriormente.
- Após, inicia uma nova cópia da mesma VM.