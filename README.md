# Sobre o Projeto
API Rest de listagem de beneficiários,
com alguns dados básicos:
 * Nome;
 * email;
 * Data de criação;
 * CNPJ;


# Como rodar?
  ### Primeiro, clone o projeto, com o seguinte comando:
  <blockquote>
    <code>git clone https://github.com/AronNascimento2/API_teste.git</code>
  </blockquote>
  </br>

  ### Para rodar execute o comando: </br></br>
  <blockquote>
    <code>npm run start</code>
  </blockquote>
  </br>

  ### Use o insomnia ou postman para testar: </br></br>
  <blockquote>
     <strong>URL:</strong> https://api-teste-umber.vercel.app/clientes </br>
  </blockquote>
  </br>


 
# Rotas
## Criar beneficiário </br></br>

<blockquote>
  <strong>Método:</strong> POST </br>
  <strong>URL:</strong> https://api-teste-umber.vercel.app/clientes </br>
  <strong>Body (JSON):</strong> </br> </br>

  ```yaml
  {
    "name": "Empresa 01",
    "email": "empresa01@teste.com",
    "cnpj": "12.345.678/0001-00",
    "created_at": "08/05/2024",
    "id": "5765"
  }
  ```
</blockquote>
</br>

## Listar todos projetos: </br></br>

<blockquote>
  <strong>Método:</strong> GET </br>
  <strong>URL:</strong> https://api-teste-umber.vercel.app/clientes </br>

  <strong>Resposta (JSON):</strong> </br></br>

  ```yaml
    [
     {
    "name": "Empresa 01",
    "email": "empresa01@teste.com",
    "cnpj": "12.345.678/0001-00",
    "created_at": "08/05/2024",
    "id": "5765"
  }
    ]
  ```
</blockquote>
</br>

## Listar um único projeto: </br></br>

<blockquote>
  <strong>Método:</strong> GET </br>
  <strong>URL:</strong> https://api-teste-umber.vercel.app/clientes/:id </br>
  <strong>Resposta (JSON):</strong> </br></br>

  ```yaml
  {
    "name": "Empresa 01",
    "email": "empresa01@teste.com",
    "cnpj": "12.345.678/0001-00",
    "created_at": "08/05/2024",
    "id": "5765"
  }
  ```
</blockquote>
</br>

## Alterar um beneficiário: </br></br>

<blockquote>
  <strong>Método:</strong> PUT </br>
  <strong>URL:</strong>  https://api-teste-umber.vercel.app/clientes/:id </br>
  <strong>Body (JSON):</strong> </br> </br>

  ```yaml
    {
 "name": "Terrus Carbon Coffe"
    }
  ```
</blockquote>
</br>

## Deletar um beneficiário </br></br>

<blockquote>
 <strong>Método:</strong> DELETE </br>
  <strong>URL:</strong> https://api-teste-umber.vercel.app/clientes/:id
</blockquote>
</br>


