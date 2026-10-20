
# 171

## Documentação do Jogo

 **171 é um jogo de ação em mundo aberto, ambientado numa cidade brasileira. O jogador pode explorar a cidade, conduzir veículos e realizar diferentes atividades**.  

## 1. Requisitos do Jogo

- **Número máximo de jogadores:** 1 jogador (nesta versão fictícia).
- **Plataforma:** PC (Windows).
- **Idade mínima recomendada:** 18 anos.
- **Género:** Ação e mundo aberto.

## 2. Imagem do Jogo

![Capa do jogo 171 mostrando uma cidade brasileira](images.jpg)

## 3. Link do Jogo

[Visitar a página do jogo 171](https://betagamesgroup.com/)


# Fluxograma do Jogo 171

## Gameplay

```mermaid
flowchart TD
    A([Início]) --> B[Menu Principal]
    B --> C[Entrar na Cidade]
    C --> D{Escolher Atividade}

    D -->|Missões| E[Completar Missões]
    D -->|Explorar| F[Explorar Cidade]
    D -->|Veículos| G[Conduzir]
    D -->|Combate| H[Combater]

    E --> I[Receber Dinheiro]
    H --> J[Fugir da Polícia]

    I --> K{Continuar?}
    F --> K
    G --> K
    J --> K

    K -->|Sim| D
    K -->|Não| L([Fim])
```


## 5. Conclusão

O fluxograma apresenta as diferentes escolhas do jogador. Cada decisão leva a um acontecimento e, no final, o jogo termina.
