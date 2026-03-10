# Helios Secure Text v1.0.0

📧 **Contato:** devhansoft@gmail.com  
📄 **Licença:** Licença Proprietária — HANSoft

---

## Descrição

**Helios Secure Text** é um software desenvolvido para proteger comunicações sensíveis por meio de criptografia de texto avançada.

Seu objetivo é permitir que usuários criem mensagens altamente seguras, que podem ser copiadas e enviadas por e-mail ou salvas em arquivos **TXT**, sendo uma ferramenta prática e segura para:

- Jornalistas  
- Profissionais que lidam com informações sensíveis  
- Usuários que precisam de comunicação confidencial  
- Qualquer pessoa que deseje maior privacidade digital  

---

## Tecnologias de Segurança

O sistema utiliza técnicas modernas e múltiplas camadas de proteção, incluindo:

- **Criptografia em cascata (AES + ChaCha20)** para aumentar a complexidade contra ataques  
- **Autenticação HMAC-SHA256** para verificação de integridade  
- **Ofuscação de dados e particionamento de constantes**  
- **Inserção de bytes aleatórios**  
- **Codificação customizada** para dificultar engenharia reversa  

Essas camadas foram projetadas para tornar a análise criptográfica e engenharia reversa significativamente mais difíceis.

---

## Biblioteca Cryptography

A segurança do **Helios Secure Text** é baseada na biblioteca **`cryptography`** do Python.

Essa biblioteca implementa padrões modernos de criptografia simétrica amplamente reconhecidos e utilizados na indústria, garantindo:

- confiabilidade  
- segurança  
- robustez no processamento das informações  

---

## Aviso de Responsabilidade

Ao utilizar este software, recomenda-se seguir boas práticas de segurança:

- Utilize **senhas fortes**, com pelo menos **12 caracteres**  
- Combine **letras maiúsculas, minúsculas, números e símbolos**  
- Recomenda-se **testar a descriptografia logo após criptografar**  
- Tenha cuidado com os **meios de envio e armazenamento**  
- **Mantenha backups** dos arquivos originais  
- Erros podem ocorrer devido a **falhas do sistema**  
- A **expiração por tempo** é útil, mas pode ser burlada caso a fonte de tempo (servidor) seja manipulada; a criptografia permanece segura  
- Não nos responsabilizamos por **perda ou acesso não autorizado aos seus dados**  

Ao utilizar este programa, você **reconhece e aceita os termos descritos acima**.

---

## Aviso Legal

Este aplicativo é fornecido **"no estado em que se encontra" ("as is")**, sem garantias de qualquer tipo, expressas ou implícitas.

O desenvolvedor **não se responsabiliza por quaisquer danos, perdas de dados ou outros problemas** decorrentes do uso deste software.

---

## Licença

Este software está protegido por **licença proprietária da HANSoft**.

A redistribuição, modificação, engenharia reversa ou uso do código-fonte sem autorização prévia **não é permitida**.

Consulte o arquivo **LICENSE.md** para os termos completos da licença.
