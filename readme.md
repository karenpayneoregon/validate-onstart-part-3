# About

A demonstration for checking if a directory exists using ValidateOnStart.

## ⚙️ Prerequisites

Creating the folder indicated in the `appsettings.json` file in the project `HelpDeskApplication`.

The folder location is the developer's choice, but it must be created before running the application.

```json
{
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "AllowedHosts": "*",
  "HelpDesk": {
    "Phone": "555-555-1234",
    "Email": "ServiceDesk@SomeCompany.net"
  },
  "FileSettings": {
    "SecretsDirectory": "C:\\OED\\Secrets"
  }
}
```

## Article

TODO