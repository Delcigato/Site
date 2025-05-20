body {
    font-family: sans-serif;
    background-color: #f8f0f5; /* Rosa pink bem suave */
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.container {
    background-color: #e6e0eb; /* Roxo suave */
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    padding: 30px;
    width: 80%;
    max-width: 960px;
    animation: fadeIn 1s ease-in-out; /* Animação de fade in */
}

header h1 {
    color: #800080; /* Roxo mais intenso */
    text-align: center;
    margin-bottom: 20px;
    text-shadow: 2px 2px #d8bfd8; /* Sombra suave no título */
}

main section {
    margin-bottom: 25px;
    padding: 20px;
    background-color: #f0808020; /* Rosa pink transparente */
    border-radius: 8px;
    border: 1px solid #d8bfd8; /* Borda suave */
}

main section h2 {
    color: #9932cc; /* Roxo médio */
    margin-top: 0;
    border-bottom: 2px solid #d8bfd8;
    padding-bottom: 10px;
    margin-bottom: 15px;
}

footer {
    text-align: center;
    color: #778899; /* Cinza azulado suave */
    font-size: 0.9em;
    margin-top: 20px;
}

/* Animações */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
}

main section:hover {
    transform: scale(1.02); /* Pequena animação ao passar o mouse */
    transition: transform 0.3s ease-in-out;
}
