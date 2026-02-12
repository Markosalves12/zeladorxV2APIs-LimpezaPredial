
### 2. README para o repositório: `Markosalves12/zeladorxV2APIs-LimpezaPredial`

```markdown
# APIs Limpeza Predial - ZeladorX V2

API RESTful para gerenciamento de serviços de **limpeza e conservação predial** na plataforma **ZeladorX**.

## ✨ Visão Geral

Funcionalidades principais:
- Agendamento e controle de limpezas diárias, semanais e periódicas
- Registro de faxinas em áreas comuns, fachadas, garagens e subsolos
- Gestão de equipes de limpeza e materiais utilizados
- Relatórios de frequência, conformidade e não conformidades
- Integração com checklist digital e fotos de antes/depois
- Suporte a normas ABNT e exigências sindicais

Perfeito para síndicos, administradoras e empresas terceirizadas de limpeza.

## 📄 Documentação Oficial

A documentação completa (em PDF) está disponível aqui:  
→ [Documentação API Limpeza Predial ZeladorX](https://drive.google.com/file/d/1avhzJyIkYjFO7Xbx8JbxU8zjOpD1ILIp/view)

Visualização inline:  
→ [Página de Documentação](https://seu-dominio.com/docs/limpeza-predial) *(substitua pelo link real da sua página HTML)*

## 🚀 Como Começar

### Pré-requisitos
- Acesso à API ZeladorX (chave gerada no painel)
- Ferramenta de teste: Postman, Insomnia ou cURL

### Exemplo de Chamada (cURL)

```bash
curl -X GET "https://api.zeladorx.com/v2/limpeza/agendamentos" \
  -H "Authorization: Bearer SUA_CHAVE_API" \
  -H "Accept: application/json"
