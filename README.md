GOS - GuluOS

GOS é um sistema operacional(versão atual) 32 bits, sendo feito em assembly e C, contendo sua propria lingaugem .gos e .gsc , sendo uma para softwares e jogos(.gos) e outra pra configrtacoes do sistema e apps

• versão nova sempre em 1 ou 2 semanas(as vezes até menos)

sei la oque colocar a mais kk

• comandos pra executar(apenas versoes 16bits qemu):

0.4.x:
qemu-system-i386 -drive format=raw,file=guluos.img,if=flopp

antes da 0.4:
qemu-system-i386 -fda guluos.img

ATENÇÂO:
esses comandos antes da 0.4 são assim pois nessas versoes nao tinha armazenamento totalemente funcional, apenas na RAM em tempo real, então quando você executa esses comandos em versoes mais modernas como
as depois da 0.4.x ou sendo a 0.4, ele nao salvara direto no .img que foi baixado

entao nao espere as versoes antigas salvar algo, apenas as novas salvam

• comandos pra exeutar(apenas 32bits, mas acho que da 16 bits tambem, qemu):
qemu-system-i386 -drive format=raw,file=guluos-mp.img,if=floppy

• fotos:
<img width="727" height="461" alt="image" src="https://github.com/user-attachments/assets/883ab397-4429-4f72-b8c7-38969fe6b172" />
<img width="725" height="461" alt="image" src="https://github.com/user-attachments/assets/beb5a479-868b-4863-8264-6dbc08402afe" />
<img width="646" height="458" alt="image" src="https://github.com/user-attachments/assets/6196b039-f463-4a74-91e5-f4cd9563c2ed" />

e tambem, tem tipo um nome pra cada versao do guluos,do 16, 32, 64 bits:
16 bits = guluos MR(modo real)
32 bits = guluos MP(modo protegido)
64 bits = guluos ML(modo longo)
