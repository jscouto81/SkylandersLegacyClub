# Skylanders Legacy Club

Uma aplicação Android para colecionadores e fãs da série **Skylanders**, criada para preservar o legado da franquia e organizar coleções pessoais.


## ✨ Funcionalidades
- 📂 Importar ficheiros JSON com listas de Skylanders por jogo
- 📋 Visualizar Skylanders em lista com nome, elemento e ícone
- 🔍 Filtrar por jogo ou elemento
- ✅ Marcar Skylanders como "Tenho" ou "Não tenho"
- 📝 Adicionar notas pessoais a cada personagem
- 📊 Estatísticas da coleção (quantos tens por jogo/elemento)


## 🚀 Instalação
1. Clonar o repositório:
   ```bash
   git clone https://github.com/<teu_user>/SkylandersLegacyClub.git
2. Abrir o projeto no Android Studio.
3. Certificar que tens instalado:
   - Java SE Development Kit 25.0.1
   - Android Studio Otter (última versão)
4. Executar no emulador ou dispositivo físico.


## 📂 Estrutura do Projeto
 - app/src/main/java/.../Skylander.kt → modelo de dados
 - app/src/main/assets/ → ficheiros JSON com Skylanders
 - app/src/main/res/layout/ → layouts XML (lista, detalhes, estatísticas)
 - app/src/main/res/drawable/ → ícones e imagens


## 🛠️ Tecnologias
 - Kotlin
 - Android SDK
 - Gson (para parsing de JSON)
 - RecyclerView (para listas)
 - Room/SQLite (para persistência local)


## 📅 Roadmap
 - [ ] Importar múltiplos jogos (Spyro’s Adventure, Giants, etc.)
 - [ ] Estatísticas detalhadas por elemento
 - [ ] Exportar coleção para ficheiro JSON
 - [ ] Tema visual inspirado nos portais Skylanders


## 📜 Licença
Projeto fan-made, sem fins comerciais. Skylanders é uma marca registada da Activision. Este projeto é apenas para fins educativos e de preservação da comunidade.