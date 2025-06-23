# Este repositório, tem como objetivo, ensinar como baixar e instalar o Java no seu pc, lembrando que eu estou usando a versão do Java 17, mais, você pode usar a versão que preferir. 

--- 

# 🔽 Baixando o Java: 
  1. Acesse o site oficial da Oracle para baixar o instalador:
    👉 Baixar Java 1

  2. Após o download, execute o instalador .exe e siga os passos da instalação até a conclusão.

---

# ⚙️ Configurando as Variáveis de Ambiente
  1. No menu Iniciar, pesquise por "Editar variáveis de ambiente do sistema" e abra a opção.

  2. Na janela que se abrir, clique no botão "Variáveis de Ambiente...".

  3. Em Variáveis do sistema, clique em Novo... e adicione:

    . Nome da variável: JAVA_HOME

    . Valor da variável: o caminho onde o Java foi instalado.    
        Exemplo: C:\Program Files\Java\jdk-17

  4. Ainda em Variáveis do sistema, localize a variável chamada Path, selecione-a e clique em Editar....

    Depois, clique em Novo e adicione o seguinte valor:

    %JAVA_HOME%\bin    

  5. Clique em OK em todas as janelas para salvar as alterações.

---

# ✅ Verificando se o Java foi instalado corretamente

  - Abra o terminal (Prompt de Comando) e execute o seguinte comando:

    java --version
    

