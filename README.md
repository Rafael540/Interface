## Sistema de Aluguel de Carros

🚗 Sistema de Aluguel de Carros em Java
Este projeto implementa um sistema orientado a objetos para simular o aluguel de veículos, com foco em boas práticas de design, como o uso de interfaces para flexibilizar a aplicação de diferentes estratégias de imposto.

📌 Objetivo
Calcular o valor de uma locação de carro com base no período de uso (por hora ou por dia), e aplicar impostos por meio de uma interface genérica (TaxService), que pode ser implementada para diferentes contextos tributários — como o serviço BrazilTaxService.

💡 Funcionalidades principais:
Entrada de dados via terminal: modelo do veículo, datas de retirada e devolução, tarifas.

Cálculo automático da fatura com base em tarifas e tempo de uso.

Aplicação de impostos usando uma interface (TaxService) para permitir diferentes implementações de política tributária.

Geração e exibição de uma fatura com:

Pagamento básico

Imposto

Total

🛠️ Tecnologias e conceitos utilizados:
Java 8+

Orientação a Objetos (POO)

Interface para injeção de dependência (TaxService)

API moderna de datas (java.time)

Separação de responsabilidades com serviços e entidades

📁 Estrutura do projeto:
model.entities: classes principais do domínio (Vehicle, CarRental, Invoice)

model.services: lógica de negócio (RentalService) e imposto (TaxService, BrazilTaxService)

application: ponto de entrada da aplicação (classe Program)
