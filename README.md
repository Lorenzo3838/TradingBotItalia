# TradingBotItalia – RL Bot (ENI, Borsa Italiana)

Repository pronto per eseguire training RL su **ENI.MI** con Stable-Baselines3 (PPO) dentro GitHub Actions.

## Avvio rapido (GitHub Actions)
1. Carica tutti i file di questo progetto nella root del repo.
2. Vai su **Actions → Train ENI RL Bot → Run workflow**.
3. A fine esecuzione scarica l’artifact `rl_model_and_logs` per ottenere i modelli e i log.

## Parametri (modificabili)
- `SYMBOL` (default `ENI.MI`)
- `COMMISSION` (default `0.0005`) – 5 bps
- `WINDOW` (default `30`)
- `TIMESTEPS` (default `40000` – consigliato aumentare)
