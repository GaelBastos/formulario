# formulario
formulario feito com bootstrap
<!DOCTYPE html>
<html lang="pt_br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="./css/style.css">
    <title> cadastro </title>
</head>


<body>
    <header>
        <div class="container">
            <div class="row">
                <div class="col">
                    <h1> <img src="" alt="imagem"> </h1>
                </div>

                <div class="col">

                    <ul class="nav justify-content-end">
                        <li class="nav-item"><a class="nav-link active" href="">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#sobre">Sobre</a></li>
                        <li class="nav-item"><a class="nav-link" href="#produtos">Produtos</a></li>
                        <li class="nav-item"><a class="nav-link" href="#contatos">Contatos</a></li>
                    </ul>

                </div>
            </div>
        </div>
    </header>

    <section id="cadastro">
        <div class="container">
            <div class="row">
                <div class="col-md-12 col-sm-12">
                    <h2> Cadastro </h2>
                    <p>prenchass os campos pra concluir o cadastro </p>
                </div>
            </div>


            <form class="form">
                <div class="row">
                    <div class="col">
                        <div class="imput-group">
                            <label for="nome">Nome</label>
                            <input class="form-control" type="text" name="nome" placeholder="digite seu nome">
                        </div>
                    </div>

                    <div class="col">
                        <div class="imput-group">
                            <label for="email">Email</label>
                            <input class="form-control" type="text" name="email" placeholder="digite seu Email">
                        </div>
                    </div>
                </div>

                <div class="row">
                    <div class="col">
                        <label for="endereco">Endereço completo</label>
                        <input type="text" name="endereço" class="form-control" placeholder="Endereço completo">
                    </div>
                </div>

                <div class="row">
                    <div class="col">
                        <label for="cidade"> cidade </label>
                        <input type="text" name="cidade" id="cidade" class="form-control">
                    </div>

                    <div class="col">
                        <label for="estado"> Estado </label>
                        <select name="estado" id="estado" class="form-control">                        
                        <option value> selecione o estado </option>
                        <option value="sp"> Sâo paulo </option>
                        <option value="al"> alagoas </option>
                        <option value="rj"> rio de janeiro </option>
                        <option value="bc"> baoneario camburiu</option>
                        <option value="am"> amazonas </option>
                    </select>
                    </div>

                    <div class="col">
                        <label for="cep"> CEP</label>
                        <input type="text" name="cep" id="cep" class="form-control">
                    </div>
                </div>

                <div class="row">
                    <div class="col">
                        <div class="input-group"></div>
                        <label for="info">informações</label>
                        <textarea class="form-control" name="informacoes" id="informacoes" rows="05"></textarea>
                    </div>
                </div>

                <div class="row">
                    <div class="col">
                        <div class="form-check">
                            <input type="checkbox" name="promocionais" id="promocionais">
                            <label for="promocionais" class="form-check-label"> aceito receber mensagens promocionais</label>
                        </div>
                    </div>
                </div>

                <button type="submit" class="btn btn-lg btn-success"> Cadastrar </button>

            </form>

            <p>
                <a href="#modal1" data-bs-toggle="modal" data-bs-target="#modal1">Cadastre-se</a> Para receber novidades.</p>







        </div>

        <section>

            <div class="modal fade" id="modal1">
                <div class="modal-dialog">
                    <div class="modal-content">

                        <div class="modal-header">
                            <h5 class="modal-title"> inscrever-me na lista </h5>
                            <button class="btn-close" data-bs-dismiss="modal" aria-label="Close"> </button>
                        </div>

                        <div class="modal-body">
                            <h6> preencha os campos pra receber promoções</h6>

                            <form class="form-inline ">
                                <div class="form-group col-8">
                                    <input type="text" class="form-control mb-2" name="nome" placeholder="nome">
                                </div>
                                <div class="form-group col-8">
                                    <input type="text" class="form-control mb-2" name="email" placeholder="email" required>
                                </div>
                                <div class="form-group col-4">
                                    <button type="submit" class="btn btn-sm btn btn-outline-success"> Receber novidades</button>
                                </div>
                            </form>

                        </div>
                        <div class="modal-footer">
                            <button type="button" class="btn btn-secondary mb-2" data-bs-dismiss="modal">fechar</button>
                        </div>
                    </div>
                </div>
            </div>
            </div>

            <script src="./bootstrap/js/bootstrap.bundle.min.js">
            </script>
</body>

</html>
