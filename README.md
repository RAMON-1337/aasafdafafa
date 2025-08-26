<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>
      <form>
        Nome: <input type="text" name="nome" required /><br />
        Idade: <input type="date" name="idade" required /><br />
        cpf:
        <input
          type="text"
          id="cpf"
          name="cpf"
          pattern="\d{3}\.\d{3}\.\d{3}-\d{2}"
          required
        />
        <br />
        Email: <input type="email" name="email" required /><br />
        Estado:
        <select name="estado" id="estado" required>
          <option value="AC">Acre</option>
          <option value="AL">Alagoas</option>
          <option value="AP">Amapá</option>
          <option value="AM">Amazonas</option>
          <option value="BA">Bahia</option>
          <option value="CE">Ceará</option>
          <option value="DF">Distrito Federal</option>
          <option value="ES">Espírito Santo</option>
          <option value="GO">Goiás</option>
          <option value="MA">Maranhão</option>
          <option value="MT">Mato Grosso</option>
          <option value="MS">Mato Grosso do Sul</option>
          <option value="MG">Minas Gerais</option>
          <option value="PA">Pará</option>
          <option value="PB">Paraíba</option>
          <option value="PR">Paraná</option>
          <option value="PE">Pernambuco</option>
          <option value="PI">Piauí</option>
          <option value="RJ">Rio de Janeiro</option>
          <option value="RN">Rio Grande do Norte</option>
          <option value="RS">Rio Grande do Sul</option>
          <option value="RO">Rondônia</option>
          <option value="RR">Roraima</option>
          <option value="SC">Santa Catarina</option>
          <option value="SP">São Paulo</option>
          <option value="SE">Sergipe</option>
          <option value="TO">Tocantins</option>
          </select><br />
        Gênero: <br />
        <label>
          <input type="radio" name="genero" value="masculino" />
          Masculino </label
        ><br />
        <label>
          <input type="radio" name="genero" value="feminino" />
          Feminino </label
        ><br />
        Filme favorito:
        <select name="filme" id="filme" >
          <option value="acao">Ação</option>
          <option value="comedia">Comédia</option>
          <option value="drama">Drama</option>
          <option value="terror">Terror</option>
          <option value="romance">Romance</option>
        </select> <br>
        <button type="submit">Enviar formulário</button>
      </form>
    </h1>
  </body>
</html>
