# Sistema de Aluguer de Veículos
Uma aplicação de desktop desenvolvida em Java com Swing para gerir aluguer de veículos. O sistema permite administrar veículos, clientes, colaboradores e alugueres com uma interface gráfica intuitiva.

Funcionalidades
Gestão de Veículos: Adicionar, listar e remover veículos (Carros, Motas, Autocaravanas) com suporte a imagens e detalhes completos
Gestão de Clientes: Criar, listar e eliminar perfis de clientes com informações pessoais e de contacto
Gestão de Colaboradores: Administrar colaboradores do sistema de aluguer
Sistema de Alugueres: Criar alugueres ligando veículos, clientes e colaboradores com datas de início e fim
Preview de Imagens: Visualizar foto do veículo ao selecionar no combobox durante operações
Pesquisa em Tempo Real: Filtrar veículos por marca com debounce
Carregamento Assíncrono: Operações de I/O em background via SwingWorker para interface responsiva
Cache de Imagens: Sistema inteligente de cache e carregamento assíncrono de imagens
Tecnologias
Linguagem: Java 11+
UI Framework: Swing
Build Tool: Maven
Componentes: JDateChooser para seleção de datas, ImageLoader para gestão de imagens
