## 🔍 Matriz de Criticidade - Método Crystal

```mermaid
graph TD
    subgraph Matriz de Impacto

    AC["1. Ar-condicionado parou (C20)"]:::amarelo
    SB["2. Sistema bancário fora do ar (D100)"]:::vermelho
    HP["3. Hospital sem energia (E100)"]:::vermelho
    AT["4. App de transporte com erro de tarifa (D20)"]:::amarelo
    BE["5. Bairro sem luz por 6h (E50)"]:::laranja
    VD["6. Vazamento de dados e-commerce (D50)"]:::laranja
    EL["7. Elevador parou com pessoas (V100)"]:::vermelho
    IP["8. Iluminação pública apagada (E20)"]:::amarelo

    end

classDef branco fill:#fff,stroke:#000,color:#000;
classDef amarelo fill:#FFD84D,stroke:#000,color:#000;
classDef laranja fill:#FFA233,stroke:#000,color:#000;
classDef vermelho fill:#E64C3C,stroke:#000,color:#000;
