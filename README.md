# Cibersegurança do Zero à Prática - Santander
## Desafio: 

### Simulando ataque de brute force com Medusa e Kali Linux

#### Kali instalado:
![This is an alt text.](/images/Kali.png "This is a sample image.")

#### Metasploitable instalado:
![This is an alt text.](/images/metaspl.png "This is a sample image.")

#### NMAP descobrindo algumas vulnerabilidades no Metasploitable:
![This is an alt text.](/images/NMAP.png "This is a sample image.")

#### Medusa encontrou credencial válida no FTP e foi feito login nele com sucesso:
![This is an alt text.](/images/Medusa%20achou%20FTP%20aceitou.png "This is a sample image.")

#### Medusa encontrou credenciais válidas no formulário DVWA:
![This is an alt text.](/images/DVWA%20varias%20crdenciais.png "This is a sample image.")

#### Foi feito o login com credenciais encontradas:
![This is an alt text.](/images/DVWA%20acessado.png "This is a sample image.")

## Conclusão:
### Dadas as várias falhas de segurança encontradas, precisaria ser feito um trabalho junto à 'empresa alvo' para mitigar esses riscos. Algumas medidas à serem tomadas:
1. Alteração imediata das senhas para valores mais difíceis de ser encontrados (caracteres especiais, senhas mais longas, números e letras, maiúsculas e minúsculas, etc.);
2. Não permitir repetidas tentativas de login sem sucesso;
3. Implementar CAPTCHA;
4. Utilizar autenticação multifator (MFA);
5. Desabilitar login anônimo.
