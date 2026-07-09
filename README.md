## Mehdi Zaoui

Alternant en trade surveillance et étudiant en Ingénierie du risque, je me spécialise en **risque de marché** : de la valorisation d'options à la mesure du risque de portefeuille.

Mes projets sont construits depuis zéro, sans librairies de pricing tierces, pour comprendre les mécaniques sous-jacentes plutôt que d'utiliser des boîtes noires.

---

### Projets

**[options-pricing](https://github.com/mezaouifinance/options-pricing)** — librairie Python de pricing et de gestion du risque options

Pricing Black-Scholes et binomial CRR, Greeks complets (Δ Γ ν θ ρ), solveur de volatilité implicite, et un moteur de **P&L Explain** qui décompose le P&L journalier d'un portefeuille d'options en contributions par Greek.

Démonstration sur le crash COVID (SPY, jan–juin 2020) : le delta perd 24$, la gamma en récupère 18$, le vega 15$ — 81% du P&L expliqué.

**[portfolio-risk-VAR-ES](https://github.com/mezaouifinance/portfolio-risk-VAR-ES)** — mesure du risque sur portefeuille multi-actifs

VaR historique, paramétrique et Monte Carlo, Expected Shortfall, backtesting sur fenêtre glissante. **Test de Kupiec** (chi²) sur le taux d'exceptions, classification **feux tricolores Bâle II**.

**[garch-volatility](https://github.com/mezaouifinance/garch-volatility)** — modèle GARCH(1,1) calibré par MLE

Estimation par maximum de vraisemblance, variance conditionnelle, comparaison VaR statique vs VaR dynamique GARCH. Motivation : le modèle paramétrique suppose une volatilité constante, ce qui ne tient pas sur des données financières réelles.

---

### Stack

Python · NumPy · SciPy · pandas · matplotlib · yfinance · pytest · GitHub Actions
