# para essa conf de create-react-app, node com typescript a versão 1.15.0 funciona bem e não costuma dar problemas
FROM nginx:1.15.0

# apagar o arquivo de configuração default do nginx
RUN rm /etc/nginx/conf.d/default.conf

# e copia o arquivo nginx.conf que criamos na pasta mencionada acima
COPY nginx.conf /etc/nginx/conf.d