#### Dicionário de dados

* `customerID`: número de identificação único de cada cliente
* `Churn`: se o cliente deixou ou não a empresa 
* `gender`: gênero (masculino e feminino) 
* `SeniorCitizen`: informação sobre um cliente ter ou não idade igual ou maior que 65 anos 
* `Partner`:  se o cliente possui ou não um parceiro ou parceira
* `Dependents`: se o cliente possui ou não dependentes
* `tenure`:  meses de contrato do cliente
* `PhoneService`: assinatura de serviço telefônico 
* `MultipleLines`: assisnatura de mais de uma linha de telefone 
* `InternetService`: assinatura de um provedor internet 
* `OnlineSecurity`: assinatura adicional de segurança online 
* `OnlineBackup`: assinatura adicional de backup online 
* `DeviceProtection`: assinatura adicional de proteção no dispositivo 
* `TechSupport`: assinatura adicional de suporte técnico, menos tempo de espera
* `StreamingTV`: assinatura de TV a cabo 
* `StreamingMovies`: assinatura de streaming de filmes 
* `Contract`: tipo de contrato
* `PaperlessBilling`: se o cliente prefere receber online a fatura
* `PaymentMethod`: forma de pagamento
* `Charges.Monthly`: total de todos os serviços do cliente por mês
* `Charges.Total`: total gasto pelo cliente

### 📘 Novo Dicionário de Dados

| Coluna                           | Tipo de Dado    | Descrição                                                                 |
|----------------------------------|------------------|---------------------------------------------------------------------------|
| `ID_Cliente`                     | String           | Identificador único de cada cliente.                                     |
| `Abandono`                       | Boolean          | Indica se o cliente abandonou o serviço.|
| `Genero_Cliente`                 | Category | Gênero do cliente (`Male` ou `Female`).                              |
| `Eh_Idoso`                       | Boolean          | Indica se o cliente é idoso.                                             |
| `Tem_Parceiro`                   | Boolean          | Cliente tem parceiro(a).                                                 |
| `Tem_Dependentes`               | Boolean          | Cliente possui dependentes.                                              |
| `Meses_Cliente`                  | Inteiro          | Tempo em meses que o cliente está com a empresa.                         |
| `Assinatura_Tem_Servico_Telefone`| Boolean          | Indica se o cliente possui serviço telefônico.                           |
| `Assinatura_Multiplas_Linhas`    | Boolean          | Cliente tem múltiplas linhas telefônicas.                                |
| `Tipo_Servico_Internet`          | Category | Tipo de serviço de internet (`No`, `DSL` ou `Fiber optic`).         |
| `Assinatura_Seguranca_Online`    | Boolean          | Cliente assinou segurança online.                                        |
| `Assinatura_Backup_Online`       | Boolean          | Cliente assinou backup online.                                           |
| `Assinatura_Protecao_Dispositivo`| Boolean          | Cliente assinou proteção de dispositivo.                                 |
| `Assinatura_Suporte_Tecnico`     | Boolean          | Cliente assinou suporte técnico premium.                                 |
| `Assinatura_Streaming_TV`        | Boolean          | Cliente assinou serviço de TV por streaming.                             |
| `Assinatura_Streaming_Filmes`    | Boolean          | Cliente assinou filmes por streaming.                                    |
| `Tipo_Contrato`                  | Category | Tipo de contrato: (`Mensal`, `Anual`, `Bianual`).                                |
| `Fatura_Digital`                 | Boolean          | Indica se o cliente recebe a fatura digital.                             |
| `Metodo_Pagamento`               | Category | Método de pagamento utilizado pelo cliente.                         |
| `Mensalidade`                    | Float            | Valor da mensalidade paga pelo cliente.                                  |
| `Total_Cobrado`                  | Float            | Valor total já cobrado do cliente.                                       |
| `Custo_Diario`                   | Float            | Custo médio por dia (gerado na análise).                                 |