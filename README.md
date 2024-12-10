# Sistema de Rastreamento de Veículos

## 📚 Sobre o Projeto

O **Sistema de Rastreamento de Veículos** é uma solução desenvolvida para monitorar e gerenciar frotas de veículos de maneira eficiente. Ele oferece funcionalidades tanto para administradores quanto para motoristas, permitindo o acompanhamento em tempo real e a gestão otimizada de rotas.

### 🎯 Funcionalidades Principais

#### **Administrador (ADM):**

- **Gerenciamento de Rotas**: Criar, atualizar e remover rotas para os motoristas.
- **Consulta de Direções**: Visualizar as direções configuradas para os veículos.
- **Troca de Direções**: Ajustar as rotas de forma dinâmica, garantindo eficiência.

#### **Motorista:**

- **Escolha de Rotas**: Selecionar a rota mais adequada para sua viagem.
- **Início de Rotas**: Iniciar uma rota para ser rastreado pelo sistema.
- **Postagem de Localização**: Atualizar o servidor com sua localização em tempo real, permitindo o rastreamento contínuo.

### 🛠️ Tecnologias Utilizadas

- **Backend**: [Nest.js](https://nestjs.com/)
- **Frontend**: [Next.js](https://nextjs.org/)
- **Mensageria**: [Apache Kafka](https://kafka.apache.org/)
- **Simulador de Veículos**: [Golang](https://go.dev/)

---

### ⚡ Próximos Passos

- Implementar os endpoints para gerenciar as funcionalidades do administrador.
- Criar o módulo de postagem de localização para motoristas.
- Desenvolver a interface de visualização de rotas.
- Configurar o sistema de mensageria com Apache Kafka para comunicação eficiente.
- Criar e integrar o simulador de veículos em Golang.

---

### 🚀 Como Contribuir

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b minha-feature`).
3. Commit suas alterações (`git commit -m 'Adicionei uma nova feature'`).
4. Faça o push para a branch (`git push origin minha-feature`).
5. Abra um Pull Request.

---

### 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).
