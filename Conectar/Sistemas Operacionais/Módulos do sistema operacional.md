
# Kernel

O **kernel** é o cerne do sistema operacional. A grosso modo é a ponte entre o **usuário** e **hardware** mas não somente. O **kernel** compõe a parte central do programa e responde por tarefas cruciais , como: 

- **Estabelecer a camada de abstração de baixo nível (linguagem de máquina) com o hardware.**
- **Gerenciar recursos como processador, RAM, sistemas de arquivos e dispositivos de entrada e saída (monitor, teclado, mouse impressora, etc...)**
- **Gerenciar processos de programas.**
- **Gerenciar o uso de dispositivos, memória do sistema e chamadas dos programas, definindo quais têm prioridade**

## Qual a diferença entre kernel e firmware?

Embora possam conversar entre si são coisas diferentes. Um firmware ou software embarcado é um conjunto de instruções programadas diretamente no hardware, que contém parâmetros específicos para a operação de um determinado dispositivo. 
Por exemplo, em um sistema operacional a **BIOS** (Sistema Básico de entrada e saída) e a **UEFI** (Interface Extensível Unificada de Firmware) são exemplos de firmware, pois comportam instruções voltadas para a operação do hardware de um computador.

Um firmware pode ser operado pelo usuário da mesma forma que um **Kernel** (o **linux é só o kernel**, a interface varia conforme a empresa responsável pela distribuição, também chamada de distro), mas suas aplicações são distintas.

---

#  Gerenciador de Processos

Um processo é um programa em execução, se um programa não está ligado, então não há processo. O gerenciador de processos de um sistema operacional é responsável por fazer o agendamento dos processos (**scheduling**). Com isso o sistema sabe qual processo está executando naquele momento.

## Thread

Uma thread é a divisão de um processo para uma melhor performance, ele executa um pedaço do processo e poderá executar em paralelo.

## Multitasking

São várias tarefas que podem ser executadas simultaneamente. 

---

# Gerenciador de arquivos

Também chamado de **file system**, ele serve para organizar os armazenamentos de arquivos. 
- Videos 
- Imagens
- Documentos

## Tipos de sistemas de arquivos

- FAT , NTFS (WIndows)]
- ext3, ext4 (Linux)
- HFS+, APFS (MacOS)

Eles são criados quando formatamso o nosso disco, por exemplo.


