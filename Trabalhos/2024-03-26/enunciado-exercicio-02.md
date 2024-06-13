No dia de ontem, ficamos sabendo que houve um ataque hacker no nosso site de OTA (Online Travel Agency), o que ocasionou a criação de algumas compras de passagens aéreas inválidas. O time de Segurança está atuando, mas para adiantar, enviou a nós um relatório com algumas compras suspeitas. Precisamos formatar o relatório e enviar a gestão.
Entende-se por suspeita toda compra cujo Trigrama (IATA) é inválido ou ZERO.

Dado o csv raw_data.csv,criar nova planilha com os dados consolidados:

1. Nome+Sobrenome, e-mail,  endereço ip (V4) e duas colunas: SUSPEITA (SIM/NAO) e Endereço IP (caso suspeita)
2. A pasta de trabalho FINAL deve conter apenas duas planilhas: a planilha com os dados brutos e a planilha formatada
3. A primeira planilha deve permitir a inserção de dados a qualquer momento.

Dicas:

- Fique a vontade para usar as funcionalidades de "ocultar/reexibir" caso precise de planilhas adicionais;
- Você pode formatar o endereço IP (V4) no padrão 000.000.000.000, ou formato texto, como preferir. A máscara é livre.


