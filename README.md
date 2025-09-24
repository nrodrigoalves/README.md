# arquivo: funcionalidade_saudacao.py

def saudacao(nome):
    """
    Recebe um nome e retorna uma saudação personalizada.
    """
    return f"Olá, {nome}! Bem-vindo ao projeto Open Source."

# Exemplo de uso
if __name__ == "__main__":
    nome_usuario = input("Digite seu nome: ")
    print(saudacao(nome_usuario))
