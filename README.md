<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  
  <!-- Bootstrap CSS (CDN) -->
  <link 
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" 
    rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"  
    crossorigin="anonymous" 
  />
  
  <!-- Seu CSS personalizado -->
  <link rel="stylesheet" href="style.css" />
  
  <title>Meu Projeto com Bootstrap</title>
</head>
<body>

  <header class="container my-4">
    <h1 class="text-center text-primary">Bem-vindo ao meu projeto!</h1>
  </header>

  <main class="container">
    <div class="row">
      <div class="col-md-6">
        <div class="card">
          <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="Imagem Exemplo" />
          <div class="card-body">
            <h5 class="card-title">Título do Card</h5>
            <p class="card-text">Este é um exemplo de um card utilizando Bootstrap para estruturar conteúdo e imagens.</p>
            <a href="#" class="btn btn-primary">Saiba Mais</a>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <p>Este é um texto simples ao lado do card. O layout é responsivo e se adapta para dispositivos móveis automaticamente.</p>
      </div>
    </div>
  </main>

  <!-- Bootstrap JS Bundle (Popper + Bootstrap JS) -->
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
    crossorigin="anonymous"
  ></script>
</body>
</html>
