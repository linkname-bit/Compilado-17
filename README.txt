RX¹⁷ — Site público + painel de visitas

REQUISITOS
- Node.js 18 ou superior

EXECUTAR LOCALMENTE
1. Descompacte este arquivo.
2. Abra um terminal na pasta.
3. Execute: node server.js
4. Abra http://localhost:3000 para o site público.
5. Abra http://localhost:3000/admin para o painel.
6. Senha inicial: Batata157 (altere antes de publicar)

ANTES DE PUBLICAR
- Defina uma senha forte na variável de ambiente ADMIN_PASSWORD.
- Publique em um serviço que suporte Node.js (por exemplo, Render ou Railway).
- Configure armazenamento persistente para visits.json, pois alguns hosts apagam arquivos locais em reinicializações.
- Configure HTTPS no serviço de hospedagem.
- Adicione uma política de privacidade adequada e informe os visitantes sobre os registros.
- Este protótipo não coleta IP, localização precisa, nem tenta identificar visitantes silenciosamente.
