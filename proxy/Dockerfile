# Use uma imagem base adequada
FROM nginx:latest

# Copie o certificado e a chave para o container
COPY ./certificados/certificado.crt /etc/nginx/ssl/certificado.crt
COPY ./certificados/certificado.key /etc/nginx/ssl/certificado.key

# Copie o arquivo de configuração do Nginx para o container
COPY ./nginx.conf /etc/nginx/nginx.conf

# Exponha a porta 443 para HTTPS
EXPOSE 443
