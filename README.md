# Entendendo-sobre-Seguran-a-e-Identidade-na-Azure
Resposta ao desafio DIO - Entendendo sobre Segurança e Identidade na Azure
Microsoft Entra ID, anteriormente conhecido como Azure Active Directory (Azure AD), é o sistema de gerenciamento de identidades e acesso da Microsoft que fornece funcionalidades de autenticação, autorização e segurança para usuários, aplicativos e dispositivos. Ele é amplamente utilizado em ambientes corporativos e na nuvem para garantir que apenas as pessoas certas tenham acesso aos recursos certos de forma segura. 

Aqui estão os principais componentes e funcionalidades do Microsoft Entra ID:

1. **Autenticação Multifatorial (MFA)**: O Entra ID oferece MFA para fortalecer a segurança ao exigir múltiplos fatores de verificação (como senhas, biometria e dispositivos autenticadores) antes de conceder acesso, reduzindo o risco de acesso não autorizado.

2. **Gestão de Identidade Unificada**: Permite integrar identidades de várias fontes (como identidades corporativas locais e serviços de terceiros) em uma única solução. Isso facilita o gerenciamento centralizado de credenciais e o Single Sign-On (SSO), para que os usuários possam acessar várias aplicações com uma única autenticação.

3. **Single Sign-On (SSO)**: O Entra ID fornece SSO, permitindo que os usuários acessem múltiplos aplicativos e serviços sem a necessidade de autenticações repetitivas. Isso melhora a experiência do usuário e a segurança, reduzindo o número de pontos de entrada para ataques.

4. **Gerenciamento de Condicional Access**: A funcionalidade de acesso condicional permite que administradores definam políticas de acesso baseadas em fatores como localização, dispositivo, nível de risco e conformidade. Assim, pode-se exigir autenticação adicional ou bloquear o acesso dependendo do contexto da solicitação de acesso.

5. **Proteção de Identidade**: Com ferramentas avançadas de monitoramento, Entra ID ajuda a identificar atividades suspeitas, como logins de locais incomuns ou tentativas de login com falha. Ele também utiliza inteligência de segurança para marcar contas comprometidas e gerenciar esses incidentes proativamente.

6. **Gerenciamento de Direitos de Acesso (Entitlement Management)**: O Entra ID oferece fluxos de trabalho automatizados para a solicitação, aprovação e atribuição de acessos, o que facilita a gestão de permissões e ajuda a garantir que os usuários tenham apenas os acessos necessários.

7. **Integração com Aplicações e Dispositivos**: Entra ID se integra a milhares de aplicativos e dispositivos, incluindo soluções locais e SaaS. Além disso, ele oferece suporte ao gerenciamento de identidades híbridas, para que as empresas possam integrar infraestruturas locais com a nuvem.

8. **Segurança Baseada em Risco e Inteligência Artificial**: A solução utiliza AI e machine learning para identificar padrões e anomalias em tempo real, protegendo contra ataques como phishing, compromissos de identidade e movimentações laterais de ameaças.

9. **Self-Service e Fluxos de Recuperação de Conta**: Permite que os usuários façam a autogestão de senhas e tenham ferramentas de autoatendimento, o que reduz a dependência do suporte de TI e melhora a experiência dos usuários.

10. **Regulamentação e Compliance**: Atende aos requisitos de conformidade de setores específicos, como GDPR, HIPAA, entre outros, facilitando o gerenciamento de identidades de maneira segura e regulamentada.

11. **Gerenciamento de Aplicativos e Funções Personalizadas**: Permite definir funções personalizadas para aplicativos e atribuir permissões com base em perfis de usuário específicos, oferecendo um controle granular sobre o acesso a dados e serviços.

Em resumo, o Microsoft Entra ID é uma plataforma robusta de gerenciamento de identidades que oferece uma gama completa de recursos para a autenticação e proteção de acesso, além de flexibilidade para integrá-la com soluções em nuvem, SaaS e ambientes locais. Ela se destaca especialmente pela segurança baseada em inteligência artificial e acesso condicional, ajudando empresas a proteger seus dados e usuários contra uma variedade de ameaças cibernéticas.

No Microsoft Entra ID, quando um usuário é deletado, suas informações são retidas por 30 dias antes de serem permanentemente removidas, permitindo a restauração em caso de exclusão acidental.

Já o **Microsoft Defender for Cloud** é uma plataforma de gerenciamento e segurança de cargas de trabalho em nuvem. Ele ajuda a proteger recursos e dados em ambientes multicloud e locais, detectando vulnerabilidades, fornecendo recomendações de segurança e monitorando continuamente para prevenir ameaças. O Defender for Cloud oferece ferramentas de análise de segurança e detecção de ameaças, incluindo visibilidade em tempo real das configurações de segurança, correção guiada para problemas detectados e proteção contra ataques avançados, como movimentos laterais de ameaças. Ele é integrado ao Azure, mas também oferece suporte para outras nuvens, como AWS e Google Cloud Platform (GCP), permitindo uma proteção ampla para diversas infraestruturas de TI.
