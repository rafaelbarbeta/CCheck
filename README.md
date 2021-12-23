# CCheck
Um shell script de Linux simples que compara outputs de um programa em C com uma série de arquivos

Utilização:
CCheck <programa_em_c_binario> <pasta_de_saidas>


O CCheck suporta atualmente 10, e apenas 10, arquivos de saidas na pasta_de_saidas. Todos eles devem ser da forma output1.out, output2.out, output3.out etc...

Para que o CCheck funcione direto do terminal sem a necessidade do "./", recomenda-se colocar o arquivo em /home/<nome_usuario>/bin. Em seguida, atualize o arquivo .bashrc colocando a seguinte linha:

PATH=$PATH:/home/<nome_usuario>/bin

Isso fará com que o sistema operacional busque o comando nessa pasta automaticamente. Lembrando que para achar o arquivo .bashrc, será necessário ir até o diretório /home/<nome_usuario> e inserir ls -a para achar o arquivo "escondido"

