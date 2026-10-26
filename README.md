# C.T. Taurus — Muay Thai

Site institucional do Centro de Treinamento Taurus Muay Thai, professor Russo.
Projeto estático em HTML, CSS e JavaScript, sem dependências e sem etapa de build.

## Recursos
- Layout responsivo, logo original e fotos da equipe.
- Galeria com filtros e ampliação de imagens.
- Seção Federação com o material institucional fornecido.
- WhatsApp: +55 11 96042-5925, com botão flutuante e formulário que prepara a mensagem.
- Não coleta nem armazena dados do formulário; o usuário confirma o envio no WhatsApp.

## Enviar ao repositório existente
Repositório: https://github.com/abarakus11/cttaurus

1. Extraia o ZIP em uma pasta no computador. Não envie o ZIP ao repositório.
2. Na tela do repositório vazio, clique em **uploading an existing file**.
3. Arraste todos os arquivos extraídos e a pasta `assets` para a página.
4. Escreva `Publicar site C.T. Taurus` como mensagem do commit e confirme em **Commit changes**.
5. Confira que `index.html`, `vercel.json` e a pasta `assets` estão diretamente na raiz, sem uma pasta intermediária.

Os arquivos `.gitignore` e `.gitattributes` são auxiliares do Git. Caso o explorador os oculte, o site ainda funciona sem eles no envio manual.

## Publicar na Vercel
1. Importe o repositório `abarakus11/cttaurus` em um novo projeto.
2. Framework Preset: **Other**.
3. Root Directory: raiz do repositório (deixe o padrão).
4. Build Command: vazio/desativado. Output Directory: `.`.
5. Não há dependências para instalar. Não é necessário configurar variáveis de ambiente.
6. Clique em **Deploy**. O arquivo `vercel.json` já contém a configuração estática.

## Ver no computador
Abra `index.html` no navegador. Para copiar mensagens automaticamente, prefira o site publicado em HTTPS.

## Editar
| Arquivo | Conteúdo |
| --- | --- |
| `index.html` | Textos, seções e menu |
| `style.css` | Cores, layout e regras para celular |
| `config.js` | WhatsApp, endereço, horários e Instagram |
| `script.js` | Galeria, menu e formulário |
| `assets/` | Logo, fotos e imagem da Federação |
| `vercel.json` | Configuração de publicação |

Endereço, horários e Instagram ainda não foram informados e permanecem vazios em `config.js`. O WhatsApp já está configurado. Se o número mudar, atualize também o link do botão flutuante em `index.html`.

## Git pelo terminal (opcional)
Execute dentro da pasta extraída, com Git instalado e sua conta autenticada:

```sh
git init -b main
git add .
git commit -m "Publicar site C.T. Taurus"
git remote add origin https://github.com/abarakus11/cttaurus.git
git push -u origin main
```

Esses comandos pressupõem que a pasta ainda não é um repositório Git e que o repositório remoto está vazio. Não use push forçado para substituir trabalho existente.
