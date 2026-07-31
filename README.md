<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C3E50,100:3498DB&height=220&section=header&text=Kayke%20Rodrigues%20de%20Oliveira&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Engenharia%20de%20Software%20%7C%20C%2B%2B%20%7C%20Sistemas%20%26%20Banco%20de%20Dados&descAlignY=55&descSize=18" width="100%"/>

<a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:seuemail@exemplo.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="#"><img src="https://img.shields.io/badge/Currículo-2C3E50?style=for-the-badge&logo=readdotcv&logoColor=white" /></a>

</div>

<br/>

## 👋 Sobre mim

Estudante de Engenharia na **UFV**, focado em **C++**, estruturas de dados e sistemas que se conectam a bancos de dados reais. Gosto de entender **o porquê** de cada decisão técnica — não só fazer o código funcionar, mas entender o que acontece por baixo: como uma query é otimizada, por que um `is_open()` não basta pra saber se uma conexão está viva, por que SSL mal configurado pode te expor a um MITM silencioso.

Meus projetos vão de simulações acadêmicas com estruturas de dados implementadas do zero, a um sistema de gestão municipal em produção com PostgreSQL, SSL obrigatório e reconexão automática.

- 🔭 Atualmente desenvolvendo o **TFD** — sistema de transporte de pacientes para uma prefeitura, com interface em Qt e PostgreSQL 16.
- 🌱 Aprofundando conhecimento em **SQL avançado, segurança de aplicações e arquitetura em camadas (entidade → repository → serviço)**.
- 💬 Pergunte-me sobre C++, estruturas de dados implementadas na mão, ou PostgreSQL/libpqxx.
- ⚡ Prefiro entender a raiz de um bug a só resolver o sintoma.

<br/>

## 🛠️ Stack

<div align="center">

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![SFML](https://img.shields.io/badge/SFML-8CC445?style=for-the-badge&logo=sfml&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

<br/>

## 🚀 Projetos em destaque

<table>
<tr>
<td width="50%" valign="top">

### 🏥 [TFD — Transporte Municipal de Pacientes](https://github.com/Kayke-Oli/Projeto-transporte-Prefeitura-Piranga)

Sistema de gestão para uma prefeitura, controlando o transporte de pacientes (Tratamento Fora de Domicílio) até consultas em outras cidades. Migrado de SQLite local para **PostgreSQL 16** multi-máquina.

**Destaques técnicos:**
- Conexão **SSL obrigatória** (TLSv1.3), recusando modos fracos antes mesmo de tentar conectar
- Reconexão automática via *ping* ativo — `is_open()` sozinho não detecta quedas do lado do servidor
- Validação de CPF com algoritmo de dígito verificador corrigido
- Credenciais via variáveis de ambiente, nada hardcoded
- Interface desktop em **Qt**, arquitetura em camadas (entidade → repository → UI)

`C++` `PostgreSQL` `libpqxx` `Qt` `SQL`

</td>
<td width="50%" valign="top">

### 📈 [Simulador de Carteira de Ações](https://github.com/Kayke-Oli/Banco-de-Dados-de-A-es---Simulador-de-Carteira)

Simulador de carteira de investimentos em C++ puro, processando históricos de cotações e dividendos via stdin — com até 500 mil linhas de entrada.

**Destaques técnicos:**
- **Zero STL**: arrays dinâmicos, busca binária e ordenação estável implementados do zero
- Valores monetários em centavos (inteiros) para evitar erro de ponto flutuante
- Consultas de valor por data, cálculo de dividendos por período e rebalanceamento automático por aporte

`C++` `Estruturas de Dados` `Algoritmos`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎮 [Tom & Jerry (inspirado em Pac-Man)](https://github.com/Kayke-Oli/Tom-and-Jerry-game-inspired-by-Pac-Man)

Jogo 2D em C++ com **SFML**, reimaginando a mecânica clássica do Pac-Man com a temática de Tom e Jerry.

**Destaques técnicos:**
- Movimentação em grid com colisão precisa
- IA básica para os inimigos
- Animações em pixel art

`C++` `SFML` `Game Dev`

</td>
<td width="50%" valign="top">

### ✨ Próximo projeto?

Este espaço é seu. Que tal documentar o próximo desafio aqui assim que começar?

</td>
</tr>
</table>

<br/>

## 📊 Estatísticas

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=Kayke-Oli&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kayke-Oli&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Kayke-Oli&theme=tokyonight&hide_border=true" />
</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3498DB,100:2C3E50&height=100&section=footer" width="100%"/>

</div>
