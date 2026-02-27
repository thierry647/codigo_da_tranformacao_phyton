'''
]# codigo_da_tranformacao_phyton
├── Modulo_01/
│   ├── introducao.py
│   ├── dados_iniciais.json
├── Modulo_02/
│   ├── logica.py
│   ├── exemplos.csv
├── Modulo_03/
│   ├── estruturas_dados.py
│   ├── configuracoes.json
├── README.md

git clone https://github.com/thierry647/codigo_da_tranformacao_phyton/edit/main/README.md
'''
def boas_vindas():
    print("Bem-vindo ao Código da Transformação em Python!")

if __name__ == "__main__":
    boas_vindas()def par_ou_impar(numero: int) -> str:
    return "Par" if numero % 2 == 0 else "Ímpar"

if __name__ == "__main__":
    print(par_ou_impar(7))

    def lista_exemplo():
    frutas = ["maçã", "banana", "laranja"]
    for fruta in frutas:
        print(fruta)

if __name__ == "__main__":
    lista_exemplo()
