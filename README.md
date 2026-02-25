<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VANTAGE AUTO | Export Afrique (Dubaï & Chine)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lucide/0.263.0/lucide.min.js" id="lucide-script"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&family=Outfit:wght@900&display=swap');
        
        body { 
            font-family: 'Plus Jakarta Sans', sans-serif; 
            scroll-behavior: smooth; 
        }

        h1, h2, h3, .brand-font { font-family: 'Outfit', sans-serif; }

        .glass-nav { 
            background: rgba(15, 23, 42, 0.9); 
            backdrop-filter: blur(12px); 
            border-bottom: 1px solid rgba(255, 255, 255, 0.05); 
        }

        .hero-bg {
            background: linear-gradient(to bottom, rgba(15, 23, 42, 0.8), rgba(15, 23, 42, 1)), url('https://images.unsplash.com/photo-1541899481282-d53bffe3c35d?auto=format&fit=crop&q=80&w=1920');
            background-size: cover;
            background-position: center;
        }

        .car-card { 
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1); 
        }

        .car-card:hover { 
            transform: translateY(-10px); 
            border-color: #3b82f6;
            background: rgba(255, 255, 255, 0.07);
        }

        .step-card {
            background: linear-gradient(135deg, rgba(59, 130, 246, 0.1) 0%, rgba(37, 99, 235, 0.05) 100%);
        }

        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background-color: #25d366;
            color: white;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 10px 25px rgba(37, 211, 102, 0.4);
            z-index: 1000;
            transition: transform 0.3s;
        }

        .whatsapp-float:hover { transform: scale(1.1); }
    </style>
</head>
<body class="bg-slate-950 text-white">

    <!-- BOUTON WHATSAPP FLOTTANT -->
    <a href="https://wa.me/33618667257" target="_blank" class="whatsapp-float">
        <i data-lucide="message-circle" style="width: 32px; height: 32px;"></i>
    </a>

    <!-- NAVIGATION -->
    <nav class="fixed w-full z-50 glass-nav py-4">
        <div class="max-w-7xl mx-auto px-6 flex items-center justify-between">
            <div class="flex items-center gap-2 brand-font">
                <div class="w-10 h-10 bg-blue-600 rounded-lg flex items-center justify-center text-white italic font-black text-xl">V</div>
                <div class="flex flex-col leading-none">
                    <span class="text-xl font-bold tracking-tighter uppercase">Vantage</span>
                    <span class="text-[10px] tracking-[0.3em] text-blue-400 font-bold uppercase">Auto Afrique</span>
                </div>
            </div>
            <div class="hidden md:flex items-center gap-8 text-[11px] font-bold uppercase tracking-widest text-slate-400">
                <a href="#how" class="hover:text-blue-500">Comment ça marche</a>
                <a href="#stock" class="hover:text-blue-500">Véhicules</a>
                <a href="https://wa.me/33618667257" class="px-5 py-2.5 bg-blue-600 text-white rounded-full hover:bg-blue-700">Contact WhatsApp</a>
            </div>
        </div>
    </nav>

    <!-- SECTION HERO -->
    <section class="relative h-screen flex items-center hero-bg px-6">
        <div class="max-w-7xl mx-auto w-full pt-20">
            <div class="max-w-3xl space-y-8">
                <div class="inline-flex items-center gap-3 px-4 py-2 bg-blue-500/10 border border-blue-500/20 rounded-full text-blue-400 text-[10px] font-black uppercase tracking-widest">
                    Spécialiste Export vers l'Afrique
                </div>
                <h1 class="text-6xl md:text-8xl font-black tracking-tighter leading-[0.9] uppercase italic">
                    Dubaï & Chine <br><span class="text-blue-600 text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-blue-700">Livrés au Port.</span>
                </h1>
                <p class="text-lg text-slate-400 max-w-xl leading-relaxed">
                    Achetez votre véhicule en toute sécurité. Nous gérons l'achat, l'inspection technique et le transit vers Dakar, Abidjan, Douala, Lomé ou Cotonou.
                </p>
                <div class="flex flex-wrap gap-4 pt-4">
                    <a href="#stock" class="px-8 py-4 bg-blue-600 text-white rounded-xl font-bold uppercase tracking-widest text-xs hover:bg-blue-700 transition">Voir le catalogue</a>
                    <a href="https://wa.me/33618667257" class="px-8 py-4 bg-white/5 border border-white/10 rounded-xl font-bold uppercase tracking-widest text-xs hover:bg-white/10 transition">Parler à un agent</a>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION COMMENT ÇA MARCHE -->
    <section id="how" class="py-32 px-6 bg-slate-900/50">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-20">
                <h2 class="text-4xl font-black uppercase italic tracking-tighter mb-4 text-white">Processus <span class="text-blue-600">Simplifié</span></h2>
                <p class="text-slate-400">Importer une voiture n'a jamais été aussi facile.</p>
            </div>
            <div class="grid md:grid-cols-4 gap-8">
                <div class="step-card p-8 rounded-[2rem] border border-white/5 text-center">
                    <div class="w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center font-bold text-xl mx-auto mb-6">1</div>
                    <h3 class="font-bold uppercase mb-2">Choix</h3>
                    <p class="text-sm text-slate-500">Vous choisissez le modèle sur les marchés de Dubaï ou Chine.</p>
                </div>
                <div class="step-card p-8 rounded-[2rem] border border-white/5 text-center">
                    <div class="w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center font-bold text-xl mx-auto mb-6">2</div>
                    <h3 class="font-bold uppercase mb-2">Inspection</h3>
                    <p class="text-sm text-slate-500">Nos experts inspectent le véhicule et vous envoient les photos/vidéos.</p>
                </div>
                <div class="step-card p-8 rounded-[2rem] border border-white/5 text-center">
                    <div class="w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center font-bold text-xl mx-auto mb-6">3</div>
                    <h3 class="font-bold uppercase mb-2">Transit</h3>
                    <p class="text-sm text-slate-500">Nous gérons la paperasse et l'expédition maritime vers votre port.</p>
                </div>
                <div class="step-card p-8 rounded-[2rem] border border-white/5 text-center">
                    <div class="w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center font-bold text-xl mx-auto mb-6">4</div>
                    <h3 class="font-bold uppercase mb-2">Livraison</h3>
                    <p class="text-sm text-slate-500">Vous récupérez votre véhicule prêt à rouler avec ses documents.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION CATALOGUE -->
    <section id="stock" class="py-32 px-6">
        <div class="max-w-7xl mx-auto">
            <div class="flex flex-col md:flex-row justify-between items-end mb-16 gap-4">
                <div>
                    <h2 class="text-4xl font-black uppercase italic tracking-tighter">Modèles <span class="text-blue-600">Recommandés</span></h2>
                    <p class="text-slate-500 uppercase text-[10px] font-bold tracking-widest mt-2">Adaptés aux routes africaines</p>
                </div>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- VÉHICULE 1 -->
                <div class="car-card rounded-[2.5rem] overflow-hidden group">
                    <div class="h-64 relative overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1594502184342-2e12f877aa73?auto=format&fit=crop&q=80&w=800" class="w-full h-full object-cover group-hover:scale-110 transition duration-700" alt="[Toyota Prado]">
                        <div class="absolute top-4 left-4 bg-yellow-600 text-[9px] px-2 py-1 rounded font-bold uppercase">Stock Dubaï</div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-black italic uppercase leading-none mb-2">Toyota Prado</h3>
                        <p class="text-slate-500 text-xs mb-6 italic">Moteur Diesel Tropicalisé - 4x4 Robuste</p>
                        <a href="https://wa.me/33618667257?text=Bonjour, je souhaite un devis pour une Toyota Prado" class="flex items-center justify-center gap-2 w-full bg-blue-600 py-4 rounded-2xl font-bold uppercase text-[10px] hover:bg-blue-700 transition">
                            <i data-lucide="send" class="w-3 h-3"></i> Demander Devis Port
                        </a>
                    </div>
                </div>

                <!-- VÉHICULE 2 -->
                <div class="car-card rounded-[2.5rem] overflow-hidden group">
                    <div class="h-64 relative overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1621245789643-4e672778736d?auto=format&fit=crop&q=80&w=800" class="w-full h-full object-cover group-hover:scale-110 transition duration-700" alt="[Toyota Hiace]">
                        <div class="absolute top-4 left-4 bg-yellow-600 text-[9px] px-2 py-1 rounded font-bold uppercase">Stock Dubaï</div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-black italic uppercase leading-none mb-2">Toyota Hiace</h3>
                        <p class="text-slate-500 text-xs mb-6 italic">15 Places - Idéal Transport Commun</p>
                        <a href="https://wa.me/33618667257?text=Bonjour, je souhaite un devis pour un Toyota Hiace" class="flex items-center justify-center gap-2 w-full bg-blue-600 py-4 rounded-2xl font-bold uppercase text-[10px] hover:bg-blue-700 transition">
                            <i data-lucide="send" class="w-3 h-3"></i> Infos & Prix
                        </a>
                    </div>
                </div>

                <!-- VÉHICULE 3 -->
                <div class="car-card rounded-[2.5rem] overflow-hidden group">
                    <div class="h-64 relative overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1695029315516-43f114620023?auto=format&fit=crop&q=80&w=800" class="w-full h-full object-cover group-hover:scale-110 transition duration-700" alt="[BYD ATTO 3]">
                        <div class="absolute top-4 left-4 bg-blue-600 text-[9px] px-2 py-1 rounded font-bold uppercase">Stock Chine</div>
                    </div>
                    <div class="p-8">
                        <h3 class="text-2xl font-black italic uppercase leading-none mb-2">BYD ATTO 3</h3>
                        <p class="text-slate-500 text-xs mb-6 italic">E-SUV Électrique - 420km Autonomie</p>
                        <a href="https://wa.me/33618667257?text=Bonjour, je souhaite un devis pour une BYD" class="flex items-center justify-center gap-2 w-full bg-blue-600 py-4 rounded-2xl font-bold uppercase text-[10px] hover:bg-blue-700 transition">
                            <i data-lucide="send" class="w-3 h-3"></i> Devis Import Chine
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- TÉMOIGNAGES -->
    <section class="py-24 px-6 bg-blue-600">
        <div class="max-w-7xl mx-auto text-center">
            <h2 class="text-3xl font-black uppercase italic mb-12">Ils nous ont fait <span class="text-slate-900">Confiance</span></h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-white/10 p-8 rounded-[2rem] text-left">
                    <p class="italic mb-6">"J'ai commandé ma Toyota Hilux depuis Abidjan. Vantage Auto a tout géré, de Dubaï jusqu'au port. Véhicule impeccable."</p>
                    <p class="font-bold uppercase text-xs">— Moussa K., Côte d'Ivoire</p>
                </div>
                <div class="bg-white/10 p-8 rounded-[2rem] text-left">
                    <p class="italic mb-6">"Service très sérieux pour l'importation de bus pour ma société à Dakar. Les prix sont bien meilleurs qu'en local."</p>
                    <p class="font-bold uppercase text-xs">— Amadou S., Sénégal</p>
                </div>
            </div>
        </div>
    </section>

    <!-- PIED DE PAGE -->
    <footer class="py-12 px-6 bg-slate-950 border-t border-white/5 text-center">
        <div class="brand-font flex items-center justify-center gap-2 mb-6">
            <div class="w-8 h-8 bg-blue-600 rounded flex items-center justify-center text-white italic font-black">V</div>
            <span class="font-bold text-lg uppercase">Vantage Auto</span>
        </div>
        <p class="text-slate-500 text-[10px] font-bold uppercase tracking-[0.3em]">
            Export Expert Dubaï & Chine | +33 6 18 66 72 57
        </p>
    </footer>

    <script>
        // Initialisation des icônes Lucide
        function init() {
            if (typeof lucide !== 'undefined') {
                lucide.createIcons();
            }
        }
        // Attendre que le script Lucide soit chargé
        if (document.getElementById('lucide-script')) {
            document.getElementById('lucide-script').addEventListener('load', init);
        }
        // Fallback au cas où le load ne se déclenche pas
        window.onload = init;
    </script>
</body>
</html>

