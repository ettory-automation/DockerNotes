#glossario

- **Deploy:** processo de disponibilizar uma aplicação ou serviço em um ambiente de execução (produção, teste, etc.), tornando-o acessível aos usuários.
    
- **Hypervisor:** software ou firmware que permite executar múltiplos sistemas operacionais (máquinas virtuais) em um único host físico, isolando recursos e controlando o hardware subjacente.
    
- **OS (Operating System):** sistema operacional; software base que gerencia o hardware e fornece serviços essenciais para programas e aplicações.
    
- **Open Container Initiative (OCI):** organização que define padrões abertos para contêineres, como formato de imagem e especificações de runtime, garantindo interoperabilidade entre ferramentas.
    
- **Docker:** plataforma que automatiza o empacotamento, a distribuição e a execução de aplicações em contêineres.
    
- **cri-o:** runtime leve e compatível com OCI, desenvolvido para orquestradores Kubernetes, com foco em segurança e simplicidade.
    
- **containerd:** runtime de contêineres de nível intermediário, usado por plataformas como Docker e Kubernetes para gerenciar o ciclo de vida dos contêineres.
    
- **kaniko:** ferramenta para construir imagens Docker em ambientes sem privilégios de root, ideal para pipelines CI/CD e Kubernetes.
    
- **buildah:** ferramenta para construir imagens OCI/Docker sem precisar do daemon Docker, voltada para automação e scripts.
    
- **libraries:** coleções de funções e recursos reutilizáveis que facilitam o desenvolvimento de software, evitando reescrever código comum.
    
- **Tuning:** ajuste fino de parâmetros de sistema, contêineres ou aplicações para melhorar desempenho, consumo de recursos ou estabilidade.
    
- **Secrets:** informações sensíveis (senhas, tokens, chaves privadas etc.) que precisam ser armazenadas e gerenciadas de forma segura durante a execução de aplicações.
    
- **Imutabilidade:** conceito de que um artefato (como uma imagem de contêiner) não deve ser alterado após criado; mudanças exigem nova versão.
    
- **Docker-Compose:** ferramenta que define e gerencia múltiplos contêineres Docker com um único arquivo YAML, facilitando orquestração local.
    
- **Continuous Integration (CI):** prática que integra código continuamente, executando testes e validações automáticas para detectar falhas precocemente.
    
- **Continuous Delivery (CD):** extensão do CI que automatiza o processo de entrega de software, garantindo implantação rápida e segura.
    
- **Filesystem Hierarchy Standard (FHS):** padrão que define a estrutura e organização de diretórios em sistemas Linux e Unix-like.
    
- **Unix-like:** sistemas operacionais que seguem os princípios e padrões do UNIX, como Linux, macOS e BSD.
    
- **Daemon:** processo em segundo plano que executa tarefas contínuas ou oferece serviços, como o `dockerd` (daemon do Docker).
    
- **runc:** runtime compatível com OCI usado por Docker, cri-o e containerd para criar e gerenciar contêineres.
    
- **Dockerfile:** arquivo que define instruções para construir uma imagem Docker, como base, dependências e comandos de execução.
    
- **DockerHub:** repositório público de imagens Docker, usado para armazenar e compartilhar imagens de contêineres.
    
- **Token:** chave de autenticação usada para validar acesso a serviços, APIs ou repositórios.
    
- **Cloud Native:** abordagem de desenvolvimento voltada para execução em nuvem, com foco em escalabilidade, resiliência e automação.
    
- **macvlan:** driver de rede do Docker que atribui um endereço MAC e IP únicos a cada contêiner, fazendo-o aparecer como um dispositivo físico na rede.
    
- **Fully Stateless:** arquitetura em que a aplicação não mantém estado local (dados ou sessões), permitindo escalabilidade horizontal e resiliência.
    
- **Bind Mount:** tipo de volume no Docker que conecta um diretório do host diretamente a um contêiner, permitindo persistência e compartilhamento de dados.
    
- **Path:** caminho (diretório ou arquivo) usado para localizar recursos no sistema de arquivos.
    
- **Build:** processo de criação de uma imagem de contêiner a partir de um Dockerfile e seus arquivos de contexto.
    
- **Multi-stage Build:** técnica que divide o processo de build em várias etapas, otimizando tamanho e segurança da imagem.
    
- **Common Base Stage:** estágio compartilhado entre diferentes etapas de um build multi-stage, permitindo reutilização de dependências.
    
- **Pinning:** prática de fixar versões exatas de pacotes, imagens ou dependências para garantir reprodutibilidade.
    
- **Build Cache:** mecanismo que armazena etapas anteriores de builds Docker para acelerar reconstruções futuras.
    
- **Build Arguments / Build Args:** variáveis passadas durante o processo de build de uma imagem Docker, usadas para parametrizar o Dockerfile sem alterá-lo.

- **Short Hash:** versão resumida de um hash de um git commit  