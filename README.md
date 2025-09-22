Desafio: Website Institucional UNES em HTML Puro
Este projeto é um exercício prático focado em criar um website institucional completo para uma universidade (UNES) utilizando apenas HTML, sem qualquer uso de CSS para estilização. O objetivo era simular um layout visualmente organizado e navegável, recorrendo exclusivamente aos recursos e atributos nativos do HTML.

Estratégias de Estilização em HTML
Para contornar a ausência do CSS e alcançar uma estrutura de layout funcional, foram empregadas as seguintes técnicas:

Layout com $\mathbf{\<\text{table}\>}$:

O esqueleto de todas as páginas (index.html, quem−somos.html, contato.html) é uma única tag $\mathbf{\<\text{table}\>}$ com border=0, width=900 e align=center. Esta tabela foi fundamental para centralizar o conteúdo e dividir a página em seções distintas (cabeçalho, corpo e rodapé).

Imagens e Cores de Fundo:

Foi usado o atributo background na tag $\mathbf{\<\text{body}\>}$ (background="imagens/fundo.png" ou background="imagens/fundo2.png") para aplicar texturas e cores de fundo em cada página.

Controle de Conteúdo com colspan e align:

O atributo colspan="2" em várias tags $\mathbf{\<\text{td}\>}$ foi crucial para fazer com que o conteúdo principal (como o texto sobre a universidade e a imagem de capa) se estendesse por toda a largura definida para a tabela.

O atributo align="right" na célula de navegação e align="center" no rodapé foram usados para posicionamento do texto.

Hierarquia e Divisores:

Tags de cabeçalho ($\mathbf{\ e $\mathbf{\) e a tag $\mathbf{\ (linha horizontal) foram utilizadas para criar uma hierarquia clara e separadores visuais entre as seções.

Formulário Básico:

A página de contato (contato.html) demonstra a estrutura básica de um formulário ($\mathbf{\<\text{form}\>}$) com campos $\mathbf{\<\text{input}\>}$ e $\mathbf{\<\text{textarea}\>}$ e um botão de submit.

Destaques do Código
Este projeto serve como um estudo de caso sobre como a estruturação e a navegação eram gerenciadas na web antes da separação de responsabilidades (HTML para estrutura, CSS para estilo). Ele reforça a importância da marcação semântica e mostra as técnicas necessárias para construir um layout funcional sem folhas de estilo.

<img width="691" height="593" alt="image" src="https://github.com/user-attachments/assets/9ba0ec10-7a40-4497-8628-918cc4907753" />

<img width="715" height="571" alt="image" src="https://github.com/user-attachments/assets/9b0ab9e9-b2d1-4dc5-ae0a-110895a3fd44" />

<img width="849" height="598" alt="image" src="https://github.com/user-attachments/assets/6c0dfcbd-08e6-4312-93f2-451f3c63228a" />


