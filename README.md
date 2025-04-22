#Olá! Vou documentar o passo a passo do meu scritp.
Começando com os comandos necessário e explicando para que serve cada um deles.

No terminal entramos no diretório $ /bin/bash
#Verificar se o apache está instalado
$ if [ ! -x /etc/init.d/apache2 ]; then
echo "apache não encontrado, iniciando a instalação"

#atualiza a lista de pacotes
$sudo apt-get update

#instalação do apache2
$sudo apt-get install apache2 -y "O -y você está dizendo ao sistema para aceitar todas as permissões e continuar a instalação automaticamente, sem precisar de confirmação manual"

#ele vai te mostrar uma mensagem se o seu apache já estiver instalado 
else
  $echo " você já possui o apache instalado 
 fi

 # Criação do diretório e site 
 echo " criando diretório para o site..."
 #Cria o diretório do site 
 $sudo mkdir -p /var/www/ifrn/public_html
 $ Cd /var/www/ifrn/public_html " O comando CD ele permite você entra dentro do diretório "
 
 # Clona o repositório git no diretório do site
  #atenção " Substitua (link)  pelo URL do seu repositório
    #No terminal digite 
     $sudo git clone (link)

#Copia o conteúdo do repositório para o diretório de produção 
#Substitua 

