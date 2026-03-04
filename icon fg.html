<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>FitGram PRO - The Ultimate Challenge</title>
    <!-- Icona per iPhone (Apple Touch Icon) -->
    <link rel="apple-touch-icon" href="fitgram-icon.png">
    <link rel="apple-touch-icon" sizes="180x180" href="fitgram-icon.png">
    <!-- Icona generica browser -->
    <link rel="icon" type="image/png" href="fitgram-icon.png">
    <!-- Nome app quando aggiunta alla home -->
    <meta name="apple-mobile-web-app-title" content="FitGram">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800;900&family=Dancing+Script:wght@700&family=Syne:wght@700;800&family=Space+Grotesk:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
    /* Font fallbacks for offline use */
    @font-face { font-family: 'Inter'; src: local('Arial'), local('Helvetica'); font-weight: 400 900; }
    </style>
    <style>
        :root { --neon: #00F5FF; --dark-green: #004d4d; }
        /* Foto profilo sempre cerchio perfetto */
        #profile-img, #up-avatar, #edit-avatar-preview {
            width: 100%; height: 100%; object-fit: cover; border-radius: 50%;
        }

        body { 
            font-family: 'Inter', sans-serif; min-height: 100vh; 
            background: linear-gradient(0deg, #000 0%, #004d4d 25%, #fff 65%); 
            background-attachment: fixed; color: #1a1a1a; overflow-x: hidden; 
        }
        .logo-gradient { 
            background: linear-gradient(180deg, #000 0%, #006666 50%, #00F5FF 100%); 
            -webkit-background-clip: text; -webkit-text-fill-color: transparent; 
        }
        .font-disney { font-family: 'Dancing Script', cursive; }
        .glass-header { background: rgba(255, 255, 255, 0.4); backdrop-filter: blur(10px); border-bottom: 1px solid rgba(0, 245, 255, 0.1); }
        .post-card { background: #fff; color: #000; border-radius: 2.5rem; margin-bottom: 1.5rem; overflow: hidden; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }
        .nav-active { color: var(--neon) !important; filter: drop-shadow(0 0 8px var(--neon)); }
        
        #sidebar { position: fixed; inset: 0; transform: translateX(-100%); transition: 0.4s cubic-bezier(0.4, 0, 0.2, 1); z-index: 1000; }
        #sidebar.open { transform: translateX(0); }
        #sidebar-content { background: linear-gradient(180deg, #001a1a 0%, #000 100%); }
        
        .radar-line { position: absolute; width: 50%; height: 2px; background: var(--neon); top: 50%; left: 50%; transform-origin: left; animation: rotate 4s linear infinite; box-shadow: 0 0 15px var(--neon); }
        @keyframes rotate { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
        
        .story-circle { width: 70px; height: 70px; border-radius: 50%; border: 3px solid var(--neon); padding: 2px; flex-shrink: 0; background: white; }
        .btn-challenge { background: #000; color: var(--neon); font-weight: 900; text-transform: uppercase; border-radius: 50px; padding: 8px 16px; font-size: 10px; cursor: pointer; }
        .btn-plus { background: var(--neon); width: 55px; height: 55px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 30px; color: #000; transform: translateY(-15px); box-shadow: 0 0 20px rgba(0,245,255,0.6); border: none; cursor: pointer; }
        
        /* Modal Sfida */
        #challenge-request { position: fixed; bottom: 100px; left: 20px; right: 20px; background: black; color: white; padding: 20px; border-radius: 25px; z-index: 2000; border: 2px solid var(--neon); display: none; transform: translateY(200px); transition: 0.5s; }
        #challenge-request.show { display: block; transform: translateY(0); }

        .hidden { display: none; }
        .page-content { padding-bottom: 120px; }

        /* CTA Sfida fisso profilo */
        #profile-cta {
            position: fixed;
            bottom: 90px;
            left: 50%;
            transform: translateX(-50%);
            width: calc(100% - 48px);
            max-width: 400px;
            z-index: 99;
            display: none;
        }
        #profile-cta.visible { display: block; }

        /* Modal Modifica Profilo */
        #edit-profile-modal {
            position: fixed; inset: 0; background: rgba(0,0,0,0.75);
            backdrop-filter: blur(12px); z-index: 3000;
            display: flex; align-items: flex-end;
            transition: opacity 0.3s;
        }
        #edit-profile-modal.hidden { display: none; }
        #edit-profile-sheet {
            background: #111; width: 100%; border-radius: 2.5rem 2.5rem 0 0;
            padding: 1.5rem 1.5rem 3rem; max-height: 92vh; overflow-y: auto;
            animation: slideUp 0.4s cubic-bezier(0.4,0,0.2,1);
            border-top: 1px solid rgba(255,255,255,0.08);
        }
        @keyframes slideUp { from { transform: translateY(100%); } to { transform: translateY(0); } }

        .edit-input {
            width: 100%; border: 1.5px solid rgba(255,255,255,0.1); border-radius: 1rem;
            padding: 0.85rem 1rem; font-size: 13px; font-weight: 600;
            outline: none; transition: border-color 0.2s;
            background: rgba(255,255,255,0.05); color: #fff;
            font-family: 'Inter', sans-serif;
        }
        .edit-input:focus { border-color: #00F5FF; }
        .edit-input::placeholder { color: rgba(255,255,255,0.25); }
        .edit-label { font-size: 9px; font-weight: 900; text-transform: uppercase; letter-spacing: .1em; color: rgba(255,255,255,0.35); display: block; margin-bottom: 8px; }
        .sport-pill {
            padding: 6px 14px; border-radius: 50px; font-size: 10px; font-weight: 900;
            border: 1.5px solid rgba(255,255,255,0.1); cursor: pointer; transition: all 0.2s;
            color: rgba(255,255,255,0.5); background: rgba(255,255,255,0.04);
        }
        .sport-pill.selected { background: #00F5FF; color: #000; border-color: #00F5FF; }

        /* Toggle switch */
        .toggle-switch { position:relative; width:44px; height:24px; flex-shrink:0; }
        .toggle-switch input { opacity:0; width:0; height:0; }
        .toggle-track { position:absolute; inset:0; background:rgba(255,255,255,0.1); border-radius:24px; cursor:pointer; transition:.3s; }
        .toggle-track:before { content:''; position:absolute; width:18px; height:18px; left:3px; bottom:3px; background:#fff; border-radius:50%; transition:.3s; }
        input:checked + .toggle-track { background:#00F5FF; }
        input:checked + .toggle-track:before { transform:translateX(20px); background:#000; }
        /* Sidebar moderna */
        .sidebar-logo { font-family: 'Syne', sans-serif; font-weight: 800; letter-spacing: -0.03em; }
        .sidebar-nav-item { font-family: 'Space Grotesk', sans-serif; font-weight: 500; font-size: 13px; letter-spacing: 0.01em; text-transform: none; }
        .sidebar-nav-label { font-family: 'Space Grotesk', sans-serif; font-weight: 400; font-size: 10px; letter-spacing: 0.08em; text-transform: uppercase; color: rgba(255,255,255,0.3); }

        /* Modal sfida testo libero */
        .challenge-input {
            width: 100%; background: #111; border: 2px solid #333;
            border-radius: 1rem; padding: 1rem 1.2rem;
            color: white; font-size: 14px; font-weight: 600;
            outline: none; transition: border-color 0.2s;
            font-family: 'Space Grotesk', sans-serif;
        }
        .challenge-input::placeholder { color: rgba(255,255,255,0.25); }
        .challenge-input:focus { border-color: var(--neon); }

        /* Blip radar */
        .radar-blip {
            position: absolute; width: 10px; height: 10px; border-radius: 50%;
            background: var(--neon); box-shadow: 0 0 8px var(--neon);
            transform: translate(-50%, -50%);
            animation: blipPulse 2s ease-in-out infinite;
        }
        @keyframes blipPulse { 0%,100%{opacity:1;transform:translate(-50%,-50%) scale(1)} 50%{opacity:0.5;transform:translate(-50%,-50%) scale(1.4)} }

        /* Pagina profilo utente */
        #user-profile-page {
            position: fixed; inset: 0; background: linear-gradient(0deg,#000 0%,#004d4d 25%,#fff 65%);
            z-index: 4500; transform: translateX(100%);
            transition: transform 0.4s cubic-bezier(0.4,0,0.2,1);
            overflow-y: auto; padding-bottom: 100px;
        }
        #user-profile-page.open { transform: translateX(0); }

        /* Pagina Follower/Seguiti/Trofei */
        #page-users {
            position: fixed; inset: 0;
            background: #0a0a0a;
            z-index: 4000;
            transform: translateY(100%);
            transition: transform 0.4s cubic-bezier(0.4,0,0.2,1);
            overflow-y: auto; padding-bottom: 60px;
        }
        #page-users.open { transform: translateY(0); }
        .users-tab-btn { flex:1; padding: 10px 0; font-size:10px; font-weight:900; text-transform:uppercase; letter-spacing:.08em; border-bottom: 2px solid transparent; transition: all .2s; color: rgba(255,255,255,0.35); }
        .users-tab-btn.active { color: #00F5FF; border-color: #00F5FF; }
        .user-card { background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.07); border-radius: 20px; padding: 14px 16px; display:flex; align-items:center; gap:12px; margin-bottom: 10px; cursor:pointer; transition: background .15s; }
        .user-card:active { background: rgba(255,255,255,0.08); }

        /* Post viewer */
        #post-viewer { max-width: 400px; margin: 0 auto; }
        #post-viewer.pv-open { transform: translateX(-50%) translateY(0) !important; }        /* Commenti mini-modale */
        .comments-box {
            background: #f9f9f9; border-radius: 0 0 2rem 2rem;
            padding: 16px; border-top: 1px solid #eee;
            animation: fadeIn 0.2s ease;
        }
        @keyframes fadeIn { from { opacity:0; transform:translateY(-8px); } to { opacity:1; transform:translateY(0); } }
        .comment-input-row { display: flex; gap: 8px; margin-top: 10px; }
        .comment-input-row input {
            flex: 1; border: 1.5px solid #e5e5e5; border-radius: 50px;
            padding: 8px 14px; font-size: 12px; outline: none; background: white;
            font-family: 'Inter', sans-serif;
        }
        .comment-input-row input:focus { border-color: var(--neon); }
        .comment-send { background: #000; color: var(--neon); border: none; border-radius: 50px; padding: 8px 14px; font-size: 10px; font-weight: 900; cursor: pointer; }

        /* ── RESULT MODAL & TROPHY ANIMATION ── */
        #result-modal {
            position: fixed; inset: 0; z-index: 8000;
            background: rgba(0,0,0,.85); backdrop-filter: blur(16px);
            display: none; align-items: center; justify-content: center;
            padding: 24px;
        }
        #result-modal.open { display: flex; }
        .result-card {
            background: #111; border: 1px solid rgba(255,255,255,.08);
            border-radius: 28px; padding: 28px 24px 32px;
            width: 100%; max-width: 360px; text-align: center;
        }
        .result-btn {
            flex: 1; padding: 16px 8px; border-radius: 16px;
            font-weight: 900; font-size: 12px; text-transform: uppercase;
            letter-spacing: .08em; border: none; cursor: pointer; transition: all .2s;
        }
        .result-btn:active { transform: scale(.97); }

        #trophy-modal {
            position: fixed; inset: 0; z-index: 8500;
            background: #000; display: none; flex-direction: column;
            align-items: center; justify-content: center; gap: 0;
        }
        #trophy-modal.open { display: flex; }
        @keyframes trophyDrop {
            0%   { transform: translateY(-80px) scale(.5); opacity: 0; }
            60%  { transform: translateY(12px) scale(1.15); opacity: 1; }
            80%  { transform: translateY(-6px) scale(.95); }
            100% { transform: translateY(0) scale(1); }
        }
        @keyframes trophyGlow {
            0%, 100% { text-shadow: 0 0 20px rgba(0,245,255,.4); }
            50%       { text-shadow: 0 0 60px rgba(0,245,255,.9), 0 0 100px rgba(0,245,255,.4); }
        }
        @keyframes confettiFall {
            0%   { transform: translateY(-20px) rotate(0deg); opacity: 1; }
            100% { transform: translateY(100vh) rotate(720deg); opacity: 0; }
        }
        .trophy-anim { animation: trophyDrop .7s cubic-bezier(.34,1.56,.64,1) forwards, trophyGlow 2s ease-in-out 1s infinite; }
        .confetti-piece {
            position: absolute; width: 8px; height: 8px; border-radius: 2px;
            animation: confettiFall linear forwards;
        }
        @keyframes fadeInUp {
            from { opacity:0; transform:translateY(20px); }
            to   { opacity:1; transform:translateY(0); }
        }
        .trophy-text { opacity: 0; animation: fadeInUp .5s ease forwards; }


        .ob-sport-pill{padding:8px 14px;border-radius:50px;font-size:11px;font-weight:700;background:rgba(255,255,255,.06);color:rgba(255,255,255,.5);border:1px solid rgba(255,255,255,.1);cursor:pointer;transition:all .2s}
        .ob-sport-pill.active{background:#00F5FF;color:#000;border-color:#00F5FF}
        /* Like animato */
        @keyframes likePop { 0%{transform:scale(1)} 50%{transform:scale(1.4)} 100%{transform:scale(1)} }
        .like-pop { animation: likePop 0.3s ease; }

        /* Notifica sfida in arrivo */
        #challenge-notify {
            position: fixed; top: 90px; left: 16px; right: 16px;
            background: #000; color: white; border-radius: 20px;
            border: 2px solid var(--neon); z-index: 6000; padding: 16px 18px;
            box-shadow: 0 0 40px rgba(0,245,255,0.25);
            transform: translateY(-140px); transition: transform 0.45s cubic-bezier(0.34,1.56,0.64,1);
            display: none;
        }
        #challenge-notify.show { display: block; transform: translateY(0); }

        /* Chat match fullscreen */
        #chat-match-page {
            position: fixed; inset: 0; background: #f4f4f4;
            z-index: 5500; transform: translateX(100%);
            transition: transform 0.4s cubic-bezier(0.4,0,0.2,1);
            display: flex; flex-direction: column;
        }
        #chat-match-page.open { transform: translateX(0); }
        .chat-header { background: #fff; border-bottom: 1px solid #eee; padding: 14px 18px; display: flex; align-items: center; gap: 12px; }
        .chat-bubble-me { background: #000; color: #00F5FF; border-radius: 20px 20px 4px 20px; padding: 10px 14px; font-size: 13px; max-width: 75%; align-self: flex-end; }
        .chat-bubble-them { background: #fff; color: #111; border-radius: 20px 20px 20px 4px; padding: 10px 14px; font-size: 13px; max-width: 75%; align-self: flex-start; box-shadow: 0 2px 8px rgba(0,0,0,0.07); }
        .chat-time { font-size: 9px; color: #aaa; font-weight: 600; margin-top: 2px; }
        .chat-input-bar { background: #fff; border-top: 1px solid #eee; padding: 12px 16px; display: flex; gap: 10px; align-items: center; }
        .chat-input-bar input { flex:1; border: 1.5px solid #e5e5e5; border-radius: 50px; padding: 10px 16px; font-size: 13px; outline: none; font-family: 'Inter', sans-serif; }
        .chat-input-bar input:focus { border-color: var(--neon); }
        .chat-send-btn { background: #000; color: var(--neon); border: none; border-radius: 50%; width: 40px; height: 40px; display: flex; align-items: center; justify-content: center; cursor: pointer; flex-shrink: 0; }

        /* Banner trofeo in chat */
        #trophy-banner {
            background: linear-gradient(135deg, #001a1a, #000);
            border-top: 2px solid var(--neon); padding: 16px 18px;
            display: none;
        }
        #trophy-banner.show { display: block; }

        /* Sport icon fade */
        #sport-icon { transition: opacity 0.4s ease; }
        #sport-icon.fade { opacity: 0; }

        /* Modal sfida sport */
        #challenge-sport-modal {
            position: fixed; inset: 0; background: rgba(0,0,0,0.7);
            backdrop-filter: blur(8px); z-index: 3000;
            display: flex; align-items: flex-end;
        }
        #challenge-sport-modal.hidden { display: none; }
        #challenge-sport-sheet {
            background: #000; width: 100%; border-radius: 2.5rem 2.5rem 0 0;
            padding: 2rem 1.5rem 3rem; max-height: 80vh; overflow-y: auto;
            animation: slideUp 0.4s cubic-bezier(0.4,0,0.2,1);
            border-top: 2px solid var(--neon);
        }
    
        /* ── AUTH / SPLASH / TOAST ── */
        #splash-screen{position:fixed;inset:0;z-index:9999;background:#000;display:flex;flex-direction:column;align-items:center;justify-content:center;transition:opacity .6s ease}
        #auth-screen{position:fixed;inset:0;z-index:9998;background:linear-gradient(160deg,#000 0%,#001a1a 50%,#000 100%);overflow-y:auto;display:none;flex-direction:column}
        #auth-screen.visible{display:flex}
        #onboarding-screen{position:fixed;inset:0;z-index:9997;background:#000;display:none;flex-direction:column}
        #onboarding-screen.visible{display:flex}
        .auth-input{width:100%;background:rgba(255,255,255,.06);border:1.5px solid rgba(255,255,255,.1);border-radius:14px;padding:14px 16px;color:#fff;font-size:14px;font-weight:600;outline:none;font-family:Inter,sans-serif;transition:border-color .2s;box-sizing:border-box}
        .auth-input:focus{border-color:#00F5FF}
        .auth-input::placeholder{color:rgba(255,255,255,.25)}
        .spinner{width:20px;height:20px;border:2.5px solid rgba(0,0,0,.15);border-top-color:#000;border-radius:50%;animation:spin .7s linear infinite;display:inline-block;vertical-align:middle}
        .spinner-white{border-color:rgba(255,255,255,.15);border-top-color:#fff}
        @keyframes spin{to{transform:rotate(360deg)}}
        #toast{position:fixed;bottom:110px;left:50%;transform:translateX(-50%) translateY(16px);background:#111;color:#fff;border:1px solid rgba(255,255,255,.1);border-radius:50px;padding:10px 22px;font-size:11px;font-weight:700;z-index:9500;opacity:0;transition:all .3s;white-space:nowrap;pointer-events:none;max-width:90vw;text-align:center}
        #toast.show{opacity:1;transform:translateX(-50%) translateY(0)}
        #toast.success{border-color:#00F5FF;color:#00F5FF}
        #toast.error{border-color:#ef4444;color:#ef4444}
        .ob-step{display:none;flex-direction:column;flex:1;padding:32px 28px 28px}
        .ob-step.active{display:flex}
        .ob-dot{width:6px;height:6px;border-radius:50%;background:rgba(255,255,255,.2);transition:all .3s;flex-shrink:0}
        .ob-dot.active{background:#00F5FF;width:20px;border-radius:3px}
        #register-wall{position:fixed;inset:0;z-index:9990;background:rgba(0,0,0,.75);backdrop-filter:blur(14px);display:none;align-items:flex-end;justify-content:center;opacity:0;transition:opacity .3s}
        #register-wall.rw-show{opacity:1}
        </style>
<style id="critical-fallback">
/* Critical styles that work WITHOUT Tailwind */
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; }
.hidden { display: none !important; }
.fixed { position: fixed; }
.inset-0 { top: 0; right: 0; bottom: 0; left: 0; }
.flex { display: flex; }
.flex-col { flex-direction: column; }
.items-center { align-items: center; }
.justify-center { justify-content: center; }
.w-full { width: 100%; }
.h-full { height: 100%; }
.overflow-hidden { overflow: hidden; }
.rounded-full { border-radius: 9999px; }
.rounded-2xl { border-radius: 1rem; }
.rounded-3xl { border-radius: 1.5rem; }
.font-black { font-weight: 900; }
.font-bold { font-weight: 700; }
.uppercase { text-transform: uppercase; }
.text-center { text-align: center; }
.cursor-pointer { cursor: pointer; }
.relative { position: relative; }
.absolute { position: absolute; }
.sticky { position: sticky; }
.gap-1 { gap: 0.25rem; }
.gap-2 { gap: 0.5rem; }
.gap-3 { gap: 0.75rem; }
.gap-4 { gap: 1rem; }
.gap-5 { gap: 1.25rem; }
.gap-6 { gap: 1.5rem; }
.p-1 { padding: 0.25rem; }
.p-4 { padding: 1rem; }
.p-5 { padding: 1.25rem; }
.p-6 { padding: 1.5rem; }
.px-4 { padding-left: 1rem; padding-right: 1rem; }
.py-3 { padding-top: 0.75rem; padding-bottom: 0.75rem; }
.py-4 { padding-top: 1rem; padding-bottom: 1rem; }
.mt-1 { margin-top: 0.25rem; }
.mt-2 { margin-top: 0.5rem; }
.mt-3 { margin-top: 0.75rem; }
.mt-4 { margin-top: 1rem; }
.mb-1 { margin-bottom: 0.25rem; }
.mb-3 { margin-bottom: 0.75rem; }
.mb-4 { margin-bottom: 1rem; }
.mb-5 { margin-bottom: 1.25rem; }
.mx-auto { margin-left: auto; margin-right: auto; }
.text-white { color: #fff; }
.text-black { color: #000; }
.border { border-width: 1px; }
.border-none { border: none; }
.object-cover { object-fit: cover; }
.overflow-y-auto { overflow-y: auto; }
.overflow-x-auto { overflow-x: auto; }
.flex-1 { flex: 1 1 0%; }
.flex-shrink-0 { flex-shrink: 0; }
.min-w-0 { min-width: 0; }
.space-y-3 > * + * { margin-top: 0.75rem; }
.space-y-4 > * + * { margin-top: 1rem; }
.grid { display: grid; }
.grid-cols-3 { grid-template-columns: repeat(3, minmax(0, 1fr)); }
.grid-cols-2 { grid-template-columns: repeat(2, minmax(0, 1fr)); }
.aspect-square { aspect-ratio: 1 / 1; }
.truncate { overflow: hidden; text-overflow: ellipsis; white-space: nowrap; }
.italic { font-style: italic; }
.no-scrollbar::-webkit-scrollbar { display: none; }
.no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
.transition-all { transition: all 0.2s; }
.transition-colors { transition: color 0.2s, background-color 0.2s; }
.opacity-0 { opacity: 0; }
.opacity-40 { opacity: 0.4; }
.z-50 { z-index: 50; }
.top-0 { top: 0; }
.shadow-sm { box-shadow: 0 1px 2px rgba(0,0,0,0.05); }
.border-b { border-bottom-width: 1px; }
.border-t { border-top-width: 1px; }
.w-8 { width: 2rem; }
.h-8 { height: 2rem; }
.w-9 { width: 2.25rem; }
.h-9 { height: 2.25rem; }
.w-10 { width: 2.5rem; }
.h-10 { height: 2.5rem; }
.w-12 { width: 3rem; }
.h-12 { height: 3rem; }
.w-14 { width: 3.5rem; }
.h-14 { height: 3.5rem; }
.w-20 { width: 5rem; }
.h-20 { height: 5rem; }
.w-24 { width: 6rem; }
.h-24 { height: 6rem; }
.max-w-md { max-width: 28rem; }
.h-16 { height: 4rem; }
.h-1 { height: 0.25rem; }
.w-4\/5 { width: 80%; }
.w-1\/5 { width: 20%; }
.leading-none { line-height: 1; }
.leading-relaxed { line-height: 1.625; }
.tracking-widest { letter-spacing: 0.1em; }
.tracking-wide { letter-spacing: 0.025em; }
.block { display: block; }
.inline-flex { display: inline-flex; }
.pointer-events-none { pointer-events: none; }
.select-none { user-select: none; }
.flex-wrap { flex-wrap: wrap; }
.justify-between { justify-content: space-between; }
.justify-around { justify-content: space-around; }
.items-start { align-items: flex-start; }
.items-end { align-items: flex-end; }
.pb-1 { padding-bottom: 0.25rem; }
.pt-3 { padding-top: 0.75rem; }
.pt-5 { padding-top: 1.25rem; }
.pb-2 { padding-bottom: 0.5rem; }
.pl-4 { padding-left: 1rem; }
.pr-4 { padding-right: 1rem; }
.ml-auto { margin-left: auto; }
.mr-1 { margin-right: 0.25rem; }
.ml-1 { margin-left: 0.25rem; }
.max-h-40 { max-height: 10rem; }
.max-h-56 { max-height: 14rem; }
.w-2\.5 { width: 0.625rem; }
.h-2\.5 { height: 0.625rem; }
.w-3 { width: 0.75rem; }
.h-3 { height: 0.75rem; }
.text-xl { font-size: 1.25rem; line-height: 1.75rem; }
.text-2xl { font-size: 1.5rem; line-height: 2rem; }
.text-lg { font-size: 1.125rem; }
.text-sm { font-size: 0.875rem; }
.text-xs { font-size: 0.75rem; }
.bg-black { background-color: #000; }
.bg-white { background-color: #fff; }
.bg-gray-100 { background-color: #f3f4f6; }
.bg-gray-50 { background-color: #f9fafb; }
.text-gray-400 { color: #9ca3af; }
.text-gray-500 { color: #6b7280; }
.text-gray-600 { color: #4b5563; }
.border-gray-100 { border-color: #f3f4f6; }
.border-gray-200 { border-color: #e5e7eb; }
.border-cyan-400 { border-color: #22d3ee; }
.text-cyan-400 { color: #22d3ee; }
.text-cyan-600 { color: #0891b2; }
.bg-cyan-50 { background-color: #ecfeff; }
.hover\:bg-gray-100:hover { background-color: #f3f4f6; }
.hover\:bg-white\/5:hover { background-color: rgba(255,255,255,0.05); }
.group:hover .group-hover\:opacity-100 { opacity: 1; }
.group:hover .group-hover\:bg-black\/50 { background-color: rgba(0,0,0,0.5); }
.group:hover .group-hover\:bg-black\/40 { background-color: rgba(0,0,0,0.4); }
.space-y-2 > * + * { margin-top: 0.5rem; }
.space-y-1 > * + * { margin-top: 0.25rem; }
.pb-6 { padding-bottom: 1.5rem; }
.pt-4 { padding-top: 1rem; }
.px-3 { padding-left: 0.75rem; padding-right: 0.75rem; }
.px-5 { padding-left: 1.25rem; padding-right: 1.25rem; }
.py-1 { padding-top: 0.25rem; padding-bottom: 0.25rem; }
.py-2 { padding-top: 0.5rem; padding-bottom: 0.5rem; }
.py-2\.5 { padding-top: 0.625rem; padding-bottom: 0.625rem; }
.left-0 { left: 0; }
.right-0 { right: 0; }
.bottom-6 { bottom: 1.5rem; }
.left-6 { left: 1.5rem; }
.right-6 { right: 1.5rem; }
.z-\[100\] { z-index: 100; }
.max-h-\[420px\] { max-height: 420px; }
.max-h-\[92vh\] { max-height: 92vh; }
.max-w-\[400px\] { max-width: 400px; }
.max-w-\[360px\] { max-width: 360px; }
.w-\[300px\] { width: 300px; }
.h-\[55px\] { height: 55px; } 
.w-\[55px\] { width: 55px; }
.translate-y-\[-15px\] { transform: translateY(-15px); }
</style>
    <script>
    // ── STORAGE GLOBALE - deve essere disponibile prima di tutto ──
    var FG_STORE = (function() {
        try {
            localStorage.setItem('_fg_test','1');
            localStorage.removeItem('_fg_test');
            return localStorage;
        } catch(e) {
            var _d = {};
            return {
                getItem: function(k){ return _d[k]!==undefined ? _d[k] : null; },
                setItem: function(k,v){ _d[k]=String(v); },
                removeItem: function(k){ delete _d[k]; }
            };
        }
    })();
    var FGKEY = 'fitgram_v1';
    var isGuest = false;
    </script>
</head>
<body class="max-w-md mx-auto">

    <!-- TOAST -->
    <div id="toast"></div>

    <!-- SPLASH -->
    <div id="splash-screen" style="position:fixed;inset:0;z-index:9999;background:#000;display:flex;flex-direction:column;align-items:center;justify-content:center;transition:opacity .6s ease">
        <div class="flex items-baseline logo-gradient" style="margin-bottom:12px">
            <span class="text-5xl font-black italic uppercase" style="margin-right:3px">Fit</span>
            <span class="text-6xl font-disney">Gram</span>
        </div>
        <p style="font-size:9px;font-weight:900;text-transform:uppercase;letter-spacing:.3em;color:rgba(255,255,255,.3)">The Ultimate Challenge</p>
        <div style="margin-top:48px"><div class="spinner spinner-white"></div></div>
    </div>

    <!-- AUTH -->
    <div id="auth-screen">
        <div style="flex:1;display:flex;flex-direction:column;padding:64px 28px 40px;max-width:400px;margin:0 auto;width:100%;box-sizing:border-box">
            <div class="flex items-baseline logo-gradient" style="margin-bottom:6px">
                <span class="text-4xl font-black italic uppercase" style="margin-right:3px">Fit</span>
                <span class="text-5xl font-disney">Gram</span>
            </div>
            <p style="color:rgba(255,255,255,.3);font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.15em;margin-bottom:40px">The Ultimate Challenge</p>
            <div style="display:flex;gap:4px;margin-bottom:28px;background:rgba(255,255,255,.05);padding:4px;border-radius:16px">
                <button id="auth-tab-login" onclick="switchAuthTab('login')" style="flex:1;padding:10px;border-radius:12px;font-size:10px;font-weight:900;text-transform:uppercase;background:#fff;color:#000;border:none;cursor:pointer">Accedi</button>
                <button id="auth-tab-register" onclick="switchAuthTab('register')" style="flex:1;padding:10px;border-radius:12px;font-size:10px;font-weight:900;text-transform:uppercase;background:transparent;color:rgba(255,255,255,.4);border:none;cursor:pointer">Registrati</button>
            </div>
            <div id="auth-form-login" style="display:flex;flex-direction:column;gap:14px">
                <input id="login-email" class="auth-input" type="email" placeholder="Email" autocomplete="email">
                <input id="login-password" class="auth-input" type="password" placeholder="Password" autocomplete="current-password">
                <button onclick="doLogin()" id="login-btn" style="width:100%;padding:16px;border-radius:16px;font-weight:900;font-size:13px;text-transform:uppercase;letter-spacing:.15em;background:#00F5FF;color:#000;border:none;cursor:pointer;margin-top:6px">Accedi</button>
                <p onclick="switchAuthTab('register')" style="text-align:center;color:rgba(255,255,255,.3);font-size:10px;font-weight:700;cursor:pointer;margin:0">Non hai un account? <span style="color:#00F5FF">Registrati</span></p>
            </div>
            <div id="auth-form-register" style="display:none;flex-direction:column;gap:14px">
                <input id="reg-name" class="auth-input" type="text" placeholder="Nome utente" autocomplete="username">
                <input id="reg-email" class="auth-input" type="email" placeholder="Email" autocomplete="email">
                <input id="reg-password" class="auth-input" type="password" placeholder="Password (min. 6 caratteri)" autocomplete="new-password">
                <button onclick="doRegister()" id="register-btn" style="width:100%;padding:16px;border-radius:16px;font-weight:900;font-size:13px;text-transform:uppercase;letter-spacing:.15em;background:#00F5FF;color:#000;border:none;cursor:pointer;margin-top:6px">Crea account</button>
                <p onclick="switchAuthTab('login')" style="text-align:center;color:rgba(255,255,255,.3);font-size:10px;font-weight:700;cursor:pointer;margin:0">Hai già un account? <span style="color:#00F5FF">Accedi</span></p>
            </div>
            <div style="display:flex;align-items:center;gap:12px;margin:24px 0">
                <div style="flex:1;height:1px;background:rgba(255,255,255,.08)"></div>
                <span style="color:rgba(255,255,255,.2);font-size:10px;font-weight:700;text-transform:uppercase">oppure</span>
                <div style="flex:1;height:1px;background:rgba(255,255,255,.08)"></div>
            </div>
            <!-- demo button rimosso -->
        </div>
    </div>

    <!-- ONBOARDING -->
    <div id="onboarding-screen">
        <div style="display:flex;gap:8px;justify-content:center;padding-top:56px;padding-bottom:8px">
            <div class="ob-dot active" id="ob-dot-0"></div><div class="ob-dot" id="ob-dot-1"></div><div class="ob-dot" id="ob-dot-2"></div><div class="ob-dot" id="ob-dot-3"></div>
        </div>
        <div class="ob-step active" id="ob-step-0">
            <div style="text-align:center;margin-bottom:40px">
                <div style="font-size:64px;margin-bottom:20px">&#9876;</div>
                <h2 style="color:#fff;font-weight:900;font-size:26px;text-transform:uppercase;font-style:italic;margin-bottom:12px;line-height:1.2">Benvenuto<br>su FitGram</h2>
                <p style="color:rgba(255,255,255,.4);font-size:13px;font-weight:700;line-height:1.7">La prima piattaforma social<br>per sfidare atleti vicino a te</p>
            </div>
            <div style="margin-top:auto"><button onclick="nextObStep(1)" style="width:100%;padding:16px;border-radius:16px;font-weight:900;font-size:13px;text-transform:uppercase;letter-spacing:.15em;background:#00F5FF;color:#000;border:none;cursor:pointer">Inizia &rarr;</button></div>
        </div>
        <div class="ob-step" id="ob-step-1">
            <div style="text-align:center;margin-bottom:40px">
                <div style="width:80px;height:80px;border-radius:22px;margin:0 auto 20px;display:flex;align-items:center;justify-content:center;background:rgba(0,245,255,.08);border:1px solid rgba(0,245,255,.2)">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="1.5"><line x1="2" y1="2" x2="22" y2="22"/><line x1="22" y1="2" x2="2" y2="22"/></svg>
                </div>
                <h2 style="color:#fff;font-weight:900;font-size:22px;text-transform:uppercase;font-style:italic;margin-bottom:12px">Lancia Sfide</h2>
                <p style="color:rgba(255,255,255,.4);font-size:13px;font-weight:700;line-height:1.7">Sfida chiunque in qualsiasi cosa</p>
            </div>
            <div style="margin-top:auto;display:flex;gap:12px">
                <button onclick="nextObStep(0)" style="flex:1;padding:14px;border-radius:16px;font-weight:900;font-size:11px;background:transparent;color:rgba(255,255,255,.35);border:1px solid rgba(255,255,255,.1);cursor:pointer">&larr;</button>
                <button onclick="nextObStep(2)" style="flex:1;padding:14px;border-radius:16px;font-weight:900;font-size:13px;text-transform:uppercase;background:#00F5FF;color:#000;border:none;cursor:pointer">Avanti &rarr;</button>
            </div>
        </div>
        <div class="ob-step" id="ob-step-2">
            <div style="text-align:center;margin-bottom:40px">
                <div style="width:80px;height:80px;border-radius:22px;margin:0 auto 20px;display:flex;align-items:center;justify-content:center;background:rgba(0,245,255,.08);border:1px solid rgba(0,245,255,.2)">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="1.5"><path d="M6 9H4.5a2.5 2.5 0 0 1 0-5H6"/><path d="M18 9h1.5a2.5 2.5 0 0 0 0-5H18"/><path d="M4 22h16"/><path d="M18 2H6v7a6 6 0 0 0 12 0V2Z"/><path d="M12 17v5"/></svg>
                </div>
                <h2 style="color:#fff;font-weight:900;font-size:22px;text-transform:uppercase;font-style:italic;margin-bottom:12px">Vinci Trofei</h2>
                <p style="color:rgba(255,255,255,.4);font-size:13px;font-weight:700;line-height:1.7">Scala le classifiche mondiali</p>
            </div>
            <div style="margin-top:auto;display:flex;gap:12px">
                <button onclick="nextObStep(1)" style="flex:1;padding:14px;border-radius:16px;font-weight:900;font-size:11px;background:transparent;color:rgba(255,255,255,.35);border:1px solid rgba(255,255,255,.1);cursor:pointer">&larr;</button>
                <button onclick="nextObStep(3)" style="flex:1;padding:14px;border-radius:16px;font-weight:900;font-size:13px;text-transform:uppercase;background:#00F5FF;color:#000;border:none;cursor:pointer">Avanti &rarr;</button>
            </div>
        </div>

        <!-- STEP 3: Setup profilo -->
        <div class="ob-step" id="ob-step-3">
            <h2 style="color:#fff;font-weight:900;font-size:22px;text-transform:uppercase;font-style:italic;margin-bottom:6px">Crea il tuo profilo</h2>
            <p style="color:rgba(255,255,255,.4);font-size:12px;font-weight:600;margin-bottom:24px">Due info e sei dentro</p>
            <div style="display:flex;flex-direction:column;gap:14px;flex:1">
                <div>
                    <p style="color:rgba(255,255,255,.4);font-size:10px;font-weight:900;text-transform:uppercase;letter-spacing:.1em;margin-bottom:8px">Il tuo sport principale</p>
                    <div style="display:flex;flex-wrap:wrap;gap:8px" id="ob-sport-pills">
                        <button onclick="selectObSport(this,'Boxe')" class="ob-sport-pill">Boxe</button>
                        <button onclick="selectObSport(this,'Running')" class="ob-sport-pill">Running</button>
                        <button onclick="selectObSport(this,'Powerlifting')" class="ob-sport-pill">Powerlifting</button>
                        <button onclick="selectObSport(this,'Nuoto')" class="ob-sport-pill">Nuoto</button>
                        <button onclick="selectObSport(this,'Ciclismo')" class="ob-sport-pill">Ciclismo</button>
                        <button onclick="selectObSport(this,'MMA')" class="ob-sport-pill">MMA</button>
                        <button onclick="selectObSport(this,'Tennis')" class="ob-sport-pill">Tennis</button>
                        <button onclick="selectObSport(this,'Yoga')" class="ob-sport-pill">Yoga</button>
                        <button onclick="selectObSport(this,'Calcio')" class="ob-sport-pill">Calcio</button>
                        <button onclick="selectObSport(this,'Scacchi')" class="ob-sport-pill">Scacchi</button>
                        <button onclick="selectObSport(this,'Skateboard')" class="ob-sport-pill">Skateboard</button>
                        <button onclick="selectObSport(this,'Altro')" class="ob-sport-pill">Altro</button>
                    </div>
                </div>
                <div>
                    <p style="color:rgba(255,255,255,.4);font-size:10px;font-weight:900;text-transform:uppercase;letter-spacing:.1em;margin-bottom:8px">La tua città</p>
                    <input id="ob-city-input" class="auth-input" type="text" placeholder="Es. Roma, Milano, Napoli…">
                </div>
            </div>
            <div style="margin-top:24px">
                <button onclick="completeOnboarding()" style="width:100%;padding:16px;border-radius:16px;font-weight:900;font-size:13px;text-transform:uppercase;letter-spacing:.1em;background:#00F5FF;color:#000;border:none;cursor:pointer">Entra su FitGram &rarr;</button>
            </div>
        </div>
    </div>

    <!-- REGISTER WALL -->
    <div id="register-wall" onclick="if(event.target===this)closeRegisterWall()">
        <div style="background:#111;border:1px solid rgba(255,255,255,.08);border-radius:32px 32px 0 0;padding:28px 24px 44px;width:100%;max-width:400px">
            <div style="width:36px;height:4px;border-radius:4px;background:rgba(255,255,255,.15);margin:0 auto 20px"></div>
            <div style="text-align:center;margin-bottom:24px">
                <div id="rw-icon" style="font-size:40px;margin-bottom:12px">&#x26A1;</div>
                <h3 style="color:#fff;font-weight:900;font-size:18px;margin-bottom:8px">Registrati per <span id="rw-action">continuare</span></h3>
                <p style="color:rgba(255,255,255,.4);font-size:12px;font-weight:600;line-height:1.6">Crea un account gratuito per<br>sbloccare tutte le funzionalità</p>
            </div>
            <div style="display:flex;flex-direction:column;gap:10px">
                <button onclick="goRegisterFromWall()" style="width:100%;padding:15px;border-radius:16px;font-weight:900;font-size:13px;text-transform:uppercase;letter-spacing:.1em;background:#00F5FF;color:#000;border:none;cursor:pointer">Crea account gratis</button>
                <button onclick="goLoginFromWall()" style="width:100%;padding:13px;border-radius:16px;font-weight:900;font-size:11px;text-transform:uppercase;background:transparent;color:rgba(255,255,255,.4);border:1px solid rgba(255,255,255,.1);cursor:pointer">Ho già un account</button>
                <button onclick="closeRegisterWall()" style="width:100%;padding:10px;font-size:10px;font-weight:700;color:rgba(255,255,255,.2);background:transparent;border:none;cursor:pointer;text-transform:uppercase">Continua a esplorare</button>
            </div>
        </div>
    </div>


    <!-- NOTIFICA SFIDA IN ARRIVO (banner top) -->
    <div id="challenge-notify">
        <div class="flex items-center gap-3 mb-3">
            <div class="relative">
                <img id="notify-avatar" src="" class="w-11 h-11 rounded-full border-2 border-cyan-400">
                <span class="absolute -bottom-1 -right-1 text-base">⚔️</span>
            </div>
            <div class="flex-1 min-w-0">
                <p class="text-[10px] font-black uppercase text-cyan-400 tracking-wider">Sfida ricevuta!</p>
                <p class="font-black text-sm truncate" id="notify-name">@User</p>
                <p class="text-[10px] text-white/50 truncate" id="notify-sport">vuole sfidarti</p>
            </div>
            <button onclick="dismissNotify()" class="text-white/30 text-xl leading-none ml-1">×</button>
        </div>
        <div class="flex gap-2">
            <button onclick="acceptNotify()" class="flex-1 bg-[#00F5FF] text-black py-2.5 rounded-xl font-black uppercase text-[10px] tracking-wider">Accetta</button>
            <button onclick="dismissNotify()" class="flex-1 bg-white/10 text-white/70 py-2.5 rounded-xl font-black uppercase text-[10px] tracking-wider">Ignora</button>
        </div>
    </div>

    <!-- CHAT MATCH FULLSCREEN -->
    <div id="chat-match-page">
        <div class="chat-header">
            <button onclick="closeChatMatch()" class="w-9 h-9 flex items-center justify-center rounded-full bg-gray-100 flex-shrink-0">
                <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#000" stroke-width="2.5"><polyline points="15 18 9 12 15 6"></polyline></svg>
            </button>
            <img id="chat-match-avatar" src="" class="w-10 h-10 rounded-full border-2 border-cyan-400">
            <div class="flex-1 min-w-0">
                <p class="font-black text-sm truncate" id="chat-match-name">@User</p>
                <p class="text-[9px] text-cyan-600 font-black uppercase" id="chat-match-sport">Match attivo ⚔️</p>
            </div>
            <button onclick="showTrophyBanner()" class="flex-shrink-0 bg-black text-[#00F5FF] text-[9px] font-black uppercase px-3 py-2 rounded-xl tracking-wide">
                Fine match
            </button>
        </div>

        <!-- Messaggi -->
        <div class="flex-1 overflow-y-auto p-4 flex flex-col gap-3" id="chat-match-messages" style="padding-bottom:8px"></div>

        <!-- Banner assegna trofeo -->
        <div id="trophy-banner">
            <p class="text-[10px] font-black uppercase text-white/40 mb-3 tracking-wider">Chi ha vinto il match?</p>
            <div class="flex gap-2">
                <button onclick="assignMatchTrophy('me')" class="flex-1 bg-[#00F5FF] text-black py-3 rounded-xl font-black text-[10px] uppercase">Ho vinto io 🏆</button>
                <button onclick="assignMatchTrophy('them')" id="trophy-them-btn" class="flex-1 bg-white/10 text-white py-3 rounded-xl font-black text-[10px] uppercase">Ha vinto lui</button>
            </div>
        </div>

        <!-- Input chat -->
        <div class="chat-input-bar">
            <input type="text" id="chat-match-input" placeholder="Scrivi un messaggio…" onkeydown="if(event.key==='Enter')sendMatchMessage()">
            <button class="chat-send-btn" onclick="sendMatchMessage()">
                <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="22" y1="2" x2="11" y2="13"></line><polygon points="22 2 15 22 11 13 2 9 22 2"></polygon></svg>
            </button>
        </div>
    </div>

    <!-- MODAL SFIDA RICEVUTA (vecchio, mantenuto per compatibilità) -->
    <div id="challenge-request" style="display:none!important"></div>

    <!-- PAGINA PROFILO UTENTE (altri utenti) -->
    <div id="user-profile-page">
        <div class="sticky top-0 glass-header px-4 py-3 flex items-center gap-3 z-10">
            <button onclick="closeUserProfile()" class="w-9 h-9 flex items-center justify-center rounded-full bg-white/60">
                <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#000" stroke-width="2.5"><polyline points="15 18 9 12 15 6"/></svg>
            </button>
            <span class="font-black text-sm text-[#004d4d]" id="up-username-header">@User</span>
        </div>
        <div class="p-5 bg-white/30">
            <div class="flex items-start gap-5">
                <div style="width:80px;height:80px;min-width:80px;border-radius:50%;border:4px solid #22d3ee;padding:4px;background:white;overflow:hidden;flex-shrink:0;">
                    <img id="up-avatar" src="" class="w-full h-full object-cover rounded-full">
                </div>
                <div class="flex-1">
                    <h2 class="text-lg font-black text-[#004d4d]" id="up-username">@User</h2>
                    <p class="text-[9px] font-black text-cyan-600 uppercase mt-0.5" id="up-sport"></p>
                    <p class="text-[9px] text-gray-400 font-bold mt-0.5" id="up-city"></p>
                    <div class="flex gap-4 mt-2">
                        <div class="text-center"><span class="block font-black text-xs" id="up-followers">0</span><span class="text-[7px] font-bold text-gray-500 uppercase">Follower</span></div>
                        <div class="text-center"><span class="block font-black text-xs text-[#008B8B]" id="up-trofei">0</span><span class="text-[7px] font-bold text-[#008B8B] uppercase">Trofei</span></div>
                    </div>
                </div>
            </div>
            <!-- Tasti azione -->
            <div class="flex gap-2 mt-4">
                <button id="up-follow-btn" onclick="toggleFollowUser()" class="flex-1 bg-black text-white py-2.5 rounded-2xl font-black text-[10px] uppercase tracking-wide">
                    + Segui
                </button>
                <button onclick="openChallengeSport(currentUserProfileUser, currentUserProfileSport)" class="flex-1 bg-black text-[#00F5FF] py-2.5 rounded-2xl font-black text-[10px] uppercase tracking-wide flex items-center justify-center gap-1.5">
                    <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="2" y1="2" x2="22" y2="22"/><line x1="22" y1="2" x2="2" y2="22"/><line x1="2" y1="5" x2="5" y2="2"/><line x1="19" y1="22" x2="22" y2="19"/></svg> Sfida
                </button>
                <button onclick="openChatMatch(currentUserProfileUser, currentUserProfileSport)" class="w-11 h-10 bg-white rounded-2xl border border-gray-200 flex items-center justify-center flex-shrink-0">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#008B8B" stroke-width="2.5"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/></svg>
                </button>
            </div>
        </div>
        <!-- Griglia post utente -->
        <div class="grid grid-cols-3 gap-1 p-1 mt-1" id="up-grid"></div>
    </div>

    <!-- PAGINA FOLLOWER / SEGUITI / TROFEI -->
    <div id="page-users">
        <!-- Header -->
        <div class="sticky top-0 z-10 px-5 pt-5 pb-0" style="background:#0a0a0a">
            <div class="flex items-center gap-3 mb-4">
                <button onclick="closeUsersPage()" class="w-9 h-9 flex items-center justify-center rounded-full" style="background:rgba(255,255,255,0.08)">
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2.5"><polyline points="15 18 9 12 15 6"/></svg>
                </button>
                <h3 class="text-white font-black text-base uppercase tracking-widest flex-1" id="users-page-title">Follower</h3>
                <span class="text-[10px] font-black uppercase text-white/30" id="users-page-count"></span>
            </div>
            <!-- Tab switcher -->
            <div class="flex border-b border-white/10" id="users-tabs">
                <button class="users-tab-btn active" onclick="switchUsersTab('follower')">Follower</button>
                <button class="users-tab-btn" onclick="switchUsersTab('seguiti')">Seguiti</button>
                <button class="users-tab-btn" onclick="switchUsersTab('trofei')">Trofei</button>
            </div>
        </div>
        <!-- Lista -->
        <div id="users-list" class="px-4 pt-4"></div>
    </div>

    <!-- POST VIEWER MODERNO -->
    <div id="post-viewer" class="hidden fixed inset-0 z-[5000] flex flex-col" style="background:#000; transform: translateY(100%); transition: transform 0.35s cubic-bezier(0.4,0,0.2,1);">
        <!-- Header -->
        <div class="flex items-center gap-3 px-4 py-3 border-b border-white/10">
            <button onclick="closeLightbox()" class="text-white/60 mr-1">
                <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="15 18 9 12 15 6"/></svg>
            </button>
            <img id="pv-avatar" src="" class="w-9 h-9 rounded-full border-2 border-cyan-400 object-cover">
            <div class="flex-1">
                <p class="text-white font-black text-xs" id="pv-username"></p>
                <p class="text-[#00F5FF] text-[9px] font-black uppercase" id="pv-sport"></p>
            </div>
            <button onclick="sharePost(pvUser, pvSport)" class="text-white/40">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="18" cy="5" r="3"/><circle cx="6" cy="12" r="3"/><circle cx="18" cy="19" r="3"/><line x1="8.59" y1="13.51" x2="15.42" y2="17.49"/><line x1="15.41" y1="6.51" x2="8.59" y2="10.49"/></svg>
            </button>
        </div>

        <!-- Immagine -->
        <div class="flex-1 flex items-center justify-center overflow-hidden bg-black" style="max-height:55vh">
            <img id="pv-img" src="" class="max-w-full max-h-full object-contain">
        </div>

        <!-- Azioni like/commento -->
        <div class="px-4 pt-3 pb-2 flex items-center gap-5">
            <button class="flex items-center gap-1.5 pv-like-btn" onclick="togglePvLike(this)">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" class="pv-like-icon"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l8.78-8.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
                <span class="text-white font-black text-sm pv-like-count">0</span>
            </button>
            <button onclick="focusPvComment()">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/></svg>
            </button>
        </div>

        <!-- Commenti -->
        <div class="flex-1 overflow-y-auto px-4 pb-2 space-y-3" id="pv-comments-list" style="max-height: 30vh"></div>

        <!-- Input commento -->
        <div class="flex items-center gap-3 px-4 py-3 border-t border-white/10">
            <img src="https://i.pravatar.cc/150?u=myuser" id="pv-my-avatar" class="w-8 h-8 rounded-full border border-cyan-400 object-cover flex-shrink-0">
            <input id="pv-comment-input" type="text" placeholder="Aggiungi un commento…"
                class="flex-1 bg-white/5 border border-white/10 rounded-full px-4 py-2 text-white text-xs font-bold outline-none focus:border-cyan-400 transition-colors"
                onkeydown="if(event.key==='Enter') sendPvComment()">
            <button onclick="sendPvComment()" class="text-[#00F5FF] font-black text-xs uppercase">Invia</button>
        </div>
    </div>

    <!-- MODAL SFIDA RICEVUTA -->
    <div id="challenge-request">
        <div class="flex items-center gap-4 mb-4">
            <div class="w-12 h-12 bg-cyan-400 rounded-full overflow-hidden" id="challenger-img"></div>
            <div>
                <p class="text-[10px] font-black uppercase text-cyan-400">Nuova Sfida Ricevuta!</p>
                <p class="text-sm font-bold" id="challenger-name">@User</p>
            </div>
        </div>
        <div class="flex gap-2">
            <button onclick="acceptChallenge()" class="flex-1 bg-white text-black py-3 rounded-xl font-black uppercase text-[10px]">Accetta</button>
            <button onclick="ignoreChallenge()" class="flex-1 bg-white/10 text-white py-3 rounded-xl font-black uppercase text-[10px]">Ignora</button>
        </div>
    </div>

    <!-- SIDEBAR -->
    <div id="sidebar" class="flex">
        <div id="sidebar-content" class="w-4/5 h-full p-8 shadow-2xl overflow-y-auto">
            <!-- Logo identico alla home -->
            <div class="flex items-baseline mb-10 border-b border-white/10 pb-6">
                <div class="flex items-baseline logo-gradient">
                    <span class="text-2xl font-black italic uppercase mr-0.5">Fit</span>
                    <span class="text-3xl font-disney">Gram</span>
                </div>
            </div>
            <nav class="space-y-1">
                <div class="sidebar-nav-label px-2 mb-3">Menu</div>
                <div onclick="switchPage('profile'); toggleSidebar()" class="sidebar-nav-item flex items-center gap-3 text-white cursor-pointer px-3 py-3 rounded-2xl hover:bg-white/5 transition-colors">
                    <span class="w-8 h-8 rounded-xl flex items-center justify-center" style="background:rgba(0,245,255,0.08)">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
                    </span>
                    Profilo Atleta
                </div>
                <div onclick="alert('PRO Attivo')" class="sidebar-nav-item flex items-center gap-3 cursor-pointer px-3 py-3 rounded-2xl hover:bg-white/5 transition-colors" style="color:#00F5FF">
                    <span class="w-8 h-8 rounded-xl flex items-center justify-center" style="background:rgba(0,245,255,0.08)">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
                    </span>
                    FitGram Premium
                </div>
                <div class="sidebar-nav-label px-2 mt-6 mb-3">Impostazioni</div>
                <div class="sidebar-nav-item flex items-center gap-3 text-white/60 cursor-pointer px-3 py-3 rounded-2xl hover:bg-white/5 transition-colors">
                    <span class="w-8 h-8 rounded-xl flex items-center justify-center" style="background:rgba(0,245,255,0.05)">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
                    </span>
                    Notifiche
                </div>
                <div class="sidebar-nav-item flex items-center gap-3 text-white/60 cursor-pointer px-3 py-3 rounded-2xl hover:bg-white/5 transition-colors">
                    <span class="w-8 h-8 rounded-xl flex items-center justify-center" style="background:rgba(0,245,255,0.05)">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
                    </span>
                    Privacy
                </div>
                <div onclick="location.reload()" class="sidebar-nav-item flex items-center gap-3 cursor-pointer px-3 py-3 rounded-2xl hover:bg-red-500/10 transition-colors mt-6" style="color:#ef4444">
                    <span class="w-8 h-8 rounded-xl flex items-center justify-center" style="background:rgba(239,68,68,0.08)">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#ef4444" stroke-width="2"><path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"/><polyline points="16 17 21 12 16 7"/><line x1="21" y1="12" x2="9" y2="12"/></svg>
                    </span>
                    Disconnetti
                </div>
            </nav>
        </div>
        <div class="w-1/5 bg-black/40 backdrop-blur-sm" onclick="toggleSidebar()"></div>
    </div>

    <!-- HEADER -->
    <header class="sticky top-0 z-50 glass-header p-4 flex justify-between items-center h-20">
        <button onclick="toggleSidebar()"><svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#008B8B" stroke-width="2.5"><line x1="3" y1="12" x2="21" y2="12"></line><line x1="3" y1="6" x2="21" y2="6"></line><line x1="3" y1="18" x2="15" y2="18"></line></svg></button>
        <div class="absolute inset-0 flex items-center justify-center pointer-events-none">
            <div class="flex items-baseline logo-gradient"><span class="text-2xl font-black italic uppercase mr-0.5">Fit</span><span class="text-3xl font-disney text-black">Gram</span></div>
        </div>
        <div class="flex items-center gap-3">
            <button onclick="toggleNotifications()" class="relative">
                <svg width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="#008B8B" stroke-width="2.5"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
                <span id="notif-dot" class="absolute -top-1 -right-1 w-3 h-3 bg-red-500 rounded-full border-2 border-white hidden"></span>
            </button>
            <button onclick="switchPage('chat')" class="relative">
                <svg width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="#008B8B" stroke-width="2.5"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"></path></svg>
                <span id="chat-dot" class="absolute -top-1 -right-1 w-3 h-3 bg-red-500 rounded-full border-2 border-white hidden"></span>
            </button>
        </div>
    </header>

    <!-- PANNELLO NOTIFICHE -->
    <div id="notif-panel" style="position:fixed;top:76px;right:12px;width:300px;max-height:420px;overflow-y:auto;background:#fff;border-radius:20px;box-shadow:0 8px 40px rgba(0,0,0,.18);border:1px solid rgba(0,139,139,.1);z-index:300;display:none;flex-direction:column;animation:fadeInUp .2s ease">
        <div style="padding:14px 16px 10px;display:flex;align-items:center;justify-content:space-between;border-bottom:1px solid rgba(0,0,0,.06);position:sticky;top:0;background:#fff;border-radius:20px 20px 0 0">
            <span style="font-weight:900;font-size:13px;color:#004d4d">Notifiche</span>
            <button onclick="clearNotifications()" style="font-size:10px;font-weight:700;color:#008B8B;background:none;border:none;cursor:pointer;text-transform:uppercase;letter-spacing:.05em">Lette ✓</button>
        </div>
        <div id="notif-list" style="padding:6px 0">
            <p id="notif-empty" style="text-align:center;padding:28px 16px;color:rgba(0,0,0,.3);font-size:12px;font-weight:600">Nessuna notifica</p>
        </div>
    </div>

    <!-- PAGE HOME -->
    <div id="page-home" class="page-content">
        <div class="flex gap-4 p-4 overflow-x-auto no-scrollbar" id="stories-container">
            <div class="flex flex-col items-center gap-1">
                <div class="story-circle border-dashed border-gray-400 flex items-center justify-center cursor-pointer" onclick="toggleCreateModal()"><span class="text-2xl text-black font-bold">+</span></div>
                <span class="text-[9px] font-black uppercase text-gray-600">La tua Storia</span>
            </div>
        </div>
        <div id="feed-container" class="p-4 space-y-6"></div>
    </div>

    <!-- PAGE SEARCH / RADAR -->
    <div id="page-search" class="hidden page-content p-5">
        <!-- Tab: Radar / Cerca Utenti -->
        <div class="flex gap-2 mb-5 bg-white/40 p-1 rounded-2xl">
            <button onclick="switchSearchTab('radar')" id="stab-radar" class="flex-1 py-2 rounded-xl text-[10px] font-black uppercase tracking-wide transition-all bg-black text-[#00F5FF]">📡 Radar</button>
            <button onclick="switchSearchTab('cerca')" id="stab-cerca" class="flex-1 py-2 rounded-xl text-[10px] font-black uppercase tracking-wide transition-all text-[#004d4d]">🔍 Cerca</button>
        </div>

        <!-- TAB RADAR -->
        <div id="search-tab-radar">
            <h2 class="text-2xl font-black italic mb-1 text-[#004d4d]">RADAR ATLETI</h2>
            <p class="text-[10px] font-bold text-gray-400 uppercase mb-4">Cerca atleti per città</p>

        <!-- Filtro città -->
        <div class="relative mb-4">
            <div class="flex items-center gap-2 bg-white rounded-2xl px-4 py-3 shadow-sm border border-[#008B8B]/20 cursor-pointer" onclick="toggleCityList()">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#008B8B" stroke-width="2.5"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
                <span class="flex-1 font-black text-sm text-[#004d4d]" id="city-selected-label">Tutte le città</span>
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#008B8B" stroke-width="2"><polyline points="6 9 12 15 18 9"/></svg>
            </div>
            <!-- Dropdown città -->
            <div id="city-dropdown" class="hidden absolute top-full left-0 right-0 mt-2 bg-white rounded-2xl shadow-xl border border-gray-100 z-50 max-h-56 overflow-y-auto">
                <div class="sticky top-0 bg-white px-3 pt-3 pb-2 border-b border-gray-100">
                    <input id="city-search-input" type="text" placeholder="Cerca città…" oninput="filterCityList(this.value)"
                        class="w-full border border-gray-200 rounded-xl px-3 py-2 text-xs font-bold outline-none focus:border-cyan-400">
                </div>
                <div id="city-list-items"></div>
            </div>
        </div>

        <!-- Radar animato + badge città -->
        <div class="relative w-full aspect-square bg-white/40 rounded-full border-4 border-[#008B8B]/20 flex items-center justify-center overflow-hidden mb-5">
            <div class="radar-line"></div>
            <div class="absolute inset-0 flex items-center justify-center pointer-events-none">
                <span id="radar-city-badge" class="text-[10px] font-black text-[#004d4d]/40 uppercase tracking-widest"></span>
            </div>
            <!-- Blip animati -->
            <div id="radar-blips"></div>
        </div>

        <!-- Lista atleti filtrati -->
        <div id="radar-athletes" class="space-y-3"></div>
        </div><!-- end search-tab-radar -->

        <!-- TAB CERCA UTENTI -->
        <div id="search-tab-cerca" class="hidden">
            <div class="relative mb-4">
                <input id="user-search-input" type="text" placeholder="Cerca per nome o sport…" oninput="searchUsers(this.value)"
                    class="w-full bg-white rounded-2xl px-4 py-3 pr-10 font-bold text-sm shadow-sm border border-[#008B8B]/20 outline-none focus:border-[#008B8B]">
                <svg class="absolute right-4 top-3.5" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#008B8B" stroke-width="2.5"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg>
            </div>
            <!-- Filtro sport -->
            <div class="flex gap-2 overflow-x-auto no-scrollbar mb-4 pb-1">
                <button onclick="filterBySport('')" class="search-sport-tag active flex-shrink-0 px-3 py-1.5 rounded-full text-[10px] font-black uppercase bg-black text-[#00F5FF]">Tutti</button>
                <button onclick="filterBySport('Boxe')" class="search-sport-tag flex-shrink-0 px-3 py-1.5 rounded-full text-[10px] font-black uppercase bg-white text-[#004d4d] border border-gray-200">🥊 Boxe</button>
                <button onclick="filterBySport('Running')" class="search-sport-tag flex-shrink-0 px-3 py-1.5 rounded-full text-[10px] font-black uppercase bg-white text-[#004d4d] border border-gray-200">🏃 Running</button>
                <button onclick="filterBySport('Powerlifting')" class="search-sport-tag flex-shrink-0 px-3 py-1.5 rounded-full text-[10px] font-black uppercase bg-white text-[#004d4d] border border-gray-200">🏋️ Lifting</button>
                <button onclick="filterBySport('MMA')" class="search-sport-tag flex-shrink-0 px-3 py-1.5 rounded-full text-[10px] font-black uppercase bg-white text-[#004d4d] border border-gray-200">🥋 MMA</button>
                <button onclick="filterBySport('Nuoto')" class="search-sport-tag flex-shrink-0 px-3 py-1.5 rounded-full text-[10px] font-black uppercase bg-white text-[#004d4d] border border-gray-200">🏊 Nuoto</button>
            </div>
            <div id="user-search-results" class="space-y-3"></div>
        </div>
    </div>

    <!-- PAGE RANKING -->
    <div id="page-ranking" class="hidden page-content p-6">
        <h2 class="text-2xl font-black italic mb-5 text-[#004d4d]">CLASSIFICHE 🏆</h2>
        <!-- Tab selector -->
        <div class="flex gap-2 mb-5 bg-white/40 p-1 rounded-2xl">
            <button onclick="switchRankTab('amici')" id="tab-amici" class="flex-1 py-2 rounded-xl text-[10px] font-black uppercase tracking-wide transition-all bg-black text-[#00F5FF]">Amici</button>
            <button onclick="switchRankTab('nazionali')" id="tab-nazionali" class="flex-1 py-2 rounded-xl text-[10px] font-black uppercase tracking-wide transition-all text-[#004d4d]">Nazionali</button>
            <button onclick="switchRankTab('mondiali')" id="tab-mondiali" class="flex-1 py-2 rounded-xl text-[10px] font-black uppercase tracking-wide transition-all text-[#004d4d]">Mondiali</button>
        </div>
        <div id="rank-list" class="space-y-4"></div>
    </div>

    <!-- PAGE CHAT -->
    <div id="page-chat" class="hidden page-content p-5">
        <h2 class="text-2xl font-black italic mb-5 text-[#004d4d]">MESSAGGI</h2>
        <div id="active-chats" class="space-y-3">
            <p class="text-gray-400 text-[10px] uppercase font-bold mt-10 text-center">Nessuna conversazione attiva</p>
        </div>
    </div>

    <!-- PAGE PROFILE -->
    <div id="page-profile" class="hidden page-content">
        <div class="p-6 bg-white/30 rounded-b-[3rem] border-b border-[#008B8B]/10">
            <div class="flex items-start gap-6">
                <div class="w-24 h-24 rounded-full border-4 border-cyan-400 p-1 bg-white overflow-hidden relative cursor-pointer" onclick="openAvatarPicker()">
                    <img id="profile-img" src="https://i.pravatar.cc/150?u=myuser" class="w-full h-full object-cover rounded-full">
                    <div class="absolute inset-0 bg-black/30 rounded-full flex items-center justify-center opacity-0 hover:opacity-100 transition-opacity">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
                    </div>
                </div>
                <input type="file" id="avatar-input" class="hidden" accept="image/*" onchange="updateProfilePhoto(this)">
                <input type="file" id="avatar-camera-input" class="hidden" accept="image/*" capture="user" onchange="updateProfilePhoto(this)">
                <div class="flex-1">
                    <h2 class="text-xl font-black text-[#004d4d]" id="profile-username">Il tuo profilo</h2>
                    <p id="profile-sport-badge" class="text-[9px] font-black uppercase text-cyan-600 mt-0.5 hidden"></p>
                    <p id="profile-city-badge" class="text-[9px] font-bold text-gray-400 mt-0.5 hidden"></p>
                    <div class="flex gap-4 mt-2">
                        <div class="text-center cursor-pointer" onclick="openUsersPage('follower')">
                            <span class="block font-black text-xs" id="my-follower-count">0</span>
                            <span class="text-[7px] font-bold text-gray-500 uppercase">Follower</span>
                        </div>
                        <div class="text-center cursor-pointer" onclick="openUsersPage('seguiti')">
                            <span class="block font-black text-xs" id="my-seguiti-count">0</span>
                            <span class="text-[7px] font-bold text-gray-500 uppercase">Seguiti</span>
                        </div>
                        <div id="my-trophy-display" class="text-center cursor-pointer" onclick="openUsersPage('trofei')">
                            <span class="block font-black text-xs text-[#008B8B]" id="my-trofei-count">0</span>
                            <span class="text-[7px] font-bold text-[#008B8B] uppercase">Trofei</span>
                        </div>
                    </div>
                    <!-- Tasto Segui sotto le stats -->
                    <button id="my-follow-btn" onclick="toggleMyFollow()" class="mt-3 flex items-center gap-1.5 border-2 border-[#008B8B] text-[#008B8B] rounded-full px-4 py-1.5 text-[9px] font-black uppercase tracking-wide transition-all">
                        + Segui
                    </button>
                </div>
                <button onclick="doLogout()" title="Esci" style="flex-shrink:0;width:32px;height:32px;display:flex;align-items:center;justify-content:center;border-radius:50%;border:2px solid #fca5a5;color:#f87171;background:transparent;cursor:pointer"><svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"/><polyline points="16 17 21 12 16 7"/><line x1="21" y1="12" x2="9" y2="12"/></svg></button>
                <!-- TASTO MODIFICA -->
                <button onclick="openEditProfile()" class="flex-shrink-0 flex items-center gap-1.5 border-2 border-[#008B8B] text-[#008B8B] rounded-full px-3 py-1.5 text-[9px] font-black uppercase tracking-wide">
                    <svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3"><path d="M11 4H4a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7"></path><path d="M18.5 2.5a2.121 2.121 0 0 1 3 3L12 15l-4 1 1-4 9.5-9.5z"></path></svg>
                    Modifica
                </button>
            </div>
            <!-- BIO -->
            <p id="profile-bio" class="text-xs text-gray-500 mt-4 leading-relaxed hidden"></p>
        </div>
        <div class="grid grid-cols-3 gap-1 p-1 mt-4" id="profile-grid"></div>

        <!-- STATISTICHE PERSONALI -->
        <div class="p-5 mt-2">
            <h3 class="text-sm font-black uppercase text-[#004d4d] mb-3 italic">📊 Le tue statistiche</h3>
            <div class="grid grid-cols-2 gap-3">
                <div class="bg-white/60 rounded-2xl p-4 border border-[#008B8B]/10">
                    <p class="text-2xl font-black text-[#004d4d]" id="stat-sfide">0</p>
                    <p class="text-[9px] font-black uppercase text-gray-400 mt-0.5">Sfide lanciate</p>
                </div>
                <div class="bg-white/60 rounded-2xl p-4 border border-[#008B8B]/10">
                    <p class="text-2xl font-black text-[#00F5FF]" id="stat-vittorie">0</p>
                    <p class="text-[9px] font-black uppercase text-gray-400 mt-0.5">Vittorie</p>
                </div>
                <div class="bg-white/60 rounded-2xl p-4 border border-[#008B8B]/10">
                    <p class="text-2xl font-black text-[#004d4d]" id="stat-winrate">—</p>
                    <p class="text-[9px] font-black uppercase text-gray-400 mt-0.5">Win rate</p>
                </div>
                <div class="bg-black rounded-2xl p-4">
                    <p class="text-2xl font-black text-[#00F5FF]" id="stat-trofei-profile">0</p>
                    <p class="text-[9px] font-black uppercase text-[#00F5FF]/50 mt-0.5">Trofei totali</p>
                </div>
            </div>
        </div>
    </div>

    <!-- CTA SFIDA FISSA (visibile solo su pagina profilo) -->
    <div id="profile-cta">
        <button onclick="openChallengeSport()" class="w-full bg-black text-[#00F5FF] py-4 rounded-2xl font-black uppercase text-sm tracking-widest shadow-2xl flex items-center justify-center gap-3" style="box-shadow: 0 0 30px rgba(0,245,255,0.35);">
            <span style="font-size:18px; display:inline-flex; align-items:center;">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="2" y1="2" x2="22" y2="22"/><line x1="22" y1="2" x2="2" y2="22"/><line x1="2" y1="5" x2="5" y2="2"/><line x1="19" y1="22" x2="22" y2="19"/></svg>
            </span> Lancia una Sfida
        </button>    </div>

    <!-- MODAL SCELTA FOTO PROFILO -->
    <div id="avatar-picker" class="hidden fixed inset-0 bg-black/50 backdrop-blur-sm z-[6000] flex items-end">
        <div class="w-full bg-white rounded-t-3xl p-6 animate-[slideUp_0.3s_ease]">
            <div class="w-10 h-1 bg-gray-300 rounded-full mx-auto mb-5"></div>
            <p class="text-[10px] font-black uppercase text-gray-400 tracking-widest mb-4">Cambia foto profilo</p>
            <div class="space-y-3">
                <button onclick="pickAvatar('camera')" class="w-full flex items-center gap-4 p-4 rounded-2xl bg-gray-50 hover:bg-gray-100 transition-colors">
                    <span class="w-10 h-10 rounded-xl bg-black flex items-center justify-center flex-shrink-0">
                        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2" stroke-linecap="round"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
                    </span>
                    <div class="text-left">
                        <p class="font-black text-sm">Scatta una foto</p>
                        <p class="text-[10px] text-gray-400 font-bold">Usa la fotocamera</p>
                    </div>
                </button>
                <button onclick="pickAvatar('gallery')" class="w-full flex items-center gap-4 p-4 rounded-2xl bg-gray-50 hover:bg-gray-100 transition-colors">
                    <span class="w-10 h-10 rounded-xl bg-black flex items-center justify-center flex-shrink-0">
                        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2" stroke-linecap="round"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.5"/><polyline points="21 15 16 10 5 21"/></svg>
                    </span>
                    <div class="text-left">
                        <p class="font-black text-sm">Scegli dalla galleria</p>
                        <p class="text-[10px] text-gray-400 font-bold">Carica dal dispositivo</p>
                    </div>
                </button>
            </div>
            <button onclick="closeAvatarPicker()" class="w-full mt-4 py-3 rounded-2xl bg-gray-100 text-gray-500 font-black text-xs uppercase tracking-wide">Annulla</button>
        </div>
    </div>

    <!-- MODAL CREA POST -->
    <div id="create-modal" class="hidden fixed inset-0 z-[2000] flex flex-col" style="background:#000">
        <!-- Header -->
        <div class="flex items-center justify-between px-5 py-4 border-b border-white/10">
            <button onclick="toggleCreateModal()" class="text-white/60">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>
            </button>
            <span class="text-white font-black text-sm uppercase tracking-widest">Nuovo post</span>
            <button onclick="publishNew()" class="text-[#00F5FF] font-black text-sm uppercase tracking-wide">Pubblica</button>
        </div>

        <!-- Anteprima media -->
        <div class="relative flex-1 bg-black flex items-center justify-center overflow-hidden" style="max-height:55vh">
            <div id="create-preview" class="w-full h-full flex items-center justify-center">
                <!-- Placeholder -->
                <div class="flex flex-col items-center gap-3 text-white/20">
                    <svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
                    <p class="text-xs font-bold uppercase tracking-widest">Nessun media selezionato</p>
                </div>
            </div>
        </div>

        <!-- Tab tipo contenuto -->
        <div class="flex border-b border-white/10">
            <button onclick="setCreateTab('post')" id="ctab-post" class="flex-1 py-3 text-[10px] font-black uppercase tracking-widest text-[#00F5FF] border-b-2 border-[#00F5FF]">
                📸 Foto
            </button>
            <button onclick="setCreateTab('video')" id="ctab-video" class="flex-1 py-3 text-[10px] font-black uppercase tracking-widest text-white/40">
                🎬 Video
            </button>
            <button onclick="setCreateTab('reel')" id="ctab-reel" class="flex-1 py-3 text-[10px] font-black uppercase tracking-widest text-white/40">
                🎞️ Reel
            </button>
        </div>

        <!-- Azioni -->
        <div class="p-5 space-y-3 bg-black">
            <!-- Scatta/registra -->
            <button onclick="openCreateCamera()" class="w-full flex items-center gap-4 p-4 rounded-2xl bg-white/5 border border-white/10 active:bg-white/10 transition-colors">
                <span class="w-10 h-10 rounded-xl bg-[#00F5FF]/10 border border-[#00F5FF]/20 flex items-center justify-center flex-shrink-0">
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
                </span>
                <div class="text-left">
                    <p class="text-white font-black text-sm" id="camera-btn-label">Scatta una foto</p>
                    <p class="text-white/40 text-[10px] font-bold">Usa la fotocamera</p>
                </div>
                <svg class="ml-auto" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" opacity="0.3"><polyline points="9 18 15 12 9 6"/></svg>
            </button>

            <!-- Galleria -->
            <button onclick="openCreateGallery()" class="w-full flex items-center gap-4 p-4 rounded-2xl bg-white/5 border border-white/10 active:bg-white/10 transition-colors">
                <span class="w-10 h-10 rounded-xl bg-[#00F5FF]/10 border border-[#00F5FF]/20 flex items-center justify-center flex-shrink-0">
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2"><rect x="3" y="3" width="18" height="18" rx="2"/><circle cx="8.5" cy="8.5" r="1.5"/><polyline points="21 15 16 10 5 21"/></svg>
                </span>
                <div class="text-left">
                    <p class="text-white font-black text-sm" id="gallery-btn-label">Scegli dalla galleria</p>
                    <p class="text-white/40 text-[10px] font-bold">Foto e video salvati</p>
                </div>
                <svg class="ml-auto" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" opacity="0.3"><polyline points="9 18 15 12 9 6"/></svg>
            </button>

            <!-- Storia -->
            <button onclick="publishNew('story')" class="w-full flex items-center gap-4 p-4 rounded-2xl bg-white/5 border border-white/10 active:bg-white/10 transition-colors">
                <span class="w-10 h-10 rounded-xl bg-[#00F5FF]/10 border border-[#00F5FF]/20 flex items-center justify-center flex-shrink-0">
                    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2"><circle cx="12" cy="12" r="9"/><circle cx="12" cy="12" r="3"/></svg>
                </span>
                <div class="text-left">
                    <p class="text-white font-black text-sm">Aggiungi alla storia</p>
                    <p class="text-white/40 text-[10px] font-bold">Visibile per 24 ore</p>
                </div>
                <svg class="ml-auto" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" opacity="0.3"><polyline points="9 18 15 12 9 6"/></svg>
            </button>
        </div>

        <!-- Input file nascosti -->
        <input type="file" id="create-file-photo" class="hidden" accept="image/*" onchange="previewCreateFile(this,'post')">
        <input type="file" id="create-file-video" class="hidden" accept="video/*" onchange="previewCreateFile(this,'video')">
        <input type="file" id="create-file-reel"  class="hidden" accept="video/*" onchange="previewCreateFile(this,'reel')">
        <input type="file" id="create-camera-photo" class="hidden" accept="image/*" capture="environment" onchange="previewCreateFile(this,'post')">
        <input type="file" id="create-camera-video" class="hidden" accept="video/*" capture="environment" onchange="previewCreateFile(this,'video')">
        <input type="file" id="post-input" class="hidden" onchange="previewNewPost(this)">
    </div>

    <!-- MODAL MODIFICA PROFILO -->
    <div id="edit-profile-modal" class="hidden">
        <div id="edit-profile-sheet">
            <!-- Handle -->
            <div class="w-10 h-1 rounded-full mx-auto mb-5" style="background:rgba(255,255,255,0.15)"></div>
            <!-- Header -->
            <div class="flex justify-between items-center mb-6">
                <h3 class="text-white font-black text-base uppercase tracking-widest">Modifica profilo</h3>
                <button onclick="closeEditProfile()" style="color:rgba(255,255,255,0.3)">
                    <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg>
                </button>
            </div>

            <!-- Avatar -->
            <div class="flex items-center gap-4 mb-6 pb-6" style="border-bottom:1px solid rgba(255,255,255,0.07)">
                <div class="relative cursor-pointer" onclick="openAvatarPicker()">
                    <img id="edit-avatar-preview" src="https://i.pravatar.cc/150?u=myuser" class="w-16 h-16 rounded-full object-cover border-2 border-cyan-400">
                    <span class="absolute inset-0 rounded-full flex items-center justify-center" style="background:rgba(0,0,0,0.4)">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
                    </span>
                </div>
                <div>
                    <p class="text-white font-black text-sm" id="edit-avatar-label">Cambia foto</p>
                    <p class="text-[10px] font-bold" style="color:rgba(255,255,255,0.3)">Tocca per modificare</p>
                </div>
            </div>

            <div class="space-y-5">
                <!-- Username -->
                <div>
                    <label class="edit-label">Username</label>
                    <input id="edit-username" class="edit-input" type="text" placeholder="tuousername" value="Atleta_PRO">
                </div>
                <!-- Sport preferito -->
                <div>
                    <label class="edit-label">Sport preferito</label>
                    <div class="flex flex-wrap gap-2 mt-1" id="sport-pills">
                        <span class="sport-pill" onclick="selectSport(this)">Boxe</span>
                        <span class="sport-pill" onclick="selectSport(this)">Powerlifting</span>
                        <span class="sport-pill" onclick="selectSport(this)">Running</span>
                        <span class="sport-pill" onclick="selectSport(this)">Calcio</span>
                        <span class="sport-pill" onclick="selectSport(this)">Nuoto</span>
                        <span class="sport-pill" onclick="selectSport(this)">Ciclismo</span>
                        <span class="sport-pill" onclick="selectSport(this)">Yoga</span>
                        <span class="sport-pill" onclick="selectSport(this)">MMA</span>
                        <span class="sport-pill" onclick="selectSport(this)">Tennis</span>
                        <span class="sport-pill" onclick="selectSport(this)">Basket</span>
                        <span class="sport-pill" onclick="selectSport(this)">Ping Pong</span>
                        <span class="sport-pill" onclick="selectSport(this)">Scacchi</span>
                        <span class="sport-pill" onclick="selectSport(this)">Bowling</span>
                        <span class="sport-pill" onclick="selectSport(this)">Freccette</span>
                        <span class="sport-pill" onclick="selectSport(this)">Braccio di ferro</span>
                        <span class="sport-pill" onclick="selectSport(this)">Biliardo</span>
                        <span class="sport-pill" onclick="selectSport(this)">Danza</span>
                        <span class="sport-pill" onclick="selectSport(this)">Parkour</span>
                        <span class="sport-pill" onclick="selectSport(this)">Skateboard</span>
                        <span class="sport-pill" onclick="selectSport(this)">Surf</span>
                        <span class="sport-pill" onclick="selectSport(this)">Arrampicata</span>
                        <span class="sport-pill" onclick="selectSport(this)">Tiro con l'arco</span>
                        <span class="sport-pill" onclick="selectSport(this)">Golf</span>
                        <span class="sport-pill" onclick="selectSport(this)">Pallavolo</span>
                        <span class="sport-pill" onclick="selectSport(this)">Rugby</span>
                    </div>
                    <div class="flex gap-2 mt-3">
                        <input id="custom-sport-input" class="edit-input flex-1" type="text" placeholder="Altro sport non in lista…"
                            oninput="syncCustomSport(this.value)">
                    </div>
                </div>
                <!-- Città -->
                <div>
                    <label class="edit-label">Città</label>
                    <input id="edit-city" class="edit-input" type="text" placeholder="Es. Roma, Milano...">
                </div>
                <!-- Bio -->
                <div>
                    <label class="edit-label">Bio</label>
                    <textarea id="edit-bio" class="edit-input resize-none" rows="3" placeholder="Scrivi qualcosa su di te..."></textarea>
                </div>

                <!-- Impostazioni visibilità -->
                <div class="pt-2 pb-1" style="border-top:1px solid rgba(255,255,255,0.07)">
                    <p class="edit-label mb-4">Visibilità</p>

                    <!-- Toggle tasto sfida profilo -->
                    <div class="flex items-center justify-between py-3" style="border-bottom:1px solid rgba(255,255,255,0.05)">
                        <div>
                            <p class="text-white font-black text-xs">Tasto Sfida sul profilo</p>
                            <p class="text-[9px] font-bold mt-0.5" style="color:rgba(255,255,255,0.3)">Mostra il tasto ⚔️ Lancia una Sfida</p>
                        </div>
                        <label class="toggle-switch">
                            <input type="checkbox" id="toggle-challenge-profile" checked onchange="toggleChallengeVisibility('profile', this.checked)">
                            <span class="toggle-track"></span>
                        </label>
                    </div>

                    <!-- Toggle tasto sfida sui post -->
                    <div class="flex items-center justify-between py-3">
                        <div>
                            <p class="text-white font-black text-xs">Tasto Sfida sui post</p>
                            <p class="text-[9px] font-bold mt-0.5" style="color:rgba(255,255,255,0.3)">Mostra Sfida ⚔️ accanto ai post</p>
                        </div>
                        <label class="toggle-switch">
                            <input type="checkbox" id="toggle-challenge-posts" checked onchange="toggleChallengeVisibility('posts', this.checked)">
                            <span class="toggle-track"></span>
                        </label>
                    </div>
                </div>

                <!-- Salva -->
                <button onclick="saveProfile()" class="w-full py-4 rounded-2xl font-black uppercase text-xs tracking-widest" style="background:#00F5FF;color:#000;">
                    Salva modifiche
                </button>
            </div>
        </div>
    </div>

    <!-- MODAL SFIDA TESTO LIBERO -->
    <div id="challenge-sport-modal" class="hidden">
        <div id="challenge-sport-sheet">
            <div class="w-10 h-1 bg-white/20 rounded-full mx-auto mb-6"></div>
            <div class="flex justify-between items-center mb-2">
                <h3 class="text-lg font-black italic text-[#00F5FF] flex items-center gap-2">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="2" y1="2" x2="22" y2="22"/><line x1="22" y1="2" x2="2" y2="22"/><line x1="2" y1="5" x2="5" y2="2"/><line x1="19" y1="22" x2="22" y2="19"/></svg>
                    LANCIA UNA SFIDA
                </h3>
                <button onclick="closeChallengeSport()" class="text-2xl text-white/40 leading-none">&times;</button>
            </div>
            <p class="text-[10px] font-bold uppercase text-white/30 mb-6" id="challenge-modal-subtitle">Sfida chiunque, in qualsiasi cosa</p>
            <div class="mb-6">
                <p class="text-[10px] font-black uppercase text-white/40 mb-3">In cosa vuoi sfidarmi?</p>
                <input id="challenge-text-input" class="challenge-input" type="text" placeholder="Es. 100m, scacchi, braccio di ferro…" maxlength="60">
            </div>
            <div id="challenge-sport-confirm" class="hidden mb-4">
                <p class="text-[10px] font-black uppercase text-white/40 mb-3">Sfida inviata a:</p>
                <div class="space-y-2" id="challenge-target-list"></div>
            </div>
            <button id="launch-challenge-btn" onclick="launchChallenge()" class="w-full py-4 rounded-2xl font-black uppercase text-[11px] tracking-widest" style="background:#00F5FF;color:#000;">
                Invia Sfida
            </button>
        </div>
    </div>

    <!-- NAV -->
    <nav class="fixed bottom-6 left-6 right-6 h-16 bg-black rounded-full flex justify-around items-center z-[100]">
        <button onclick="switchPage('home')" id="nav-home" class="text-white/40 nav-active"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path></svg></button>
        <button onclick="switchPage('search')" id="nav-search" class="text-white/40"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg></button>
        <button onclick="toggleCreateModal()" class="btn-plus">
                <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="#000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
            </button>
        <button onclick="switchPage('ranking')" id="nav-rank" class="text-white/40"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M6 9H4.5a2.5 2.5 0 0 1 0-5H6M18 9h1.5a2.5 2.5 0 0 0 0-5H18M4 22h16M18 2H6v7a6 6 0 0 0 12 0V2Z"></path></svg></button>
        <button onclick="switchPage('profile')" id="nav-profile" class="w-8 h-8 rounded-full overflow-hidden opacity-40"><img src="https://i.pravatar.cc/150?u=myuser" class="w-full h-full object-cover"></button>
    </nav>

    <script>
        let currentChallenger = "";
        let myTrophies = 24;
        let statSfide = 0, statVittorie = 0;
        let selectedSport = "";
        let selectedChallengeSport = "";
        let challengeTargetUser = null;

        function toggleSidebar() { document.getElementById('sidebar').classList.toggle('open'); }
        let currentCreateTab = 'post';
        let currentCreateFile = null;

        function setCreateTab(tab) {
            currentCreateTab = tab;
            ['post','video','reel'].forEach(t => {
                const btn = document.getElementById('ctab-' + t);
                btn.style.color = t === tab ? '#00F5FF' : 'rgba(255,255,255,0.4)';
                btn.style.borderBottom = t === tab ? '2px solid #00F5FF' : '2px solid transparent';
            });
            const labels = {
                post:  { cam: 'Scatta una foto',    gal: 'Scegli dalla galleria' },
                video: { cam: 'Registra un video',  gal: 'Scegli un video' },
                reel:  { cam: 'Registra un reel',   gal: 'Scegli dalla galleria' },
            };
            document.getElementById('camera-btn-label').innerText  = labels[tab].cam;
            document.getElementById('gallery-btn-label').innerText = labels[tab].gal;
        }

        function openCreateCamera() {
            const id = currentCreateTab === 'post' ? 'create-camera-photo' : 'create-camera-video';
            document.getElementById(id).click();
        }

        function openCreateGallery() {
            const id = currentCreateTab === 'post' ? 'create-file-photo' : currentCreateTab === 'video' ? 'create-file-video' : 'create-file-reel';
            document.getElementById(id).click();
        }

        function previewCreateFile(input, type) {
            if (!input.files || !input.files[0]) return;
            currentCreateFile = { file: input.files[0], type };
            const reader = new FileReader();
            const preview = document.getElementById('create-preview');
            reader.onload = (e) => {
                if (type === 'post') {
                    preview.innerHTML = `<img src="${e.target.result}" class="w-full h-full object-cover">`;
                } else {
                    preview.innerHTML = `<video src="${e.target.result}" class="w-full h-full object-cover" autoplay muted loop playsinline></video>`;
                }
            };
            reader.readAsDataURL(input.files[0]);
        }

        function publishNew(forceType) {
            const preview = document.getElementById('create-preview');
            const img = preview.querySelector('img');
            const vid = preview.querySelector('video');
            const src = img?.src || vid?.src;
            const type = forceType || currentCreateTab;

            if (src && (img || vid)) {
                const username = document.getElementById('profile-username')?.innerText || 'Tu';
                const sport = selectedSport || '🏋️ Fitness';
                if (type === 'story') {
                    document.getElementById('stories-container').insertAdjacentHTML('afterbegin', `
                        <div class="flex flex-col items-center gap-1">
                            <div class="story-circle overflow-hidden relative cursor-pointer">
                                <img src="${src}" class="w-full h-full object-cover">
                            </div>
                            <span class="text-[9px] font-black uppercase text-gray-600">Tua</span>
                        </div>`);
                    switchPage('home');
                    showToast('Storia pubblicata! 📸', 'success');
                } else {
                    // Aggiungi al feed
                    const newPost = buildPost({ user: username, sport: sport, imgUrl: src, comments: [] });
                    const feedContainer = document.getElementById('feed-container');
                    feedContainer.insertAdjacentHTML('afterbegin', newPost);
                    // Aggiungi anche alla griglia profilo
                    document.getElementById('profile-grid').insertAdjacentHTML('afterbegin', `
                        <div class="aspect-square bg-gray-200 overflow-hidden rounded-lg cursor-pointer" onclick="openLightbox('${src}','${sport}','${username}',[])">
                            <img src="${src}" class="w-full h-full object-cover">
                        </div>`);
                    switchPage('home');
                    showToast('Post pubblicato! 🎉', 'success');
                    pushNotification('📸', 'Hai pubblicato un nuovo post!', sport);
                }
            } else {
                showToast('Seleziona una foto prima!', 'error');
                return;
            }
            // Reset preview
            preview.innerHTML = `<div class="flex flex-col items-center gap-3 text-white/20"><svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg><p class="text-xs font-bold uppercase tracking-widest">Nessun media selezionato</p></div>`;
            currentCreateFile = null;
            toggleCreateModal();
        }

        function toggleCreateModal() { document.getElementById('create-modal').classList.toggle('hidden'); }

        // ── SEARCH TAB ──
        function switchSearchTab(tab) {
            document.getElementById('search-tab-radar').classList.toggle('hidden', tab !== 'radar');
            document.getElementById('search-tab-cerca').classList.toggle('hidden', tab !== 'cerca');
            ['radar','cerca'].forEach(t => {
                const btn = document.getElementById('stab-' + t);
                if (t === tab) { btn.style.background='#000'; btn.style.color='#00F5FF'; }
                else { btn.style.background=''; btn.style.color='#004d4d'; }
            });
            if (tab === 'cerca') { searchUsers(''); document.getElementById('user-search-input').focus(); }
        }

        const ALL_SEARCH_USERS = [
            {u:'Trainer_Marco', sport:'🥊 Boxe', city:'Roma', f:412, t:42},
            {u:'Giulia_Fit', sport:'🧘 Yoga', city:'Milano', f:310, t:21},
            {u:'Power_Lift', sport:'🏋️ Powerlifting', city:'Torino', f:290, t:38},
            {u:'SpeedRunner99', sport:'🏃 Running', city:'Roma', f:180, t:17},
            {u:'MilanoFit', sport:'🏋️ Powerlifting', city:'Milano', f:520, t:33},
            {u:'NapoliBoxe', sport:'🥊 Boxe', city:'Napoli', f:290, t:22},
            {u:'KarateGio', sport:'🥋 MMA', city:'Bologna', f:210, t:19},
            {u:'CycloLuca', sport:'🚴 Ciclismo', city:'Firenze', f:175, t:11},
            {u:'IronMax', sport:'🏋️ Powerlifting', city:'Torino', f:340, t:38},
            {u:'AquaMaria', sport:'🏊 Nuoto', city:'Venezia', f:220, t:14},
            {u:'Miky_Power', sport:'🥊 Boxe', city:'Napoli', f:400, t:42},
            {u:'TorinoMMA', sport:'🥋 MMA', city:'Torino', f:195, t:17},
        ];
        let searchSportFilter = '';

        function filterBySport(sport) {
            searchSportFilter = sport;
            document.querySelectorAll('.search-sport-tag').forEach(btn => {
                const isActive = (sport === '' && btn.innerText === 'Tutti') || btn.innerText.includes(sport);
                btn.style.background = isActive ? '#000' : '';
                btn.style.color = isActive ? '#00F5FF' : '';
                btn.style.borderColor = isActive ? '#000' : '';
            });
            searchUsers(document.getElementById('user-search-input').value);
        }

        function searchUsers(query) {
            const q = query.toLowerCase();
            let results = ALL_SEARCH_USERS.filter(u => {
                const matchQ = !q || u.u.toLowerCase().includes(q) || u.sport.toLowerCase().includes(q) || u.city.toLowerCase().includes(q);
                const matchSport = !searchSportFilter || u.sport.includes(searchSportFilter);
                return matchQ && matchSport;
            });
            const container = document.getElementById('user-search-results');
            if (results.length === 0) {
                container.innerHTML = '<p class="text-center text-gray-400 text-[11px] font-bold mt-8 uppercase">Nessun atleta trovato</p>';
                return;
            }
            container.innerHTML = results.map(({u, sport, city, f, t}) => {
                const followed = followedUsers.has(u);
                return `<div class="bg-white rounded-2xl p-4 flex items-center gap-3 shadow-sm border border-gray-100 cursor-pointer" onclick="openUserProfile('${u}','${sport}','${city}',${f},${t})">
                    <img src="https://i.pravatar.cc/100?u=${u}" class="w-12 h-12 rounded-full border-2 border-cyan-400 flex-shrink-0">
                    <div class="flex-1 min-w-0">
                        <p class="font-black text-sm">@${u}</p>
                        <p class="text-[#00F5FF] text-[9px] font-black uppercase">${sport}</p>
                        <p class="text-gray-400 text-[9px] font-bold">📍 ${city} · 🏆 ${t} trofei</p>
                    </div>
                    <button onclick="event.stopPropagation(); toggleSearchFollow(this,'${u}')"
                        class="px-3 py-2 rounded-xl text-[9px] font-black uppercase border transition-all"
                        style="${followed ? 'background:rgba(0,0,0,0.05);color:#999;border-color:#eee' : 'background:#000;color:#00F5FF;border-color:#000'}">
                        ${followed ? '✓ Seguito' : '+ Segui'}
                    </button>
                </div>`;
            }).join('');
        }

        function toggleSearchFollow(btn, user) {
            if (followedUsers.has(user)) {
                followedUsers.delete(user);
                btn.innerText = '+ Segui';
                btn.style.cssText = 'background:#000;color:#00F5FF;border-color:#000';
            } else {
                followedUsers.add(user);
                btn.innerText = '✓ Seguito';
                btn.style.cssText = 'background:rgba(0,0,0,0.05);color:#999;border-color:#eee';
                pushNotification('👥', `Stai seguendo @${user}`, '');
            }
            doFollow(user);
        }

        function switchPage(pId) {
            document.querySelectorAll('.page-content').forEach(p => p.classList.add('hidden'));
            document.querySelectorAll('nav button').forEach(b => b.classList.remove('nav-active'));
            document.getElementById('page-' + pId).classList.remove('hidden');
            const bId = pId === 'ranking' ? 'rank' : pId;
            if(document.getElementById('nav-' + bId)) document.getElementById('nav-' + bId).classList.add('nav-active');
            const cta = document.getElementById('profile-cta');
            if (pId === 'profile') { cta.classList.add('visible'); if(typeof updateProfileStats==='function') updateProfileStats(); }
            else cta.classList.remove('visible');
        }

        // ── SFIDA RICEVUTA → notifica banner top ──
        let pendingChallenger = { user: '', sport: '', avatar: '' };
        let activeMatchUser = '';
        let activeMatchSport = '';
        let myVote = null; // 'me' | 'them' | null

        function triggerChallenge(user, sport) {
            // Simula notifica in arrivo
            pendingChallenger = { user, sport: sport || 'una sfida' };
            document.getElementById('notify-avatar').src = `https://i.pravatar.cc/100?u=${user}`;
            document.getElementById('notify-name').innerText = `@${user}`;
            document.getElementById('notify-sport').innerText = `ti sfida: ${sport || '⚔️'}`;
            const n = document.getElementById('challenge-notify');
            n.style.display = 'block';
            setTimeout(() => n.classList.add('show'), 30);
            // Auto-dismiss dopo 8 secondi
            clearTimeout(window._notifyTimer);
            window._notifyTimer = setTimeout(() => dismissNotify(), 8000);
        }

        function dismissNotify() {
            const n = document.getElementById('challenge-notify');
            n.classList.remove('show');
            setTimeout(() => { n.style.display = 'none'; }, 450);
            pendingChallenger = { user: '', sport: '' };
        }

        function acceptNotify() {
            dismissNotify();
            const { user, sport } = pendingChallenger.user ? pendingChallenger : { user: currentChallenger, sport: '⚔️' };
            openChatMatch(user, sport);
        }

        // ── CHAT MATCH ──
        function openChatMatch(user, sport) {
            activeMatchUser = user;
            activeMatchSport = sport;
            myVote = null;
            document.getElementById('chat-match-avatar').src = `https://i.pravatar.cc/100?u=${user}`;
            document.getElementById('chat-match-name').innerText = `@${user}`;
            document.getElementById('chat-match-sport').innerText = sport + ' — Match attivo ⚔️';
            document.getElementById('trophy-them-btn').innerText = `Ha vinto @${user}`;
            document.getElementById('trophy-banner').classList.remove('show');
            document.getElementById('chat-match-input').value = '';

            // Messaggi di apertura
            const msgs = document.getElementById('chat-match-messages');
            msgs.innerHTML = '';
            addMatchMessage('system', `Sfida accettata! 🎉 Organizzate il match per: ${sport}`);
            setTimeout(() => addMatchMessage('them', `Ciao! Quando sei disponibile?`), 600);

            // Mostra la chat e aggiorna badge
            document.getElementById('chat-match-page').classList.add('open');
            document.getElementById('chat-dot').classList.remove('hidden');
            updateChatList(user, sport);
        }

        function closeChatMatch() {
            document.getElementById('chat-match-page').classList.remove('open');
        }

        function sendMatchMessage() {
            const input = document.getElementById('chat-match-input');
            const txt = input.value.trim();
            if (!txt) return;
            addMatchMessage('me', txt);
            input.value = '';
            // Risposta automatica simulata
            const replies = [
                'Ok perfetto! 👊',
                'Ottima scelta, ci vediamo lì!',
                'Concordato. Preparati! 😤',
                '👍 Ti aspetto!',
                'Confermato!',
            ];
            setTimeout(() => {
                addMatchMessage('them', replies[Math.floor(Math.random() * replies.length)]);
            }, 800 + Math.random() * 800);
        }

        function addMatchMessage(who, text) {
            const msgs = document.getElementById('chat-match-messages');
            const now = new Date().toLocaleTimeString('it-IT', { hour: '2-digit', minute: '2-digit' });
            if (who === 'system') {
                msgs.insertAdjacentHTML('beforeend', `
                    <div class="text-center my-1">
                        <span class="text-[9px] font-black uppercase text-cyan-600 bg-cyan-50 px-3 py-1 rounded-full">${text}</span>
                    </div>`);
            } else {
                const cls = who === 'me' ? 'chat-bubble-me' : 'chat-bubble-them';
                msgs.insertAdjacentHTML('beforeend', `
                    <div class="flex flex-col ${who === 'me' ? 'items-end' : 'items-start'}">
                        <div class="${cls}">${text}</div>
                        <span class="chat-time ${who === 'me' ? 'mr-1' : 'ml-1'}">${now}</span>
                    </div>`);
            }
            msgs.scrollTop = msgs.scrollHeight;
        }

        function showTrophyBanner() {
            // Ora apre il modale risultato completo
            addMatchMessage('system', '⚔️ Match terminato — dichiara il risultato!');
            setTimeout(function() {
                openResultModal(activeMatchUser, activeMatchSport);
                if (typeof pushNotification === 'function') pushNotification('⚔️', 'Match terminato!', 'Dichiara il risultato contro @' + activeMatchUser);
            }, 600);
        }

        function assignMatchTrophy(winner) {
            // Legacy — ora delegato a openResultModal
            openResultModal(activeMatchUser, activeMatchSport);
        }

        function updateChatList(user, sport, concluded = false) {
            document.getElementById('chat-dot').classList.remove('hidden');
            const existing = document.getElementById('chatcard-' + user);
            const card = `
                <div id="chatcard-${user}" class="flex items-center gap-3 p-4 bg-white rounded-2xl shadow-sm border ${concluded ? 'border-gray-200 opacity-60' : 'border-cyan-400'} cursor-pointer" onclick="openChatMatch('${user}','${sport}')">
                    <img src="https://i.pravatar.cc/100?u=${user}" class="w-12 h-12 rounded-full border-2 border-cyan-400 flex-shrink-0">
                    <div class="flex-1 min-w-0">
                        <p class="font-black text-xs">@${user}</p>
                        <p class="text-[9px] text-cyan-600 font-bold uppercase truncate">${sport}</p>
                        <p class="text-[9px] text-gray-400 font-bold">${concluded ? 'Match concluso ✓' : 'Match attivo ⚔️'}</p>
                    </div>
                    ${!concluded ? '<span class="w-2.5 h-2.5 bg-cyan-400 rounded-full flex-shrink-0"></span>' : ''}
                </div>`;
            const chatList = document.getElementById('active-chats');
            if (existing) existing.outerHTML = card;
            else chatList.innerHTML = card + (chatList.querySelector('p') ? '' : chatList.innerHTML.replace('<p class="text-gray-400', '<p class="hidden'));
            // Rimuovi placeholder
            const placeholder = chatList.querySelector('p.text-gray-400');
            if (placeholder) placeholder.remove();
        }

        // Mantengo vecchie funzioni per compatibilità con triggerChallenge nei post
        function ignoreChallenge() {} // legacy
        function acceptChallenge() {} // legacy - replaced by window._ac/_ic
        function assignTrophy(w) { assignMatchTrophy(w); }

        // ── SFIDA RICEVUTA ──
        function triggerChallenge(user, sport) {
            // Usa la nuova notifica banner top
            pendingChallenger = { user, sport: sport || '⚔️ Sfida' };
            currentChallenger = user;
            document.getElementById('notify-avatar').src = `https://i.pravatar.cc/100?u=${user}`;
            document.getElementById('notify-name').innerText = `@${user}`;
            document.getElementById('notify-sport').innerText = `ti sfida: ${sport || '⚔️'}`;
            const n = document.getElementById('challenge-notify');
            n.style.display = 'block';
            setTimeout(() => n.classList.add('show'), 30);
            clearTimeout(window._notifyTimer);
            window._notifyTimer = setTimeout(() => dismissNotify(), 8000);
        }

        const rankData = {
            amici: [
                { name: 'TU (Atleta)', trofei: null, flag: '🇮🇹', sport: '⚽' },
                { name: 'Miky_Power',  trofei: 42,   flag: '🇮🇹', sport: '🥊' },
                { name: 'IronMax',     trofei: 38,   flag: '🇮🇹', sport: '🏋️' },
                { name: 'Giulia_Fit',  trofei: 21,   flag: '🇮🇹', sport: '🧘' },
                { name: 'SpeedRun99',  trofei: 17,   flag: '🇮🇹', sport: '🏃' },
            ],
            nazionali: [
                { name: 'DragonFist',  trofei: 118,  flag: '🇮🇹', sport: '🥋' },
                { name: 'AlphaLift',   trofei: 104,  flag: '🇮🇹', sport: '🏋️' },
                { name: 'VeloceRoma',  trofei: 97,   flag: '🇮🇹', sport: '🚴' },
                { name: 'TU (Atleta)', trofei: null, flag: '🇮🇹', sport: '⚽' },
                { name: 'NuotoAce',    trofei: 81,   flag: '🇮🇹', sport: '🏊' },
                { name: 'Miky_Power',  trofei: 42,   flag: '🇮🇹', sport: '🥊' },
            ],
            mondiali: [
                { name: 'IronBull_US',  trofei: 312, flag: '🇺🇸', sport: '🏋️' },
                { name: 'ShadowKick',   trofei: 289, flag: '🇧🇷', sport: '🥋' },
                { name: 'SprintKing',   trofei: 274, flag: '🇯🇵', sport: '🏃' },
                { name: 'AquaShark',    trofei: 251, flag: '🇦🇺', sport: '🏊' },
                { name: 'BoxingLegend', trofei: 238, flag: '🇬🇧', sport: '🥊' },
                { name: 'TU (Atleta)',  trofei: null, flag: '🇮🇹', sport: '⚽' },
                { name: 'CycloMaster',  trofei: 201, flag: '🇫🇷', sport: '🚴' },
            ],
        };

        let currentRankTab = 'amici';

        function switchRankTab(tab) {
            currentRankTab = tab;
            ['amici','nazionali','mondiali'].forEach(t => {
                const btn = document.getElementById('tab-' + t);
                if (t === tab) {
                    btn.style.background = '#000'; btn.style.color = '#00F5FF';
                } else {
                    btn.style.background = ''; btn.style.color = '#004d4d';
                }
            });
            updateRankings();
        }

        const medalSvg = (color) => `<svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="${color}" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="8"/><path d="M12 4v4M12 16v4M4 12h4M16 12h4"/></svg>`;
        const trophySvg = (color) => `<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="${color}" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9H4.5a2.5 2.5 0 0 1 0-5H6"/><path d="M18 9h1.5a2.5 2.5 0 0 0 0-5H18"/><path d="M4 22h16"/><path d="M18 2H6v7a6 6 0 0 0 12 0V2Z"/><path d="M12 17v5"/></svg>`;

        function updateRankings() {
            const list = document.getElementById('rank-list');
            if (!list) return;
            let data = rankData[currentRankTab].map(r => ({
                ...r, trofei: r.trofei === null ? myTrophies : r.trofei
            }));
            data.sort((a, b) => b.trofei - a.trofei);
            list.innerHTML = data.map((r, i) => {
                const isMe = r.name.includes('TU');
                const podiumColors = ['#FFD700', '#C0C0C0', '#CD7F32'];
                const medal = i < 3
                    ? medalSvg(isMe ? '#00F5FF' : podiumColors[i])
                    : `<span class="font-black text-[11px] text-[#008B8B]">#${i+1}</span>`;
                return `
                <div class="flex justify-between items-center p-4 rounded-3xl border ${isMe ? 'bg-black border-[#00F5FF]/40' : 'bg-white/60 border-[#008B8B]/10'}">
                    <div class="flex items-center gap-3">
                        <span class="w-6 flex items-center justify-center">${medal}</span>
                        <div>
                            <span class="font-bold text-xs uppercase block ${isMe ? 'text-[#00F5FF]' : ''}">${r.name} ${isMe ? '★' : ''}</span>
                            <span class="text-[9px] text-gray-400 font-bold">${r.flag} ${currentRankTab === 'mondiali' ? '' : 'Italia'}</span>
                        </div>
                    </div>
                    <div class="flex items-center gap-1.5">
                        <span class="font-black text-sm ${isMe ? 'text-[#00F5FF]' : 'text-[#008B8B]'}">${r.trofei}</span>
                        ${trophySvg(isMe ? '#00F5FF' : '#008B8B')}
                    </div>
                </div>`;
            }).join('');
        }

        function openAvatarPicker() {
            document.getElementById('avatar-picker').classList.remove('hidden');
        }

        function closeAvatarPicker() {
            document.getElementById('avatar-picker').classList.add('hidden');
        }

        function pickAvatar(source) {
            closeAvatarPicker();
            if (source === 'camera') {
                document.getElementById('avatar-camera-input').click();
            } else {
                document.getElementById('avatar-input').click();
            }
        }

        function updateProfilePhoto(input) {
            if(input.files && input.files[0]) {
                const reader = new FileReader();
                reader.onload = (e) => { 
                    document.getElementById('profile-img').src = e.target.result;
                    document.querySelector('#nav-profile img').src = e.target.result;
                };
                reader.readAsDataURL(input.files[0]);
            }
        }

        function previewNewPost(input) {
            const preview = document.getElementById('post-preview');
            preview.classList.remove('hidden');
            const reader = new FileReader();
            reader.onload = (e) => { preview.innerHTML = `<img src="${e.target.result}" class="w-full h-full object-cover">`; };
            reader.readAsDataURL(input.files[0]);
        }

        function publish(type) {
            const img = document.querySelector('#post-preview img')?.src;
            if(!img) return;
            if(type === 'post') {
                document.getElementById('profile-grid').insertAdjacentHTML('afterbegin', `<div class="aspect-square bg-gray-200 overflow-hidden"><img src="${img}" class="w-full h-full object-cover"></div>`);
                switchPage('profile');
            } else {
                document.getElementById('stories-container').insertAdjacentHTML('afterbegin', `<div class="flex flex-col items-center gap-1"><div class="story-circle overflow-hidden relative"><img src="${img}" class="w-full h-full object-cover"><div class="absolute inset-0 bg-black/10 flex items-center justify-center text-[8px] font-black text-white" onclick="triggerChallenge('Tua_Storia')">⚔️</div></div><span class="text-[9px] font-black uppercase text-gray-600">Tua</span></div>`);
                switchPage('home');
            }
            toggleCreateModal();
        }

        // ── MODIFICA PROFILO ──
        let showChallengeProfile = true;
        let showChallengePosts = true;

        function openEditProfile() {
            const modal = document.getElementById('edit-profile-modal');
            modal.classList.remove('hidden');
            const uname = document.getElementById('profile-username').innerText.replace('@','');
            document.getElementById('edit-username').value = uname;
            document.getElementById('edit-city').value = document.getElementById('profile-city-badge').innerText.replace('📍 ','');
            document.getElementById('edit-bio').value = document.getElementById('profile-bio').innerText;
            // Sync avatar preview
            document.getElementById('edit-avatar-preview').src = document.getElementById('profile-img').src;
            // Sync toggles
            document.getElementById('toggle-challenge-profile').checked = showChallengeProfile;
            document.getElementById('toggle-challenge-posts').checked = showChallengePosts;
            // Riseleziona sport
            if(selectedSport) {
                document.querySelectorAll('#sport-pills .sport-pill').forEach(p => {
                    p.classList.toggle('selected', p.innerText.includes(selectedSport));
                });
            }
        }

        function toggleChallengeVisibility(target, visible) {
            if (target === 'profile') {
                showChallengeProfile = visible;
                const cta = document.getElementById('profile-cta');
                cta.style.display = visible ? 'block' : 'none';
                cta.classList.toggle('visible', visible);
            } else {
                showChallengePosts = visible;
                document.querySelectorAll('.btn-challenge').forEach(btn => {
                    btn.style.display = visible ? '' : 'none';
                });
            }
        }

        function closeEditProfile() {
            document.getElementById('edit-profile-modal').classList.add('hidden');
        }

        function selectSport(el) {
            document.querySelectorAll('#sport-pills .sport-pill').forEach(p => p.classList.remove('selected'));
            el.classList.add('selected');
            selectedSport = el.innerText;
            document.getElementById('custom-sport-input').value = '';
        }

        function syncCustomSport(val) {
            // Se l'utente scrive nel campo libero, deseleziona le pill
            if (val.trim()) {
                document.querySelectorAll('#sport-pills .sport-pill').forEach(p => p.classList.remove('selected'));
                selectedSport = val.trim();
            }
        }

        function saveProfile() {
            const username = document.getElementById('edit-username').value.trim();
            const city = document.getElementById('edit-city').value.trim();
            const bio = document.getElementById('edit-bio').value.trim();

            if(username) {
                document.getElementById('profile-username').innerText = username.replace('@','');
            }
            const sportBadge = document.getElementById('profile-sport-badge');
            if(selectedSport) {
                sportBadge.innerText = selectedSport;
                sportBadge.classList.remove('hidden');
            }
            const cityBadge = document.getElementById('profile-city-badge');
            if(city) {
                cityBadge.innerText = '📍 ' + city;
                cityBadge.classList.remove('hidden');
            }
            const bioEl = document.getElementById('profile-bio');
            if(bio) {
                bioEl.innerText = bio;
                bioEl.classList.remove('hidden');
            }
            closeEditProfile();
        }

        // ── SFIDA DAL PROFILO ──
        function openChallengeSport(targetUser = null, sportHint = '') {
            challengeTargetUser = targetUser;
            document.getElementById('challenge-sport-modal').classList.remove('hidden');
            document.getElementById('challenge-sport-confirm').classList.add('hidden');
            document.getElementById('challenge-text-input').value = sportHint;
            document.getElementById('challenge-modal-subtitle').innerText = targetUser ? `Stai sfidando @${targetUser}` : 'Sfida chiunque, in qualsiasi cosa';
            document.getElementById('launch-challenge-btn').innerText = 'Invia Sfida';
            document.getElementById('launch-challenge-btn').style.opacity = '1';
        }

        function closeChallengeSport() {
            document.getElementById('challenge-sport-modal').classList.add('hidden');
            document.getElementById('challenge-text-input').value = '';
        }

        function launchChallenge() {
            const txt = document.getElementById('challenge-text-input').value.trim();
            if(!txt) { document.getElementById('challenge-text-input').focus(); return; }
            const targets = challengeTargetUser ? [challengeTargetUser] : ['Trainer_Marco', 'Giulia_Fit', 'Power_Lift'];
            document.getElementById('challenge-target-list').innerHTML = targets.map(u => `
                <div class="flex items-center justify-between p-3 rounded-xl bg-white/5 border border-white/10">
                    <div class="flex items-center gap-3">
                        <img src="https://i.pravatar.cc/100?u=${u}" class="w-8 h-8 rounded-full border border-cyan-400">
                        <span class="text-white text-[10px] font-black uppercase">@${u}</span>
                    </div>
                    <span class="text-[9px] text-cyan-400 font-black uppercase">Inviata ✓</span>
                </div>`).join('');
            document.getElementById('challenge-sport-confirm').classList.remove('hidden');
            document.getElementById('launch-challenge-btn').innerText = '✓ Sfida inviata!';
            document.getElementById('launch-challenge-btn').style.opacity = '0.5';

            // Aggiorna statistiche
            statSfide++;
            if (typeof updateProfileStats === 'function') updateProfileStats();

            // -- Sfida inviata: notifica nella campanella --
            const responder = targets[0];
            const sport = txt;
            pushNotification('⚔️', `Sfida inviata a @${responder}`, sport);
            setTimeout(() => {
                closeChallengeSport();
                if (typeof pushChallengeNotif === "function") pushChallengeNotif(responder, sport);
            }, 400);
        }

        // ── RADAR CITTÀ ──
        const CITTA_ITALIANE = [
            'Agrigento','Alessandria','Ancona','Aosta','Arezzo','Ascoli Piceno','Asti','Avellino',
            'Bari','Barletta','Belluno','Benevento','Bergamo','Biella','Bologna','Bolzano','Brescia','Brindisi',
            'Cagliari','Caltanissetta','Campobasso','Caserta','Catania','Catanzaro','Chieti','Como','Cosenza','Cremona','Crotone','Cuneo',
            'Enna','Fermo','Ferrara','Firenze','Foggia','Forlì','Frosinone',
            'Genova','Gorizia','Grosseto','Imperia','Isernia',
            'La Spezia','L\'Aquila','Latina','Lecce','Lecco','Livorno','Lodi','Lucca',
            'Macerata','Mantova','Massa','Matera','Messina','Milano','Modena','Monza',
            'Napoli','Novara','Nuoro','Oristano','Padova','Palermo','Parma','Pavia','Perugia','Pesaro','Pescara','Piacenza','Pisa','Pistoia','Pordenone','Potenza','Prato',
            'Ragusa','Ravenna','Reggio Calabria','Reggio Emilia','Rieti','Rimini','Roma','Rovigo',
            'Salerno','Sassari','Savona','Siena','Siracusa','Sondrio',
            'Taranto','Teramo','Terni','Torino','Trapani','Trento','Treviso','Trieste',
            'Udine','Varese','Venezia','Verbania','Vercelli','Verona','Vibo Valentia','Vicenza','Viterbo'
        ];

        const ATLETI_PER_CITTA = {
            'Roma':    [{u:'RomaBoxer',  sport:'🥊 Boxe',         f:312,t:18},{u:'RomaRun',   sport:'🏃 Running',      f:204,t:11},{u:'RomaCyclo', sport:'🚴 Ciclismo',    f:189,t:9}],
            'Milano':  [{u:'MilanoFit',  sport:'🏋️ Powerlifting', f:520,t:33},{u:'MilanoYoga',sport:'🧘 Yoga',         f:310,t:14},{u:'MilanoMMA', sport:'🥋 MMA',          f:270,t:21}],
            'Napoli':  [{u:'NapoliBoxe', sport:'🥊 Boxe',         f:290,t:22},{u:'NapoliSwim',sport:'🏊 Nuoto',        f:155,t:8},{u:'NapoliTenn',sport:'🎾 Tennis',       f:180,t:16}],
            'Torino':  [{u:'TorinoLift', sport:'🏋️ Powerlifting', f:340,t:27},{u:'TorinoRun', sport:'🏃 Running',      f:260,t:13},{u:'TorinoMMA', sport:'🥋 MMA',          f:195,t:17}],
            'Firenze': [{u:'FirenzeYoga',sport:'🧘 Yoga',         f:210,t:10},{u:'FirenzeBox', sport:'🥊 Boxe',        f:170,t:15},{u:'FirenzeSwim',sport:'🏊 Nuoto',       f:140,t:7}],
            'Bologna': [{u:'BolognaFit', sport:'🏋️ Powerlifting', f:280,t:20},{u:'BolognaCyclo',sport:'🚴 Ciclismo',  f:220,t:12},{u:'BolognaRun', sport:'🏃 Running',     f:190,t:9}],
            'default': [{u:'Trainer_Marco',sport:'🥊 Boxe',f:412,t:42},{u:'Giulia_Fit',sport:'🧘 Yoga',f:310,t:21},{u:'Power_Lift',sport:'🏋️ Powerlifting',f:290,t:38}]
        };

        let selectedCity = '';

        function toggleCityList() {
            const dd = document.getElementById('city-dropdown');
            dd.classList.toggle('hidden');
            if (!dd.classList.contains('hidden')) {
                populateCityList(CITTA_ITALIANE);
                document.getElementById('city-search-input').focus();
            }
        }

        function populateCityList(cities) {
            const container = document.getElementById('city-list-items');
            const all = ['Tutte le città', ...cities];
            container.innerHTML = all.map(c => `
                <div onclick="selectCity('${c}')" class="px-4 py-2.5 text-sm font-bold cursor-pointer hover:bg-cyan-50 transition-colors ${selectedCity === c ? 'text-cyan-600 bg-cyan-50' : 'text-gray-700'}">
                    ${c === 'Tutte le città' ? '🌍 ' : '📍 '}${c}
                </div>`).join('');
        }

        function filterCityList(q) {
            const filtered = q.length < 1 ? CITTA_ITALIANE : CITTA_ITALIANE.filter(c => c.toLowerCase().startsWith(q.toLowerCase()));
            populateCityList(filtered);
        }

        function selectCity(city) {
            document.getElementById('city-dropdown').classList.add('hidden');
            selectedCity = city === 'Tutte le città' ? '' : city;
            document.getElementById('city-selected-label').innerText = city;
            document.getElementById('radar-city-badge').innerText = selectedCity || '';
            renderRadarAthletes(selectedCity);
            filterFeedByCity(selectedCity);
            // Aggiungi blip casuali sul radar
            const blips = document.getElementById('radar-blips');
            blips.innerHTML = '';
            const count = selectedCity ? 3 + Math.floor(Math.random()*3) : 5;
            for (let i=0; i<count; i++) {
                const angle = Math.random() * 360;
                const dist = 20 + Math.random() * 35;
                const x = 50 + dist * Math.cos(angle * Math.PI/180);
                const y = 50 + dist * Math.sin(angle * Math.PI/180);
                blips.innerHTML += `<div class="radar-blip" style="left:${x}%;top:${y}%;animation-delay:${Math.random()*2}s"></div>`;
            }
        }

        function renderRadarAthletes(city) {
            const data = ATLETI_PER_CITTA[city] || ATLETI_PER_CITTA['default'];
            const list = document.getElementById('radar-athletes');
            list.innerHTML = data.map(({u, sport, f, t}) => `
                <div class="flex items-center justify-between p-4 bg-white rounded-2xl shadow-sm border border-gray-100 cursor-pointer" onclick="openUserProfile('${u}','${sport}','${city || 'Italia'}',${f},${t})">
                    <div class="flex items-center gap-3">
                        <img src="https://i.pravatar.cc/100?u=${u}" class="w-12 h-12 rounded-full border-2 border-cyan-400">
                        <div>
                            <p class="font-black text-xs">@${u}</p>
                            <p class="text-[9px] text-cyan-600 font-bold uppercase">${sport}</p>
                            <p class="text-[9px] text-gray-400 font-bold">📍 ${city || 'Italia'}</p>
                        </div>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="text-[10px] font-black text-[#008B8B]">${t} 🏆</span>
                        <button onclick="event.stopPropagation();toggleFollowBtn(this)" class="border border-black text-black px-3 py-1.5 rounded-full text-[9px] font-black uppercase follow-radar-btn" data-user="${u}">Segui</button>
                        <button onclick="event.stopPropagation();openChallengeSport('${u}','${sport}')" class="btn-challenge flex items-center gap-1 px-3 py-1.5"><svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="2" y1="2" x2="22" y2="22"/><line x1="22" y1="2" x2="2" y2="22"/><line x1="2" y1="5" x2="5" y2="2"/><line x1="19" y1="22" x2="22" y2="19"/></svg></button>
                    </div>
                </div>`).join('');
        }

        function toggleFollowBtn(btn) {
            const user = btn.dataset.user || btn.getAttribute('data-user') || '';
            doFollow(user || btn.innerText);
        }

        // ── FILTRA FEED PER CITTÀ ──
        const allFeedPosts = [
            { user:'Trainer_Marco', sport:'🥊 Boxe',         city:'Roma',    imgUrl:'https://images.unsplash.com/photo-1549719386-74dfcbf7dbed?w=500&q=80', comments:[{u:'Giulia_Fit',txt:'Che gancio! 💥'},{u:'IronMax',txt:'Top trainer 🔥'}] },
            { user:'Giulia_Fit',    sport:'🧘 Yoga',          city:'Milano',  imgUrl:'https://images.unsplash.com/photo-1506126613408-eca07ce68773?w=500&q=80', comments:[{u:'SpeedRunner99',txt:'Che equilibrio 🙏'},{u:'CycloLuca',txt:'Incredibile!'}] },
            { user:'Power_Lift',    sport:'🏋️ Powerlifting', city:'Napoli',  imgUrl:'https://images.unsplash.com/photo-1534438327276-14e5300c3a48?w=500&q=80', comments:[{u:'Miky_Power',txt:'Bestia! 🏋️'},{u:'KarateGio',txt:'Quanto sollevi?'}] },
            { user:'MilanoFit',     sport:'🏋️ Powerlifting', city:'Milano',  imgUrl:'https://images.unsplash.com/photo-1517836357463-d25dfeac3438?w=500&q=80', comments:[{u:'Power_Lift',txt:'Grande!'},{u:'IronMax',txt:'Forte 💪'}] },
            { user:'RomaBoxer',     sport:'🥊 Boxe',          city:'Roma',    imgUrl:'https://images.unsplash.com/photo-1583454110551-21f2fa2afe61?w=500&q=80', comments:[{u:'Trainer_Marco',txt:'Bel gancio!'},{u:'Miky_Power',txt:'🔥'}] },
            { user:'TorinoLift',    sport:'🏋️ Powerlifting', city:'Torino',  imgUrl:'https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=500&q=80', comments:[{u:'Power_Lift',txt:'Bestia!'},{u:'IronMax',txt:'Forza Torino!'}] },
        ];

        function filterFeedByCity(city) {
            const container = document.getElementById('feed-container');
            container.innerHTML = '';
            postIdCounter = 0;
            const filtered = city ? allFeedPosts.filter(p => p.city === city) : allFeedPosts;
            if (filtered.length === 0) {
                container.innerHTML = `<p class="text-center text-gray-400 text-[11px] font-bold uppercase mt-8">Nessun post da ${city}</p>`;
            } else {
                filtered.forEach(p => container.innerHTML += buildPost(p));
            }
        }

        // ── PROFILO UTENTE ──
        let currentUserProfileUser = '';
        let currentUserProfileSport = '';
        // Follow state — persistente
        let followedUsers = new Set(JSON.parse((typeof FG_STORE !== 'undefined' ? FG_STORE.getItem('fg_followed') : null) || '[]'));

        function saveFollowed() {
            if (typeof FG_STORE !== 'undefined') FG_STORE.setItem('fg_followed', JSON.stringify([...followedUsers]));
        }

        function isFollowing(user) {
            return followedUsers.has(user);
        }

        // Aggiorna TUTTI i tasti Segui per questo utente nella pagina
        function syncFollowButtons(user) {
            const following = followedUsers.has(user);
            // Tasti feed (toggleFollowBtn)
            document.querySelectorAll('.follow-radar-btn, .follow-feed-btn').forEach(btn => {
                const u = btn.dataset.user;
                if (!u || u !== user) return;
                applyFollowStyle(btn, following);
            });
            // Tasto profilo utente
            const upBtn = document.getElementById('up-follow-btn');
            if (upBtn && upBtn.dataset.user === user) {
                upBtn.innerText = following ? '✓ Seguito' : '+ Segui';
                upBtn.style.background = following ? 'rgba(255,255,255,0.1)' : '#000';
                upBtn.style.color = following ? 'rgba(255,255,255,0.5)' : '#fff';
            }
            // Tasti nella lista utenti
            document.querySelectorAll('.follow-list-btn').forEach(btn => {
                if (btn.dataset.user === user) applyFollowStyle(btn, following);
            });
            // Aggiorna contatore seguiti nel profilo
            const seguitiEl = document.getElementById('my-seguiti-count');
            if (seguitiEl) seguitiEl.innerText = followedUsers.size;
        }

        function applyFollowStyle(btn, following) {
            if (following) {
                btn.innerText = '✓ Seguito';
                btn.style.background = 'rgba(255,255,255,0.06)';
                btn.style.color = 'rgba(255,255,255,0.4)';
                btn.style.border = '1px solid rgba(255,255,255,0.1)';
            } else {
                btn.innerText = 'Segui';
                btn.style.background = 'transparent';
                btn.style.color = '#000';
                btn.style.border = '1px solid #000';
            }
        }

        function doFollow(user) {
            if (!user) return;
            const wasFollowing = followedUsers.has(user);
            if (wasFollowing) {
                followedUsers.delete(user);
                showToast('Non segui più @' + user, '');
            } else {
                followedUsers.add(user);
                showToast('Segui @' + user + '!', 'success');
                if (typeof pushNotification === 'function') pushNotification('👤', 'Ora segui @' + user, 'Vedrai i suoi post nel feed');
            }
            saveFollowed();
            syncFollowButtons(user);
        }


        function openUserProfile(user, sport, city, followers, trofei) {
            currentUserProfileUser = user;
            currentUserProfileSport = sport;
            document.getElementById('up-avatar').src = `https://i.pravatar.cc/150?u=${user}`;
            document.getElementById('up-username').innerText = `@${user}`;
            document.getElementById('up-username-header').innerText = `@${user}`;
            document.getElementById('up-sport').innerText = sport;
            document.getElementById('up-city').innerText = `📍 ${city}`;
            document.getElementById('up-followers').innerText = followers >= 1000 ? (followers/1000).toFixed(1)+'k' : followers;
            document.getElementById('up-trofei').innerText = trofei;
            // Stato segui
            const btn = document.getElementById('up-follow-btn');
            btn.dataset.user = user;
            if (followedUsers.has(user)) {
                btn.innerText = '✓ Seguito'; btn.style.background='#e5e5e5'; btn.style.color='#444';
            } else {
                btn.innerText = '+ Segui'; btn.style.background='#000'; btn.style.color='#fff';
            }
            // Griglia post fake
            const grid = document.getElementById('up-grid');
            const imgs = [30,31,32,33,34,35].map(s => `https://images.unsplash.com/photo-151783${6357+s*7}-d25dfeac3438?w=300&q=80`);
            const realImgs = [
                'https://images.unsplash.com/photo-1517836357463-d25dfeac3438?w=300&q=80',
                'https://images.unsplash.com/photo-1583454110551-21f2fa2afe61?w=300&q=80',
                'https://images.unsplash.com/photo-1476480862126-209bfaa8edc8?w=300&q=80',
                'https://images.unsplash.com/photo-1530549387789-4c1017266635?w=300&q=80',
                'https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=300&q=80',
                'https://images.unsplash.com/photo-1555597673-b21d5c935865?w=300&q=80',
            ];
            grid.innerHTML = realImgs.map((url, i) => `
                <div class="aspect-square bg-gray-200 overflow-hidden rounded-lg cursor-pointer relative group"
                     onclick="openLightbox('${url}','${sport}','${user}',[])">
                    <img src="${url}" class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-black/0 group-hover:bg-black/40 transition-all flex items-center justify-center opacity-0 group-hover:opacity-100">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="white" stroke="white" stroke-width="1"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l8.78-8.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
                    </div>
                </div>`).join('');
            document.getElementById('user-profile-page').classList.add('open');
        }

        function closeUserProfile() {
            document.getElementById('user-profile-page').classList.remove('open');
        }

        function toggleMyFollow() {
            const btn = document.getElementById('my-follow-btn');
            const following = btn.innerText.includes('Seguito');
            if (following) {
                btn.innerText = '+ Segui';
                btn.style.background = '';
                btn.style.color = '#008B8B';
                btn.style.borderColor = '#008B8B';
            } else {
                btn.innerText = '✓ Seguito';
                btn.style.background = '#008B8B';
                btn.style.color = '#fff';
                btn.style.borderColor = '#008B8B';
            }
        }

        function toggleFollowUser() {
            doFollow(currentUserProfileUser);
        }

        // ── PAGINA UTENTI ──
        const fakeUsers = {
            follower: [
                { u: 'Miky_Power',    sport: '🥊 Boxe',       trofei: 42 },
                { u: 'IronMax',       sport: '🏋️ Powerlifting', trofei: 38 },
                { u: 'Giulia_Fit',    sport: '🧘 Yoga',        trofei: 21 },
                { u: 'SpeedRunner99', sport: '🏃 Running',     trofei: 17 },
                { u: 'SurfKing',      sport: '🏄 Surf',        trofei: 15 },
                { u: 'CycloLuca',     sport: '🚴 Ciclismo',    trofei: 12 },
                { u: 'KarateGio',     sport: '🥋 MMA',         trofei: 9 },
            ],
            seguiti: [
                { u: 'Trainer_Marco', sport: '🏋️ Powerlifting', trofei: 33 },
                { u: 'Power_Lift',    sport: '🥊 Boxe',        trofei: 28 },
                { u: 'TennisAce',     sport: '🎾 Tennis',      trofei: 19 },
                { u: 'BasketBros',    sport: '🏀 Basket',      trofei: 14 },
                { u: 'NuotoFast',     sport: '🏊 Nuoto',       trofei: 11 },
            ],
            trofei: [
                { u: 'Miky_Power',    sport: '🥊 Boxe',        trofei: 42, label: '1° posto classifica' },
                { u: 'IronMax',       sport: '🏋️ Powerlifting', trofei: 38, label: 'Sfida vinta' },
                { u: 'TennisAce',     sport: '🎾 Tennis',      trofei: 19, label: 'Sfida vinta' },
            ]
        };

        let currentUsersTab = 'follower';

        function openUsersPage(type) {
            currentUsersTab = type || 'follower';
            document.getElementById('page-users').classList.add('open');
            renderUsersTab(currentUsersTab);
            // Aggiorna tab attivo
            document.querySelectorAll('.users-tab-btn').forEach((btn, i) => {
                const tabs = ['follower','seguiti','trofei'];
                btn.classList.toggle('active', tabs[i] === currentUsersTab);
            });
        }

        function switchUsersTab(type) {
            currentUsersTab = type;
            document.querySelectorAll('.users-tab-btn').forEach((btn, i) => {
                const tabs = ['follower','seguiti','trofei'];
                btn.classList.toggle('active', tabs[i] === type);
            });
            renderUsersTab(type);
        }

        function renderUsersTab(type) {
            const data = fakeUsers[type] || fakeUsers.follower;
            const isTrofei = type === 'trofei';
            document.getElementById('users-page-title').innerText =
                type === 'follower' ? 'Follower' : type === 'seguiti' ? 'Seguiti' : 'Trofei';
            document.getElementById('users-page-count').innerText = data.length + ' utenti';
            const list = document.getElementById('users-list');
            list.innerHTML = data.map(({ u, sport, trofei, label }, idx) => {
                const followed = followedUsers.has(u);
                const medal = idx === 0 ? '#FFD700' : idx === 1 ? '#C0C0C0' : idx === 2 ? '#CD7F32' : null;
                return `
                <div class="user-card" onclick="openUserProfile('${u}','${sport}','Italia',${Math.floor(Math.random()*400)+50},${trofei})">
                    <!-- Avatar + badge posizione trofei -->
                    <div class="relative flex-shrink-0">
                        <img src="https://i.pravatar.cc/100?u=${u}" class="w-14 h-14 rounded-full object-cover border-2" style="border-color:${medal || 'rgba(0,245,255,0.4)'}">
                        ${isTrofei && medal ? `<span class="absolute -bottom-1 -right-1 w-5 h-5 rounded-full flex items-center justify-center" style="background:${medal}">
                            <svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="#000" stroke-width="2.5"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
                        </span>` : ''}
                    </div>
                    <!-- Info -->
                    <div class="flex-1 min-w-0">
                        <p class="text-white font-black text-sm truncate">@${u}</p>
                        <p class="text-[#00F5FF] text-[9px] font-black uppercase mt-0.5 truncate">${sport}</p>
                        ${label ? `<p class="text-white/30 text-[8px] font-bold mt-0.5">${label}</p>` : ''}
                        <!-- Mini stats -->
                        <div class="flex items-center gap-3 mt-1.5">
                            <span class="flex items-center gap-1 text-white/40 text-[9px] font-bold">
                                <svg width="9" height="9" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M6 9H4.5a2.5 2.5 0 0 1 0-5H6"/><path d="M18 9h1.5a2.5 2.5 0 0 0 0-5H18"/><path d="M4 22h16"/><path d="M18 2H6v7a6 6 0 0 0 12 0V2Z"/><path d="M12 17v5"/></svg>
                                ${trofei}
                            </span>
                        </div>
                    </div>
                    <!-- Azioni -->
                    <div class="flex flex-col gap-2 flex-shrink-0" onclick="event.stopPropagation()">
                        <button onclick="toggleFollowInList(this,'${u}')"
                            class="px-4 py-2 rounded-xl text-[9px] font-black uppercase tracking-wide border transition-all"
                            style="${followed ? 'background:rgba(255,255,255,0.1);color:rgba(255,255,255,0.5);border-color:rgba(255,255,255,0.1)' : 'background:#00F5FF;color:#000;border-color:#00F5FF'}">
                            ${followed ? '✓ Seguito' : '+ Segui'}
                        </button>
                        <button onclick="openChallengeSport('${u}','${sport}')"
                            class="px-4 py-2 rounded-xl text-[9px] font-black uppercase tracking-wide border border-white/10 text-white/50 flex items-center gap-1 justify-center">
                            <svg width="9" height="9" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><line x1="2" y1="2" x2="22" y2="22"/><line x1="22" y1="2" x2="2" y2="22"/><line x1="2" y1="5" x2="5" y2="2"/><line x1="19" y1="22" x2="22" y2="19"/></svg>
                            Sfida
                        </button>
                    </div>
                </div>`;
            }).join('');
        }

        function toggleFollowInList(btn, user) {
            if (followedUsers.has(user)) {
                followedUsers.delete(user);
                btn.innerText = '+ Segui';
                btn.style.cssText = 'background:#00F5FF;color:#000;border-color:#00F5FF';
            } else {
                followedUsers.add(user);
                btn.innerText = '✓ Seguito';
                btn.style.cssText = 'background:rgba(255,255,255,0.1);color:rgba(255,255,255,0.5);border-color:rgba(255,255,255,0.1)';
            }
            doFollow(user);
        }

        function closeUsersPage() {
            document.getElementById('page-users').classList.remove('open');
        }

        // ── POST VIEWER ──
        let pvUser = '', pvSport = '';
        const pvDefaultComments = {
            'Trainer_Marco': [{u:'Giulia_Fit', txt:'Che gancio! 💥'}, {u:'IronMax', txt:'Top trainer 🔥'}],
            'Giulia_Fit':    [{u:'SpeedRunner99', txt:'Che equilibrio 🙏'}, {u:'CycloLuca', txt:'Incredibile!'}],
            'Power_Lift':    [{u:'Miky_Power', txt:'Bestia! 🏋️'}, {u:'KarateGio', txt:'Quanto sollevi?'}],
        };

        function openLightbox(src, sport, user = '', comments = []) {
            pvUser = user || '';
            pvSport = sport || '';
            const viewer = document.getElementById('post-viewer');
            document.getElementById('pv-img').src = src;
            document.getElementById('pv-sport').innerText = sport || '';
            document.getElementById('pv-username').innerText = user ? `@${user}` : '';
            document.getElementById('pv-avatar').src = user ? `https://i.pravatar.cc/100?u=${user}` : 'https://i.pravatar.cc/150?u=myuser';
            // Like count casuale
            document.querySelector('.pv-like-count').innerText = Math.floor(Math.random() * 200) + 20;
            const likeIcon = document.querySelector('.pv-like-icon');
            likeIcon.setAttribute('fill', 'none'); likeIcon.setAttribute('stroke', 'white');
            // Commenti
            const list = document.getElementById('pv-comments-list');
            const coms = comments.length ? comments : (pvDefaultComments[user] || [{u:'SpeedRunner99', txt:'Fortissimo! 💪'}, {u:'CycloLuca', txt:'Ottimo! 🔥'}]);
            list.innerHTML = coms.map(c => `
                <div class="flex gap-2 items-start">
                    <img src="https://i.pravatar.cc/100?u=${c.u}" class="w-7 h-7 rounded-full flex-shrink-0 border border-cyan-400 object-cover">
                    <div><span class="text-white font-black text-[10px]">@${c.u}</span> <span class="text-white/60 text-[11px]">${c.txt}</span></div>
                </div>`).join('');
            // Apri con animazione
            viewer.classList.remove('hidden');
            setTimeout(() => viewer.style.transform = 'translateY(0)', 10);
        }

        function closeLightbox() {
            const viewer = document.getElementById('post-viewer');
            viewer.style.transform = 'translateY(100%)';
            setTimeout(() => viewer.classList.add('hidden'), 350);
        }

        function togglePvLike(btn) {
            if(!requireAuth("mettere like","❤")) return;
            const icon = btn.querySelector('.pv-like-icon');
            const count = btn.querySelector('.pv-like-count');
            const liked = icon.getAttribute('fill') === '#ef4444';
            icon.setAttribute('fill', liked ? 'none' : '#ef4444');
            icon.setAttribute('stroke', liked ? 'white' : '#ef4444');
            count.innerText = parseInt(count.innerText) + (liked ? -1 : 1);
            icon.classList.add('like-pop');
            setTimeout(() => icon.classList.remove('like-pop'), 300);
        }

        function focusPvComment() {
            document.getElementById('pv-comment-input').focus();
        }

        function sendPvComment() {
            if(!requireAuth("commentare","💬")) return;
            const input = document.getElementById('pv-comment-input');
            const txt = input.value.trim();
            if (!txt) return;
            const list = document.getElementById('pv-comments-list');
            list.insertAdjacentHTML('beforeend', `
                <div class="flex gap-2 items-start">
                    <img src="https://i.pravatar.cc/150?u=myuser" class="w-7 h-7 rounded-full flex-shrink-0 border border-cyan-400 object-cover">
                    <div><span class="text-white font-black text-[10px]">@Tu</span> <span class="text-white/60 text-[11px]">${txt}</span></div>
                </div>`);
            input.value = '';
            list.scrollTop = list.scrollHeight;
        }

        // ── POST ID counter ──
        let postIdCounter = 0;

        function buildPost({ user, sport, imgUrl, comments = [] }) {
            const pid = 'post-' + (postIdCounter++);
            const likeCount = Math.floor(Math.random() * 200) + 20;
            const fakeComments = comments.length ? comments : [
                { u: 'SpeedRunner99', txt: 'Fortissimo! 💪' },
                { u: 'CycloLuca', txt: 'Ottimo allenamento!' },
            ];
            return `
            <div class="post-card" id="${pid}">
                <div class="p-4 flex justify-between items-center">
                    <div class="flex items-center gap-3">
                        <img src="https://i.pravatar.cc/100?u=${user}" class="w-10 h-10 rounded-full border-2 border-cyan-400">
                        <div>
                            <span class="font-black text-xs block">@${user}</span>
                            <span class="text-[8px] font-black text-cyan-600 uppercase">${sport}</span>
                        </div>
                    </div>
                    <div class="flex gap-2">
                        <button onclick="toggleFollowBtn(this)" class="px-4 py-1.5 rounded-full text-[9px] font-black uppercase" style="border:1px solid #000;color:#000;background:transparent">Segui</button>
                        <button onclick="openChallengeSport('${user}', '${sport.replace(/'/g,"\\'")}'); event.stopPropagation()" class="btn-challenge flex items-center gap-1"><svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="#00F5FF" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="2" y1="2" x2="22" y2="22"/><line x1="22" y1="2" x2="2" y2="22"/><line x1="2" y1="5" x2="5" y2="2"/><line x1="19" y1="22" x2="22" y2="19"/></svg> Sfida</button>
                    </div>
                </div>
                <img src="${imgUrl}" class="w-full aspect-square object-cover cursor-pointer" onclick="openLightbox('${imgUrl}', '${sport}', '${user}', ${JSON.stringify(fakeComments)})">
                <div class="px-4 pt-3 pb-1 flex justify-between items-center text-[#1a1a1a]">
                    <div class="flex gap-5 items-center">
                        <button class="flex items-center gap-1.5 like-btn" onclick="toggleLike(this, '${pid}')">
                            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="like-icon"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l8.78-8.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path></svg>
                            <span class="like-count text-[11px] font-black">${likeCount}</span>
                        </button>
                        <button class="flex items-center gap-1.5" onclick="toggleComments('${pid}')">
                            <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"></path></svg>
                            <span class="text-[11px] font-black comment-count">${fakeComments.length}</span>
                        </button>
                    </div>
                    <button onclick="sharePost('${user}', '${sport}')" class="flex items-center gap-1.5 text-[#1a1a1a]">
                        <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="22" y1="2" x2="11" y2="13"></line><polygon points="22 2 15 22 11 13 2 9 22 2"></polygon></svg>
                    </button>
                </div>
                <div class="comments-box hidden" id="comments-${pid}">
                    <div class="space-y-2 max-h-40 overflow-y-auto" id="comments-list-${pid}">
                        ${fakeComments.map(c => `
                        <div class="flex gap-2 items-start">
                            <img src="https://i.pravatar.cc/100?u=${c.u}" class="w-7 h-7 rounded-full flex-shrink-0 border border-cyan-400">
                            <div><span class="font-black text-[10px]">@${c.u}</span> <span class="text-[11px] text-gray-600">${c.txt}</span></div>
                        </div>`).join('')}
                    </div>
                    <div class="comment-input-row">
                        <input type="text" placeholder="Scrivi un commento…" id="cinput-${pid}" onkeydown="if(event.key==='Enter')sendComment('${pid}')">
                        <button class="comment-send" onclick="sendComment('${pid}')">Invia</button>
                    </div>
                </div>
            </div>`;
        }

        function toggleLike(btn, pid) {
            const icon = btn.querySelector('.like-icon');
            const count = btn.querySelector('.like-count');
            const liked = icon.getAttribute('fill') === '#ef4444';
            icon.setAttribute('fill', liked ? 'none' : '#ef4444');
            icon.setAttribute('stroke', liked ? 'currentColor' : '#ef4444');
            count.innerText = parseInt(count.innerText) + (liked ? -1 : 1);
            icon.classList.add('like-pop');
            setTimeout(() => icon.classList.remove('like-pop'), 300);
        }

        function toggleComments(pid) {
            const box = document.getElementById('comments-' + pid);
            box.classList.toggle('hidden');
            if (!box.classList.contains('hidden')) {
                setTimeout(() => document.getElementById('cinput-' + pid)?.focus(), 100);
            }
        }

        function sendComment(pid) {
            const input = document.getElementById('cinput-' + pid);
            const txt = input.value.trim();
            if (!txt) return;
            const list = document.getElementById('comments-list-' + pid);
            list.insertAdjacentHTML('beforeend', `
                <div class="flex gap-2 items-start">
                    <img src="https://i.pravatar.cc/150?u=myuser" class="w-7 h-7 rounded-full flex-shrink-0 border border-cyan-400">
                    <div><span class="font-black text-[10px]">@Tu</span> <span class="text-[11px] text-gray-600">${txt}</span></div>
                </div>`);
            const cnt = list.querySelectorAll(':scope > div').length;
            const countEl = document.querySelector(`#${pid} .comment-count`);
            if (countEl) countEl.innerText = cnt;
            input.value = '';
            list.scrollTop = list.scrollHeight;
        }

        function sharePost(user, sport) {
            if (navigator.share) {
                navigator.share({ title: `FitGram - @${user}`, text: `Guarda questo post di ${sport} su FitGram PRO!` });
            } else {
                const dummy = document.createElement('input');
                document.body.appendChild(dummy);
                dummy.value = `FitGram PRO — @${user} • ${sport}`;
                dummy.select(); document.execCommand('copy');
                document.body.removeChild(dummy);
                alert('Link copiato! 📋');
            }
        }

        function initApp() {
            if (typeof isGuest === 'undefined') window.isGuest = false;
            // ── FEED iniziale (tutte le città) ──
            allFeedPosts.forEach(p => {
                document.getElementById('feed-container').innerHTML += buildPost(p);
            });

            // ── GRIGLIA PROFILO con foto sportive Unsplash ──
            const fakePosts = [
                { imgUrl: 'https://images.unsplash.com/photo-1517836357463-d25dfeac3438?w=300&q=80', sport: '🏋️ Powerlifting', label: 'Powerlifting' },
                { imgUrl: 'https://images.unsplash.com/photo-1583454110551-21f2fa2afe61?w=300&q=80', sport: '🥊 Boxe', label: 'Boxe' },
                { imgUrl: 'https://images.unsplash.com/photo-1476480862126-209bfaa8edc8?w=300&q=80', sport: '🏃 Running', label: 'Running' },
                { imgUrl: 'https://images.unsplash.com/photo-1530549387789-4c1017266635?w=300&q=80', sport: '🏊 Nuoto', label: 'Nuoto' },
                { imgUrl: 'https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=300&q=80', sport: '🚴 Ciclismo', label: 'Ciclismo' },
                { imgUrl: 'https://images.unsplash.com/photo-1555597673-b21d5c935865?w=300&q=80', sport: '🥋 MMA', label: 'MMA' },
            ];
            const grid = document.getElementById('profile-grid');
            fakePosts.forEach(({ imgUrl, sport, label }) => {
                const likes = Math.floor(Math.random() * 200) + 20;
                grid.innerHTML += `
                <div class="aspect-square bg-gray-200 overflow-hidden relative group cursor-pointer rounded-lg"
                     onclick="openLightbox('${imgUrl}', '${sport}', 'Atleta_PRO', [])">
                    <img src="${imgUrl}" class="w-full h-full object-cover">
                    <div class="absolute inset-0 bg-black/0 group-hover:bg-black/50 transition-all flex flex-col items-center justify-end pb-2 gap-1 opacity-0 group-hover:opacity-100">
                        <span class="text-white text-[8px] font-black uppercase">${label}</span>
                        <div class="flex gap-3">
                            <span class="text-white text-[8px] font-black flex items-center gap-0.5">
                                <svg width="10" height="10" viewBox="0 0 24 24" fill="white" stroke="white" stroke-width="2"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l8.78-8.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
                                ${likes}
                            </span>
                            <span class="text-white text-[8px] font-black flex items-center gap-0.5">
                                <svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/></svg>
                                2
                            </span>
                        </div>
                    </div>
                </div>`;
            });

            // ── RADAR iniziale: mostra atleti di default ──
            renderRadarAthletes('');

            // ── SPORT ICONS ANIMAZIONE ──
            const sportIcons = [
                // Pallone da calcio
                '<circle cx="12" cy="12" r="9"/><path d="M12 7l2.5 3.5L18 11l-2.5 3 1 4-4.5-2-4.5 2 1-4L6 11l3.5-.5z"/>',
                // Racchetta tennis
                '<ellipse cx="11" cy="10" rx="6" ry="8" transform="rotate(-35 11 10)"/><line x1="15" y1="15" x2="21" y2="21"/><line x1="8" y1="7" x2="14" y2="7"/><line x1="7.5" y1="10" x2="14.5" y2="10"/>',
                // Ping pong (racchetta tonda + pallina)
                '<circle cx="10" cy="11" r="7"/><line x1="15" y1="16" x2="21" y2="21"/><circle cx="19" cy="5" r="2.5"/>',
                // Bowling (palla + birilli)
                '<circle cx="8" cy="15" r="5"/><circle cx="8" cy="15" r="2"/><line x1="16" y1="4" x2="16" y2="10"/><line x1="13" y1="4" x2="13" y2="8"/><line x1="19" y1="4" x2="19" y2="8"/>',
                // Scacchi (re)
                '<path d="M9 4h6"/><path d="M12 4v3"/><path d="M7 21h10l1-9H6l1 9z"/><path d="M6 12h12"/><path d="M8 12V8h8v4"/>',
                // Sci
                '<path d="M4 20l5-14 4 6 3-4 4 12"/><path d="M2 20h20"/>',
                // Pugilato (guantone)
                '<path d="M6 12V7a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v5"/><rect x="4" y="12" width="16" height="6" rx="3"/><path d="M8 18v2"/><path d="M16 18v2"/><path d="M4 15h16"/>',
                // Pallavolo
                '<circle cx="12" cy="12" r="9"/><path d="M12 3c0 5-4 8-9 9"/><path d="M12 3c0 5 4 8 9 9"/><path d="M3 16c3-1 6-4 9-4s6 3 9 4"/>',
            ];

            let sportIdx = 0;
            const iconEl = document.getElementById('sport-icon');
            function cycleSportIcon() {
                if (!iconEl) return;
                iconEl.classList.add('fade');
                setTimeout(() => {
                    iconEl.innerHTML = sportIcons[sportIdx];
                    sportIdx = (sportIdx + 1) % sportIcons.length;
                    iconEl.classList.remove('fade');
                }, 400);
            }
            cycleSportIcon();
            setInterval(cycleSportIcon, 1800);

            updateRankings();

            // ── SPLASH & AUTH INIT ──
            try {
                var _origSP2 = saveProfile;
                if (typeof _origSP2 === 'function' && typeof persistProfile === 'function') {
                    saveProfile = function() { _origSP2(); persistProfile(); };
                }
            } catch(e) {}

            function hideSplash() {
                var spEl = document.getElementById('splash-screen');
                if (!spEl) return;
                spEl.style.opacity = '0';
                spEl.style.pointerEvents = 'none';
                setTimeout(function() {
                    try { spEl.style.display = 'none'; } catch(e) {}
                    var saved = null;
                    try {
                        var store = (typeof FG_STORE !== 'undefined') ? FG_STORE : localStorage;
                        var key = (typeof FGKEY !== 'undefined') ? FGKEY : 'fitgram_v1';
                        saved = JSON.parse(store.getItem(key) || 'null');
                    } catch(e) { saved = null; }
                    if (saved && saved.email && saved.pass) {
                        // Utente già registrato: entra nell'app
                        try { isGuest = false; applyUD(saved); } catch(e) {}
                        try { if (typeof switchPage === 'function') switchPage('feed'); } catch(e) {}
                        try { showToast('Bentornato ' + (saved.name || '') + '!', 'success'); } catch(e) {}
                    } else {
                        // Nessun account: mostra registrazione
                        var authEl = document.getElementById('auth-screen');
                        if (authEl) {
                            authEl.style.display = 'flex';
                            authEl.style.flexDirection = 'column';
                            authEl.classList.add('visible');
                        }
                        if (typeof switchAuthTab === 'function') switchAuthTab('register');
                    }
                }, 400);
            }
            setTimeout(hideSplash, 1500);
        }

        if (document.readyState === 'loading') {
            document.addEventListener('DOMContentLoaded', initApp);
        } else {
            initApp();
        }

    </script>


    <script>
    // ── SISTEMA NOTIFICHE ──
    var notifications = JSON.parse(FG_STORE.getItem('fg_notifs') || '[]');
    var notifPanelOpen = false;

    function pushNotification(icon, text, sub) {
        var n = { id: Date.now(), icon: icon, text: text, sub: sub || '', read: false, ts: new Date().toLocaleTimeString('it-IT', {hour:'2-digit', minute:'2-digit'}) };
        notifications.unshift(n);
        if (notifications.length > 30) notifications = notifications.slice(0, 30);
        FG_STORE.setItem('fg_notifs', JSON.stringify(notifications));
        renderNotifications();
        var dot = document.getElementById('notif-dot');
        if (dot) dot.classList.remove('hidden');
        if (navigator.vibrate) navigator.vibrate(60);
    }

    function renderNotifications() {
        var list = document.getElementById('notif-list');
        if (!list) return;
        if (notifications.length === 0) { list.innerHTML = '<p style="text-align:center;padding:28px;color:rgba(0,0,0,.3);font-size:12px;font-weight:600">Nessuna notifica</p>'; return; }
        list.innerHTML = notifications.map(function(n) {
            var bg = n.read ? '#fff' : 'rgba(0,139,139,.04)';
            var w = '<div style="border-bottom:1px solid rgba(0,0,0,.04);background:' + bg + '">';
            if (n.type === 'challenge' && n.status === 'pending') {
                var id = String(n.id), fr = (n.from||'').replace(/'/g,''), sp = (n.sport||'').replace(/'/g,'');
                return w + '<div style="display:flex;align-items:center;gap:10px;padding:12px 16px 8px"><img src="https://i.pravatar.cc/100?u=' + fr + '" style="width:38px;height:38px;border-radius:50%;border:2px solid #00F5FF;flex-shrink:0"/><div style="flex:1"><p style="font-size:12px;font-weight:800;color:#004d4d;margin:0">@' + fr + ' ti sfida!</p><p style="font-size:11px;color:#008B8B;font-weight:700;margin:2px 0 0">&#9876; ' + sp + '</p></div><span style="font-size:9px;color:rgba(0,0,0,.3);flex-shrink:0">' + n.ts + '</span></div><div style="display:flex;gap:8px;padding:0 16px 12px"><button onclick="window._ac(' + JSON.stringify(id) + ',' + JSON.stringify(fr) + ',' + JSON.stringify(sp) + ')" style="flex:1;padding:9px;border-radius:12px;font-weight:900;font-size:11px;text-transform:uppercase;background:#00F5FF;color:#000;border:none;cursor:pointer">&#10003; Accetta</button><button onclick="window._ic(' + JSON.stringify(id) + ')" style="flex:1;padding:9px;border-radius:12px;font-weight:900;font-size:11px;text-transform:uppercase;background:rgba(0,0,0,.06);color:rgba(0,0,0,.4);border:none;cursor:pointer">Ignora</button></div></div>';
            }
            if (n.type === 'challenge') {
                var ic2 = n.status === 'accepted' ? '&#9989;' : '&#128683;';
                var op2 = n.status === 'ignored' ? 'opacity:.5;' : '';
                var tx2 = n.status === 'accepted' ? 'Sfida accettata con @' + (n.from||'') : 'Sfida ignorata - @' + (n.from||'');
                return w + '<div style="display:flex;align-items:center;gap:10px;padding:10px 16px;' + op2 + '"><span style="font-size:22px;flex-shrink:0">' + ic2 + '</span><p style="flex:1;font-size:12px;font-weight:700;color:#004d4d;margin:0">' + tx2 + '</p><span style="font-size:9px;color:rgba(0,0,0,.3);flex-shrink:0">' + n.ts + '</span></div></div>';
            }
            return w + '<div style="display:flex;align-items:center;gap:10px;padding:10px 16px"><span style="font-size:22px;flex-shrink:0">' + (n.icon||'&#128276;') + '</span><div style="flex:1;min-width:0"><p style="font-size:12px;font-weight:700;color:#004d4d;margin:0;line-height:1.3">' + n.text + '</p>' + (n.sub ? '<p style="font-size:10px;color:rgba(0,0,0,.4);font-weight:600;margin:2px 0 0">' + n.sub + '</p>' : '') + '</div><span style="font-size:9px;color:rgba(0,0,0,.3);font-weight:600;flex-shrink:0">' + n.ts + '</span></div></div>';
        }).join('');
    }
    window._ac = function(id, fr, sp) {
        notifications.forEach(function(n) { if (String(n.id)===String(id)) { n.status='accepted'; n.read=true; } });
        FG_STORE.setItem('fg_notifs', JSON.stringify(notifications));
        renderNotifications();
        if (notifPanelOpen) toggleNotifications();
        setTimeout(function() { if (typeof openChatMatch==='function') openChatMatch(fr, sp); }, 200);
        showToast('Sfida accettata! Vai in chat &#9876;', 'success');
        if (navigator.vibrate) navigator.vibrate([80,40,80]);
    };
    window._ic = function(id) {
        notifications.forEach(function(n) { if (String(n.id)===String(id)) { n.status='ignored'; n.read=true; } });
        FG_STORE.setItem('fg_notifs', JSON.stringify(notifications));
        renderNotifications();
        showToast('Sfida ignorata', '');
    };
    function pushChallengeNotif(fr, sp) {
        var n = { id: Date.now(), type:'challenge', status:'pending', from:fr, sport:sp, read:false, ts: new Date().toLocaleTimeString('it-IT',{hour:'2-digit',minute:'2-digit'}) };
        notifications.unshift(n);
        FG_STORE.setItem('fg_notifs', JSON.stringify(notifications));
        var dot = document.getElementById('notif-dot');
        if (dot) dot.classList.remove('hidden');
        if (notifPanelOpen) renderNotifications();
        var bell = document.querySelector('button[onclick="toggleNotifications()"] svg');
        if (bell) { var s=0, iv=setInterval(function(){ bell.style.transform=s%2===0?'rotate(18deg)':'rotate(-18deg)'; if(++s>6){clearInterval(iv);bell.style.transform='';} },80); }
        if (navigator.vibrate) navigator.vibrate([60,40,60]);
    }

    function toggleNotifications() {
        var panel = document.getElementById('notif-panel');
        if (!panel) return;
        notifPanelOpen = !notifPanelOpen;
        panel.style.display = notifPanelOpen ? 'flex' : 'none';
        panel.style.flexDirection = 'column';
        if (notifPanelOpen) {
            // Segna tutte come lette quando apri
            notifications.forEach(function(n){ n.read = true; });
            FG_STORE.setItem('fg_notifs', JSON.stringify(notifications));
            var dot = document.getElementById('notif-dot');
            if (dot) dot.classList.add('hidden');
            renderNotifications();
        }
    }

    function clearNotifications() {
        notifications = [];
        FG_STORE.removeItem('fg_notifs');
        renderNotifications();
        var dot = document.getElementById('notif-dot');
        if (dot) dot.classList.add('hidden');
        var empty = document.getElementById('notif-empty');
        if (empty) empty.style.display = 'block';
        var list = document.getElementById('notif-list');
        if (list) list.innerHTML = '<p id="notif-empty" style="text-align:center;padding:28px 16px;color:rgba(0,0,0,.3);font-size:12px;font-weight:600">Nessuna notifica</p>';
    }

    // Chiudi pannello cliccando fuori
    document.addEventListener('click', function(e) {
        if (!notifPanelOpen) return;
        var panel = document.getElementById('notif-panel');
        var bell = e.target.closest('button[onclick="toggleNotifications()"]');
        if (!bell && panel && !panel.contains(e.target)) {
            notifPanelOpen = false;
            panel.style.display = 'none';
        }
    });

    function updateProfileStats() {
        var tc=document.getElementById('my-trofei-count'); if(tc) tc.innerText=myTrophies;
        var td=document.getElementById('my-trophy-display'); if(td){var sp=td.querySelector('span');if(sp)sp.innerText=myTrophies;}
        var sc=document.getElementById('my-seguiti-count'); if(sc) sc.innerText=followedUsers?followedUsers.size:0;
        var fc=document.getElementById('my-follower-count'); if(fc) fc.innerText=(followedUsers?followedUsers.size:0)+12;
        // stats box
        var sfideEl=document.getElementById('stat-sfide'); if(sfideEl) sfideEl.innerText=statSfide||0;
        var vittEl=document.getElementById('stat-vittorie'); if(vittEl) vittEl.innerText=statVittorie||0;
        var wrEl=document.getElementById('stat-winrate'); if(wrEl) wrEl.innerText=(statSfide>0?Math.round((statVittorie/statSfide)*100)+'%':'—');
        var trEl=document.getElementById('stat-trofei-profile'); if(trEl) trEl.innerText=myTrophies;
    }
    function doLogout() {
        if(!confirm('Vuoi uscire dal tuo account?')) return;
        // NON cancellare i dati — solo segna come non loggato
        isGuest = true;
        // Mostra schermata di accesso
        var auth = document.getElementById('auth-screen');
        if (auth) { auth.style.display = 'flex'; auth.style.flexDirection = 'column'; auth.classList.add('visible'); }
        // Vai al tab login
        if (typeof switchAuthTab === 'function') switchAuthTab('login');
        // Chiudi sidebar se aperta
        var sidebar = document.getElementById('sidebar');
        if (sidebar) sidebar.classList.remove('open');
        showToast('Logout effettuato', '');
    }

    // ── AUTH & PERSISTENZA ── (FG_STORE, FGKEY, isGuest definiti nell'head)

    function showToast(m, t) {
        var el = document.getElementById('toast');
        if (!el) return;
        el.innerText = m;
        el.className = 'show' + (t ? ' ' + t : '');
        clearTimeout(el._t);
        el._t = setTimeout(function() { el.className = ''; }, 2800);
    }

    function setLoading(id, on, lbl) {
        var b = document.getElementById(id);
        if (!b) return;
        b.disabled = on;
        b.style.opacity = on ? '0.6' : '1';
        b.innerHTML = on ? '<span class="spinner"></span>' : lbl;
    }

    function switchAuthTab(tab) {
        var il = tab === 'login';
        var fl = document.getElementById('auth-form-login');
        var fr = document.getElementById('auth-form-register');
        if (fl) { fl.style.display = il ? 'flex' : 'none'; fl.style.flexDirection = 'column'; }
        if (fr) { fr.style.display = !il ? 'flex' : 'none'; fr.style.flexDirection = 'column'; }
        var base = 'flex:1;padding:10px;border-radius:12px;font-size:10px;font-weight:900;text-transform:uppercase;border:none;cursor:pointer;';
        var tl = document.getElementById('auth-tab-login');
        var tr2 = document.getElementById('auth-tab-register');
        if (tl) tl.style.cssText = base + (il ? 'background:#fff;color:#000' : 'background:transparent;color:rgba(255,255,255,.35)');
        if (tr2) tr2.style.cssText = base + (!il ? 'background:#fff;color:#000' : 'background:transparent;color:rgba(255,255,255,.35)');
    }

    function doLogin() {
        var e = document.getElementById('login-email').value.trim();
        var p = document.getElementById('login-password').value.trim();
        if (!e || !p) { showToast('Compila tutti i campi', 'error'); return; }
        setLoading('login-btn', true, 'Accedi');
        setTimeout(function() {
            setLoading('login-btn', false, 'Accedi');
            var s = JSON.parse(FG_STORE.getItem(FGKEY) || 'null');
            if (s && s.email === e && s.pass === p) { isGuest = false; applyUD(s); enterApp(false); }
            else if (s && s.email === e) { showToast('Password errata', 'error'); }
            else { showToast('Account non trovato — registrati!', 'error'); }
        }, 900);
    }

    function doRegister() {
        var n = document.getElementById('reg-name').value.trim();
        var e = document.getElementById('reg-email').value.trim();
        var p = document.getElementById('reg-password').value.trim();
        if (!n || !e || !p) { showToast('Compila tutti i campi', 'error'); return; }
        if (p.length < 6) { showToast('Password min. 6 caratteri', 'error'); return; }
        if (!e.includes('@')) { showToast('Email non valida', 'error'); return; }
        setLoading('register-btn', true, 'Crea account');
        setTimeout(function() {
            setLoading('register-btn', false, 'Crea account');
            var d = { name: n, email: e, pass: p, trofei: 0, city: '', bio: '', sport: '', avatar: '' };
            FG_STORE.setItem(FGKEY, JSON.stringify(d));
            isGuest = false;
            applyUD(d);
            enterApp(true);
        }, 1000);
    }

    function doDemo() {
        // Demo disabilitato — reindirizza a registrazione
        switchAuthTab('register');
    }

    function applyUD(d) {
        if (d.name) { var e = document.getElementById('profile-username'); if (e) e.innerText = d.name; }
        if (d.sport && typeof selectedSport !== 'undefined') {
            selectedSport = d.sport;
            var e = document.getElementById('profile-sport-badge');
            if (e) { e.innerText = d.sport; e.classList.remove('hidden'); }
        }
        if (d.city) { var e = document.getElementById('profile-city-badge'); if (e) { e.innerText = '📍 ' + d.city; e.classList.remove('hidden'); } }
        if (d.bio) { var e = document.getElementById('profile-bio'); if (e) { e.innerText = d.bio; e.classList.remove('hidden'); } }
        if (d.trofei && typeof myTrophies !== 'undefined') { myTrophies = d.trofei; if (typeof updateRankings === 'function') updateRankings(); }
        setTimeout(function(){ if(typeof updateProfileStats==='function') updateProfileStats(); }, 80);
        if (d.avatar) {
            ['profile-img', 'pv-my-avatar', 'edit-avatar-preview'].forEach(function(id) {
                var el = document.getElementById(id); if (el) el.src = d.avatar;
            });
            var nav = document.querySelector('#nav-profile img'); if (nav) nav.src = d.avatar;
        }
    }

    function persistProfile() {
        if (isGuest) return;
        var s = JSON.parse(FG_STORE.getItem(FGKEY) || '{}');
        s.name = (document.getElementById('profile-username') || {}).innerText || s.name;
        s.city = ((document.getElementById('profile-city-badge') || {}).innerText || '').replace('📍 ', '');
        s.bio = (document.getElementById('profile-bio') || {}).innerText || '';
        s.sport = typeof selectedSport !== 'undefined' ? selectedSport : s.sport;
        s.trofei = typeof myTrophies !== 'undefined' ? myTrophies : s.trofei;
        s.avatar = (document.getElementById('profile-img') || {}).src || '';
        FG_STORE.setItem(FGKEY, JSON.stringify(s));
        showToast('Profilo salvato! ✓', 'success');
    }

    function enterApp(isNew) {
        var auth = document.getElementById('auth-screen');
        var ob = document.getElementById('onboarding-screen');
        if (auth) { auth.classList.remove('visible'); auth.style.display = 'none'; }
        if (isNew && ob) {
            // Nuovo utente: mostra onboarding (4 step di benvenuto)
            ob.classList.add('visible');
            ob.style.display = 'flex';
        } else {
            // Utente già registrato: vai direttamente alla home
            if (typeof switchPage === 'function') switchPage('feed');
        }
    }

    function nextObStep(step) {
        document.querySelectorAll('.ob-step').forEach(function(s, i) { s.classList.toggle('active', i === step); });
        document.querySelectorAll('.ob-dot').forEach(function(d, i) { d.classList.toggle('active', i === step); });
    }

    var obSelectedSport = '';
    function selectObSport(btn, sport) {
        obSelectedSport = sport;
        document.querySelectorAll('.ob-sport-pill').forEach(function(p) { p.classList.remove('active'); });
        btn.classList.add('active');
    }

    function completeOnboarding() {
        // Salva sport e città dal setup
        var city = (document.getElementById('ob-city-input') || {}).value || '';
        var sport = obSelectedSport;

        if (sport) {
            selectedSport = sport;
            var badge = document.getElementById('profile-sport-badge');
            if (badge) { badge.innerText = sport; badge.classList.remove('hidden'); }
        }
        if (city) {
            var cityBadge = document.getElementById('profile-city-badge');
            if (cityBadge) { cityBadge.innerText = '📍 ' + city; cityBadge.classList.remove('hidden'); }
        }

        // Salva in localStorage
        var saved = JSON.parse(FG_STORE.getItem(FGKEY) || '{}');
        if (sport) saved.sport = sport;
        if (city) saved.city = city;
        FG_STORE.setItem(FGKEY, JSON.stringify(saved));

        var ob = document.getElementById('onboarding-screen');
        if (ob) { ob.classList.remove('visible'); ob.style.display = 'none'; }
        if (typeof switchPage === 'function') switchPage('feed');
        showToast('Benvenuto su FitGram! 🏆', 'success');
    }

    function requireAuth(action, icon) {
        if (!isGuest) return true;
        var m = document.getElementById('register-wall');
        if (!m) return true;
        var ra = document.getElementById('rw-action');
        var ri = document.getElementById('rw-icon');
        if (ra) ra.innerText = action || 'continuare';
        if (ri) ri.innerText = icon || '⚡';
        m.style.display = 'flex';
        setTimeout(function() { m.classList.add('rw-show'); }, 10);
        return false;
    }

    function closeRegisterWall() {
        var m = document.getElementById('register-wall');
        if (!m) return;
        m.classList.remove('rw-show');
        setTimeout(function() { m.style.display = 'none'; }, 300);
    }

    function goRegisterFromWall() {
        closeRegisterWall();
        var auth = document.getElementById('auth-screen');
        if (auth) auth.classList.add('visible');
        switchAuthTab('register');
    }

    function goLoginFromWall() {
        closeRegisterWall();
        var auth = document.getElementById('auth-screen');
        if (auth) auth.classList.add('visible');
        switchAuthTab('login');
    }

    // ── RESULT MODAL & TROPHY FUNCTIONS ──
    var _resultOpponent = '';
    var _resultSport = '';

    function openResultModal(user, sport) {
        _resultOpponent = user || activeMatchUser || 'Avversario';
        _resultSport = sport || activeMatchSport || '⚔️';
        var modal = document.getElementById('result-modal');
        var oppAvatar = document.getElementById('result-opp-avatar');
        var oppName = document.getElementById('result-opp-name');
        if (oppAvatar) oppAvatar.src = 'https://i.pravatar.cc/100?u=' + _resultOpponent;
        if (oppName) oppName.innerText = '@' + _resultOpponent;
        if (modal) modal.classList.add('open');
        // Chiudi chat
        closeChatMatch();
    }

    function declareResult(outcome) {
        var modal = document.getElementById('result-modal');
        if (modal) modal.classList.remove('open');

        if (outcome === 'win') {
            myTrophies++;
            statVittorie++;
            statSfide = Math.max(statSfide, statVittorie);
            if (typeof updateRankings === 'function') updateRankings();
            if (typeof updateProfileStats === 'function') updateProfileStats();
            if (typeof persistProfile === 'function' && !isGuest) persistProfile();
            // Lancia animazione trofeo
            setTimeout(function() {
                var tm = document.getElementById('trophy-modal');
                var headline = document.getElementById('trophy-headline');
                var sub = document.getElementById('trophy-sub');
                var rank = document.getElementById('trophy-rank');
                var emoji = document.getElementById('trophy-emoji');
                if (headline) headline.innerText = 'Vittoria! 🏆';
                if (sub) sub.innerText = '+1 Trofeo aggiunto · Totale: ' + myTrophies;
                if (rank) rank.innerText = 'Continua a sfidare per scalare la classifica!';
                if (emoji) emoji.innerText = '🏆';
                if (tm) tm.classList.add('open');
                launchConfetti();
                if (typeof pushNotification === 'function') pushNotification('🏆', 'Hai vinto! +1 trofeo', 'vs @' + _resultOpponent + ' · ' + _resultSport);
            }, 300);
            // Aggiorna chat come conclusa con vittoria
            updateChatList(_resultOpponent, _resultSport, true);
        } else if (outcome === 'loss') {
            statSfide = Math.max(statSfide, statVittorie + 1);
            if (typeof updateProfileStats === 'function') updateProfileStats();
            showToast('Ottima lotta! Riprova! 💪', '');
            if (typeof pushNotification === 'function') pushNotification('⚔️', 'Match concluso vs @' + _resultOpponent, 'Continua ad allenarti!');
            updateChatList(_resultOpponent, _resultSport, true);
        } else {
            showToast('Pareggio! Siete forti entrambi 🤝', '');
            if (typeof pushNotification === 'function') pushNotification('🤝', 'Pareggio vs @' + _resultOpponent, _resultSport);
            updateChatList(_resultOpponent, _resultSport, true);
        }
    }

    function launchConfetti() {
        var container = document.getElementById('confetti-container');
        if (!container) return;
        container.innerHTML = '';
        var colors = ['#00F5FF','#FFD700','#fff','#00ff88','#ff6b6b'];
        for (var i = 0; i < 60; i++) {
            var el = document.createElement('div');
            el.className = 'confetti-piece';
            el.style.cssText = 'left:' + Math.random()*100 + '%;background:' + colors[Math.floor(Math.random()*colors.length)] + ';animation-duration:' + (1.5 + Math.random()*2) + 's;animation-delay:' + Math.random()*0.8 + 's;transform:rotate(' + Math.random()*360 + 'deg);border-radius:' + (Math.random() > 0.5 ? '50%' : '2px') + ';width:' + (6+Math.random()*6) + 'px;height:' + (6+Math.random()*6) + 'px';
            container.appendChild(el);
        }
    }

    function closeTrophyModal() {
        var tm = document.getElementById('trophy-modal');
        if (tm) tm.classList.remove('open');
        var cc = document.getElementById('confetti-container');
        if (cc) cc.innerHTML = '';
        switchPage('profile');
    }

    function shareTrophyResult() {
        var text = 'Ho vinto una sfida su FitGram PRO! 🏆 Ora ho ' + myTrophies + ' trofei!';
        if (navigator.share) {
            navigator.share({ title: 'FitGram PRO', text: text });
        } else {
            var d = document.createElement('input');
            document.body.appendChild(d);
            d.value = text;
            d.select(); document.execCommand('copy');
            document.body.removeChild(d);
            showToast('Copiato! Condividi la vittoria 🏆', 'success');
        }
    }

    // Patch saveProfile per aggiungere persistenza
    // auth init in window.onload;
    </script>


    <!-- RESULT DECLARATION MODAL -->
    <div id="result-modal">
        <div class="result-card">
            <div style="font-size:36px;margin-bottom:12px">⚔️</div>
            <h3 style="color:#fff;font-weight:900;font-size:20px;margin-bottom:6px" id="result-title">Chi ha vinto?</h3>
            <p style="color:rgba(255,255,255,.4);font-size:12px;font-weight:600;margin-bottom:24px" id="result-subtitle">Dichiara onestamente il risultato del match</p>

            <!-- Avatar sfidante -->
            <div style="display:flex;align-items:center;justify-content:center;gap:16px;margin-bottom:28px">
                <div style="text-align:center">
                    <div style="width:56px;height:56px;border-radius:50%;background:rgba(0,245,255,.15);border:2px solid #00F5FF;display:flex;align-items:center;justify-content:center;margin:0 auto 6px">
                        <span style="font-size:20px">👤</span>
                    </div>
                    <p style="color:#fff;font-size:10px;font-weight:900">Tu</p>
                </div>
                <div style="color:rgba(255,255,255,.3);font-weight:900;font-size:18px">VS</div>
                <div style="text-align:center">
                    <img id="result-opp-avatar" src="" style="width:56px;height:56px;border-radius:50%;border:2px solid rgba(255,255,255,.2);display:block;margin:0 auto 6px">
                    <p id="result-opp-name" style="color:#fff;font-size:10px;font-weight:900">@Avversario</p>
                </div>
            </div>

            <!-- Bottoni risultato -->
            <div style="display:flex;gap:10px;margin-bottom:12px">
                <button class="result-btn" onclick="declareResult('win')"
                    style="background:#00F5FF;color:#000;">
                    🏆 Ho vinto io
                </button>
                <button class="result-btn" onclick="declareResult('loss')"
                    style="background:rgba(255,255,255,.08);color:rgba(255,255,255,.7);">
                    👏 Ha vinto lui
                </button>
            </div>
            <button onclick="declareResult('draw')"
                style="width:100%;padding:12px;border-radius:14px;font-weight:700;font-size:11px;text-transform:uppercase;background:transparent;color:rgba(255,255,255,.3);border:1px solid rgba(255,255,255,.08);cursor:pointer;letter-spacing:.08em">
                🤝 Pareggio
            </button>
        </div>
    </div>

    <!-- TROPHY CELEBRATION SCREEN -->
    <div id="trophy-modal">
        <div id="confetti-container" style="position:absolute;inset:0;overflow:hidden;pointer-events:none"></div>
        <div style="font-size:96px;margin-bottom:8px" class="trophy-anim" id="trophy-emoji">🏆</div>
        <div class="trophy-text" style="animation-delay:.4s">
            <h2 style="color:#fff;font-weight:900;font-size:28px;text-align:center;margin-bottom:8px" id="trophy-headline">Vittoria!</h2>
            <p style="color:#00F5FF;font-weight:900;font-size:14px;text-align:center;margin-bottom:4px" id="trophy-sub">+1 Trofeo aggiunto</p>
            <p style="color:rgba(255,255,255,.4);font-size:12px;font-weight:600;text-align:center" id="trophy-rank">Sei al posto #12 in classifica</p>
        </div>
        <div class="trophy-text" style="animation-delay:.8s;margin-top:40px;width:100%;max-width:320px;padding:0 24px;box-sizing:border-box">
            <div style="display:flex;gap:10px">
                <button onclick="closeTrophyModal()" style="flex:1;padding:16px;border-radius:16px;font-weight:900;font-size:13px;text-transform:uppercase;background:#00F5FF;color:#000;border:none;cursor:pointer">
                    Continua
                </button>
                <button onclick="shareTrophyResult()" style="width:52px;height:52px;border-radius:16px;background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.1);cursor:pointer;display:flex;align-items:center;justify-content:center">
                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2"><circle cx="18" cy="5" r="3"/><circle cx="6" cy="12" r="3"/><circle cx="18" cy="19" r="3"/><line x1="8.59" y1="13.51" x2="15.42" y2="17.49"/><line x1="15.41" y1="6.51" x2="8.59" y2="10.49"/></svg>
                </button>
            </div>
        </div>
    </div>

</body>
</html>
