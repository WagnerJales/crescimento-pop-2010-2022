Trabalho desenvolvido com o objetivo de estimar o crescimento populacional entre os censos de 2010 e 2022 para a cidade de São Luís/MA com as seguinte etapas:
As bases gráficas (SHP files) não eram compatíveis sendo necessário um tratamento prévio no QGIS para limitar as feições dos setores censitários para os limites do municipio;
O censo de 2022 subdividiu os centores censitários de 2010 e em alguns casos, redimensionou não sendo possivel uma sobreposição direta dos dados em função das feições;
Foi preciso calcular a proporção das áreas dos setores censitários de 20222 nos setores de 2010 e com base nesta proporção, ponderar a população de 2022 e recalcular o total para nova base gráfica usando python.
Ao final, voltou-se com os dados para o QGIS para melhorar a visualização dos dados em mapa.
