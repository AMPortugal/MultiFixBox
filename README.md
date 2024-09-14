# Pendrive de Manutenção - Projeto Conjunto

## Conceito:
Este projeto foi criado para oferecer uma solução completa e portátil para instalação, testes, recuperação e manutenção de sistemas operacionais e dispositivos Android. Ele inclui ISOs e ferramentas diversas para uma ampla gama de tarefas, desde a instalação de sistemas Windows e Linux até a manutenção de dispositivos Android com ferramentas como ADB e Fastboot.

## Funcionalidades:
- Instalação de **Windows 11** (possibilidade de adicionar outras versões, como Windows 10).
- Ferramentas de manutenção com o **Hiren's BootCD PE**.
- **Kali Linux** com persistência para testes de segurança e diagnóstico de sistemas.
- Suporte para dispositivos Android com **ADB**, **Fastboot**, e ferramentas de recuperação como **TWRP** e suporte a ROMs.
- Ferramentas adicionais, como o **Clonezilla** para backup de discos e partições, e o **GParted Live** para gerenciamento de discos.

## Avisos de Licenciamento:
Este projeto inclui ou pode incluir produtos e ferramentas que possuem diferentes licenças de uso. **Os produtos da Microsoft, como Windows 11 e Windows 10, não estão incluídos neste repositório** devido às restrições de licenciamento. No entanto, o usuário pode adicionar tais ISOs por **conta e risco**, respeitando as licenças da Microsoft e outras leis aplicáveis.

**Ferramentas de código aberto** como Kali Linux, Clonezilla, GParted, e ADB/Fastboot estão incluídas e são distribuídas sob suas respectivas licenças, todas elas permitindo o uso, modificação e distribuição conforme descrito em seus termos.

## Como Personalizar:
Para adicionar mais funcionalidades, você pode incluir novas ISOs e ferramentas de manutenção. As etapas a seguir mostram como customizar o pendrive de acordo com suas necessidades:

1. **Adicionar ISOs**:
   - Simplesmente copie suas ISOs personalizadas para o pendrive, no diretório raiz do Ventoy.

2. **Ferramentas Android**:
   - ADB e Fastboot estão incluídos, com suporte para dispositivos Android. O TWRP pode ser adicionado como um arquivo `.img` e utilizado via Fastboot.

3. **Excluir produtos Microsoft**:
   - Para respeitar as licenças de software proprietário, nenhum produto Microsoft foi incluído no repositório. Para adicionar Windows 11 ou 10, siga as instruções oficiais de cada sistema operacional e tenha certeza de que você possui as licenças apropriadas.

## Como Usar:
1. Prepare seu pendrive com o [Ventoy](https://www.ventoy.net/en/index.html).
2. Adicione as ISOs que você quer utilizar (ex: Hiren's BootCD PE, Kali Linux, etc.).
3. Configure as ferramentas Android, como ADB e Fastboot, instalando-as no Kali Linux com persistência, para mantê-las prontas para uso.
4. Crie partições de persistência no Kali Linux para salvar arquivos e configurações.

## Créditos:
Este projeto foi desenvolvido em colaboração entre **AMPortugal** e **Alex ( IA ChatGPT )**, com o intuito de criar uma ferramenta versátil para múltiplos cenários de manutenção e testes.

Agradecemos a todos os projetos de código aberto que tornam possível a criação de ferramentas como estas, que facilitam o dia a dia de técnicos e desenvolvedores.

## Aviso Final:
Este projeto foi criado para fins educacionais e de uso pessoal. Qualquer adição de software proprietário é de responsabilidade do usuário final, que deve garantir que está em conformidade com as leis de licenciamento de software.
