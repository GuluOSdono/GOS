GOS - GuluOS

GOS é um sistema operacional(versão atual) 16 bits, sendo feito em puro assembly, contendo sua propria lingaugem .gos e .gsc , sendo uma para softwares e jogos(.gos) e outra pra configrtacoes do sistema e apps

• versão nova sempre em 1 ou 2 semanas(as vezes até menos)

sei la oque colocar a mais kk

comandos pra executar(qemu):

0.4.x:
qemu-system-i386 -drive format=raw,file=guluos.img,if=flopp

antes da 0.4:
qemu-system-i386 -fda guluos.img

ATENÇÂO:
esses comandos antes da 0.4 são assim pois nessas versoes nao tinha armazenamento totalemente funcional, apenas na RAM em tempo real, então quando você executa esses comandos em versoes mais modernas como
as depois da 0.4.x ou sendo a 0.4, ele nao salvara direto no .img que foi baixado

entao nao espere as versoes antigas salvar algo, apenas as novas salvam
