# Лабораторная работа 2
## Тема: Кластеризация K-mean
## Цель работы: 
Познакомиться с методом кластеризации K-mean с помощью пакета sklearn.

Из-за реального характера данных датасет, использованный в первой лабораторной работе, содержит большое количество выбросов, являющихся естественной аномалией (магнитуда, глубина и т.д.). В связи с этим был выбран новый датасет.
## 1. Описание нового набора данных
+ **Предметная область:** эффективность, когнитивное давление и поведенческие показатели разработчиков.  
+ **Источник данных:** https://www.kaggle.com/datasets/zeesolver/ai-agent-dataset
+ **Характер данных:** реальные.  
+ **Атрибуты:** 
| Атрибуты | Тип данных | Описание |
| --- | --- | --- |
| Hours_Coding Daily |  | hours spent coding |  
| Lines_of_Code |  |	Total lines of code written |  
| Bugs_Found |  |	Number of bugs identified |  
| Bugs_Fixed |  |	Number of bugs fixed |  
| AI_Usage_Hours |  |	Hours spent using AI coding tools |  
| Sleep_Hours |  |	Average daily sleep |  
| Cognitive_Load |  |	Mental pressure score (0–100) |
| Task_Success_Rate	|  | Completion score (0–100) |  
| Coffee_Intake |  |	Daily cups of coffee |  
| Stress_Level |  |	Stress score (0–100) |  
| Task_Duration_Hours |  |	Hours taken to complete a task |  
| Commits	|  | Total Git commits |  
| Errors	|  | Number of coding errors |  
