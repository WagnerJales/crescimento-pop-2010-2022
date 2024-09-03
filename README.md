Trabalho desenvolvido com o objetivo de estimar o crescimento populacional entre os #censos de 2010 e 2022 para a cidade de #SãoLuís #maranhão que seguiu conforme descrito:

Como as bases dos 2 censos (#SHPfiles) não eram compatíveis, foi  necessário um tratamento prévio no #QGIS para limitar as feições dos #setorescensitários dos 2 períodos para os limites do município; 

O #censo2022 subdividiu os setores censitários de 2010 ,e em alguns casos, redimensionou não sendo possível uma sobreposição direta dos dados em função das feições.

Foi preciso calcular a proporção das áreas dos setores censitários de 2022 nos setores de 2010 e com base nesta proporção, ponderou-se a população de 2022 e recalculou-se o total para nova base gráfica usando bibliotecas do #Python. 

Ao final, voltou-se com os dados para o QGIS para melhorar a visualização dos dados em mapa.
