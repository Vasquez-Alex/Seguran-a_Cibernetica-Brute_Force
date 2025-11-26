# Segurança_Cibernetica-Brute_Force
aqui irei mostra sobre habilidades que adiquiri pelo curso da DIO, mostrando a sistematização de metodos de brute force em uma maquina Metasploited 2

utilizei wordlist com senhas e usuarios genericos, assim como o exemplo:
users.txt          -> user/nmsfadmin/nadmin/nroot/admin/etc...
pass.txt           -> 123456/password/pass/admin/nmsadmin/etc...
smb_users.txt      -> nservice/admin/nmsfadmin/user/etc...
senhas_spray.txt   -> password/n123456/nwelcome123/nmsfadmin/etc...


  Neste conteudo eu aprendi sobre Brute Force e suas variaveis, aprendi varios exemplos como ataque de dicionário, pura de permutação e hibridos. Junto suas ferramentas comomcrack, John, Wpscam, Patator, Medusa e como eles trabalham em um ambiente.
  Nas imagens pode-se observar qu efiz a conexão de duas maquinas que se enxergam pela mesma rede e usamos o Kalli Linux para fazer os testes de auditoria no Metasploited.

      # Auditoria com um servidor FTP antigo
  1 - indentificamos o IP do alvo
  2 - logo apos verificamos as portas para poder fazer o teste no protocolo FTP do servidor que está vulneravel
  3 - Apos a verificação, nos utilizamos os wordlist para iniciar o ataque através da Meduza
  4 - Apos a utilização e verificação de dados, usamos o login e senha que adquirimos
  5 - Apos o sucesso, voce tem acesso a maquida alvo

      # Tentativa de Ataque web, 
  1 - primeiro indentificamos as areas de acesso e parametros que o formulario utiliza, apos a conexão realizada.
  2 - 
