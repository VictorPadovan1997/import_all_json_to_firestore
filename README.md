# import_all_json_to_firestore

- How to automatically import a .json file into the firebase store.

- Para fazer a importação é necessario que vai até
- Firebase -> clique no icone ⚙️ -> visão gerall do projeto(project overview) -> Contas de Serviço -> node(X) Gerar nova chave privada.
Ao fazer o download do .json substitui o nome para key_service_account e subsitui para sua configuraçoes no projeto.

Agora sobe o seus dados .json para o banco de dados de forma automatizada:

- npm install --save firebase-admin
- node upload_files.js

