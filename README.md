# Desafio-Aposentadoria

/* ======================================================================
                APOSENTADORIA

FATORES A SEREM CONSIDERADOS

    NOME
    IDADE
    SEXO
    TEMPO DE CONTRIBUIÇÃO

PADRÕES

    TEMPO MÍNIMO DE CONTRIBUIÇÃO
        35 ANOS PARA HOMES
        30 ANOS PARA MULHERES

    IDADE MAIS TEMPO DE CONTRIBUIÇÃO DEVEM SOMAR
        95 PARA HOMES
        85 PARA MULHERES

SE A PESSOA JÁ POSSUIR OS CITÉRIOS PARA APOSENTADORIA

    "FULANO", VOCÊ PREENCHEU TODOS OS REQUISITOS 
    E JÁ PODE SE APOSENTAR

SE A PESSOA NÃO POSSUIR OS CRITÉRIOS PARA APOSENTADORIA

    'FULANO, INFELIZMENTE AINDA NÃO FORAM PREENCHIDOS 
    TODOS OS CRITÉRIOS PARA SUA APOSENTADORIA.

===========================================================*/

const Nome = 'Rafael'
const Sexo = 'M'
const Idade = 68.5
const Contribuicao = 35
const fator = Idade + Contribuicao

/*const faltanteM = (95 - fator) / 2
const faltanteF = (85 - fator) / 2

console.log(fator);
console.log(faltanteM);
console.log(faltanteF);*/

if (Sexo === `M`) {
    if (Contribuicao >= 35 && fator >= 95) {
        console.log(`${Nome}, você preencheu todos os requisitos e já pode se aposentar.`);
        } else {
        console.log(`${Nome}, infelizmente ainda não foram preenchidos todos os requisitos para a sua aposentadoria.`);
        
    }
} else {
    if (Contribuicao >= 30 && fator >= 85) {
        console.log(`${Nome}, você preencheu todos os requisitos e já pode se aposentar.`);
        } else {
        console.log(`${Nome}, infelizmente ainda não foram preenchidos todos os requisitos para a sua aposentadoria.`);
        
    }
}




