<template>
    <section>
      <div class="book-form">
        <h2>Registrar Família</h2>
        <hr />
        <form>
          <div>
            <label for="nome-familia">Nome da Família:</label>
            <input type="text" id="nome-familia" required />
          </div>
          <div>
            <label for="senha">Senha:</label>
            <input type="password" id="senha" required />
          </div>
          <button type="submit">Registrar</button>
        </form>
      </div>
    </section>
  </template>
  
  <style scoped>
  .book-form {
    width: 600px;
    height: 100%;
    margin: 0 auto;
    padding: 20px;
    border-radius: 10px;
    background-color: #E7E7E7;
    color: #000000;
  }
  
  .book-form h2 {
    color: #000000;
    justify-content: center;
    display: flex;
    align-items: center;
  }
  
  .book-form div {
    margin-bottom: 30px;
  }
  
  .book-form label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
  }
  
  .book-form input {
    width: 100%;
    padding: 8px;
    box-sizing: border-box;
    color: #000000;
  }
  
  button {
    padding: 10px 15px;
    background-color: #e91e63;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  
  button:hover {
    background-color: rgb(233, 132, 149);
  }
  
  hr {
    width: 280px;
    margin: 0 auto;
    border: none;
    height: 2px;
    background-color: #e91e63;
  }
  </style>
  