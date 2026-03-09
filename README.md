# Классификация стресс-ответа биологических тканей (экспрессии белка HSP70) на основе Рамановской спектроскопии

**Nuclear IT Hackathon** | ML-пайплайн для рамановской спектроскопии

## About
Двухуровневый ML-ансамбль (Extreme Gradient Boosting + Random Forest) для бесконтактной детекции экспрессии белка HSP70 по данным рамановского сканирования тканей мозга. Решение отказывается от тяжелых нейросетей и слепого PCA в пользу строгой физической хемометрики и Explainable AI.

## Hierarchy
* `notebook.ipynb` — Полный код: от физической предобработки (Despiking, Savitzky-Golay, SNV) до обучения Soft Voting ансамбля и генерации научных дашбордов.
* `article.pdf` — Научная статья (LaTeX) с физико-математическим обоснованием метода.

## Team
* **[Nikolai Pautov](https://github.com/Pautovv)** 
* **[Miroslav Makarov](https://github.com/xevergreenx)** 
