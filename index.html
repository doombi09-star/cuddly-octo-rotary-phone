<!DOCTYPE html>
<html lang="fr">
<head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DelTraquer Pro</title>
<style>body{background:#0b0e11;color:#eaedd1;font-family:sans-serif;padding:16px}h1{color:#fff}table{width:100%;margin-top:20px}th{color:#889;text-align:left}td{padding:12px 0;border-bottom:1px solid #222}img{width:24px;height:24px;border-radius:50%;vertical-align:middle;margin-right:8px}.up{color:#b1d343}.down{color:#ff4d4d}</style>
</head>
<body>
<h1>DelTraquer Pro</h1>
<div id="status">Chargement...</div>
<table><thead><tr><th>Asset</th><th>Prix</th><th>24h</th></tr></thead><tbody id="data"></tbody></table>

<script>
async function load(){
  try{
    const r = await fetch('https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&ids=bitcoin,ethereum,solana');
    const d = await r.json();
    document.getElementById('data').innerHTML = d.map(i => `
      <tr>
        <td><img src="${i.image}">${i.symbol.toUpperCase()}</td>
        <td>$${i.current_price.toLocaleString()}</td>
        <td class="${i.price_change_percentage_24h>0?'up':'down'}">${i.price_change_percentage_24h.toFixed(2)}%</td>
      </tr>
    `).join('');
    document.getElementById('status').innerText = '✅ Live';
  }catch(e){
    document.getElementById('status').innerText = '❌ Erreur';
  }
}
load();
setInterval(load, 30000);
</script>
</body>
</html>
