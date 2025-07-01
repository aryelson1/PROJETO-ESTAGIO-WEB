
# 🔋 Sistema de Gerenciamento de Baterias para Empilhadeiras e Transpaleteiras

## 📘 Descrição do Projeto

Este sistema tem como objetivo monitorar, controlar e gerenciar o uso e o carregamento de baterias utilizadas em empilhadeiras e transpaleteiras. Ele registra os ciclos de carga e descarga, mantém o histórico de uso e gera relatórios para apoiar a manutenção preventiva e a gestão da vida útil das baterias.

---

## 📷 Telas do Sistema

| Tela                           | Imagem                          |
|--------------------------------|----------------------------------|
| Tela Principal                 | ![](TelasProjetoEstagio/tela%20principal.png)       |
| Entrada da Bateria             | ![](TelasProjetoEstagio/entrada%20bateria.png)      |
| Saída da Bateria               | ![](TelasProjetoEstagio/saida%20da%20bateria.png)   |
| Pronto para Carregar           | ![](TelasProjetoEstagio/pronto%20pra%20carregar.png)|
| Modificar Carregamento         | ![](TelasProjetoEstagio/tela%20modificar%20carregamento.png) |
| Histórico                      | ![](TelasProjetoEstagio/historico.png)              |
| Relatório                      | ![](TelasProjetoEstagio/relatorio.png)              |
| Impressão de Relatórios        | ![](TelasProjetoEstagio/impressão.png)              |
| Mudança da Água da Bateria     | ![](TelasProjetoEstagio/mudança%20da%20agua.png)    |
| Mudança de Telas               | ![](TelasProjetoEstagio/mudança%20de%20telas.png)   |
| Listagem de Baterias           | ![](TelasProjetoEstagio/listar.png)                 |
| Remover Bateria                | ![](TelasProjetoEstagio/remover.png)                |
| Adicionar Nova Bateria         | ![](TelasProjetoEstagio/adicionar.png)              |

---

## 🎯 Funcionalidades Principais

- Cadastro de baterias
- Registro de entrada e saída da bateria nos equipamentos
- Controle de carregamento e descarregamento
- Histórico completo de uso e ciclos
- Geração de relatórios diários, semanais e mensais
- Impressão dos relatórios
- Controle de manutenção preventiva (ex: troca de água)
- Alertas de necessidade de recarga ou substituição

---

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Banco de Dados**: MySQL
- **Relatórios**: Geração de PDF ou HTML para impressão

---

## 🧱 Estrutura de Diretórios (Exemplo)

```
📁 projeto/
├── 📁 css/
├── 📁 js/
├── 📁 imagens/
│   └── [telas do sistema]
├── 📁 includes/
│   └── conexao.php
├── 📁 pages/
│   └── entrada.php, saida.php, relatorio.php, etc.
├── 📁 relatorios/
│   └── gerar_pdf.php
├── index.php
└── README.md
```

---

## 💾 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/sistema-baterias.git
```

2. Configure o banco de dados MySQL:
   - Crie um banco chamado `baterias`
   - Execute o script SQL de estrutura e dados iniciais (ex: `baterias.sql`)

3. Altere o arquivo de conexão com o banco (`includes/conexao.php`) conforme necessário:
```php
$host = 'localhost';
$user = 'root';
$senha = 'sua_senha';
$banco = 'baterias';
```

4. Coloque o projeto no seu servidor local (XAMPP, WAMP ou servidor online)

5. Acesse via navegador:
```
http://localhost/sistema-baterias/
```

---

## 📋 Módulos do Sistema

### 1. 🧾 Cadastro de Baterias
- Nome, código interno, capacidade
- Tipo de equipamento associado
- Data de aquisição

### 2. 📥 Entrada da Bateria
- Registro da entrada no carregamento
- Horário de início
- Status atual

### 3. 📤 Saída da Bateria
- Horário de retirada do carregamento
- Registro de nível de carga

### 4. 🔄 Modificação de Ciclos de Carga
- Corrigir dados de um carregamento já inserido

### 5. 🧪 Manutenção e Troca de Água
- Registrar a última troca de água
- Gerar alerta após X dias (opcional)

### 6. 📚 Histórico e Relatórios
- Visualizar todos os ciclos anteriores
- Filtrar por bateria, equipamento, data
- Exportar ou imprimir

---

## 📈 Relatórios Disponíveis

- Histórico completo por bateria
- Quantidade de ciclos por período
- Tempo médio de carregamento
- Alertas de trocas pendentes

---

## 🔐 Controle de Acesso (opcional)

- Autenticação por login/senha
- Perfis: administrador, operador
- Registros de quem inseriu/alterou dados

---

## 📦 Backup e Segurança

- Backup manual do banco via phpMyAdmin
- Exportação dos dados em CSV ou PDF

---

