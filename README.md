# Baofeng UV-5R — Manual de Utilizador & Configuração para PMR

Bem-vindo ao seu Baofeng UV-5R! Este manual cobre o funcionamento básico e explica como configurar o rádio para os canais PMR, adequado para utilização na Europa, onde o PMR446 é comum.

***

## Visão Geral

O Baofeng UV-5R é um rádio transceptor portátil de banda dupla, suportando VHF (136–174 MHz) e UHF (400–520 MHz). É popular para uso amador e geral devido à flexibilidade e preço acessível.

**Nota:** Em muitos países, como é o caso de Portugal, o uso de walkie talkies como estes baofeng nao é 100% legal, exceto se o rádio estiver bloqueado nesses canais, possuir antena fixa e emitir até 0,5W. 
Verifique sempre a legislação local antes de utilizar.

***

## Primeiros Passos

1. **Carregar:** Carregue totalmente a bateria antes da primeira utilização.
2. **Ligar:** Rode o botão VOL no sentido dos ponteiros do relógio para ligar e ajustar o volume.
3. **Funções dos Botões:**
    - `VFO/MR`: Alterna entre modo de frequência (VFO) e canal (MR).
    - `MENU`: Entra no menu.
    - `A/B`: Alterna entre as linhas superior e inferior do visor.
    - `EXIT`: Sai dos menus.
    - Setas: Navega para cima/baixo nos menus.

***

## Frequências PMR446

Aqui estão os canais PMR446 standard (Europa):

| Canal | Frequência (MHz) |
|-------|------------------|
| 1     | 446.00625        |
| 2     | 446.01875        |
| 3     | 446.03125        |
| 4     | 446.04375        |
| 5     | 446.05625        |
| 6     | 446.06875        |
| 7     | 446.08125        |
| 8     | 446.09375        |
| 9     | 446.10625        |
| 10    | 446.11875        |
| 11    | 446.13125        |
| 12    | 446.14375        |
| 13    | 446.15625        |
| 14    | 446.16875        |
| 15    | 446.18125        |
| 16    | 446.19375        |

***


## Programação Manual (Sem Cabo)

1. **Entrar no Modo VFO:**  
   Carregue em `VFO/MR` para entrar no modo de frequência.

2. **Selecionar a Linha de Frequência:**  
   Use o botão `A/B` para escolher a linha superior (A) ou inferior (B).

3. **Introduzir a Frequência:**  
   Utilize o teclado para digitar a frequência PMR (ex: 446.00625).  
   *Se não conseguir inserir, confirme que está na linha/visor correta e no modo VFO.*

4. **Definir Parâmetros do Canal (Opcional):**  
   - **Potência**: MENU > 2 (TXP), escolher LOW, depois MENU para confirmar.
   - **CTCSS/DCS** (Códigos de Privacidade, se necessário):  
     - MENU > 11 (R-CTCS) ou 13 (T-CTCS), escolha o valor e depois MENU.
     - Para desativar, escolha OFF.

5. **Guardar a Frequência no Canal:**  
   - MENU > 27 (MEM-CH), use as setas para selecionar canal (ex: 001), MENU para confirmar.

6. **Repetir** para cada frequência/canal PMR.

7. **Mudar para Modo Canal:**  
   Pressione `VFO/MR` para mudar para MR (memória/canal). Use as setas para escolher os canais gravados.

***

## Programação por Computador (Recomendado)

1. **Necessário:**  
   - Cabo de programação (USB para 2 pinos)
   - Software Chirp ou Baofeng (disponível online em sites oficiais ou fontes confiáveis)

2. **Ligar o Rádio:**  
   Desligue, conecte o cabo e volte a ligar o rádio.

3. **Abrir o Software:**  
   Escolha o modelo UV-5R e selecione a porta COM correta.

4. **Ler Dados do Rádio:**  
   Transfira a configuração atual do rádio para o Chirp.

5. **Inserir Canais PMR:**  
   Preencha as frequências PMR na coluna “Frequency”. Defina a Potência como LOW.

6. **Gravar para o Rádio:**  
   Envie as configurações de volta para o rádio.

***

## Segurança & Avisos Legais

- O UV-5R é uma ferramenta poderosa, mas o seu uso nas frequências PMR é restrito por lei em muitos países.  
- Para uso legal, a potência de transmissão não pode exceder 0,5W e a antena deve ser fixa.  
- O uso não autorizado pode resultar em coimas ou apreensão do equipamento.

***

## Resolução de Problemas

- **Sem som:** Verifique o volume, squelch (MENU 0) e a frequência correta.
- **Não permite inserir frequência:** Certifique-se de que está no modo VFO (não MR).
- **Erros ao programar:** Confirme o modelo e porta COM no software.

***

## Dicas para jogos de airsoft, paintball, ciclismo, outras atividades

- baofeng uv 5r permite ouvir 2 canais ao mesmo tempo
- como desligar luz do ecra
- cobrir luz do led para jogos noturnos
- desligar beep
- ligar detecao de voz
- modo poupança de bateria
- baterias extendidas, a pilhas, usb c, etc
- DCS e CTS - Tons do baofeng sao um filtro dentro daquele canal. Imaginem que estao dentro de um pavilhao, onde cada divisao pode ser separada por paredes finas. Se o vosso grupo tiver o radio configurado para estar a escuta de um determinado tom, voces so vao ouvir transmissoes que sigam esse tom. Seria o mesmo que ter o grupo todo dentro da mesma sala no pavilhao. quem está fora da sala, que nao tem o tom configurado, pode ouvir a vossa conversa na mesma, mas voces so ouvem a conversa de quem esta dentro da sala. Alem disso, sendo um canal partilhado, se alguem falar fora da sala, voces nao vao ouvir, mas o canal está a ser usado e iria interferir com as vossas comunicaçoes
- ALARM
- DTMFST - Dual tone multi frequency - 
- S-Code - transmitir entre 1 a 15, para saber qual o squad/grupo que esta a tentar comunicar
- PTT-ID

***

## Recursos Adicionais

- Manual completo: [BAOFENG UV 5R MANUAL](https://baofengtech.com/wp-content/uploads/2020/09/BaoFeng_UV-5R_Manual.pdf?srsltid=AfmBOoo2L0pFlHP513k3Hum64U0rbzqQWkWHntk97XP5ckkDu3IMs0zp)
- Software CHIRP: [Página Oficial de Download CHIRP](https://chirpmyradio.com/projects/chirp/wiki/Download)

Boas comunicações!

***
