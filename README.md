# Claude X TradeView — Live Dashboard

Dashboard performa trading otomatis berbasis Harmonic PRZ + AI (Claude Code).

🔗 **Live:** [ikhsanabukenzie.github.io/claudexdashboard](https://ikhsanabukenzie.github.io/claudexdashboard)

---

## Apa yang ditampilkan

- Win rate per market (Crypto, Forex, IDX, US Stocks)
- TP distribution (TP1 / TP2 / TP3 / SL hit)
- Active signals & paper positions
- Recent trade journal
- System status (scanner & auto-trader)

## Mode

Semua trading berjalan di **PAPER mode** (akun demo MT5).  
Dashboard diperbarui otomatis setiap 30 menit via scheduled task.

## Tentang sistem

- **Scanner**: Harmonic PRZ v11.0 — formula PRZ+TREND+MOM+DIV+ADX+BB+VOL+CANDLE
- **Auto-trader**: Cascade compound strategy — 3 TP stages, be_lock SL
- **Pasar**: Crypto (10 simbol), Forex (15 simbol), IDX (10 saham), US Stocks (10)
- **Engine**: Python + MetaTrader 5 API + Claude Code scheduled tasks

---

*Hanya menampilkan hasil — tidak ada logika analisis, tidak ada informasi akun.*
