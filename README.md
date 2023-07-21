# node-pg_intro_exercise

This application utilizes two main routes to interact with the `biztime` database.  

## `/Companies`

You can get one specific company or all of them (`GET /companies/:code` or `GET /companies`)  
You can add edit and delete companies as well: (Required JSON will be given in parentheses)
> - `POST /companies` ({code, name, description})
> - `PUT /companies/:code` ({name, description})
> - `DELETE /comapnies/:code`

## `/invoices`

You can get one specific invoice or all of them (`GET /invoices/:id` or `GET /invoices`)  
You can add edit and delete invoices as well: (Required JSON will be given in parentheses)
> - `POST /invoices` ({comp_code, amt})
> - `PUT /invoices/:id` ({amt})
> - `DELETE /invoices/:id`
