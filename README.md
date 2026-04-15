# Calculadora-Fitcore
# 💪 FitCore

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

> Calculadora de desenvolvimento físico focada em saúde, desempenho e acompanhamento diário.

---

## 📖 Sobre o projeto

O **FitCore** é uma aplicação em Python que auxilia usuários a monitorarem indicadores importantes de saúde e desempenho físico, como:

* Índice de Massa Corporal (IMC)
* Hidratação diária recomendada
* Gasto calórico por atividade
* Metas de treino e objetivos físicos

O sistema foi desenvolvido com foco em **prática de lógica de programação** e **interação via terminal (CLI)**, sendo ideal para fins educacionais e evolução como desenvolvedor.

---

## 🚀 Funcionalidades

### 📊 Cálculo de IMC

* Cálculo automático baseado em peso e altura
* Classificação:

  * Abaixo do peso
  * Normal
  * Sobrepeso
  * Obesidade

---

### 💧 Hidratação diária

* Recomendação baseada no peso corporal:

```
35 ml × peso (kg)
```

---

### 🔥 Gasto calórico

* Cálculo de calorias gastas em atividades:

  * Caminhada
  * Corrida
  * Musculação
  * Bicicleta
* Permite múltiplas atividades no mesmo dia
* Soma total de calorias

---

### 🎯 Meta diária e TMB

* Cálculo da Taxa Metabólica Basal (TMB)
* Ajuste por nível de atividade (TDEE)
* Definição de objetivos:

  * Emagrecimento
  * Manutenção
  * Ganho de massa
* Estimativa de tempo de treino necessário

---

### 📋 Resumo diário

* Consolidação de dados:

  * IMC
  * Hidratação
  * Exercícios realizados
  * Calorias gastas
  * Meta e desempenho

---

## 🛠️ Tecnologias utilizadas

* **Python 3**
* Programação procedural
* Execução via terminal (CLI)

---

## ⚙️ Como executar

### Pré-requisitos

* Python 3 instalado

### Passos

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/fitcore.git

# Acesse a pasta
cd fitcore

# Execute o programa
python main.py
```

---

## 📂 Estrutura do projeto

```
fitcore/
│
├── main.py
├── README.md
└── assets/ (opcional)
```

---

## 📈 Roadmap (Melhorias futuras)

* [ ] Interface gráfica (Tkinter ou Web)
* [ ] Persistência de dados (arquivo ou banco)
* [ ] Sistema de login de usuário
* [ ] Histórico de treinos
* [ ] API para integração com apps fitness
* [ ] Versão mobile

---

## 🤝 Contribuição

Contribuições são bem-vindas!

1. Faça um fork do projeto
2. Crie uma branch (`git checkout -b feature/minha-feature`)
3. Commit suas alterações (`git commit -m 'Minha nova feature'`)
4. Push (`git push origin feature/minha-feature`)
5. Abra um Pull Request

---

## 👨‍💻 Autor

Desenvolvido por **Gabriel Men**

---

## 📄 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para usar, estudar e modificar.
