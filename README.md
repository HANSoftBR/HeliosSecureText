# Helios Secure Text v2.1.0
**Status:** Descontinuado  
Este projeto não está mais em desenvolvimento ou manutenção ativa.

📧 **Contato:** devhansoft@gmail.com  
📄 **Licença:** Licença Proprietária — HANSoft

---

## Descrição

**Helios Secure Text** é um software desenvolvido para proteger comunicações sensíveis por meio de criptografia de texto avançada.

Seu objetivo é permitir que usuários criem mensagens seguras, que podem ser copiadas e enviadas por e-mail ou salvas em arquivos **TXT**, sendo uma ferramenta prática para:

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

O **Helios Secure Text** é fornecido **"no estado em que se encontra"** (**"AS IS"**), de acordo com suas funcionalidades normais e limitações técnicas previsíveis, **sem garantias de qualquer tipo**, expressas ou implícitas.

Este software destina-se à **proteção local de mensagens e textos por meio de mecanismos criptográficos e recursos complementares de integridade e ofuscação**, podendo o conteúdo gerado ser copiado, armazenado ou enviado pelo próprio usuário por meios externos.

**O desenvolvedor não garante:**

- ausência total de falhas, erros, bugs ou vulnerabilidades;
- funcionamento ininterrupto;
- recuperação integral de dados em qualquer hipótese de falha;
- sigilo absoluto em todos os cenários de uso;
- proteção absoluta contra acesso indevido, falhas do sistema, comprometimento do ambiente do usuário ou exposição do conteúdo por meios externos de envio, armazenamento ou compartilhamento.

Bugs, falhas e comportamentos inesperados **podem existir e podem ocorrer durante o uso**, mesmo com testes e cuidados no desenvolvimento. Nenhum software é totalmente livre de erros.

O usuário reconhece que a **decisão de utilizar este software é feita por sua própria escolha e responsabilidade**, devendo avaliar previamente se ele atende às suas necessidades e se é adequado ao ambiente em que será utilizado.

**O usuário é responsável por:**

- proteger senhas, chaves, arquivos e meios de acesso relacionados ao uso do software;
- testar a descriptografia e a integridade do conteúdo antes de utilizá-lo em contexto real, profissional ou sensível;
- manter cópias de segurança independentes dos conteúdos relevantes;
- adotar boas práticas de segurança digital, incluindo proteção do dispositivo, atualização do sistema e cuidado com os meios de envio, armazenamento e compartilhamento do conteúdo.

Na máxima extensão permitida pela legislação aplicável, a **HANSoft** não se responsabiliza por prejuízos decorrentes de:

- perda, corrupção ou exclusão indevida de dados;
- uso inadequado do software;
- falhas, bugs ou comportamentos inesperados;
- acesso não autorizado ao dispositivo do usuário;
- falhas no sistema operacional ou no ambiente do usuário;
- malware, keyloggers, captura indevida de tela, engenharia social, interrupção elétrica, erro humano ou interferência de antivírus, filtros e softwares de terceiros;
- exposição do conteúdo causada por uso inseguro de e-mail, arquivos, dispositivos, serviços ou canais externos escolhidos pelo usuário.

**Importante:** nenhum software pode oferecer garantia absoluta de segurança, funcionamento contínuo ou recuperação total de dados em todos os cenários.

---

## Licença

Este software está protegido por **licença proprietária da HANSoft**.

A redistribuição, modificação, engenharia reversa ou uso do código-fonte sem autorização prévia **não é permitida**.

Consulte o arquivo **LICENSE.md** para os termos completos da licença.
