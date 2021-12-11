# AW2ProjetoFinal
Integrantes do projeto:
Matheus Cardoso,
Izabella Murad,
Renata Almeida,
Monise Souza


Instruções para deploy:
Clonar o repositório e setar variáveis no .env


Database:
Usar database local em SQL Server e rodar as migrations, ou utilizar as nossas configurações de arquivo .env

APP_NAME=ListDaily
APP_ENV=local
APP_KEY=base64:EVZESl5/X9E4FoHT2mzQzJxLYCi32+J3ZlzZjcNGbRw=
APP_DEBUG=true
APP_URL=http://localhost

DB_CONNECTION=sqlsrv
DB_HOST=list-daily.database.windows.net
DB_PORT=
DB_DATABASE=ListDaily
DB_USERNAME=listdaily
DB_PASSWORD=L1stDayl1

MAIL_MAILER=smtp
MAIL_HOST=smtpout.secureserver.net
MAIL_PORT=465
MAIL_USERNAME=suporte@listdaily.com.br
MAIL_PASSWORD=l1stda1ly
MAIL_ENCRYPTION=SSL
MAIL_FROM_ADDRESS=suporte@listdaily.com.br
MAIL_FROM_NAME=Suporte(ListDaily)

Através do XAMPP, rodar o comando "php artisan serve" para conseguir executar a aplicação.



