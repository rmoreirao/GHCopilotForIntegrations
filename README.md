# GHCopilotForIntegrations

## Requirements
- Create a new Dotnet API for a PaymentTransfer API

## To create the project:
`dotnet new webapi --use-controllers -o PaymentTransferWebAPI`

## Prompts to create the PaymentTransfer API

**From GH Copilot Chat:**

1) Create a Sample JSon message of a PaymentTransfer
   1.1) Check the fields, maybe add another another field using Inline copilot
2) Create an OpenAPI spec for the PaymentTransfer Json message
3) Add documentation to the OpenAPI Spec and generate all the fields again
4) Create the PaymentTransfer API for the paymentTransfer OpenAPI spec
   4.1) Iterate the solution to make it specific to you
5) run the code doing `dotnet run` from 'PaymentTransferWebAPI' folder
6) Open the Swagger specification
7) Create Unit tests for the PaymentTransfer API 
8) Create readme.md for the PaymentTransfer API
9) Commit to Github using the Commit Message Suggestion from GitHub Copilot
