# Usa uma imagem base com Apache
FROM httpd:2.4

# Copia seu index.html para o diretório padrão do Apache
COPY index.html /usr/local/apache2/htdocs/

# Copia sua imagem de perfil (certifique-se de que o nome esteja correto)
COPY minha-foto.PNG /usr/local/apache2/htdocs/

# Expõe a porta 80 para acesso web
EXPOSE 80
