# README
Link to my fly.io server application:
https://eventbrite-tp.fly.dev/


To know:
- gem Devise create automatically email senders, no need to create a usermailer.
- change parameters in config>initializers>devise :
   => change the email here : onfig.mailer_sender = 'tommytp@hotmail.fr'
- If you want to use "Confirmation_instructions.html.erb", "email_changed.html.erb" and "password_change.html.erb" you need to activate in model "Confirmable"


