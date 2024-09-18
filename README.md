# inverter-string
teste target
mkdir inverter-string
cd inverter-string

# Função para inverter uma string
def inverter_string(s):
    resultado = ""
    for i in range(len(s) - 1, -1, -1):
        resultado += s[i]
    return resultado

# Exemplo de uso
if __name__ == "__main__":
    entrada = input("Digite uma string para inverter: ")  # Entrada do usuário
    string_invertida = inverter_string(entrada)
    print(f"String invertida: {string_invertida}")
git init
git add inverter_string.py
git commit -m "Adiciona script para inverter string"
git remote add origin https://github.com/Wanderson@DESKTOP-V9VMFD4/inverter-string.git

