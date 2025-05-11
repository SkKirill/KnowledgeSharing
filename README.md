## Подтверждение SSL сертификата .NET 
> Для возможности запуска с SSL сертификатом нужно выполнить команду в Windows или macOS
``` PowerShell
dotnet dev-certs https --trust
```
> Должны получить в ответ:  

**`Trusting the HTTPS development certificate was requested. A confirmation prompt will be displayed if the certificate was not previously trusted. Click yes on the prompt to trust the certificate.
Successfully trusted the existing HTTPS certificate.`**

