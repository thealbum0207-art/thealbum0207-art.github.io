# FinControl — plano de monetização e alcance | 27/10/2026

Documento de planejamento, não ativa cobranças, publicidade ou novas versões.

## Prioridade 1 — qualidade do site
- Página inicial responsiva com foco nas três funções verificadas: Resumo, Lançamentos e Orçamentos.
- Dois guias educativos originais com links internos e convite para conhecer o app na Google Play.
- Canonical, descrição SEO, metadados sociais, dados estruturados de software, robots.txt e sitemap.xml.
- Não modificar o app-ads.txt enquanto a titularidade dos dois identificadores de editor não estiver esclarecida.
- Não usar estatísticas, depoimentos, promessas de segurança absoluta nem funcionalidades falsas.

## Prioridade 2 — monetização viável

### AdMob
A versão de teste exibe banners de demonstração. Só ativar anúncios reais após aprovação, verificação do app-ads.txt e revisão das declarações de dados e consentimento. Nunca provocar cliques inválidos.

### Compra única FinControl Plus, proposta ainda não implementada
Uma compra não consumível pelo Google Play Billing poderia retirar anúncios e/ou liberar um benefício verdadeiro (por exemplo, exportação offline em PDF). NÃO publicar essa opção no site, na loja ou no app antes de implementar, testar, garantir restauração do direito e definir preço e suporte.

### Assinatura, hipótese futura
Só faz sentido se houver valor recorrente concreto e comprovado; sincronização/backup, se um dia existirem, necessitarão projeto de segurança e nova política de privacidade. Não promover como funcionalidade atual.

### Produtos educativos independentes
É possível desenvolver guias e planilhas originais para venda independente pelo site, com produto real, preço, entrega, suporte e transparência. Não direcionar de dentro do app Google Play a pagamentos externos por conteúdo ou funcionalidades digitais sem participação em programa/exceção aplicável. Não inserir links afiliados sem autorização.

Fontes:
- https://support.google.com/googleplay/android-developer/answer/9858738?hl=pt-br
- https://support.google.com/googleplay/android-developer/answer/10281818?hl=pt-br

## Prioridade 3 — alcance real

### Página da Play Store
Nome existente: FinControl: Finanças Pessoais.

Descrição curta alternativa:
Controle receitas, despesas e orçamentos mensais de forma simples.

Primeiro parágrafo da descrição completa:
Registre receitas e despesas, acompanhe o saldo do mês e configure limites por categoria. O FinControl é um aplicativo Android para organizar suas finanças pessoais com registros locais e sem conexão bancária.

Ordenar prints da versão em PRODUÇÃO: (1) Resumo, (2) Lançamentos, (3) Orçamentos. Não exibir anúncios de teste, saldo inventado sem indicação de exemplo, compras Premium não implementadas ou estética sexualmente sugestiva. Manter identidade visual consistente.

Fonte: https://support.google.com/googleplay/android-developer/answer/13393723

### SEO
URLs de conteúdo útil:
- https://thealbum0207-art.github.io/guia-orcamento/
- https://thealbum0207-art.github.io/controle-despesas/

Enviar https://thealbum0207-art.github.io/sitemap.xml no Search Console, caso a propriedade esteja verificada. A inclusão no Google não é automática.

### Calendário orgânico inicial — 7 ideias de conteúdo
1. Reel 20s: Onde foi parar o dinheiro do mês? Demonstração do Resumo com dados fictícios sinalizados.
2. Reel 30s: Como cadastrar sua primeira despesa em Lançamentos.
3. Post carrossel: 3 categorias úteis para organizar gastos.
4. Dica educativa: Limite do cartão não é receita.
5. Vídeo: Como consultar a distribuição mensal dos gastos.
6. Vídeo: Configurar limite por categoria em Orçamentos.
7. Post: Revisão semanal de gastos em 5 minutos, com link para o guia gratuito.

Todos com CTA transparente para o app na Google Play. Sem compra de downloads, avaliações falsas ou propaganda enganosa.

### Métricas semanais a observar
- Play Console: visitas à ficha, aquisição de usuários, conversão visita-instalação, retenção e falhas/ANRs;
- Search Console: impressões, cliques e termos de busca das páginas;
- Qualidade: comentários reais e bugs resolvidos.

Não inventar números e não gastar anúncios pagos antes de verificar a estabilidade da versão distribuída.

## Pendências antes de monetização comercial
- Confirmar no AdMob qual editor é oficial: pub-3964603090939340 ou pub-3964603090393340.
- Verificar estado do app e app-ads.txt no painel.
- Revisar Segurança dos dados do Play Console para os dados técnicos do SDK de publicidade.
- Criar e testar outra AAB apenas quando houver novos recursos ou anúncios reais aprovados, preservando os dados locais dos usuários.
