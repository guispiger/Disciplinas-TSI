# 1.3 API

![diagram](https://www.plantuml.com/plantuml/svg/0/VLN1RkD63Bq7o3-mEZc04b_srDCwZj5DuQH6aiMY9uFMC5u2ew4o73cxBVelNUmXwBde5-Z7YXb9jcmdUnF8f_V8Hr9whm5zg4jxUl8JkyBMXk1p29N-F1vxVBvOS_XShsebNuWBvC958UKOZMTq6rjNzNZwxdnXqOMFD_EnnK0QnjDtowcKbRY8hnBvwSbyyljl7n-MdwuVFYpdirzcjrUZinYVYWl8Zlm8gog7R59PBZ3mHk16Lcm99ivuOPFbsHrX4SvlOvQo721Ra2yv43pL1A9GQzryyomAZ-oG5KPJo-G2AH0iF6b08vuK3C4z-GqtBtAM0nQaIYK0AZpMhdbf_eiOXCfYm4Vn9LvaPyDIdscLGxR0DJk4PrhrjMKnsdnBOKCjiK257W41JSbEENXiNfhl0aP0MGEL21LP12ehJteePQBI9Rf28gD18mgjHuaboxE5Q5XxqYW-yIN-GGwZ6otMaqrkQgnWyDw1o5pMUYmKewcdroHQI6opDXp4Cm8bkOB5fLppDw1ML0HH2Cq_XUEYVSEGajk8tN19BaZqUb1RSk3qvFvhD6Sv-n96ayNrf_ihSXWykhGa3Bj0Lw7Ml6jRPUK94AQt7w9WmGPDyrqKLXwLBR4NJJe3bLLiFeUiNusqHQw8s2JX9SupUUkfe5LRl4BK6ooQA5IunYwPXYywNBz3NIgHRTJjji4GpCvZR5yLo6qu3OTIjkD-UyMrwwFpSplkvQNKpg3_EiAAevkBwxsLEllpz0G0O7l48-MrImMk7LmxY4nUh2KVA_mLDvX13jbTD8M002il6mHFJpKh5zAMqrv3h6MVFBMLGpPhsulZszBca1cAYqBRTNwgYPL3WXrnfRdGhfOZjhtuqUkATeCvP5Dnz2NUwDNbyENOE1K1eP0I15PxntBCPcNDHQIRD__6fo7L3JgkQhixr7P6aU2ERFijx5oVovfTpnwJwUlpLh9h8NqsxkDpEihZflUmtVNt-Bkty4bpszOmrGVxOGvpNUpmYEEyyHLSVuPlvVjpESeV21pimX3PIVm0qOdy0D6djdOyU7IQ_XQl6TElre9y-khltFqh3luzEPF-bFy3)

**Nível 3: Diagrama de Componentes**

Esse container é responsavel pelas lógica do negócio, a distribuição dos dados para os outros containers e sistemas externos.

**Escope**: API da aplicação.

**Primary elements**: Sign In Controller, Recebe Dados, Lógica, Conexão DB, Envio Dados.
Elementos de Suporte : Sitema de E-mail, Serviço Financeiro, API WSDenatran, Banco de Dados da Aplicação, Banco de Dados Logs.

**Público Alvo**: Desenvolvedores e Arquitetos de Software.