<h1 align="center">App Restaurante</h1>

## Descrição do Projeto

Este projeto é uma aplicação desenvolvida para gerenciar informações sobre restaurantes, suas avaliações e estados de ativação. O objetivo é proporcionar uma interface intuitiva para os usuários adicionarem, editarem e avaliarem restaurantes, além de ativar ou desativar estabelecimentos.

## Funcionalidade do Projeto

- Adicionar restaurantes
- Listar restaurantes com suas avaliações
- Receber avaliações dos clientes
- Alternar o estado de ativação dos restaurantes
- Gerar relatórios sobre a média das avaliações dos restaurantes

## Tecnologias usadas no projeto

- Python 3.8+
- Conceitos de Programação Orientada a Objetos (POO)

## Status do Projeto

O projeto está em fase de desenvolvimento. As funcionalidades básicas foram implementadas, mas ainda há melhorias e ajustes planejados, incluindo:

- Implementação de interface gráfica
- Integração com banco de dados para persistência de dados
- Adição de funcionalidades avançadas de busca e filtragem

## Exemplos de uso do projeto

Aqui estão alguns exemplos de código para usar a aplicação:

### Código Principal

```python
from modelos.restaurante import Restaurante

restaurante_praca = Restaurante('Praça', 'Gourmet')
restaurante_praca.receber_avaliacao('Gui', 4)
restaurante_praca.receber_avaliacao('Lais', 3)
restaurante_praca.receber_avaliacao('Emy', 2)

def main():
    Restaurante.listar_restaurantes()

if __name__ == '__main__':
    main()
