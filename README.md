# Criando um Programa para Consulta de CPF com Ruby

Neste artigo, vamos explorar como criar um programa em Ruby para consultar a validade de um CPF digitado pelo usuário. Vou detalhar os passos necessários e fornecer exemplos de código prático. Vamos dividir o projeto em módulos para facilitar a organização e manutenção.

## Objetivo Geral
O objetivo deste desafio é criar um programa que permita ao usuário verificar se um número de CPF é válido. Para isso, utilizaremos uma **gem específica** que nos ajudará a validar os dígitos do CPF.

## Passos para Criar o Programa

### 1. Instalação da Gem
Primeiro, precisamos instalar a gem que nos permitirá validar o CPF. Uma opção popular é a gem `cpf_cnpj`. Para instalá-la, abra o terminal e execute o seguinte comando:

```ruby
gem install cpf_cnpj
```

### 2. Estrutura do Programa
Vamos criar um arquivo chamado `consulta_cpf.rb`. Nele, organizaremos nosso código em módulos para facilitar a manutenção. A estrutura básica do programa pode ser a seguinte:

```ruby
# consulta_cpf.rb

module CPFValidator
  def self.valid?(cpf)
    # Implementação da validação do CPF
    # Utilize a gem cpf_cnpj para verificar a validade
    # Retorne true se o CPF for válido, ou false caso contrário
  end
end

# Aqui, você pode criar outras classes ou módulos relacionados ao programa
# Por exemplo, um módulo para interagir com o usuário ou para formatar o CPF

# Exemplo de uso:
if CPFValidator.valid?('123.456.789-09')
  puts 'CPF válido!'
else
  puts 'CPF inválido!'
end
```

### 3. Implementação da Validação
Dentro do método `valid?`, você deve utilizar a gem `cpf_cnpj` para verificar se o CPF é válido. Lembre-se de remover os pontos e traços do CPF antes de fazer a validação.

### 4. Teste o Programa
Após implementar a validação, teste o programa com diferentes números de CPF para garantir que ele esteja funcionando corretamente.

## Conclusão
Com esses passos, você criou um programa em Ruby capaz de verificar a validade de um CPF. Lembre-se de sempre organizar seu código em módulos para facilitar a manutenção e reutilização. Agora é só colocar em prática e aprimorar suas habilidades em Ruby!

Espero que este artigo seja útil, para quem precisar.
