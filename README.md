<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo Completo - Roberto Alves</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Estilos gerais */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background-color: #f5f7fa;
            color: #333;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        /* Estilo do cabeçalho/navegação */
        nav {
            background: linear-gradient(135deg, #6e48aa 0%, #9d50bb 100%);
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 30px;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            padding: 0;
            margin: 0;
            justify-content: center;
        }
        
        nav li {
            margin: 0 15px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 4px;
            transition: background-color 0.3s;
        }
        
        nav a:hover {
            background-color: rgba(255, 255, 255, 0.2);
        }
        
        /* Seção do currículo */
        .resume-section {
            background-color: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            margin-bottom: 30px;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid white;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            display: block;
            margin: 0 auto 20px;
        }
        
        /* Estilos para a seção de contato */
        .contact-info {
            margin-bottom: 15px;
        }
        
        .map-container {
            margin-top: 15px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 3px 6px rgba(0,0,0,0.1);
        }
        
        /* Estilo do fieldset (moldura do formulário) */
        fieldset {
            border: 2px solid #6e48aa;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 30px;
            background-color: white;
        }
        
        legend {
            font-size: 1.2em;
            font-weight: bold;
            color: #6e48aa;
            padding: 0 10px;
        }
        
        /* Estilos dos campos do formulário */
        .form-group {
            margin-bottom: 15px;
        }
        
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: 600;
        }
        
        input[type="text"],
        input[type="email"],
        input[type="tel"],
        input[type="time"],
        input[type="date"],
        textarea,
        select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
        }
        
        textarea {
            min-height: 100px;
            resize: vertical;
        }
        
        .checkbox-group, .radio-group {
            margin: 8px 0;
        }
        
        /* Estilo dos botões */
        .buttons {
            display: flex;
            justify-content: flex-end;
            gap: 10px;
            margin-top: 20px;
        }
        
        button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        button[type="submit"] {
            background-color: #4CAF50;
            color: white;
        }
        
        button[type="reset"] {
            background-color: #f44336;
            color: white;
        }
        
        button:hover {
            opacity: 0.9;
        }
        
        /* Estilo para campos obrigatórios */
        .required:after {
            content: " *";
            color: #f44336;
        }
        
        /* Ícones */
        .icon {
            color: #6e48aa;
            width: 20px;
            display: inline-block;
            text-align: center;
            margin-right: 10px;
        }
        
        /* Cores específicas */
        .text-primary {
            color: #6e48aa;
        }
        
        .text-secondary {
            color: #9d50bb;
        }
        
        .text-center {
            text-align: center;
        }
    </style>
</head>
<body>
    <!-- Navegação entre currículo e formulário -->
    <nav>
        <ul>
            <li><a href="#curriculo">Currículo</a></li>
            <li><a href="#formulario">Formulário</a></li>
        </ul>
    </nav>

    <!-- Seção do Currículo -->
    <section id="curriculo" class="resume-section">
        <!-- SUA FOTO -->
        <img src="AppData/Local/Packages/5319275A.WhatsAppDesktop_cv1g1gvanyjgm/TempState/0B9B1194074A1EBA5D5C73F89C9E9D9C/Imagem do WhatsApp de 2025-04-05 à(s) 19.48.07_a78d6559.jpg" alt="Roberto Alves" class="profile-img">
        <h1 class="text-center text-primary">Roberto Alves Azevedo</h1>
        <h2 class="text-center text-secondary">Estudante de Análise e Desenvolvimento de Sistemas</h2>
        
        <h3><i class="fas fa-id-card icon"></i> Contato</h3>
        <div class="contact-info">
            <p><i class="fas fa-envelope icon"></i> <strong>Email:</strong> <a href="mailto:roberto2005alvesazevedo@gmail.com">roberto2005alvesazevedo@gmail.com</a></p>
            <p><i class="fab fa-github icon"></i> <strong>GitHub:</strong> <a href="https://github.com/Roberto888-alv" target="_blank">Roberto888-alv</a></p>
            <p><i class="fab fa-linkedin icon"></i> <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/roberto-azevedoo-6629a6265/" target="_blank">roberto-azevedoo</a></p>
            
            <!-- SUA LOCALIZAÇÃO E MAPA -->
            <p><i class="fas fa-map-marker-alt icon"></i> <strong>Localização:</strong> R. Alto da Boa Vista, 34 - Passarinho, Olinda/PE</p>
            <div class="map-container">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15804.208037051345!2d-34.9127447!3d-7.9935663!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7ab1779e4b133d1%3A0x117fb2b256119dc6!2sR.%20Alto%20da%20Boa%20Vista%2C%2034%20-%20Passarinho%2C%20Olinda%20-%20PE%2C%2053160-820!5e0!3m2!1spt-BR!2sbr!4v1746325068876!5m2!1spt-BR!2sbr" 
                width="100%" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
        </div>
        
        <h3><i class="fas fa-user icon"></i> Sobre</h3>
        <p>Estudante de ADS no 2º período no Senac-PE, com conhecimentos básicos em JavaScript e HTML. Buscando constantemente aprimorar minhas habilidades em desenvolvimento web.</p>
        
        <h3><i class="fas fa-graduation-cap icon"></i> Formação</h3>
        <p><strong>Análise e Desenvolvimento de Sistemas</strong><br>
        Senac-PE | 2024-2026 (Cursando)</p>
        <p><strong>Ensino Médio Completo</strong><br>
        Doutor Francisco Pessoa de Queiroz</p>
        
        <h3><i class="fas fa-code icon"></i> Habilidades</h3>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript Básico</li>
            <li>Git e GitHub</li>
        </ul>
    </section>

    <!-- Seção do Formulário -->
    <section id="formulario" class="resume-section">
        <h2 class="text-primary text-center">Formulário de Contato</h2>
        
        <form id="contactForm">
            <fieldset>
                <legend>Informações Pessoais</legend>
                
                <div class="form-group">
                    <label for="firstName" class="required">Nome</label>
                    <input type="text" id="firstName" name="firstName" required>
                </div>
                
                <div class="form-group">
                    <label for="lastName" class="required">Sobrenome</label>
                    <input type="text" id="lastName" name="lastName" required>
                </div>
                
                <div class="form-group">
                    <label for="phone" class="required">Telefone</label>
                    <input type="tel" id="phone" name="phone" placeholder="(00) 00000-0000" pattern="\([0-9]{2}\) [0-9]{5}-[0-9]{4}" required>
                </div>
                
                <div class="form-group">
                    <label for="email" class="required">E-mail</label>
                    <input type="email" id="email" name="email" placeholder="seu@email.com" required>
                </div>
            </fieldset>
            
            <fieldset>
                <legend>Detalhes do Serviço</legend>
                
                <div class="form-group">
                    <label for="language" class="required">Língua aplicada no serviço</label>
                    <select id="language" name="language" required>
                        <option value="" disabled selected>Selecione</option>
                        <option value="ingles">Inglês</option>
                        <option value="espanhol">Espanhol</option>
                        <option value="frances">Francês</option>
                        <option value="portugues">Português (pt-br)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label class="required">Linguagens de programação preferidas</label>
                    <div class="checkbox-group">
                        <input type="checkbox" id="langJs" name="languages" value="javascript">
                        <label for="langJs">JavaScript</label>
                    </div>
                    <div class="checkbox-group">
                        <input type="checkbox" id="langPython" name="languages" value="python">
                        <label for="langPython">Python</label>
                    </div>
                    <div class="checkbox-group">
                        <input type="checkbox" id="langJava" name="languages" value="java">
                        <label for="langJava">Java</label>
                    </div>
                </div>
                
                <div class="form-group">
                    <label class="required">Banco de dados recomendado</label>
                    <div class="radio-group">
                        <input type="radio" id="dbMysql" name="database" value="mysql" required>
                        <label for="dbMysql">MySQL</label>
                    </div>
                    <div class="radio-group">
                        <input type="radio" id="dbPostgres" name="database" value="postgres">
                        <label for="dbPostgres">PostgreSQL</label>
                    </div>
                    <div class="radio-group">
                        <input type="radio" id="dbMongo" name="database" value="mongodb">
                        <label for="dbMongo">MongoDB</label>
                    </div>
                </div>
            </fieldset>
            
            <fieldset>
                <legend>Agendamento</legend>
                
                <div class="form-group">
                    <label for="shift" class="required">Turno de preferência para reuniões</label>
                    <select id="shift" name="shift" required>
                        <option value="" disabled selected>Selecione</option>
                        <option value="manha">Manhã (8h-12h)</option>
                        <option value="tarde">Tarde (13h-18h)</option>
                        <option value="noite">Noite (19h-22h)</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="meetingTime" class="required">Melhor horário para reuniões</label>
                    <input type="time" id="meetingTime" name="meetingTime" required>
                </div>
                
                <div class="form-group">
                    <label for="deliveryDate" class="required">Previsão de entrega desejada</label>
                    <input type="date" id="deliveryDate" name="deliveryDate" required>
                </div>
            </fieldset>
            
            <fieldset>
                <legend>Mensagem e Anexos</legend>
                
                <div class="form-group">
                    <label for="message" class="required">Mensagem</label>
                    <textarea id="message" name="message" required></textarea>
                </div>
                
                <div class="form-group">
                    <label for="fileUpload" class="required">Upload de protótipo (PDF, DOC, JPEG, PNG)</label>
                    <input type="file" id="fileUpload" name="fileUpload" accept=".pdf,.doc,.docx,.jpg,.jpeg,.png" required>
                </div>
            </fieldset>
            
            <div class="buttons">
                <button type="reset">Limpar</button>
                <button type="submit">Enviar</button>
            </div>
        </form>
    </section>

    <script>
        // Máscara para telefone
        document.getElementById('phone').addEventListener('input', function(e) {
            const x = e.target.value.replace(/\D/g, '').match(/(\d{0,2})(\d{0,5})(\d{0,4})/);
            e.target.value = !x[2] ? x[1] : '(' + x[1] + ') ' + x[2] + (x[3] ? '-' + x[3] : '');
        });

        // Validação do formulário
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            if (!this.checkValidity()) {
                e.preventDefault();
                alert('Por favor, preencha todos os campos obrigatórios corretamente!');
            } else {
                alert('Formulário enviado com sucesso! (Simulação)');
                // this.submit(); // Descomente para envio real
            }
        });
    </script>
</body>
</html>
