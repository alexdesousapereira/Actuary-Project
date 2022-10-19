

# Seguros
***
Seguro é todo contrato pelo qual uma das partes, *segurador*, se obriga a pagar um benefício a outra, *segurado*, em caso de ocorrência de *sinistro*, em troca do recebimento de um *prêmio* seguro.

## Tipos de Seguro
***

### Seguro Vitalício
***
O seguro de vida inteira, também conhecido como seguro vitalício, garante uma cobertura para a morte do contratante durante toda sua vida.

$$
A_x = B \cdot \sum_{k=0}^{\omega - x} v^{k} {}_{k}p_{x} q_{x+k}
$$


### Seguro Temporário
***
O Seguro de Vida Temporário por 𝒏 anos é o seguro que pagará uma unidade monetária (u.m.) somente se o segurado morre antes de completar 𝒏 anos após o contrato.a.

$$
A_{_{x}^{1}:\overline{n}|} = B \cdot \sum_{k=0}^{n} v^{k} {}_{k}p_{x} q_{x+k} \hspace{.5cm} \text{for } (n+x)<\omega
$$

### Seguro Dotal Puro
***
O seguro Dotal Puro cobre o risco de sobrevida do
segurado. O segurado receberá um benefício caso chegue vivo após
o período de cobertura do seguro.

$$
A_{_{x}:{}_{\overline{n}|}^{1}} = B \cdot v^{m} {}_{m}p_{x}
$$

### Seguro Dotal Misto
***
É o seguro que cobre a vida e morte do segurado. Esse seguro paga uma certo valor se o segurado morrer durante um período ou paga (...) caso o segurado sobreviva a este período, o que ocorrer primeiro.

$$
A_{x:\overline{n}|} = B \cdot A_{_{x}:{}_{\overline{n}|}^{1}} + A_{_{x}^{1}:\overline{n}|}
$$

### Seguro Vitalício Diferido
***
O valor que a seguradora deverá gastar, em média, com o segurado cujo produto começará a vigorar daqui a “m” anos.

$$
{}_{m|}A_x = B \cdot v^{m} {}_{m}p_{x}  \cdot \sum_{k=0}^{\omega-x} v^{k} {}_{k}p_{x+m} q_{x+m+k} \hspace{.5cm} \text{for } (x+m)<\omega
$$

### Seguro de Vida Temporário Diferido
***
O Seguro de Vida Temporário Diferido por 𝒏 anos é o seguro que pagará uma unidade monetária (u.m.), cujo produto começará a vigorar daqui a “m” anos e somente se o segurado morre antes de completar 𝒏 anos após o contrato.a.

$$
{}_{m|}A_{_{x}^{1}:\overline{n}|} = B \cdot v^{m} {}_{m}p_{x}  \cdot \sum_{k=0}^{n} v^{k} {}_{k}p_{x+m} q_{x+m+k} \hspace{.5cm} \text{for } (x+m+n)<\omega
$$

# Anuidades
***
Sucessão de pagamentos (ou recibimentos) equidistantes (termos), efetuados por uma dada entidade a outrem. As Anuidades podem ser definidas em dois tipos:
- Anuidades vitalícia : apenas termina com a morte da pessoa segurada;
- Anuidades Temporária: Termina no fim do prazo estipulado ou com a morte da pessoa segurada.
Além disto as anuidades pode ser definidas como:
- Imediatas: os termos são exigiveis a partir do primeiro período;
- Diferidas: os termos são exigíveeis após um deferimento.
Por fim, o pagamento de uma anuidade pode ser dado da seguinte maneira:
- Pagamentos Antecipados: Os pagamentos começam no primeiro período;
- Pagamentos Postecipados: Os pagamentos começam no final de cada período.

## Tipos de Anuidades
***
### Anuidade Vitalícia Imediata Postecipada
***
$$
a_{x} = \sum_{k=1}^{\omega - x} v^{k} {}_{k}p_{x}
$$
***
### Anuidade Vitalícia Imediata Antecipada
***
$$
\ddot{a}_{x} = \sum_{k=0}^{\omega - x} v^{k} {}_{k}p_{x}
$$
***
### Anuidade Temporária Imediata Postecipada
***
$$
a_{x:\overline{n}|} = \sum_{k=1}^{n} v^{k} {}_{k}p_{x}
$$
***
### Anuidade Temporária Imediata Antecipada
***
$$
\ddot{a}_{x:\overline{n}|} = \sum_{k=0}^{n} v^{k} {}_{k}p_{x}
$$
***
### Anuidade Vitalícia Diferida Postecipada
***
$$
{}_{m|}a_{x} = v^{m} {}_{m}p_{x} \sum_{k=1}^{\omega - m - x} v^{k} {}_{k}p_{x+m}
$$
***
### Anuidade Vitalícia Diferida Antecipada
***
$$
{}_{m|}\ddot{a}_{x} = v^{m} {}_{m}p_{x} \sum_{k=0}^{\omega - m - x} v^{k} {}_{k}p_{x+m}
$$
***
### Anuidade Temporária Diferida Postecipada
***
$$
{}_{m|}a_{x:\overline{n}|} = v^{m} {}_{m}p_{x} \sum_{k=1}^{n} v^{k} {}_{k}p_{x+m}
$$
***
### Anuidade Temporária Diferida Antecipada
***
$$
{}_{m|}\ddot{a}_{x:\overline{n}|} = v^{m} {}_{m}p_{x} \sum_{k=0}^{n} v^{k} {}_{k}p_{x+m}
$$
***

# Direitos de Uso
***
Este repositório têm como objetivo apresentar conceitos e exemplos práticos de Matemática Atuarial utilizando da linguagem Python. Então, dentro deste repositório você pode utilizar deste conteúdo sem nenhuma restrição contanto que não me responsebilize por eventuais causas ou danos morais perante minha responsabilidade.	

Exigido | Permitido | Proibido
:---: | :---: | :---:
Aviso de licença e direitos autorais | Uso comercial | Responsabilidade Assegurada
 || Modificação ||	
 || Distribuição ||	
 || Sublicenciamento || 	
