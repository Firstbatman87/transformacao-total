<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transformação Total - eBook de Emagrecimento Saudável</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, #3b82f6 0%, #10b981 100%);
        }
        .pulse-animation {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .ebook-mockup {
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
            transform: perspective(1000px) rotateY(-15deg);
        }
        .testimonial-card {
            transition: all 0.3s ease;
        }
        .testimonial-card:hover {
            transform: translateY(-5px);
        }
        .guarantee-badge {
            animation: float 3s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="font-sans bg-gray-50">
    <!-- Header/Navbar -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center">
                <i class="fas fa-fire text-blue-500 text-2xl mr-2"></i>
                <span class="text-xl font-bold text-gray-800">Transformação Total</span>
            </div>
            <div class="hidden md:flex space-x-6">
                <a href="#beneficios" class="text-gray-600 hover:text-blue-500 font-medium">Benefícios</a>
                <a href="#conteudo" class="text-gray-600 hover:text-blue-500 font-medium">Conteúdo</a>
                <a href="#autor" class="text-gray-600 hover:text-blue-500 font-medium">Autor</a>
                <a href="#depoimentos" class="text-gray-600 hover:text-blue-500 font-medium">Depoimentos</a>
            </div>
            <button class="md:hidden text-gray-600">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-gradient text-white py-16 md:py-24">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <span class="bg-white text-blue-600 px-3 py-1 rounded-full text-sm font-semibold inline-block mb-4">LANÇAMENTO!</span>
                <h1 class="text-4xl md:text-5xl font-bold leading-tight mb-4">Descubra o Segredo Para <span class="underline decoration-yellow-300">Emagrecer de Forma Saudável</span> e Definitiva</h1>
                <p class="text-xl mb-8">O método comprovado que já ajudou mais de 5.000 pessoas a conquistarem o corpo dos sonhos sem dietas malucas ou exercícios exaustivos.</p>
                                
                <div class="flex flex-col sm:flex-row gap-4 mb-8">
                    <a href="#oferta" class="bg-yellow-400 hover:bg-yellow-300 text-gray-900 font-bold py-4 px-8 rounded-lg text-center pulse-animation">
                        <span class="block text-sm">QUERO ME TRANSFORMAR AGORA</span>
                        <span class="block text-xs">Garanta seu acesso imediato</span>
                    </a>
                    <a href="#depoimentos" class="bg-white hover:bg-gray-100 text-blue-600 font-bold py-4 px-8 rounded-lg text-center">
                        <span class="block text-sm">VER DEPOIMENTOS</span>
                        <span class="block text-xs">Veja quem já emagreceu</span>
                    </a>
                </div>
                                
                <div class="flex items-center">
                    <div class="flex -space-x-2">
                        <img src="https://randomuser.me/api/portraits/women/44.jpg" class="w-10 h-10 rounded-full border-2 border-white" alt="Cliente satisfeita">
                        <img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-10 h-10 rounded-full border-2 border-white" alt="Cliente satisfeito">
                        <img src="https://randomuser.me/api/portraits/women/68.jpg" class="w-10 h-10 rounded-full border-2 border-white" alt="Cliente satisfeita">
                    </div>
                    <div class="ml-4">
                        <p class="text-sm font-medium">+5.000 pessoas transformadas</p>
                        <div class="flex text-yellow-300">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <span class="text-white ml-1">4.9/5</span>
                        </div>
                    </div>
                </div>
            </div>
                        
            <div class="md:w-1/2 flex justify-center">
                <div class="relative">
                    <img src="https://via.placeholder.com/400x550/3b82f6/ffffff?text=TRANSFORMAÇÃO+TOTAL" alt="Mockup do eBook Transformação Total" class="ebook-mockup rounded-lg w-full max-w-xs md:max-w-md">
                    <div class="absolute -bottom-5 -right-5 bg-yellow-400 text-gray-900 font-bold py-2 px-4 rounded-lg shadow-lg">
                        <span class="block text-sm">VERSÃO DIGITAL</span>
                        <span class="block text-xs">Disponível agora</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Logos Section -->
    <section class="bg-gray-100 py-8">
        <div class="container mx-auto px-4">
            <p class="text-center text-gray-500 mb-6">Recomendado por especialistas em:</p>
            <div class="flex flex-wrap justify-center items-center gap-8 md:gap-16">
                <i class="fas fa-heartbeat text-4xl text-red-500"></i>
                <i class="fas fa-apple-alt text-4xl text-green-500"></i>
                <i class="fas fa-dumbbell text-4xl text-blue-500"></i>
                <i class="fas fa-brain text-4xl text-purple-500"></i>
                <i class="fas fa-utensils text-4xl text-yellow-500"></i>
            </div>
        </div>
    </section>

    <!-- Benefits Section -->
    <section id="beneficios" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">O Que Você Vai Alcançar Com o <span class="text-blue-600">Transformação Total</span></h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Um método passo a passo para emagrecer com saúde e manter os resultados para sempre</p>
            </div>
                        
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 hover:border-blue-300 transition-all">
                    <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-weight text-blue-600 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Perda de Peso Efetiva</h3>
                    <p class="text-gray-600">Aprenda a eliminar gordura corporal de forma saudável e sustentável, sem o temido efeito sanfona.</p>
                </div>
                                
                <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 hover:border-blue-300 transition-all">
                    <div class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-heart text-green-600 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Mais Saúde e Energia</h3>
                    <p class="text-gray-600">Descubra como melhorar sua saúde, disposição e qualidade de vida através da alimentação correta.</p>
                </div>
                                
                <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 hover:border-blue-300 transition-all">
                    <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-clock text-purple-600 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Economia de Tempo</h3>
                    <p class="text-gray-600">Pare de perder tempo com dietas que não funcionam. Nosso método é prático e se adapta à sua rotina.</p>
                </div>
                                
                <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 hover:border-blue-300 transition-all">
                    <div class="w-12 h-12 bg-yellow-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-utensils text-yellow-600 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Alimentação Sem Restrições</h3>
                    <p class="text-gray-600">Aprenda a comer de tudo, sem passar fome ou cortar seus alimentos preferidos.</p>
                </div>
                                
                <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 hover:border-blue-300 transition-all">
                    <div class="w-12 h-12 bg-red-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-brain text-red-600 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Mindset Vencedor</h3>
                    <p class="text-gray-600">Desenvolva a mentalidade certa para manter a motivação e alcançar seus objetivos de forma permanente.</p>
                </div>
                                
                <div class="bg-gray-50 p-6 rounded-xl border border-gray-200 hover:border-blue-300 transition-all">
                    <div class="w-12 h-12 bg-indigo-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="fas fa-money-bill-wave text-indigo-600 text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Economia Financeira</h3>
                    <p class="text-gray-600">Pare de gastar fortunas com produtos milagrosos que não funcionam. Nosso método é acessível e eficaz.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Content Section -->
    <section id="conteudo" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">O Que Você Vai Encontrar No <span class="text-blue-600">eBook</span></h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Um conteúdo rico e prático para transformar seu corpo e sua saúde</p>
            </div>
                        
            <div class="flex flex-col md:flex-row gap-8 items-center">
                <div class="md:w-1/2">
                    <img src="https://via.placeholder.com/500x350/e5e7eb/3b82f6?text=CONTEÚDO+EXCLUSIVO" alt="Conteúdo do eBook" class="rounded-lg shadow-lg w-full">
                </div>
                                
                <div class="md:w-1/2">
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-blue-100 rounded-full p-2 mr-4">
                                <i class="fas fa-check text-blue-600"></i>
                            </div>
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Os 5 Pilares do Emagrecimento Saudável</h3>
                                <p class="text-gray-600">Descubra os fundamentos científicos para perder peso de forma definitiva.</p>
                            </div>
                        </div>
                                                
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-blue-100 rounded-full p-2 mr-4">
                                <i class="fas fa-check text-blue-600"></i>
                            </div>
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Plano Alimentar Personalizável</h3>
                                <p class="text-gray-600">Receitas e cardápios flexíveis que se adaptam ao seu estilo de vida.</p>
                            </div>
                        </div>
                                                
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-blue-100 rounded-full p-2 mr-4">
                                <i class="fas fa-check text-blue-600"></i>
                            </div>
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Exercícios Eficientes</h3>
                                <p class="text-gray-600">Treinos curtos e eficazes que você pode fazer em casa sem equipamentos.</p>
                            </div>
                        </div>
                                                
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-blue-100 rounded-full p-2 mr-4">
                                <i class="fas fa-check text-blue-600"></i>
                            </div>
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Guia de Superação de Obstáculos</h3>
                                <p class="text-gray-600">Como vencer os desafios mais comuns no processo de emagrecimento.</p>
                            </div>
                        </div>
                                                
                        <div class="flex items-start">
                            <div class="flex-shrink-0 bg-blue-100 rounded-full p-2 mr-4">
                                <i class="fas fa-check text-blue-600"></i>
                            </div>
                            <div>
                                <h3 class="text-lg font-bold text-gray-800">Bônus Exclusivos</h3>
                                <p class="text-gray-600">Lista de compras saudáveis, diário alimentar e muito mais!</p>
                            </div>
                        </div>
                    </div>
                                        
                    <div class="mt-8">
                        <a href="#oferta" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg inline-flex items-center">
                            <span>QUERO MEU EBOOK AGORA</span>
                            <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Author Section -->
    <section id="autor" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/3 flex justify-center">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300x300/3b82f6/ffffff?text=AUTOR" alt="Autor do eBook" class="rounded-full w-48 h-48 md:w-64 md:h-64 object-cover border-4 border-blue-100 shadow-lg">
                        <div class="absolute -bottom-4 -right-4 bg-blue-600 text-white py-2 px-4 rounded-lg shadow-lg">
                            <span class="block font-bold">ESPECIALISTA</span>
                            <span class="block text-xs">em Nutrição</span>
                        </div>
                    </div>
                </div>
                                
                <div class="md:w-2/3">
                    <h2 class="text-3xl font-bold text-gray-800 mb-4">Conheça o Autor: <span class="text-blue-600">[Seu Nome]</span></h2>
                    <p class="text-lg text-gray-600 mb-6">Nutricionista com mais de 15 anos de experiência, especializado em emagrecimento saudável e mudança de hábitos.</p>
                                        
                    <div class="space-y-4 mb-6">
                        <div class="flex items-start">
                            <div class="flex-shrink-0 text-blue-600 mt-1 mr-3">
                                <i class="fas fa-graduation-cap"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-gray-800">Formação Acadêmica</h3>
                                <p class="text-gray-600">Graduado em Nutrição pela Universidade XYZ, com pós-graduação em Obesidade e Emagrecimento.</p>
                            </div>
                        </div>
                                                
                        <div class="flex items-start">
                            <div class="flex-shrink-0 text-blue-600 mt-1 mr-3">
                                <i class="fas fa-briefcase"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-gray-800">Experiência Profissional</h3>
                                <p class="text-gray-600">Já atendeu mais de 3.000 pacientes em consultório e ajudou milhares online a transformarem seus corpos e vidas.</p>
                            </div>
                        </div>
                                                
                        <div class="flex items-start">
                            <div class="flex-shrink-0 text-blue-600 mt-1 mr-3">
                                <i class="fas fa-trophy"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-gray-800">Reconhecimento</h3>
                                <p class="text-gray-600">Palestrante em congressos de nutrição e colunista em revistas de saúde e bem-estar.</p>
                            </div>
                        </div>
                    </div>
                                        
                    <p class="text-gray-800 font-medium italic">"Meu propósito é ajudar pessoas comuns a alcançarem resultados extraordinários através de métodos simples e cientificamente comprovados."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="depoimentos" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">Históricos de <span class="text-blue-600">Sucesso</span></h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Veja o que estão falando sobre o método Transformação Total</p>
            </div>
                        
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-xl shadow-md testimonial-card">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="Depoimento" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold text-gray-800">Ana Claudia</h4>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4">"Perdi 18kg em 4 meses seguindo o método. Pela primeira vez na vida consegui manter o peso depois de emagrecer. Recomendo demais!"</p>
                    <div class="flex items-center text-sm text-gray-500">
                        <i class="fas fa-check-circle text-green-500 mr-2"></i>
                        <span>Verificado</span>
                    </div>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-md testimonial-card">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="Depoimento" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold text-gray-800">Carlos Eduardo</h4>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4">"Depois de tentar várias dietas sem sucesso, finalmente encontrei um método que se adapta à minha rotina. Já eliminei 12kg e me sinto muito melhor!"</p>
                    <div class="flex items-center text-sm text-gray-500">
                        <i class="fas fa-check-circle text-green-500 mr-2"></i>
                        <span>Verificado</span>
                    </div>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-md testimonial-card">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Depoimento" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold text-gray-800">Fernanda Silva</h4>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4">"O que mais gostei foi poder comer de tudo, sem restrições absurdas. Em 3 meses perdi 8kg e minha relação com a comida mudou completamente."</p>
                    <div class="flex items-center text-sm text-gray-500">
                        <i class="fas fa-check-circle text-green-500 mr-2"></i>
                        <span>Verificado</span>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 text-center">
                <a href="#oferta" class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-lg">
                    QUERO TER RESULTADOS COMO ESSES
                </a>
            </div>
        </div>
    </section>

    <!-- Offer Section -->
    <section id="oferta" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">Sua <span class="text-blue-600">Oferta Exclusiva</span></h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Adquira agora o eBook Transformação Total com condições especiais de lançamento</p>
            </div>
            
            <div class="flex flex-col lg:flex-row gap-12 items-center">
                <div class="lg:w-1/2">
                    <div class="bg-gray-50 border-2 border-blue-200 rounded-xl p-8 relative">
                        <div class="absolute -top-5 -right-5 bg-red-600 text-white font-bold py-2 px-4 rounded-lg rotate-6">
                            OFERTA POR TEMPO LIMITADO
                        </div>
                        
                        <div class="flex flex-col md:flex-row items-center mb-8 gap-6">
                            <div class="flex-shrink-0">
                                <img src="https://via.placeholder.com/150x200/3b82f6/ffffff?text=TRANSFORMAÇÃO+TOTAL" alt="eBook" class="rounded-lg shadow-md w-32">
                            </div>
                            <div>
                                <h3 class="text-2xl font-bold text-gray-800 mb-2">Transformação Total</h3>
                                <p class="text-gray-600 mb-4">O guia definitivo para emagrecer com saúde e mudar seu corpo para sempre</p>
                                <div class="flex items-center text-yellow-400">
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <i class="fas fa-star"></i>
                                    <span class="text-gray-600 ml-2">4.9/5 (1.237 avaliações)</span>
                                </div>
                            </div>
                        </div>
                        
                        <div class="space-y-4 mb-8">
                            <div class="flex items-start">
                                <div class="flex-shrink-0 text-green-500 mt-1 mr-3">
                                    <i class="fas fa-check-circle"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-800">Acesso Imediato</h4>
                                    <p class="text-gray-600">Baixe agora mesmo e comece hoje sua transformação</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="flex-shrink-0 text-green-500 mt-1 mr-3">
                                    <i class="fas fa-check-circle"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-800">Bônus Exclusivos</h4>
                                    <p class="text-gray-600">Lista de compras, diário alimentar e guia de exercícios</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="flex-shrink-0 text-green-500 mt-1 mr-3">
                                    <i class="fas fa-check-circle"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-gray-800">Suporte Prioritário</h4>
                                    <p class="text-gray-600">Tire suas dúvidas diretamente com nossa equipe</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="bg-blue-50 rounded-lg p-4 mb-6">
                            <div class="flex justify-between items-center mb-2">
                                <span class="text-gray-600">Preço original:</span>
                                <span class="text-gray-600 line-through">R$ 97,00</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="font-bold text-gray-800">Preço com desconto:</span>
                                <span class="text-2xl font-bold text-blue-600">R$ 47,00</span>
                            </div>
                        </div>
                        
                        <div class="text-center">
                            <a href="#" class="inline-block bg-green-500 hover:bg-green-600 text-white font-bold py-4 px-8 rounded-lg w-full mb-4">
                                SIM, QUERO ME TRANSFORMAR AGORA
                            </a>
                            <p class="text-sm text-gray-500">Pagamento seguro via cartão, boleto ou PIX</p>
                        </div>
                    </div>
                </div>
                
                <div class="lg:w-1/2">
                    <div class="bg-blue-600 text-white rounded-xl p-8">
                        <h3 class="text-2xl font-bold mb-6">Garantia Incondicional de 7 Dias</h3>
                        
                        <div class="flex items-start mb-6">
                            <div class="flex-shrink-0 text-yellow-300 mt-1 mr-4">
                                <i class="fas fa-shield-alt text-3xl"></i>
                            </div>
                            <div>
                                <p class="mb-4">Se em até 7 dias você não estiver completamente satisfeito(a) com o eBook Transformação Total, devolvemos 100% do seu dinheiro, sem questionamentos.</p>
                                <p>É um risco ZERO para você e uma oportunidade de transformar sua saúde e seu corpo.</p>
                            </div>
                        </div>
                        
                        <div class="flex justify-center mt-8">
                            <div class="bg-white text-blue-600 rounded-full p-4 guarantee-badge">
                                <i class="fas fa-lock text-4xl"></i>
                            </div>
                        </div>
                        
                        <div class="mt-8 text-center">
                            <h4 class="font-bold text-xl mb-2">Perguntas Frequentes</h4>
                            
                            <div class="space-y-4 text-left">
                                <div class="border-b border-blue-500 pb-4">
                                    <h5 class="font-bold">Como recebo o eBook após a compra?</h5>
                                    <p class="text-blue-100 mt-1">Imediatamente após a confirmação do pagamento, você receberá um e-mail com o link para download do eBook em PDF.</p>
                                </div>
                                
                                <div class="border-b border-blue-500 pb-4">
                                    <h5 class="font-bold">Posso pagar com boleto ou PIX?</h5>
                                    <p class="text-blue-100 mt-1">Sim, além de cartão de crédito, aceitamos boleto bancário e PIX com 10% de desconto adicional.</p>
                                </div>
                                
                                <div>
                                    <h5 class="font-bold">Preciso imprimir o eBook?</h5>
                                    <p class="text-blue-100 mt-1">Não é necessário. Você pode acessar de qualquer dispositivo: celular, tablet ou computador.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-gradient-to-r from-blue-600 to-green-500 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Não Deixe Para Depois O Que Você Pode Começar <span class="underline decoration-yellow-300">Hoje Mesmo</span></h2>
            <p class="text-xl mb-8 max-w-3xl mx-auto">Sua jornada para um corpo mais saudável e uma vida melhor começa com um simples passo. Garanta seu eBook agora com condições exclusivas de lançamento.</p>
            
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#oferta" class="bg-yellow-400 hover:bg-yellow-300 text-gray-900 font-bold py-4 px-8 rounded-lg text-center">
                    <span class="block">QUERO ME TRANSFORMAR AGORA</span>
                    <span class="block text-sm">Acesso Imediato • Garantia de 7 Dias</span>
                </a>
                
                <a href="#depoimentos" class="bg-white hover:bg-gray-100 text-blue-600 font-bold py-4 px-8 rounded-lg text-center">
                    <span class="block">VER MAIS DEPOIMENTOS</span>
                    <span class="block text-sm">Veja resultados reais</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-12">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-4 gap-8 mb-8">
                <div>
                    <div class="flex items-center mb-4">
                        <i class="fas fa-fire text-blue-500 text-2xl mr-2"></i>
                        <span class="text-xl font-bold text-white">Transformação Total</span>
                    </div>
                    <p class="mb-4">O método definitivo para emagrecer com saúde e mudar seu corpo para sempre.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-white font-bold mb-4">Links Úteis</h4>
                    <ul class="space-y-2">
                        <li><a href="#beneficios" class="hover:text-white">Benefícios</a></li>
                        <li><a href="#conteudo" class="hover:text-white">Conteúdo</a></li>
                        <li><a href="#autor" class="hover:text-white">Autor</a></li>
                        <li><a href="#depoimentos" class="hover:text-white">Depoimentos</a></li>
                        <li><a href="#oferta" class="hover:text-white">Oferta</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-white font-bold mb-4">Suporte</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-white">Central de Ajuda</a></li>
                        <li><a href="#" class="hover:text-white">Política de Privacidade</a></li>
                        <li><a href="#" class="hover:text-white">Termos de Uso</a></li>
                        <li><a href="#" class="hover:text-white">Garantia</a></li>
                        <li><a href="#" class="hover:text-white">Contato</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-white font-bold mb-4">Newsletter</h4>
                    <p class="mb-4">Receba dicas exclusivas sobre saúde e emagrecimento diretamente no seu e-mail.</p>
                    <form class="flex">
                        <input type="email" placeholder="Seu e-mail" class="bg-gray-800 text-white px-4 py-2 rounded-l-lg focus:outline-none focus:ring-2 focus:ring-blue-500 w-full">
                        <button type="submit" class="bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-r-lg">
                            <i class="fas fa-paper-plane"></i>
                        </button>
                    </form>
                </div>
            </div>
            
            <div class="pt-8 border-t border-gray-800 text-center">
                <p>&copy; 2023 Transformação Total. Todos os direitos reservados.</p>
                <p class="text-xs mt-2">Este produto não substitui o acompanhamento profissional. Consulte sempre seu médico antes de iniciar qualquer programa de emagrecimento.</p>
            </div>
        </div>
    </footer>

    <!-- WhatsApp Button -->
    <div class="fixed bottom-6 right-6 z-50">
        <a href="https://wa.me/5511999999999" class="bg-green-500 hover:bg-green-600 text-white w-14 h-14 rounded-full flex items-center justify-center shadow-lg transition-all transform hover:scale-110">
            <i class="fab fa-whatsapp text-2xl"></i>
        </a>
    </div>

    <script>
        // Simple animation for scroll to sections
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Countdown timer for special offer
        function updateCountdown() {
            const now = new Date();
            const offerEnd = new Date();
            offerEnd.setHours(23, 59, 59, 0);
            
            const diff = offerEnd - now;
            
            const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((diff % (1000 * 60)) / 1000);
            
            document.getElementById('countdown-hours').textContent = hours.toString().padStart(2, '0');
            document.getElementById('countdown-minutes').textContent = minutes.toString().padStart(2, '0');
            document.getElementById('countdown-seconds').textContent = seconds.toString().padStart(2, '0');
        }
        
        setInterval(updateCountdown, 1000);
        updateCountdown();
    </script>
</body>
</html>
