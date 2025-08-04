#  minha primeira pagina
Essa é minha primeira aplicação web 

## Equipe 
Essa é a equipe!!
- fabricio **bizotto**
- everton
- julia
- matheus _varela_

> ✔ README.MD deve ser o nome do arquivo.

```javascript
funcion enviar(){
    console.log("Enviando...")
}
```

```c
void buscarProduto(ArvoreB *arvore, int codigo) {
    Produto *produto = buscar(arvore->raiz, codigo);
    if (produto) {
        printf("Produto encontrado:\n");
        printf("Codigo: %d\n", produto->codigo);
        printf("Nome: %s\n", produto->nome);
    } else {
        printf("Produto com codigo %d nao encontrado.\n", codigo);
    }
}

void liberarNo(NoB *no) {
    if (no == NULL) return;
    
    if (!no->folha) {
        for (int i = 0; i <= no->num_chaves; i++) {
            liberarNo(no->filhos[i]);
        }
    }
}
```

Caro <br>discente,

Segundo as <strong>normas vigentes</strong> do regulamento de graduação, o aluno será considerado aprovado, no que diz <i>respeito à assiduidade</i>,<br> se satisfizer a qualquer uma das duas condições a seguir:

- Tiver presença em um número de aulas igual ou superior a 75.0% da carga horária do componente curricular.

<p style= "color: red;"> - Tiver presença em 75.0% ou mais das aulas ministradas (o professor deve lançar 90% da frequência).</p>

