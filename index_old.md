# Backup desativado

Este arquivo foi convertido para Markdown para evitar uso como página HTML. O conteúdo original está isolado dentro de um bloco de código.

```html
<!doctype html>
<html lang="pt-BR"><head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>SimplisPay — Gestão Financeira Simplificada</title>
  <!-- SEO básico -->
  <meta name="description" content="Plataforma completa para gestão de pagamentos. Simplifique sua gestão financeira e cresça com a SimplisPay.">
  <meta name="robots" content="index, follow">
  <link rel="canonical" href="https://simplispay-site.netlify.app/">
  <meta name="theme-color" content="#7CCF00">
  
  <!-- Open Graph -->
  <meta property="og:title" content="Simplifique sua gestão financeira.">
  <meta property="og:description" content="Cresça com a SimplisPay.">
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://simplispay-site.netlify.app/">
  <meta property="og:image" content="https://simplispay-site.netlify.app/simplispay2.png">
  <meta property="og:image:alt" content="Logo da SimplisPay">
  <meta property="og:site_name" content="SimplisPay">
  <meta property="og:locale" content="pt_BR">

  <!-- Twitter Cards -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Simplifique sua gestão financeira.">
  <meta name="twitter:description" content="Cresça com a SimplisPay.">
  <meta name="twitter:image" content="https://simplispay-site.netlify.app/simplispay2.png">
  <meta name="twitter:image:alt" content="Logo da SimplisPay">

  <!-- Favicon e fontes -->
  <link rel="icon" type="image/png" href="./logo.png">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&amp;display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/lucide@latest"></script>
  
  <!-- Schema.org -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "SimplisPay",
    "url": "https://simplispay-site.netlify.app/",
    "logo": "https://simplispay-site.netlify.app/simplispay2.png"
  }
  </script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            background: 'rgb(10, 10, 10)',
            foreground: 'rgb(250, 250, 250)',
            card: 'rgb(23, 23, 23)',
            'card-foreground': 'rgb(250, 250, 250)',
            popover: 'rgb(38, 38, 38)',
            'popover-foreground': 'rgb(250, 250, 250)',
            primary: 'rgb(124, 207, 0)',
            'primary-foreground': 'rgb(23, 23, 23)',
            secondary: 'rgb(38, 38, 38)',
            'secondary-foreground': 'rgb(124, 207, 0)',
            muted: 'rgb(38, 38, 38)',
            'muted-foreground': 'rgb(161, 161, 161)',
            accent: 'rgb(64, 64, 64)',
            'accent-foreground': 'rgb(124, 207, 0)',
            destructive: 'rgb(255, 100, 103)',
            'destructive-foreground': 'rgb(250, 250, 250)',
            border: 'rgb(40, 40, 40)',
            input: 'rgb(52, 52, 52)',
            ring: 'rgb(115, 115, 115)',
          }
        }
      }
    }
  </script>
</head>
<body class="antialiased text-foreground bg-background overflow-x-hidden" style="font-family: Inter, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial;">
  
  <!-- Header -->
  <header class="w-full px-3 sm:px-4 md:px-6 pt-4 sm:pt-6 sticky top-2 sm:top-4 z-50 opacity-0 translate-y-4 animate-[fade-in-down_0.6s_ease-out_0.2s_forwards]">
    <div class="max-w-7xl mx-auto">
      <div class="flex bg-card/80 border border-border rounded-full py-2 px-3 sm:px-4 backdrop-blur-md items-center justify-between min-h-[48px] sm:min-h-[52px] shadow-xl">
        <div class="flex items-center gap-2 sm:gap-3">
          <div class="flex items-center gap-2">
            <img src="./simplispay2.png" alt="SimplisPay" class="h-6 sm:h-8 w-auto">
          </div>
        </div>
        <div class="flex items-center gap-3 sm:gap-6">
          <nav class="hidden md:flex items-center gap-6">
            <a href="#" class="text-sm font-medium text-muted-foreground hover:text-primary tracking-tight transition-colors">Suporte</a>
          </nav>
          <a href="https://portal.simplispay.com.br/" class="inline-flex items-center gap-1.5 sm:gap-2 text-primary-foreground bg-primary hover:bg-primary/90 transition-all duration-200 hover:scale-105 text-xs sm:text-sm font-medium tracking-tight rounded-full py-1.5 px-3 sm:py-2 sm:px-4">
            <span class="hidden xs:inline">Acessar Portal</span>
            <span class="xs:hidden">Portal</span>
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="arrow-right" class="lucide lucide-arrow-right w-3.5 h-3.5 sm:w-4 sm:h-4"><path d="M5 12h14"></path><path d="m12 5 7 7-7 7"></path></svg>
          </a>
        </div>
      </div>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="w-full px-3 sm:px-4 md:px-6 mt-6 sm:mt-8 mb-6 sm:mb-8">
    <div class="max-w-7xl mx-auto">
      <div class="relative overflow-hidden bg-card border border-border rounded-3xl sm:rounded-[40px] backdrop-blur opacity-0 translate-y-8 animate-[fade-in-up_0.8s_ease-out_0.4s_forwards]">
        
        <div class="relative p-4 sm:p-6 md:p-8">
          <div class="text-center max-w-4xl mx-auto">
            <div class="inline-flex items-center gap-1.5 sm:gap-2 text-[10px] sm:text-xs font-medium text-primary bg-primary/10 border border-primary/20 rounded-full px-2.5 py-1 sm:px-3 sm:py-1.5 mb-4 sm:mb-6 opacity-0 animate-[fade-in_0.6s_ease-out_0.8s_forwards]">
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="shield-check" class="lucide lucide-shield-check w-3 h-3 sm:w-3.5 sm:h-3.5"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z"></path><path d="m9 12 2 2 4-4"></path></svg>
              <span>Seguro • Simples • Confiável</span>
            </div>
            
            <h1 class="text-3xl sm:text-4xl md:text-5xl lg:text-6xl xl:text-7xl font-semibold text-foreground tracking-tight leading-[1.1] sm:leading-[0.95] mb-4 sm:mb-6 opacity-0 animate-[fade-in-up_0.8s_ease-out_1s_forwards] px-2 sm:px-0">
              Você no comando das suas finanças
            </h1>
            
            <h2 class="text-base sm:text-lg md:text-xl leading-relaxed text-muted-foreground max-w-3xl mx-auto mb-8 sm:mb-12 opacity-0 animate-[fade-in-up_0.8s_ease-out_1.2s_forwards] px-2 sm:px-4">
              Uma plataforma completa para gestão de pagamentos, feita para simplificar o dia a dia do seu negócio. Simples, segura e poderosa.
            </h2>

            <!-- Quick stats -->
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-6 mb-8 sm:mb-12 opacity-0 animate-[fade-in-up_0.8s_ease-out_1.4s_forwards]">
              <div class="text-center">
                <div class="text-xl sm:text-2xl font-bold text-primary mb-0.5 sm:mb-1">PIX</div>
                <p class="text-[10px] sm:text-xs text-muted-foreground">Instantâneo</p>
              </div>
              <div class="text-center">
                <div class="text-xl sm:text-2xl font-bold text-foreground mb-0.5 sm:mb-1">Cartão</div>
                <p class="text-[10px] sm:text-xs text-muted-foreground">Débito/Crédito</p>
              </div>
              <div class="text-center">
                <div class="text-xl sm:text-2xl font-bold text-foreground mb-0.5 sm:mb-1">Boleto</div>
                <p class="text-[10px] sm:text-xs text-muted-foreground">Personalizado</p>
              </div>
              <div class="text-center">
                <div class="text-xl sm:text-2xl font-bold text-foreground mb-0.5 sm:mb-1">TED</div>
                <p class="text-[10px] sm:text-xs text-muted-foreground">Seguro</p>
              </div>
            </div>

            <!-- CTA buttons -->
            <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 justify-center items-center mb-8 sm:mb-12 opacity-0 animate-[fade-in-up_0.8s_ease-out_1.6s_forwards] px-4">
              <button type="button" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 rounded-xl px-6 sm:px-8 py-2.5 sm:py-3 text-sm font-medium text-primary-foreground bg-primary hover:bg-primary/90 transition-all duration-200 hover:scale-105">
                <span>Criar conta grátis</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="arrow-right" class="lucide lucide-arrow-right w-4 h-4"><path d="M5 12h14"></path><path d="m12 5 7 7-7 7"></path></svg>
              </button>
              <button type="button" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 rounded-xl px-6 sm:px-8 py-2.5 sm:py-3 text-sm font-medium text-foreground bg-accent/20 border border-border hover:bg-accent/30 transition-all duration-200 hover:scale-105">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="play" class="lucide lucide-play w-4 h-4"><path d="M5 5a2 2 0 0 1 3.008-1.728l11.997 6.998a2 2 0 0 1 .003 3.458l-12 7A2 2 0 0 1 5 19z"></path></svg>
                <span>Ver demonstração</span>
              </button>
            </div>

            <!-- Demo area -->
            <div class="relative rounded-xl sm:rounded-2xl overflow-hidden border border-border bg-secondary/20 p-4 sm:p-6 md:p-8 min-h-[300px] sm:min-h-[400px] flex items-center justify-center opacity-0 animate-[fade-in-up_0.8s_ease-out_1.8s_forwards]">
              <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 sm:gap-8 w-full max-w-4xl">
                <div class="text-center opacity-0 animate-[fade-in-up_0.6s_ease-out_2.2s_forwards]">
                  <div class="w-12 h-12 sm:w-16 sm:h-16 bg-accent rounded-xl sm:rounded-2xl flex items-center justify-center mb-3 sm:mb-4 mx-auto">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="trending-up" class="lucide lucide-trending-up w-6 h-6 sm:w-8 sm:h-8 text-accent-foreground"><path d="M16 7h6v6"></path><path d="m22 7-8.5 8.5-5-5L2 17"></path></svg>
                  </div>
                  <h3 class="text-base sm:text-lg font-semibold text-foreground mb-1.5 sm:mb-2">Crescimento</h3>
                  <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Aumente sua receita com ferramentas inteligentes</p>
                </div>
                <div class="text-center opacity-0 animate-[fade-in-up_0.6s_ease-out_2.4s_forwards]">
                  <div class="w-12 h-12 sm:w-16 sm:h-16 bg-accent rounded-xl sm:rounded-2xl flex items-center justify-center mb-3 sm:mb-4 mx-auto">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="shield" class="lucide lucide-shield w-6 h-6 sm:w-8 sm:h-8 text-accent-foreground"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z"></path></svg>
                  </div>
                  <h3 class="text-base sm:text-lg font-semibold text-foreground mb-1.5 sm:mb-2">Segurança</h3>
                  <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Proteção máxima para seus dados e transações</p>
                </div>
                <div class="text-center opacity-0 animate-[fade-in-up_0.6s_ease-out_2.6s_forwards] sm:col-span-2 lg:col-span-1">
                  <div class="w-12 h-12 sm:w-16 sm:h-16 bg-accent rounded-xl sm:rounded-2xl flex items-center justify-center mb-3 sm:mb-4 mx-auto">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="zap" class="lucide lucide-zap w-6 h-6 sm:w-8 sm:h-8 text-primary"><path d="M4 14a1 1 0 0 1-.78-1.63l9.9-10.2a.5.5 0 0 1 .86.46l-1.92 6.02A1 1 0 0 0 13 10h7a1 1 0 0 1 .78 1.63l-9.9 10.2a.5.5 0 0 1-.86-.46l1.92-6.02A1 1 0 0 0 11 14z"></path></svg>
                  </div>
                  <h3 class="text-base sm:text-lg font-semibold text-foreground mb-1.5 sm:mb-2">Rapidez</h3>
                  <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Processamento instantâneo de pagamentos</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section -->
  <section class="w-full px-3 sm:px-4 md:px-6 mt-8 sm:mt-10 mb-6 sm:mb-8">
    <div class="max-w-7xl mx-auto">
      <div class="relative overflow-hidden bg-card border border-border rounded-3xl sm:rounded-[40px] backdrop-blur opacity-0 translate-y-8 animate-[fade-in-up_0.8s_ease-out_0.6s_forwards]">
        
        <div class="relative p-4 sm:p-6 md:p-8">
          <div class="text-center mb-8 sm:mb-12">
            <h2 class="text-2xl sm:text-3xl lg:text-4xl text-foreground tracking-tight font-semibold mb-3 sm:mb-4 opacity-0 animate-[fade-in-up_0.6s_ease-out_1s_forwards] px-2">Funcionalidades completas</h2>
            <p class="text-sm sm:text-base text-muted-foreground max-w-2xl mx-auto opacity-0 animate-[fade-in-up_0.6s_ease-out_1.2s_forwards] px-4">Tudo que você precisa para gerenciar seus pagamentos de forma profissional</p>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-6">
            <!-- Boleto -->
            <div class="bg-accent/10 border border-border rounded-xl sm:rounded-2xl p-4 sm:p-6 hover:bg-accent/20 transition-all duration-300 opacity-0 animate-[fade-in-up_0.6s_ease-out_1.4s_forwards] hover:scale-105">
              <div class="inline-flex items-center text-[10px] sm:text-xs font-medium text-primary bg-primary/10 border border-primary/20 rounded-full px-2 sm:px-3 py-0.5 sm:py-1 mb-3 sm:mb-4">
                PERSONALIZAÇÃO
              </div>
              <div class="w-10 h-10 sm:w-12 sm:h-12 bg-accent rounded-lg sm:rounded-xl flex items-center justify-center mb-3 sm:mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="file-text" class="lucide lucide-file-text w-5 h-5 sm:w-6 sm:h-6 text-accent-foreground"><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7Z"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M10 9H8"></path><path d="M16 13H8"></path><path d="M16 17H8"></path></svg>
              </div>
              <h3 class="text-base sm:text-lg font-semibold text-foreground mb-2 sm:mb-3 tracking-tight">Boleto</h3>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Personalize seus boletos com a identidade do seu negócio e cobre seus clientes de forma profissional e confiável.</p>
            </div>

            <!-- Link de Pagamento -->
            <div class="bg-accent/10 border border-border rounded-xl sm:rounded-2xl p-4 sm:p-6 hover:bg-accent/20 transition-all duration-300 opacity-0 animate-[fade-in-up_0.6s_ease-out_1.6s_forwards] hover:scale-105">
              <div class="inline-flex items-center text-[10px] sm:text-xs font-medium text-primary bg-primary/10 border border-primary/20 rounded-full px-2 sm:px-3 py-0.5 sm:py-1 mb-3 sm:mb-4">
                AGILIDADE PARA RECEBER
              </div>
              <div class="w-10 h-10 sm:w-12 sm:h-12 bg-primary/20 rounded-lg sm:rounded-xl flex items-center justify-center mb-3 sm:mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="link" class="lucide lucide-link w-5 h-5 sm:w-6 sm:h-6 text-primary"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg>
              </div>
              <h3 class="text-base sm:text-lg font-semibold text-foreground mb-2 sm:mb-3 tracking-tight">Link de pagamento</h3>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Envie pagamentos para seus clientes em segundos. Sem máquina de cartão, sem complicação. Receba de forma simples e rápida.</p>
            </div>

            <!-- Antecipação -->
            <div class="bg-accent/10 border border-border rounded-xl sm:rounded-2xl p-4 sm:p-6 hover:bg-accent/20 transition-all duration-300 opacity-0 animate-[fade-in-up_0.6s_ease-out_1.8s_forwards] hover:scale-105">
              <div class="inline-flex items-center text-[10px] sm:text-xs font-medium text-foreground bg-accent/20 border border-border rounded-full px-2 sm:px-3 py-0.5 sm:py-1 mb-3 sm:mb-4">
                CONTROLE DE FLUXO DE CAIXA
              </div>
              <div class="w-10 h-10 sm:w-12 sm:h-12 bg-accent rounded-lg sm:rounded-xl flex items-center justify-center mb-3 sm:mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="trending-up" class="lucide lucide-trending-up w-5 h-5 sm:w-6 sm:h-6 text-accent-foreground"><path d="M16 7h6v6"></path><path d="m22 7-8.5 8.5-5-5L2 17"></path></svg>
              </div>
              <h3 class="text-base sm:text-lg font-semibold text-foreground mb-2 sm:mb-3 tracking-tight">Antecipação de recebíveis</h3>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Não espere o cliente pagar para ter seu dinheiro em mãos. Antecipe suas vendas e mantenha o fluxo de caixa sempre em dia.</p>
            </div>

            <!-- Cobrança Recorrente -->
            <div class="bg-accent/10 border border-border rounded-xl sm:rounded-2xl p-4 sm:p-6 hover:bg-accent/20 transition-all duration-300 opacity-0 animate-[fade-in-up_0.6s_ease-out_2s_forwards] hover:scale-105">
              <div class="inline-flex items-center text-[10px] sm:text-xs font-medium text-foreground bg-accent/20 border border-border rounded-full px-2 sm:px-3 py-0.5 sm:py-1 mb-3 sm:mb-4">
                PLANOS DE ASSINATURA
              </div>
              <div class="w-10 h-10 sm:w-12 sm:h-12 bg-accent rounded-lg sm:rounded-xl flex items-center justify-center mb-3 sm:mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="repeat" class="lucide lucide-repeat w-5 h-5 sm:w-6 sm:h-6 text-accent-foreground"><path d="m17 2 4 4-4 4"></path><path d="M3 11v-1a4 4 0 0 1 4-4h14"></path><path d="m7 22-4-4 4-4"></path><path d="M21 13v1a4 4 0 0 1-4 4H3"></path></svg>
              </div>
              <h3 class="text-base sm:text-lg font-semibold text-foreground mb-2 sm:mb-3 tracking-tight">Cobrança recorrente</h3>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Automatize planos e assinaturas para receber de forma segura e programada todos os meses. Mais previsibilidade para o seu negócio.</p>
            </div>

            <!-- Dashboard -->
            <div class="bg-accent/10 border border-border rounded-xl sm:rounded-2xl p-4 sm:p-6 hover:bg-accent/20 transition-all duração-300 opacity-0 animate-[fade-in-up_0.6s_ease-out_2.2s_forwards] hover:scale-105">
              <div class="inline-flex items-center text-[10px] sm:text-xs font-medium text-foreground bg-accent/20 border border-border rounded-full px-2 sm:px-3 py-0.5 sm:py-1 mb-3 sm:mb-4">
                GESTÃO COMPLETA
              </div>
              <div class="w-10 h-10 sm:w-12 sm:h-12 bg-accent rounded-lg sm:rounded-xl flex items center justify-center mb-3 sm:mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="bar-chart-3" class="lucide lucide-bar-chart-3 w-5 h-5 sm:w-6 sm:h-6 text-accent-foreground"><path d="M3 3v16a2 2 0 0 0 2 2h16"></path><path d="M18 17V9"></path><path d="M13 17V5"></path><path d="M8 17v-3"></path></svg>
              </div>
              <h3 class="text-base sm:text-lg font-semibold text-foreground mb-2 sm:mb-3 tracking-tight">Dashboard</h3>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Um painel completo para gerenciar cada detalhe financeiro: recebíveis, relatórios, fluxo de caixa e pagamentos. Tudo em um só lugar.</p>
            </div>

            <!-- Split de Pagamento -->
            <div class="bg-accent/10 border border-border rounded-xl sm:rounded-2xl p-4 sm:p-6 hover:bg-accent/20 transition-all duration-300 opacity-0 animate-[fade-in-up_0.6s_ease-out_2.4s_forwards] hover:scale-105">
              <div class="inline-flex items-center text-[10px] sm:text-xs font-medium text-foreground bg-accent/20 border border-border rounded-full px-2 sm:px-3 py-0.5 sm:py-1 mb-3 sm:mb-4">
                CONTROLE DE REPASSES
              </div>
              <div class="w-10 h-10 sm:w-12 sm:h-12 bg-accent rounded-lg sm:rounded-xl flex items-center justify-center mb-3 sm:mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="git-branch" class="lucide lucide-git-branch w-5 h-5 sm:w-6 sm:h-6 text-accent-foreground"><line x1="6" x2="6" y1="3" y2="15"></line><circle cx="18" cy="6" r="3"></circle><circle cx="6" cy="18" r="3"></circle><path d="M18 9a9 9 0 0 1-9 9"></path></svg>
              </div>
              <h3 class="text-base sm:text-lg font-semibold text-foreground mb-2 sm:mb-3 tracking-tight">Split de pagamento</h3>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Automatize repasses e comissões para parceiros e colaboradores em uma única transação. Prático, transparente e sem dor de cabeça.</p>
            </div>

            <!-- E-commerce -->
            <div class="bg-accent/10 border border-border rounded-xl sm:rounded-2xl p-4 sm:p-6 hover:bg-accent/20 transition-all duration-300 opacity-0 animate-[fade-in-up_0.6s_ease-out_2.6s_forwards] hover:scale-105">
              <div class="inline-flex items-center text-[10px] sm:text-xs font-medium text-foreground bg-accent/20 border border-border rounded-full px-2 sm:px-3 py-0.5 sm:py-1 mb-3 sm:mb-4">
                VENDA ONLINE
              </div>
              <div class="w-10 h-10 sm:w-12 sm:h-12 bg-accent rounded-lg sm:rounded-xl flex items-center justify-center mb-3 sm:mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="shopping-cart" class="lucide lucide-shopping-cart w-5 h-5 sm:w-6 sm:h-6 text-accent-foreground"><circle cx="8" cy="21" r="1"></circle><circle cx="19" cy="21" r="1"></circle><path d="M2.05 2.05h2l2.66 12.42a2 2 0 0 0 2 1.58h9.78a2 2 0 0 0 1.95-1.57l1.65-7.43H5.12"></path></svg>
              </div>
              <h3 class="text-base sm:text-lg font-semibold text-foreground mb-2 sm:mb-3 tracking-tight">E-commerce</h3>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Conecte seu e-commerce facilmente às APIs da SimplisPay. Tenha suporte técnico especializado e realize vendas online com mais segurança.</p>
            </div>

            <!-- Transferências -->
            <div class="bg-accent/10 border border-border rounded-xl sm:rounded-2xl p-4 sm:p-6 hover:bg-accent/20 transition-all duration-300 opacity-0 animate-[fade-in-up_0.6s_ease-out_2.8s_forwards] hover:scale-105">
              <div class="inline-flex items-center text-[10px] sm:text-xs font-medium text-foreground bg-accent/20 border border-border rounded-full px-2 sm:px-3 py-0.5 sm:py-1 mb-3 sm:mb-4">
                SEGURANÇA NAS TRANSAÇÕES
              </div>
              <div class="w-10 h-10 sm:w-12 sm:h-12 bg-accent rounded-lg sm:rounded-xl flex items-center justify-center mb-3 sm:mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="send" class="lucide lucide-send w-5 h-5 sm:w-6 sm:h-6 text-accent-foreground"><path d="M14.536 21.686a.5.5 0 0 0 .937-.024l6.5-19a.496.496 0 0 0-.635-.635l-19 6.5a.5.5 0 0 0-.024.937l7.93 3.18a2 2 0 0 1 1.112 1.11z"></path><path d="m21.854 2.147-10.94 10.939"></path></svg>
              </div>
              <h3 class="text-base sm:text-lg font-semibold text-foreground mb-2 sm:mb-3 tracking-tight">Transferências rápidas</h3>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed">Agilidade nas transações digitais e bancárias, com total segurança para o seu dinheiro e de seus clientes.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Why SimplisPay Section -->
  <section class="w-full px-3 sm:px-4 md:px-6 mt-8 sm:mt-10 mb-6 sm:mb-8">
    <div class="max-w-7xl mx-auto">
      <div class="relative overflow-hidden bg-card border border-border rounded-3xl sm:rounded-[40px] backdrop-blur opacity-0 translate-y-8 animate-[fade-in-up_0.8s_ease-out_0.8s_forwards]">
        
        <div class="relative p-4 sm:p-6 md:p-8">
          <div class="text-center mb-8 sm:mb-12">
            <h2 class="text-2xl sm:text-3xl lg:text-4xl text-foreground tracking-tight font-semibold mb-4 sm:mb-6 opacity-0 animate-[fade-in-up_0.6s_ease-out_1.2s_forwards] px-2">Por que SimplisPay?</h2>
            
            <div class="max-w-4xl mx-auto space-y-4 sm:space-y-6">
              <div class="flex items-start gap-3 sm:gap-4 text-left opacity-0 animate-[fade-in-up_0.6s_ease-out_1.4s_forwards]">
                <div class="w-5 h-5 sm:w-6 sm:h-6 bg-primary/20 rounded-full flex items-center justify-center flex-shrink-0 mt-0.5 sm:mt-1">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="check" class="lucide lucide-check w-3 h-3 sm:w-4 sm:h-4 text-primary"><path d="M20 6 9 17l-5-5"></path></svg>
                </div>
                <p class="text-base sm:text-lg text-foreground leading-relaxed">Tecnologia simples que resolve a parte mais complexa do financeiro</p>
              </div>
              
              <div class="flex items-start gap-3 sm:gap-4 text-left opacity-0 animate-[fade-in-up_0.6s_ease-out_1.6s_forwards]">
                <div class="w-5 h-5 sm:w-6 sm:h-6 bg-primary/20 rounded-full flex items-center justify-center flex-shrink-0 mt-0.5 sm:mt-1">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="check" class="lucide lucide-check w-3 h-3 sm:w-4 sm:h-4 text-primary"><path d="M20 6 9 17l-5-5"></path></svg>
                </div>
                <p class="text-base sm:text-lg text-foreground leading-relaxed">Suporte humano, rápido e próximo do seu negócio</p>
              </div>
              
              <div class="flex items-start gap-3 sm:gap-4 text-left opacity-0 animate-[fade-in-up_0.6s_ease-out_1.8s_forwards]">
                <div class="w-5 h-5 sm:w-6 sm:h-6 bg-primary/20 rounded-full flex items-center justify-center flex-shrink-0 mt-0.5 sm:mt-1">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="check" class="lucide lucide-check w-3 h-3 sm:w-4 sm:h-4 text-primary"><path d="M20 6 9 17l-5-5"></path></svg>
                </div>
                <p class="text-base sm:text-lg text-foreground leading-relaxed">Experiência desenhada para economizar tempo e aumentar sua confiança</p>
              </div>
            </div>
          </div>

          <!-- Final CTA -->
          <div class="text-center bg-primary/5 border border-primary/10 rounded-2xl sm:rounded-3xl p-6 sm:p-8 opacity-0 animate-[fade-in-up_0.6s_ease-out_2s_forwards]">
            <h3 class="text-xl sm:text-2xl md:text-3xl font-semibold text-foreground tracking-tight mb-3 sm:mb-4 px-2">Simplifique sua gestão financeira.</h3>
            <p class="text-sm sm:text-base text-muted-foreground mb-5 sm:mb-6 max-w-2xl mx-auto px-2">Cresça com a SimplisPay.</p>
            <button type="button" onclick="window.location.href='https://portal.simplispay.com.br/app/cadastrar/estabelecimento'" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 rounded-xl px-6 sm:px-8 py-2.5 sm:py-3 text-sm font-medium text-primary-foreground bg-primary hover:bg-primary/90 transition-all duration-200 hover:scale-105">
              <span>Começar gratuitamente</span>
              <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="arrow-right" class="lucide lucide-arrow-right w-4 h-4"><path d="M5 12h14"></path><path d="m12 5 7 7-7 7"></path></svg>
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="w-full px-3 sm:px-4 md:px-6 mt-12 sm:mt-16 mb-6 sm:mb-8">
    <div class="max-w-7xl mx-auto">
      <div class="relative overflow-hidden bg-card border border-border rounded-3xl sm:rounded-[40px] backdrop-blur opacity-0 translate-y-8 animate-[fade-in-up_0.8s_ease-out_1s_forwards]">
        
        <div class="relative p-4 sm:p-6 md:p-8">
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 sm:gap-8">
            <div class="lg:col-span-2">
              <div class="flex items-center gap-2 mb-3 sm:mb-4">
                <img src="./simplispay2.png" alt="SimplisPay" class="h-6 sm:h-8 w-auto">
              </div>
              <p class="text-xs sm:text-sm text-muted-foreground leading-relaxed max-w-md mb-4 sm:mb-6">
                Simplificamos a gestão financeira para que você possa focar no que realmente importa: fazer seu negócio crescer.
              </p>
              <div class="flex items-center gap-3 sm:gap-4">
                <a href="#" class="text-muted-foreground hover:text-primary transition-colors">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="twitter" class="lucide lucide-twitter w-4 h-4 sm:w-5 sm:h-5"><path d="M22 4 s-.7 2.1-2 3.4c1.6 10-9.4 17.3-18 11.6 2.2.1 4.4-.6 6-2C3 15.5.5 9.6 3 5c2.2 2.6 5.6 4.1 9 4-.9-4.2 4-6.6 7-3.8 1.1 0 3-1.2 3-1.2z"></path></svg>
                </a>
                <a href="#" class="text-muted-foreground hover:text-primary transition-colors">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="linkedin" class="lucide lucide-linkedin w-4 h-4 sm:w-5 sm:h-5"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect width="4" height="12" x="2" y="9"></rect><circle cx="4" cy="4" r="2"></circle></svg>
                </a>
                <a href="#" class="text-muted-foreground hover:text-primary transition-colors">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" data-lucide="instagram" class="lucide lucide-instagram w-4 h-4 sm:w-5 sm:h-5"><rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" x2="17.51" y1="6.5" y2="6.5"></line></svg>
                </a>
              </div>
            </div>

            <div>
              <h3 class="text-xs sm:text-sm font-semibold text-foreground mb-3 sm:mb-4">Produtos</h3>
              <ul class="space-y-2 sm:space-y-3">
                <li><a href="#" class="text-xs sm:text-sm text-muted-foreground hover:text-primary transition-colors">Pagamentos</a></li>
                <li><a href="#" class="text-xs sm:text-sm text-muted-foreground hover:text-primary transition-colors">Cobrança</a></li>
                <li><a href="#" class="text-xs sm:text-sm text-muted-foreground hover:text-primary transition-colors">Antecipação</a></li>
                <li><a href="#" class="text-xs sm:text-sm text-muted-foreground hover:text-primary transition-colors">API</a></li>
              </ul>
            </div>

            <div>
              <h3 class="text-xs sm:text-sm font-semibold text-foreground mb-3 sm:mb-4">Suporte</h3>
              <ul class="space-y-2 sm:space-y-3">
                <li><a href="#" class="text-xs sm:text-sm text-muted-foreground hover:text-primary transition-colors">Central de Ajuda</a></li>
                <li><a href="#" class="text-xs sm:text-sm text-muted-foreground hover:text-primary transition-colors">Documentação</a></li>
                <li><a href="#" class="text-xs sm:text-sm text-muted-foreground hover:text-primary transition-colors">Status</a></li>
                <li><a href="#" class="text-xs sm:text-sm text-muted-foreground hover:text-primary transition-colors">Contato</a></li>
              </ul>
            </div>
          </div>

          <div class="border-t border-border mt-6 sm:mt-8 pt-4 sm:pt-6 flex flex-col sm:flex-row justify-between items-center gap-3 sm:gap-4">
            <p class="text-[10px] sm:text-xs text-muted-foreground text-center sm:text-left">© 2024 SimplisPay. Todos os direitos reservados.</p>
            <div class="flex items-center gap-4 sm:gap-6">
              <a href="#" class="text-[10px] sm:text-xs text-muted-foreground hover:text-primary transition-colors">Privacidade</a>
              <a href="#" class="text-[10px] sm:text-xs text-muted-foreground hover:text-primary transition-colors">Termos</a>
              <a href="#" class="text-[10px] sm:text-xs text-muted-foreground hover:text-primary transition-colors">Cookies</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>

  <style>
    @keyframes fade-in-down {
      0% {
        opacity: 0;
        transform: translateY(-16px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fade-in-up {
      0% {
        opacity: 0;
        transform: translateY(32px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fade-in {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }
  </style>

  <script>
    lucide.createIcons();
  </script>


</body></html>
```
