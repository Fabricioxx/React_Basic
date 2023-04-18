
## Como Instalar o Vscode e Node.js no pendrive




- site do vscode baixar a versão x64 .zip eztrair a pasta
-  site do node.js baixar o arquivo .zip do node e extrair no pendrive

Supondo que o diretório do Node.js portable esteja localizado em E:\partables\node, você pode adicionar o diretório à variável Path com o seguinte comando no PowerShell:

```javascript

 $env:Path += ";E:\partables\node"

```
Isso adiciona o caminho E:\partables\node à variável Path, permitindo que o PowerShell localize o executável do Node.js quando você o chamar em um terminal.

_Tenha em mente que essa alteração afeta **apenas a sessão atual do PowerShell**. Se você deseja que essa alteração seja permanente, você pode adicionar o caminho do diretório do Node.js portable à variável de ambiente Path no painel de controle do Windows, na seção de Variáveis de ambiente._


Este comando exibe todos os caminhos incluídos na variável de ambiente Path. Verifique se o caminho para o diretório do Node.js (no seu caso, E:\partables\node) está listado na saída do comando. Se não estiver, você precisará adicionar o caminho à variável de ambiente Path conforme descrito na minha resposta anterior.
```javascript
echo $env:Path

```

Se o caminho para o diretório do Node.js estiver listado na saída do comando echo $env:Path, verifique se você digitou o comando corretamente. O comando para exibir a versão do Node.js deve ser digitado como node -v, sem aspas. Se mesmo assim o erro persistir, tente reiniciar o PowerShell para garantir que as alterações na variável de ambiente Path sejam carregadas corretamente.
