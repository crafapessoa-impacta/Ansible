IBLISS Segurança Digital

# AmazonLinux-2-CIS - v1.0.0 - Últimas

## Amazon Linux 2 - CIS Benchmark Hardening Script

Esta role de ansible está em desenvolvimento e é considerada um trabalho em andamento.

Ela pode ser usada para fortalecer uma VM Amazon Linux 2, para torná-la compatível com CIS, atendendo ambos os níveis de ajuste 1 ou 2.

Serão feitas mudanças significativas no sistema, as quais podem impactar o funcionamento da máquina, bem como de suas aplicações. Por este motivo, recomendamos a aplicação desta role em uma máquina teste, para que seja feita a homologação de seu impacto, antes de adotá-la em ambiente produtivo. 

## Requisitos do sistema
```
Ansible 2.7+
Amazon Linux 2
```
## Role
```
role: AmazonLinux-2-CIS
```
## Role/Playbook Tags
```
tags: 
level1
level2
always
prelim_tasks
post_tasks
```
## Secção Vars
```
section1
section2
section3
section4
section5
section6
```
## Vars
```
Consulte defaults/main.yml para outros vars
```
## Amostra Playbook.ymls
```
Consulte AmazonLinux-2-CIS_Benchmark_(level1, level1_and_level2, or level2).ymls Altere a função para corresponder ao nome da pasta de função.
```
## Licença
O conteúdo desta role é disponibilizado de acordo com os termos da Mozilla Public License, v. 2.0, a que pode ser obtida em https://mozilla.org/MPL/2.0/.
