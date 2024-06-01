<h1 align="center">MIT App Inventor - Cálculo do ano bissexto</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-concluído-brightgreen.svg" alt="Status" />
</p>

</h4>
Projeto realizado como parte do 3° ano no curso de Desenvolvimento de Sistemas na disciplina de Programação de Aplicativos Mobile II (PAM II) ministrado na Escola Técnica Estadual de Itaquaquecetuba. 
</h4>

## Descrição
<p align=>O ano bissexto é introduzido no calendário para manter o ano sincronizado com as estações do ano. O cálculo é feito com base no calendário gregoriano, o sistema mais amplamente utilizado hoje em dia. As regras para aplicá-lo são:
    <ol>
        <li><strong>Divisibilidade por 4:</strong> Todos os anos divisíveis por 4 são considerados bissextos. Isso inclui anos como 1996, 2004, 2012, 2020, etc.</li>
        <li><strong>Exceção para os múltiplos de 100:</strong> No entanto, há uma exceção para essa regra. Anos que são múltiplos de 100 (como 1900, 1800, 1700, etc.) não são bissextos, mesmo que sejam divisíveis por 4.</li>
        <li><strong>Exceção para os múltiplos de 400:</strong> Apesar da exceção acima, anos que são múltiplos de 400 (como 2000, 1600, 1200, etc.) são bissextos.</li>
    </ol>
    
À vista disso, este projeto consiste em um aplicativo que verifica se um determinado ano é bissexto ou não. O aplicativo fornece respostas precisas para anos passados, presentes e futuros, indicando, respectivamente:

<ul>
  <li>Foi um ano bissexto / Não foi um ano bissexto</li>
  <li>É um ano bissexto</strong> / Não é um ano bissexto</li>
  <li>Será um ano bissexto</strong> / Não será um ano bissexto</li>
</ul>

Quanto ao design do aplicativo, a facilidade de uso e clareza das informações fornecidas foi o foco principal. A interface é composta por três telas:</p>

<ul>
<li><strong>Tela inicial:</strong> o usuário é recebido com uma mensagem de boas-vindas e é levado à próxima tela para inserir o ano desejado;</li>
<li><strong>Tela de cálculo:</strong> o usuário pode digitar o ano que deseja verificar e ir à tela "Sobre" para mais informações sobre anos bissextos;</li>
<li><strong>Tela explicativa:</strong> exibe uma explicação breve sobre o que é um ano bissexto. Esta tela também possui um botão "Voltar" para retornar à tela de boas-vindas.</li>
</ul>

</p>

## Aplicativo

![design](https://github.com/mamkot/MITCalculadora/assets/102431539/bad586cc-8c72-47ac-82c6-0e1444ccd5fe)
![cod1](https://github.com/mamkot/MITCalculadora/assets/102431539/20982d97-6ea1-4311-8c85-777b4b4e65ca)
![cod2](https://github.com/mamkot/MITCalculadora/assets/102431539/0edd5f81-0374-4097-9e00-3c9c38fcc53a)
![cod3](https://github.com/mamkot/MITCalculadora/assets/102431539/88abe3db-b9e7-466c-b6b7-e5a0db6ddf13)
![cod4](https://github.com/mamkot/MITCalculadora/assets/102431539/54d1369b-43c1-40d0-a38e-94259856552b)
![cod5](https://github.com/mamkot/MITCalculadora/assets/102431539/b371686c-110b-46f2-b72a-3b1064c49ff5)
![cod6](https://github.com/mamkot/MITCalculadora/assets/102431539/18dc3829-5891-4fe7-bd2f-f8cec211c266)

## Projeto em funcionamento

https://github.com/mamkot/MITBissexto/assets/102431539/1b4f3584-86dd-4509-8f5f-2be5ab8f406e

## Como instalar o aplicativo no celular (Android)

1. **Habilitar a instalação de fontes desconhecidas**:
    - Acesse `Configurações > Segurança` ou `Configurações > Segurança e privacidade` em seu dispositivo;
    - Ative a opção `Fontes desconhecidas` ou `Instalar apps desconhecidos`.

2. **Instalar o arquivo APK**:
    - Acesse o repositório [MITBissexto](https://github.com/mamkot/MITBissexto.git) e faça o download do arquivo `ProjetoBissexto.apk` ou `ProjetoBissexto.aab`;
    - Use um gerenciador de arquivos para localizar o projeto `apk`/`aab` e toque nele para iniciar a instalação;
    - Siga as instruções na tela para concluir a instalação;
    - Caso necessário, aceite as permissões solicitadas pelo aplicativo durante a instalação.

<h6>*  Atualmente, este projeto não oferece suporte para a instalação em dispositivos iOS.<h6>

### Ferramentas

- [MIT App Inventor (web)](https://nodejs.org/pt-br/download);
- [MIT App Inventor (Android)](https://play.google.com/store/apps/details?id=edu.mit.appinventor.aicompanion3&pcampaignid=web_share).
