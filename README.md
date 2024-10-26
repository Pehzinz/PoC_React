POC_React - Projeto de Demonstração em Next.js
Este projeto foi criado como uma prova de conceito (POC) para explorar conceitos fundamentais do Next.js 14+. Ele inclui exemplos de componentes React sem estado, bem como estilos CSS globais e módulos CSS para estilização específica.

Descrição dos Arquivos
app/page.js: Contém a página inicial do projeto. Importe o componente Headere utilize o módulo CSS Home.module.csspara estilização específica.
components/Header.js: Um componente React simples e sem estado, que exibe uma mensagem de boas-vindas.
styles/globals.css: CSS global para aplicar estilos em toda a aplicação.
styles/Home.module.css: Um módulo CSS específico para estilizar a página Home, com classes aplicadas apenas aos elementos da página principal.


Componentes Simples (sem estado)
O componente Headeré um exemplo de componente React funcional e sem estado, que apenas exibe conteúdo.
import React from 'react';

const Header = () => {
    return (
        <header>
            <h1>Bem-vindo ao Meu Projeto Next.js</h1>
        </header>
    );
};

export default Header;


Estilos CSS (Global e Módulo)
CSS Global
O arquivo globals.cssaplica estilos em todo o projeto, incluindo configurações gerais para o bodye o header. É útil para definir estilos que serão reutilizados em diferentes componentes e páginas.
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #0070f3;
    color: white;
    padding: 20px;
    text-align: center;
}


Módulo CSS
O Home.module.cssdefina estilos escondidos para a página Home, com classes exclusivas para organizar e formatar a estrutura da página.
.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 20px;
}

.title {
    color: #333;
    font-size: 2rem;
    text-align: center;
}


Objetivo do Projeto
Esta prova de conceito tem o objetivo de ilustrar o uso de Next.js e React para:

Criar componentes simples e reutilizáveis.
Aplicar estilos globais e CSS modularizados.
Demonstrar a organização e estrutura básica de um projeto em Next.js.
