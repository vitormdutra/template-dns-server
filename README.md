# Importante

Este documento serve para auxiliar na criação do servidor de DNS local para tratar os ips, assim possibilitando o tratamento de qualquer ip dentro da rede estabelecida responda por um determinado dns que funciona de forma local.

Todo esse documento foi executado no SO Oracle Linux que possui caracteristicas semelhantes ao RHEL e CentOS, utilizando a ferramenta Bind9 para executar o funcionamento do servidor de DNS.

Vale resaltar que no SO Oracle Linux, RHEL e CentOS a ferramenta Bind9 possui outro nome e outras caracteristicas de forma que essa ferramenta recebe o nome de named e não de Bind9 e seus arquivos .db default vem dentro do caminha /var/named e seu arquivo de configuração se encontra no caminho /etc/named.conf onde é efetuado a criação das zonas de DNS.
