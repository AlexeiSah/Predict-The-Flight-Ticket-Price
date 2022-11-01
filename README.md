<h1>Хакатон по прогнозированию цены авиабилета</h1>
<p>Многи путишественники говорят ,что цены на авиабилет непредсказуемы.К счастью я
являюсь специалистом по обработке данных и беру на себя честь опровернуть, это
высказывание.
<p>Здесь были предоставленны данные, то есть цены различных авиакомпаний в период
с марта по июнь 2019 года между различными городами.
<p>В этом проекте я использовал такие методы ,как LabelEncoder для нормализации
меток в фичах и Permutation Importance для выбора самых полезных фиче.
<p>Для задачи регрессии я выбрал 7 моделей: Linear Regression, kNN, SVM, Random
Forest, LightGBM, CatBoost, XGBoost. Наилучший результат показли LightGBM и CatBoost.
Из двух моих фаворитов я выбрал LightGBM  с результатом, равным 0.8455, что и помогло
мне занять 329 место из 819.