# urban_frogs
Repositório de dados do mestrado do Paulo Mateus Cruz Santos (PPGZool - UFAM). Dissertação defendida em 2023-03-06.

Este repositório contém os arquivos em formato "csv" baixados da plataforma Arbimon em 2023-04-06 e o código R utilizado para analisar os dados. Os arquivos correspondem aos dados brutos do projeto "Biodiversidade nas cidades", coordenado pela professora Cintia Cornelius (UFAM).

- **sites-export.csv:** metadados dos sítios onde os gravadores de áudio autônomos foram instalados.
- **export-recording.csv:** conjunto de arquivos de áudio (gravações) utilizado para detectar sapos por meio do algoritmo *Pattern Matching* no Arbimon. Tais gravações compõem a playlist denominada "TUDO".
- **demais arquivos csv:** arquivos para cada uma das 19 espécies investigadas com o resultado das detecções (via *Pattern Matching*) e validações (feitas por humanos para confirmar se as detecções eram positivos-verdadeiros). Das 19 espécies investigadas, 13 foram detectadas no estudo (*i.e.* pelo menos uma detecção positivo-verdadeiro).
- **study_region.tif:** raster do MapBiomas (coleção 8, ano 2020) cortado para a região de abrangência dos pontos de amostragem com uma margem de 10 km (`c(xmin = -60.744974, xmax = -58.339477, ymin = -3.376880, ymax = -1.941086)`). O raster original do Brasil foi baixado pelo link <https://storage.googleapis.com/mapbiomas-public/initiatives/brasil/collection_8/lclu/coverage/brasil_coverage_2020.tif>.
- **Rcode:** código R utilizado para analisar os dados de sapos, escrito por Anderson Saldanha Bueno. O Rcode está em constante atualização.
