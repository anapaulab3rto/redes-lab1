## Etapa 2 – Decodificação da Mensagem

A modulação de frequência por chaveamento (FSK) foi utilizada para a transmissão da mensagem.

* **Modulação Identificada:** FSK (Frequency-Shift Keying)
* **Número de Bits:** 18

### Mensagem Recuperada
A sequência de bits recuperada é:
$$101100111111100101$$

---

## Etapa 3 – Impacto do Ruído na Comunicação

A relação Sinal-Ruído (SNR) foi utilizada para medir o impacto do ruído na integridade da mensagem.

* **(a) Limite de Erro:** Os **primeiros erros** apareceram em um nível de **SNR de $ -32 \text{ dB}$**.
* **(b) Corrupção Completa:** Não houve nível de SNR testado em que **todos os bits da mensagem foram corrompidos**.

### Gráfico da Quantidade de Erros por SNR
A figura abaixo ilustra a relação entre a quantidade de erros de bit e o SNR.
![Figure_etapa3 - Gráfico da Quantidade de Erros por SNR](https://github.com/user-attachments/assets/2e4f3520-28dd-408f-a7a5-df0268be2b46)

---

## Etapa 4 – Ruído Real (Transmissão pelo Ar)

* **Mensagem Decodificada (Incompleta na maioria das tentativas):**
    $$10110$$

### Desempenho
Foram necessárias várias reproduções do sinal, e em apenas uma delas consegui decodificar a mensagem completa.
