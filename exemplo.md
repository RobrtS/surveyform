** start of undefined **

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />
    <title>Formulário</title>
  </head>
  <body>
    <div id="nav-socials">
      <main>
        <div>
         <h1 id="title">Formulário de Pesquisa</h1>
         <p id="description">Esse formulário é uma forma de entender o seu pensamento e pesquisar o seus gostos</p>
        </div>
     
      <section>
        <form id="survey-form">
          <label id="name-label" for="">
            Nome<input
              id="name"
              required
              name="full-name"
              type="text"
              placeholder="digite o seu nome"
            />
          </label>

          <label id="email-label" for=""
            >E-mail<input
              id="email"
              required
              name="email"
              type="email"
              placeholder="email@email.com"/>
          </label>

          <label id="number-label" for=""
            >Idade<input
              type="number"
              name="age"
              id="number"
              max="100"
              min="18"
              placeholder="ex:22"/>
          </label>

       

        <label for="">Como ficou sabendo de nós </label>

          <select name="dropdown" id="dropdown">
            <option value=""></option>
            <option value="1">Google</option>
            <option value="2">Facebook</option>
            <option value="3">Twitter</option>
            <option value="4">Outro</option>
          </select>
          <fieldset>
            <label for="">Você recomendaria nosso serviço?</label>
            <input value="radio" name="radio" type="radio" checked /> Sim
            <input value="radio" name="radio" type="radio" /> Não
            <input value="radio" name="radio" type="radio" /> Talvez
          </fieldset>
          <fieldset>
            <label>Qual é o seu objetivo?</label>
          <input value="checkbox" name="checkbox" type="checkbox"/> Estudar
          <input value="checkbox" name="checkbox" type="checkbox"/> Trabalhar
          <input value="checkbox" name="checkbox" type="checkbox"/> Não Sei 
          </fieldset>
          <fieldset>
            <label>Qual é o seu estado?</label>
            <select>
              <option>SP</option>
              <option>RJ</option>
              <option>ES</option>
              <option>MG</option>
              <option>BA</option>
            </select>  
          </fieldset>
          <label for=""> escreva o que você acha dos nossos serviços </label>
          <textarea name="" id="" cols="60" rows="5"></textarea>
          <button id="submit" type="submit" >Enviar</button>
           </form>
      </section>

    </main>

      <footer id="footer">
        <p>All Rights Reserved © by Robert Silva</p>
        <a href="www.google.com">
          <svg
            fill="#ad0000"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 50 50"
            width="40px"
            height="40px"
          >
            <path
              d="M 9 4 C 6.2504839 4 4 6.2504839 4 9 L 4 41 C 4 43.749516 6.2504839 46 9 46 L 25.832031 46 A 1.0001 1.0001 0 0 0 26.158203 46 L 31.832031 46 A 1.0001 1.0001 0 0 0 32.158203 46 L 41 46 C 43.749516 46 46 43.749516 46 41 L 46 9 C 46 6.2504839 43.749516 4 41 4 L 9 4 z M 9 6 L 41 6 C 42.668484 6 44 7.3315161 44 9 L 44 41 C 44 42.668484 42.668484 44 41 44 L 33 44 L 33 30 L 36.820312 30 L 38.220703 23 L 33 23 L 33 21 C 33 20.442508 33.05305 20.398929 33.240234 20.277344 C 33.427419 20.155758 34.005822 20 35 20 L 38 20 L 38 14.369141 L 37.429688 14.097656 C 37.429688 14.097656 35.132647 13 32 13 C 29.75 13 27.901588 13.896453 26.71875 15.375 C 25.535912 16.853547 25 18.833333 25 21 L 25 23 L 22 23 L 22 30 L 25 30 L 25 44 L 9 44 C 7.3315161 44 6 42.668484 6 41 L 6 9 C 6 7.3315161 7.3315161 6 9 6 z M 32 15 C 34.079062 15 35.38736 15.458455 36 15.701172 L 36 18 L 35 18 C 33.849178 18 32.926956 18.0952 32.150391 18.599609 C 31.373826 19.104024 31 20.061492 31 21 L 31 25 L 35.779297 25 L 35.179688 28 L 31 28 L 31 44 L 27 44 L 27 28 L 24 28 L 24 25 L 27 25 L 27 21 C 27 19.166667 27.464088 17.646453 28.28125 16.625 C 29.098412 15.603547 30.25 15 32 15 z"
            />
          </svg>
        </a>
      </footer>
    </div>
  </body>
</html>