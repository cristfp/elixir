# elixir
Com o computador devidamente instalado e configurado com: Elixir/ Erlang, Phoenix, Postgres, node.

É só subir o servidor via linha de comando mix phx.server

A aplicação está em localhost:4000/todos

Esta é a primeira versão com os requisitos obrigatórios do teste
##################################################################################################
A versão 2 possui a autenticação e melhoras no design


As rotas para back-end são:

     session_path  GET     /sessions/new            Coherence.SessionController :new
     session_path  POST    /sessions                Coherence.SessionController :create
     
    registration_path  GET     /registrations/new       Coherence.RegistrationController :new
    registration_path  POST    /registrations           Coherence.RegistrationController :create
    password_path  GET     /passwords/new           Coherence.PasswordController :new
    password_path  POST    /passwords               Coherence.PasswordController :create
    password_path  GET     /passwords/:id/edit      Coherence.PasswordController :edit
    password_path  PATCH   /passwords/:id           Coherence.PasswordController :update
                   PUT     /passwords/:id           Coherence.PasswordController :update
      unlock_path  GET     /unlocks/new             Coherence.UnlockController :new
      unlock_path  POST    /unlocks                 Coherence.UnlockController :create
      unlock_path  GET     /unlocks/:id/edit        Coherence.UnlockController :edit
     invitation_path  GET     /invitations/:id/edit    Coherence.InvitationController :edit
     invitation_path  POST    /invitations/create      Coherence.InvitationController :create_user
     invitation_path  GET     /invitations/new         Coherence.InvitationController :new
     invitation_path  POST    /invitations             Coherence.InvitationController :create
     invitation_path  GET     /invitations/:id/resend  Coherence.InvitationController :resend
     session_path  DELETE  /sessions                Coherence.SessionController :delete
     registration_path  GET     /registrations           Coherence.RegistrationController :show
     registration_path  PUT     /registrations           Coherence.RegistrationController :update
     registration_path  PATCH   /registrations           Coherence.RegistrationController :update
     registration_path  GET     /registrations/edit      Coherence.RegistrationController :edit
     registration_path  DELETE  /registrations           Coherence.RegistrationController :delete
        page_path  GET     /                        TodoElixirWeb.PageController :index
        todo_path  GET     /todos                   TodoElixirWeb.TodoController :index
        todo_path  GET     /todos/:id/edit          TodoElixirWeb.TodoController :edit
        todo_path  GET     /todos/new               TodoElixirWeb.TodoController :new
        todo_path  GET     /todos/:id               TodoElixirWeb.TodoController :show
        todo_path  POST    /todos                   TodoElixirWeb.TodoController :create
        todo_path  PATCH   /todos/:id               TodoElixirWeb.TodoController :update
                   PUT     /todos/:id               TodoElixirWeb.TodoController :update
        todo_path  DELETE  /todos/:id               TodoElixirWeb.TodoController :delete
        user_path  GET     /users                   TodoElixirWeb.UserController :index
        user_path  GET     /users/:id/edit          TodoElixirWeb.UserController :edit
        user_path  GET     /users/new               TodoElixirWeb.UserController :new
        user_path  GET     /users/:id               TodoElixirWeb.UserController :show
        user_path  POST    /users                   TodoElixirWeb.UserController :create
        user_path  PATCH   /users/:id               TodoElixirWeb.UserController :update
                   PUT     /users/:id               TodoElixirWeb.UserController :update
        user_path  DELETE  /users/:id               TodoElixirWeb.UserController :delete
        page_path  GET     /                        CoherenceExampleWeb.PageController :index
        
        
        
        
        
