## [3.0.6] - 02-10-2024
- Melhoria: Atualização da sdk FaceTec(9.7.34)

## [3.0.5] - 23-09-2024
- Correção: Validação se o dispositivo é um emulador.

## [3.0.4] - 13-08-2024
- Correção: Tratamento de objeto nulo.
- Correção: Tratamento de remoção da status bar.

## [3.0.3] - 31-07-2024
- Melhoria: Atualização da sdk FaceTec(9.6.104)

## [3.0.2] - 18-07-2024
- Correção: validação sslpinning.

## [3.0.1] - 17-07-2024
- Melhoria: Atualização da sdk FaceTec(9.6.102)

## [3.0.0] - 26-04-2024
- Melhoria: Adicionado flag (segurancaExtraSslPinning) para habilitar verificação sslpinning.
- Melhoria: Adicionado flag (externalDatabaseRefID) id de referência enrollment/match3d-3d.
- Melhoria: Adicionado flag (processType) para selecionar o tipo de processo ("liveness", "enrollment" ou "match").
- Melhoria: Atualização de layout para nova experiência.
- Melhoria: Permitir customização dos parâmetros de textos e cores.
- Melhoria: Atualização da sdk FaceTec(9.6.87)

## [2.6.7] - 10-04-2024
- Melhoria: Atualização da sdk FaceTec(9.6.84)

## [2.6.6] - 02-04-2024
- Melhoria: Atualização da sdk FaceTec(9.6.82)

## [2.6.5] - 19-03-2024
- Melhoria: Atualização da sdk FaceTec(9.6.80)

## [2.6.4] - 06-03-2024
- Melhoria: Atualização da sdk FaceTec(9.6.78)

## [2.6.3] - 21-02-2024
- Melhoria: Atualização da sdk FaceTec(9.6.76)

## [2.6.2] - 05-02-2024
- Melhoria: Atualização da sdk FaceTec(9.6.73)

## [2.6.1] - 22-01-2024
- Melhoria: Atualização da sdk FaceTec(9.6.71)
- Melhoria: Adicionado flag (telaSucesso).

## [2.6.0] - 29-11-2023
- Melhoria: Atualização da sdk FaceTec(9.6.59)

## [2.5.2] - 07-11-2023
- Correção: Ajustado Callback Processamento Facetec.

## [2.5.1] - 06-11-2023
- Melhoria: Statusbar ocultada.

## [2.5.0] - 30-10-2023
- Melhoria: Inclusão de strings para customização das cores dos textos, botões e shapes da aplicação.
- Melhoria: Adicionado flag (retornarErros), para permitir que o cliente, fora do SDK, faça o tratamento de erros.

## [2.4.2] - 10-10-2023
- Melhoria: Adicionado Callback Processamento Facetec.

## [2.4.1] - 01-10-2023
- Melhoria: Adicionado flag (utilizarCameraTraseira).
- 
## [2.3.0] - 11-09-2023
- Melhoria: Atualização da sdk FaceTec(9.6.49)

## [2.2.0] - 11-08-2023
- Melhoria: Atualização da sdk FaceTec(9.6.39)
- Melhoria: Alteração timeout dos services 60segundos.
- Melhoria: Adicionado flag (telaConfirmacaoDeSaida).

## [2.1.2] - 17-07-2023
- Correção: Tratamento de objeto nulo.

## [2.1.1] - 13-07-2023
- Correção: Tratamento de objeto nulo.

## [2.1.0] - 06-04-2023
- Melhoria: Atualização da sdk FaceTec(9.6.21)

## [2.0.0] - 27-01-2023
- Melhoria: atualização de layout para nova experiência com acessibilidade.
- Melhoria: ícones de telas customizáveis.

## [1.2.0] - 26-09-2022
- Melhoria: Atualização da sdk FaceTec(9.4.19)
- Melhoria: Inclusão da flag tentativasDeCaptura (default = 0)
- Melhoria: Possibilidade de customização de cores do componente
- Melhoria: Efetuar chamada do endpoint de report após o retorno da chamada do endpoint liveness3d.
- Melhoria: Mudança no package para serasa.idf.liveness3d.android.

## [1.1.0] - 02-09-2022
- Melhoria: integração com componente facatec.
- Melhoria: Adicionado flag (wizard).
- Melhoria: Adicionado flag (segurancaExtraRootCheck) para validar se o dispositivo está no modo root.
- Melhoria: Adicionado flag (segurancaExtraEmulatorCheck) para validar se o dispositivo é um emulador.
- Melhoria: Retorno de imagem em base64.