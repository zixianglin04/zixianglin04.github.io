<style>
    .game-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(130px, 1fr));
    gap: 5px;
    max-width: 900px;
    margin-top: 20px;
    margin-bottom: 20px;
}

    .game-card {
    position: relative;
    overflow: hidden;
    border-radius: 6px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.2s ease;
    height: 72px;
}

    .game-card:hover {
    transform: scale(1.02);
}

    .game-card img {
    width: 100%;
    height: 100%;
    display: block;
    border-radius: 6px;
    object-fit: cover;
}
</style>

#### 🎮 Currently Playing

<a href="https://osu.ppy.sh/u/Saki_Rin">
  <img src="https://osu-sig.vercel.app/card?user=Saki_Rin&mode=std&lang=en&animation=true&mini=true" width="260"/>
</a>

<div class="game-grid">
  <div class="game-card"><img src="https://steam-record-card.vercel.app/api?steam_id=76561199030641631&appid=588650"/></div>
  <div class="game-card"><img src="https://steam-record-card.vercel.app/api?steam_id=76561199030641631&appid=632470"/></div>
  <div class="game-card"><img src="https://steam-record-card.vercel.app/api?steam_id=76561199030641631&appid=2379780"/></div>
</div>

#### ✅ Played

[Check out my game wall!](/game-wall/)