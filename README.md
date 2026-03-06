[login.html](https://github.com/user-attachments/files/25806613/login.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <!-- Fonte moderna -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <!-- Ícones Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
  [Style.css](https://github.com/user-attachments/files/25806661/Style.css)
</head>
<body>
    <div class="login-container">
        <div class="login-header">
            <i class="fas fa-store"></i>
            <h1>Bem-vindo à nossa loja</h1>
            <p>Faça login para acessar sua conta</p>
        </div>
        
        <form action="home.html" method="post">
            <div class="input-group">
                <i class="fas fa-user"></i>
                <input type="text" id="username" name="username" placeholder="Usuário" required>
            </div>

            <div class="input-group">
                <i class="fas fa-lock"></i>
                <input type="password" id="password" name="password" placeholder="Senha" required>
            </div>

            <div class="checkbox-group">
                <input type="checkbox" id="remember" name="remember">
                <label for="remember">Lembrar-me</label>
            </div>

            <div class="checkbox-group">
                <input type="checkbox" id="termos" required>
                <label for="termos">
                    Eu li e concordo com os 
                    <a href="termos.html" target="_blank">Termos de Uso</a>
                </label>
            </div>

            


            <button type="submit">Entrar <i class="fas fa-sign-in-alt"></i></button>
        </form>
    </div>
</body>
</html>
