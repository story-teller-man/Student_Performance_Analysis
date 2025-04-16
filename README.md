# Анализ успеваемости студентов

![Визуализация](https://github.com/story-teller-man/Student_Performance_Analysis/blob/main/images/boxplot.png)  
*(График из анализа)*

## 🔍 Цель исследования  
Проверить гипотезу:  
> «Студенты, сдающие ДЗ в течение 48 часов после урока, показывают результаты на 8.5 баллов выше (p < 0.001)»

## 📊 Ключевые результаты  
1. **Разница в средних баллах**:  
   - Быстрые: 59.43  
   - Стандартные: 56.86  
   - Медлительные: 50.98  

2. **Статистическая значимость**:  
   - ANOVA p-value: < 0.05 
   - Эффект Cohen’s d (Быстрые vs Медленные): 0.46 (средний)  

3. **Визуализации**:  
   - Boxplot распределения баллов 

## 🛠 Технологии  
- Python 3  
- Библиотеки: Pandas, NumPy, Seaborn, SciPy  
- Google Colab  

## 🚀 Как запустить проект  
1. Склонируйте репозиторий:  
   ```bash
   git clone https://github.com/story-teller-man/Student_Performance_Analysis.git
   ```
2. Откройте ноутбук в Google Colab:  
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/story-teller-man/Student_Performance_Analysis/blob/main/notebooks/Student_performance.ipynb)

## 📌 Рекомендации  
1. Внедрить систему напоминаний за 24 часа до дедлайна  
2. Добавить бонусные баллы за сдачу в первые 24 часа  
3. Для "медлительных" студентов:  
   - Персональные консультации  
   - Разбивка сложных заданий на этапы  
